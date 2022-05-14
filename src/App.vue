<template>
  <div>
    <Main/>
  </div>
</template>

<script>
import Main from './components/Main.vue'
export default {
  name:"App",
  components :{
    Main,

  }
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;500;600;700;800&display=swap");

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body{
  font-family: "Poppins", sans-serif;
}


</style>