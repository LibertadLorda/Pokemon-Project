<script setup >
import LogoPokedex from '../components/LogoPokedex.vue'
import CardComponent from '../components/CardComponent.vue'; 
import FooterComponent from '../components/FooterComponent.vue';
</script>


<template>   
<div>
    <LogoPokedex/>
    <CardComponent/>
</div>
<FooterComponent/>
</template>

<style>
body{
    background-image: url(../assets/images/container_bg.png);
}
@media screen and (max-width: 500px){
body {
    margin-left: 50px;
}
}
</style>

