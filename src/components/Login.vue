<template>
   <div id="container-Modal">
    <div id="modal">
      <h1>Bienvenido a <br>
    Notes</h1>
    <hr>
      <v-card>
        <b-form @submit="onSubmit">
        <b-form-group
        label="Correo electrónico:"
        label-for="input1"
        >
        <b-form-input 
        id="input1"
        type="email"
        placeholder="Ingresa tu correo">
        </b-form-input>
        </b-form-group>
        <b-form-group
        label="Contraseña:"
        label-for="input2"
        >
        <b-form-input 
        id="input2"
        type="password"
        placeholder="Ingresa tu contraseña">
        </b-form-input>
        </b-form-group>
        <b-button >
          Iniciar Sesión
        </b-button><br>
        <p>
          ¿No tienes una cuenta?
          <a href="registro.vue">Registrate</a>
        </p>
        </b-form>
      </v-card>
    </div>
   </div>
</template>
<script>

</script>
<style>
h1{
 margin-top:30px;
 margin-bottom: 50px;
}
#container-Modal{
  display:flex;
  justify-content: center;
  align-items: center;
  z-index: 9998;
  top: 0;
  left: 0;
  width: 100vw;
  height: 90vh;
  background-color: rgba(0, 0, 0, .5);
  display: table;
  transition: opacity .3s ease
}
#modal{
  background-color: white;
  border:thin solid hsl(359, 100%, 41%);
  padding: 20px;
  display: inline-block;
  width:400px;
  height: 500px;
  text-align: center;

}
#modal>h1{
  margin:30px;
}

b-form-group > label{
text-align: left;
}
p{
  margin:15px;
}
a{
  text-decoration-line: underline;
}
b-button{
  margin:10px;
}
</style>