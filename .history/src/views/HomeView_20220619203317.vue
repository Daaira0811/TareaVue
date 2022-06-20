<template>
  <main>
    <Navbar/>
   <div id="container-Modal"><h1>Bienvenido a <br>
    Notes</h1>
    <div modal>
      <v-card>
        <b-form @submit="onSubmit">
        <b-form group
        label="Ingrese su correo:"
        label-for="input1"
        >
        <b-form-input>
          
        </b-form-input>
        </b-form>
        </b-form>
      </v-card>
    </div>
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
}
h1{
 margin : 30px;
}
#container-Modal{
  z-index: 9998;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, .5);
  display: table;
  transition: opacity .3s ease
}
</style>