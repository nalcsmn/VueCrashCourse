<template>
  <div class="container">
    <h1>Form Bindings</h1>
   <input :value="text" @input="onInput" placeholder="Type here">
  <p>{{ text }}</p>
  </div>
</template>

<script>
export default {
  name: "Header",
  methods: {},
  data() {
    return {
      text: ''
    }
  },
  methods: {
    onInput(e) {
      this.text = e.target.value
    }
  }
};
</script>


<style>
</style>