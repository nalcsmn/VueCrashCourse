<template>
  <header>
      <h1>{{title}}</h1>

       
  </header>
  <div class="container">
      <h1 class="title">Make me red</h1>
   
     
      <button @click="doStuff()" class="btn" >🎉 Congratulations!</button>
       
  </div>
</template>

<script>



export default {
    name: 'Header',
    props: {
        title: String,
       
    },methods: {
      doStuff () {
        alert('Task done!')
      }
    }
    
}
</script>

<style scoped>
    header{
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-bottom: 20px;
    }
    .title {
  color: red;
}
</style>