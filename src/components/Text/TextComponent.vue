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
    },
 
    },

};

</script>
<style>
.style{
    font-size: 1.5em;

    color:#efececc9;;
    font-family: 'Sigmar', cursive;
    z-index:3;
    position: absolute;
top: 3em;
left: 0;
}
.paragrafo{
    color: #000;
}
@media screen and (min-width:211px) and (max-width:245px){
    .style{
        top:5em;
    }
}
@media screen and (min-width:246px) and (max-width:277px){
 .style{
    top: 7em;
 }
}
@media screen and (min-width:278px) and (max-width:313px){
   .style{
    top:8em;
   }
}
@media screen and (min-width:314px) and (max-width:347px){
    .style{
        top:10em;
    }
}
@media screen and (min-width:348px) and (max-width:381px){
    .style{
        top:12em;
    }
}
@media screen and (min-width:382px){
    .style{
        top:13em;
    }
}
@media screen and (min-width:563px){
   .style{
    top:15em;
   }
}
@media screen and (min-width:639px){
   .style{
    font-size: 2em;
    top:9em;
   }
}
@media screen and (min-width:923px){
   .style{
    font-size: 3em;
    top:8em;
   }
}
@media screen and (min-width:1231px){
 .style{
    left:1em;
 }  
}
</style>