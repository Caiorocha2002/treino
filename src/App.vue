<template>

   <headerComponent/>

   <main :class="page-content">
      
  <img class="foto--ponte" src="../src/assets/fotoPonte.jpeg" alt="">
   <TextComponent tag="h1"> "A natureza nos ensina lições valiosas 
      sobre a vida e a sobrevivência."</TextComponent>
</main>
<footerCompnent/>
</template>

<script>


import TextComponent from './components/Text/TextComponent.vue';
import headerComponent from './Header/HeaderComponent.vue';
import footerCompnent from './footer/footer.vue'


 export default{
    name:'App',
    components:{
       TextComponent,
       headerComponent,
       footerCompnent,
       
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
