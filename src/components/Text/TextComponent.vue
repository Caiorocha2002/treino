<template>
    
<component class="style" :is="tag"> 
    
   <slot/>
</component> 
    
</template>

<script>
export default{
    name:'TextComponent',
    props: {
        tag: {   
        type: String,
        default: 'h1',
    }
  
    },

};
</script>
<style>
.style{
    font-size: 2em;
    color:#efececc9;;
    font-family: 'Sigmar', cursive;
    z-index:3;
    position: absolute;
top: 1em;
left: 0;
}

</style>