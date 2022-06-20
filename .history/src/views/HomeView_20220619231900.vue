<template>
  <main>
    <Navbar/>
    <body>
    <h1>
    Todo lo que necesitas en un sólo lugar
   </h1>

    <b-button class="registrarse">
      Comienza ahora
    </b-button>
    </body>
   

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
  display: block;
  flex-wrap: wrap;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  height: 100vh;
}

h1{
 margin-top:30px;
 margin-bottom: 50px;
}
body{
  display:flex;
  width: 100vw;
  height:auto;
  justify-content: center;
  align-items: center;

}
.registrarse{
}
</style>