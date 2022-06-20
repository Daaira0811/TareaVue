<template>
  <main>
    <Navbar/>
    <h1>Bienvenido a <br>
    Notes</h1>
  </main>
</template>
<script>

import Navbar from '../components/Navbar.vue'

export default{
  name:'Home',
components: {
  Navbar
},

}
</script>
<style>
main{
  display: flex;
  flex-wrap: wrap;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}
h1{

}
</style>