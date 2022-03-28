<template>
  <div class="container">
    <h1>Event Listener</h1>
    <button @click="increment">count is: {{ count }}</button>
  </div>
</template>
<script>
export default {
  name: "Header",
  methods: {
    
  },
  data() {
    return {
      count: 0,
    };
  },
  methods: {
    increment() {
      this.count++;
    },
  },
};
</script>


<style>
</style>