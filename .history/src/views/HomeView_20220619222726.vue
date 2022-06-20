<template>
  <main>
    <Navbar/>
    <div id="principal">
      <h1>Todo tu trabajo organizado</h1>
      <b-button>Comienza ahora</b-button>
    </div>
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
  width: 100vw;

}


</style>