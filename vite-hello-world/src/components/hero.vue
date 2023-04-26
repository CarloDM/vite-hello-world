
<script>
export default {
  name:'hero',
  data(){
    return {
      message : "I'm a header"
    }
  }
  
}
</script>

<template>
  <div class="container">
    <h1>{{ message }}</h1>
  </div>

</template>
<style scoped>
  .container {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100vw;
    height: 20vh;
    background-color: aliceblue;
    color: blue;
  }
</style>