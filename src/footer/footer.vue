<script>


export default{
    name:'footerCompnent',
    props:{
        footer:{
            default:'div',

        }

    }
}
</script>

<template>
    <component class="footer" :is="footer">
        <slot/>
    </component>
</template>

<style>
.footer{
    height:3em;
    background-color: #000;
    width:100%;
    position:absolute;
    left:0;
    
}
</style>