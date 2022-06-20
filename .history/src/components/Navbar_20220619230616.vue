<template>
<div id="cuerpoNav">
    <img src="../assets/image2.png"  alt="image2.png" >
    <h1>NOTES</h1>
    <div id="botones">
<b-button variant="outline-warning" size="sm">
        Iniciar Sesión
    </b-button>
    <b-button variant="outline-warning" size="sm">
        Registrate
    </b-button>
    </div>
    
</div>
</template>
<script>


</script>

<style>
#cuerpoNav{
    display:flex;
    flex-direction: row;
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
#botones{
    position: absolute;
    width: auto;
    margin-left: 20px;
    height: fit-content;
    align-content: unset;
    right: 0;
    padding: 20px;
}

</style>
