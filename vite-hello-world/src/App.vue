
<script>
import appTitle from './components/appTitle.vue'

export default {
  name: 'app',
  components : {
    appTitle,
  },
  data(){
    return{
      message :'ciao Vite!',
      
    }
  }
}
</script>

<template>
  <h1>{{ message }}</h1>
  <appTitle />
</template>

<style scoped>
h1{
  padding: 20px;
  color: black;
  background-color: rgb(209, 209, 209);
  border: 2px solid red;
  border-radius: 20px;
  line-height: 100%;
}

</style>