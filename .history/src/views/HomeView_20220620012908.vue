<template>
  <main>
    <Navbar/>
    <body>
    <h1>
    Todo lo que necesitas en un sólo lugar
   </h1>

    <b-button class="registrarse" v-on:click="showModal=true">
      Comienza ahora
    </b-button>
    <Login v-if="showModal"/>
    </body>
   
  </main>
</template>
<script>

import Navbar from '../components/Navbar.vue'
import Login from '../components/Login.vue'

export default{
  name:'Home',
  data(){
    return{
      showModal:false
    }
  },
components: {
  Navbar,
  Login
},

}
</script>
<style>
main{
  display: block;
  flex-wrap: wrap;
  flex-direction: column;
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
  height:100%;
  justify-content: center;
  align-items: center;

}
.registrarse{

}
</style>