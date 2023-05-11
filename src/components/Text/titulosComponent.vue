<script>
 export default {
    name:'componentTitulo',
     props:{
        title:{
            type: String,
            default: 'h1',
        }
     },
 }
</script>

<template>
    <component :is="title">
        <slot/>
    </component>

</template>