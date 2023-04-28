<template>

   <headerComponent/>

  <img class="foto--ponte" src="../src/assets/fotoPonte.jpeg" alt="">
   <TextComponent tag="h1"> "A natureza nos ensina lições valiosas 
      sobre a vida e a sobrevivência."</TextComponent> 
   
<footerComponent />

</template>

<script>


import TextComponent from './components/Text/TextComponent.vue';
import headerComponent from './Header/HeaderComponent.vue';
import footerComponent from './footer/footer.vue'


 export default{
    name:'App',
    components:{
       TextComponent,
       headerComponent,
       footerComponent,
       
    } ,

 };
</script>

<style >
body {
   font-family: Arial, sans-serif;
   margin: 0;
   padding: 0;
 }
 
 .container {
   max-width: 1200px;
   margin: 0 auto;
   padding: 0 20px;
 }
 .foto--ponte{
   position: absolute;
  top: 3em;
  width: 100%;
  left: 0;
  

 }



  
</style>
