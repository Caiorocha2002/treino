<template>
   <headerComponent />

   <img class="foto--ponte" src="../src/assets/fotoPonte.jpeg" alt="">

   
      <TextComponent tag="h1"> "A natureza nos ensina lições valiosas
      sobre a vida e a sobrevivência."</TextComponent>

       
      
   <ComponentP />

   <footerComponent />
</template>

<script>


import TextComponent from './components/Text/TextComponent.vue';
import headerComponent from './Header/HeaderComponent.vue';
import footerComponent from './footer/footer.vue'
import ComponentP from './components/componentP/componentP.vue'
import componentTitulo from './components/Text/titulosComponent.vue'

export default {
   name: 'App',
   components: {
      TextComponent,
      headerComponent,
      footerComponent,
      ComponentP,
      componentTitulo,

   },

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

.foto--ponte {
   position: absolute;
   top: 3em;
   width: 100%;
   left: 0;
   
}
@media screen and (min-width:555px){
   .foto--ponte{
      height: 44em;
   }
}
</style>
