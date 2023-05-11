<script>
  export default {
    name:'ComponentP',
  }
</script>

<template>
<div class="container">

      <h1>Ubatuba</h1>

    <p>


     Se você é um amante da natureza e está procurando aventuras ao ar livre, Ubatuba é o lugar ideal para você. Neste artigo, vamos falar sobre algumas das melhores trilhas da região e dar algumas dicas úteis para ajudar a planejar sua próxima aventura.

Trilha das Sete Praias

A Trilha das Sete Praias é uma das trilhas mais populares em Ubatuba. Ela começa na Praia da Fortaleza e segue por cerca de 10 km até a Praia da Lagoinha, passando por sete praias incríveis ao longo do caminho. Durante a trilha, você passará por paisagens deslumbrantes e poderá desfrutar de vistas deslumbrantes do mar.

Algumas das praias que você verá ao longo da trilha incluem a Praia da Fortaleza, Praia Brava da Almada, Praia do Bonete, Praia Grande do Bonete e Praia Deserta. Todas essas praias são lindas e têm águas cristalinas que são perfeitas para nadar e praticar esportes aquáticos.

Praia das Conchas

A Praia das Conchas é uma praia incrível em Ubatuba que é cercada por rochas e tem uma paisagem natural deslumbrante. A praia é bastante isolada e você precisará fazer uma caminhada de cerca de 20 minutos pela trilha para chegar até ela.

A Praia das Conchas é um lugar perfeito para quem procura relaxar em um ambiente natural e intocado. A praia tem águas calmas e cristalinas e é cercada por uma floresta tropical exuberante. Há uma pequena lagoa na praia que é perfeita para nadar e relaxar.

Pico do Corcovado

A Trilha do Pico do Corcovado tem duas entradas: uma no bairro Praia Dura e outra pela cidade vizinha Vargem Grande. A trilha de Vargem Grande é um pouco mais fácil e um pouco mais rápida. No entanto, a trilha do bairro Praia Dura é mais desafiadora, mas também é uma das mais gratificantes. A trilha segue por cerca de 3 horas até o topo do Pico do Corcovado, que tem uma altitude de 1.180 metros.

Ao longo do caminho, você verá uma variedade de vida selvagem e paisagens naturais deslumbrantes. No topo do Pico do Corcovado, você será recompensado com vistas panorâmicas da região e pode ver até a cidade de Paraty, no Rio de Janeiro.

Dicas Úteis

Antes de sair para uma trilha, é importante lembrar-se de levar água, lanches, protetor solar, repelente de insetos e roupas e calçados adequados para caminhadas. Também é importante ter um mapa ou GPS para ajudá-lo a navegar pelas trilhas.

Além disso, é importante lembrar-se de respeitar o meio ambiente, mantendo-se nas trilhas marcadas e não deixando lixo pelo caminho. Também é importante verificar as condições climáticas e de trilhas antes de sair, para garantir a sua segurança, algumas trilhas são obrigatorias o acompanhamento de guia, certifique antes.
    </p>
  </div>

</template>
<style>
.container{
  display: grid;
 
  grid-template-rows: 1fr;
  grid-template-columns: 1fr;
  justify-items: center;
  align-items: center;
}
p{
    color:#000;
    font-size: o.5em;
    font-family: 'Sigmar', cursive;
    position:absolute;
    text-align: center;
    
    top: 19em;
  left: 0em;
  margin: 0 1em;
  font-size: 1em;
}

@media screen and (min-width:185px) and (max-width: 210px)  {
  p{
    top:21em;
  }
  
}
@media screen and (min-width:211px) and (max-width: 245px) {
  p{
    top:24em;
  }
}
@media screen and (min-width:246px) and (max-width:277px){
  p{
    top:27em;
  }

}
@media screen and (min-width:278px) and (max-width:313px){
p{
  top:30em;
}
}
@media screen and (min-width:314px) and (max-width: 347px){
  p{
    top:33em;
  }
}
  @media screen and (min-width:348px)and (max-width:381px){
    p{
      top:36em;
    }
  }
  @media screen and (min-width:382px){
    p{
      top:40em;
    }
  }

  @media screen and (min-width:437px){
P{
  top:44em;
}
  }
  @media screen and (min-width:479px){
    p{
      top:47em;
    }
  }
  @media screen and (min-width:521px){
    p{
      top:51em;
    }
  }
</style>