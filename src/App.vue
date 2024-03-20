<script>
export default {
  data(){
    return{
      title: "Hello World"
    }
  }
}
</script>

<template>
  <div class="container">
    <h1> {{ title }}</h1>
  </div>
</template>

<style scoped>
  .container{
    max-width: 1200px;
    height: 500px;
    max-height: 1200px;
    margin: 0 auto;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: green;
  }

  h1:hover{
    transition: all 1s linear;
    font-size: 200px;
    color: red;
  }
  
</style>