21a<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import logo from './assets/logo.png'
import suno from './assets/suno.jpg'
import marte from './assets/marte.jpg'

</script>

<template>

<img :src="logo" alt="logo">

<br>
<br>

<div class="btn-button">


<button>Clique</button>
        
</div>


<div class="postagem1" style="text-align: center;">
<h2 style="color: black">“É uma mudança de paradigma”, diz cientista do Perseverance sobre indícios de vida em Marte"
</h2>

<img :src="marte" alt="marte" width="1200px" height="700px">

<h3 style="text-align:center; color: black;"> 
  Na última semana, uma nova descoberta do Perseverance pode ter encontrado algo buscado há muito tempo:
vida em Marte. Mas é preciso ter calma, as amostras ainda são iniciais e a confirmação se os elementos encontrados
realmente são orgânicos só poderá ser feita (o que deve levar bastante tempo).
  De acordo com uma das pesquisadoras que atuam no projeto do rover, esses novos indícios podem ser uma grande mudança de paradigma.
De acordo com a NASA, o rover coletou uma rocha em forma de ponta de flecha apelidada de “Cheyava Falls”, 
A pequena rocha passou por análises iniciais feitas pelos instrumentos de bordo do próprio Perseverance.
 Os resultados mostram que a amostra se encaixa nos critérios de definição de um possível indicador de vida antiga.

<br>
<br>
<br>
<br>


<footer><h5 style="text-align: end;">

  A recente descoberta do Perseverance em Marte, que inclui
uma rocha apelidada de "Cheyava Falls", pode indicar a presença
de elementos orgânicos. No entanto, a confirmação de vida em Marte
ainda depende de análises mais aprofundadas e demoradas. Segundo uma
pesquisadora do projeto, esses achados podem significar uma grande mudança
de paradigma. A NASA informou que os resultados iniciais indicam que a amostra 
pode ser um possível indicador de vida antiga.</h5></footer>
</h3>

</div>

<br>
<br>
<br>
<br>


<div class="postagem2" style="text-align: center;">
<h1 style="color: black">"Essas IAs fazem música — e gravadoras não estão gostando"</h1>

<img :src="suno" alt="suno"width="1200px" height="700px">

<h3 style="text-align: center; color: black;">Suno e Udio, duas startups de IA que usam músicas de artistas em seus modelos, responderam
a ações judiciais de direitos autorais movidas contra elas por grandes gravadoras. A Suno argumenta que o caso contra ela
é “fundamentalmente falho tanto nos fatos quanto na lei”. As informações são da Reuters.
As startups alegam que treinar os seus modelos de IA em músicas protegidas por direitos autorais pertencentes àseditoras discográficas para
criar serviços que permitam a qualquer pessoa criar música constitui “utilização justa” conforme o que está na lei.

<br>
<br>

<footer><h5 style="text-align: end;">

As startups Suno e Udio enfrentam ações judiciais por parte de grandes gravadoras, que alegam 
violação de direitos autorais. A Suno defende que o processo é falho, 
tanto em termos legais quanto factuais, e argumenta que o uso das músicas para treinar modelos
de IA se enquadra na "utilização justa" prevista pela lei. As informações são da Reuters.</h5></footer>

</h3>



</div>

<br>
<br>
<br>
<br>


</template>

<style scoped>
header {
  line-height: 1.5;
}

button {
position:absolute;
top:80px;
right:90px;
background-color:brown;
color:white;
border-radius: 5px 5px 5px 5px;
border-color: white;
font-size: larger;

}
button:hover{
  cursor: pointer;
  background-color:rgb(114, 35, 35);
}

template{
  background-color: black;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    height: 20px;
    width: 30px;
    position: relative;
  }

  template{
    background-color: white;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
