<template>
<div id="cuerpoNav">
    
    <img src="../assets/image2.png"  alt="image2.png" >
    <h1>NOTES</h1>
</div>
</template>
<script>
import { NavbarPlugin } from 'bootstrap-vue';

export default{
    name:Navbar
    
}
</script>
<style>
#cuerpoNav{
    display:flex;
    width:100%;
    height:10vh;
    background-color: #172420;
    color: white;

}

img {
    max-width: auto;
    height: 100%;
}
h1{
    margin:20px;
}
</style>
