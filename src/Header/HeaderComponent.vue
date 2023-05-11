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
            <li> <a href="#"> Produtos

            </a>
            </li>
            <li>
                <a href="#">   Trilhas </a>
            </li>
            <li>
                <a href="#">  Home </a>
            </li>
        </ul>

        <img class="imgStyle" src="../assets/logo.jpeg" alt="">
  




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
   z-index:5;
   color: #fff;
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
    height: 15em;
border: solid #ffffff38;
left: 0em;
background:#ffffff38;
}
li{
    margin: 1em auto;
}
a{
    text-decoration: none;
    color:#fff;
    border: solid 0em;
    background-color: #000;
    border-radius: 1em;
    padding: 0.3em;
}
img{
    position: absolute;
    width:5em;
    top:1.5em;
  left: 4em;
    margin:0 auto;
    box-shadow: #92b7b7cc  0em 0em 8em;
    z-index: 1;
    

}
@media screen and (min-width:636px){
    .imgStyle{
        left: 18em;
        
    }
   
}

@media screen and (min-width:804px){
    .imgStyle{
        left:23em;
        width: 9em;
top: 1em;
    }
}
@media screen and (min-width:983px){
    .imgStyle{
        left:30em;
    }
}
@media screen and (min-width:1204px){
    .imgStyle{
        left:35em;
    }
}
@media screen and (min-width:1334px){
    .imgStyle{
        left:40em;
    }
}
</style>