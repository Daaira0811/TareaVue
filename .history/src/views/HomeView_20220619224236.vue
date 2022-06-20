<template>
  <main>
    <Navbar/>
  </main>
</template>
<script>

import Navbar from '../components/Navbar.vue'

export default{
  name:'home',

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