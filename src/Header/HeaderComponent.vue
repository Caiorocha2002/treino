<script>
export default {
    name:'headerComponent',
     data(){
        return{
            menuVisivel: false
            
        }
     },
  methods: {
    exibirMenu() {
      this.menuVisivel = !this.menuVisivel
    }
  }
  
};

</script>

<template>
   <header>
    
    <div class="menuStyle" @click="exibirMenu" >
        <span class="hamburguer-line"></span>
        <span class="hamburguer-line"></span>
        <span class="hamburguer-line"></span>
      </div>

        <ul class="menuHamburgue"  :class="{ 'visible': menuVisivel}" id="ul--Menu">
            <li>
                deu certo
            </li>
            <li>
                deu certo
            </li>
            <li>
                deu certo
            </li>
        </ul>

        <img src="../assets/logo.jpeg" alt="">
  




</header> 
</template>

<style >

.hamburguer-line {
    display: block;
    width: 15px;
height: 5px;
margin: 3px 0;
    background-color: black;
    border-radius:5em;
}
.menuHamburgue{
    visibility: hidden;
    position:absolute;
    top:3em;
   
    margin:auto 0;

}
.menuHamburgue.visible{
    visibility: visible;
}
.menuStyle{
    position: absolute;
top: 1em;
 left: 1em;
border: none;

}
ul{
    list-style: none;
    margin:0;
    padding:0;
    left:0.5em;
}
img{
    position: absolute;
    width:5em;
    top:1.5em;
  left: 4em;
    margin:0 auto;
    

}


</style>