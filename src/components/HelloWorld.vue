<script setup>
// METODOS
// iportacion del card principal
import CardPrincipal from './CardPrincipal.vue';
</script>

<template  >
<!-- ESTRUCTURA HTML -->
<div class="container">
   <h1 class=" mt-4">Mi Primer Card en Vue</h1>
   <CardPrincipal />

   <!-- inicio del 1 row -->
   <div class="row">
<div class="col-md-6">
   <div class="card mt-4">
       <div style="background-color: #f6a68d;" class="card-header">
           <h6 class="text-white text-center">¿Qué tipos de programación web existen?</h6>
       </div>
       <div style="background-color: #fce4be;"  class="card-body">
    <p class="text">Creación de sitios estáticos o dinámicos, Programación de aplicaciones para dispositivos móviles, Creación de tiendas en línea.</p>
    <br>
    <img class="img" src="https://st3.depositphotos.com/1007566/13259/v/450/depositphotos_132592684-stock-illustration-programmer-languages-working-laptop.jpg" alt="Imagen de programación"><br>
    <button class="btn btn-warning">Más información</button>
  </div>
   </div>
</div>
<div class="col-md-6">
   <div class="card mt-4">
       <div style="background-color: #f6a68d;" class="card-header">
           <h6 class="text-white text-center">¿Qué herramientas se usan para la programación web?</h6>
       </div>
       <div style="background-color: #fce4be;" class="card-body">
<!-- agregar imagen y un texto -->
 <p>Google Trends, Hotjar, Semrush, Figma, Adobe XD, Sketch, Wix, WordPress.</p>
  <br>
  <img class="img" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT2QOjUDq0KNTjfSy4qXKK4nst7EHrhEDmq0A&s" alt="">
  <br>
  <button class="btn btn-warning">Más información</button>
  <br>
</div>
   </div>
</div>
   </div>

 <!-- fin del primer row -->

 <!-- inicio del segundo row -->
  <div class="row">
   <div class="col-md-2">
       <div class="card mt-4">
           <div style="background-color: #e8c8a1;" class="card-header">
            <h3 class="text-white text-center">Vue</h3> </div>
           <div style="background-color: #fce4be;" class="card-body">
    <P class="text">Vue es un framework de JavaScript de código abierto que permite crear interfaces de usuario (UI) para aplicaciones web y de página única. Es uno de los frameworks web más populares, junto con Angular y React.</P><br>
    <img class="img1" src="https://static.platzi.com/media/blog/vuejs-4163d340-e1b8-4554-b42a-43d31e9c5b21.jpg" alt=""><br>
    <button class="btn btn-primary">Más Información</button>
           </div></div></div>
   <div class="col-md-2">
       <div class="card mt-4">
           <div style="background-color: #e8c8a1;" class="card-header">
            <h3 class="text-white text-center">Js</h3>
           </div>
           <div style="background-color: #fce4be;" class="card-body">
    <p class="text">JS es la abreviatura de JavaScript, un lenguaje de programación que se utiliza para crear páginas web interactivas.</p> <br>
    <img class="img1" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/99/Unofficial_JavaScript_logo_2.svg/1200px-Unofficial_JavaScript_logo_2.svg.png" alt="">
    <br><br> <br>
    <button class="btn btn-primary">Más Información</button>
           </div></div></div>
   <div class="col-md-8">
       <div class="card mt-4">
           <div style="background-color: #e8c8a1;" class="card-header">
            <h3 class="text-white text-center">Vite</h3>
           </div>
           <div style="background-color: #fce4be;" class="card-body">
    <p class="text">Vite es una herramienta de desarrollo frontend ultrarrápida y flexible, diseñada para crear aplicaciones web modernas, que ofrece una experiencia de desarrollo instantánea y se integra bien con frameworks como Vue, React y Svelte.</p>
    <img class="img2" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSqzNXPKYxcz8WYLDjarAYpG0c-L5wnUYQ2DQ&s" alt="">
    <br>  <br><br>  <button class="btn btn-primary">Más Información</button>
           </div></div></div></div>
  <!-- fin del segundo row -->
<div class="container">

    <div class="row">
        <div class="cold-md-4">
    <div class="card mt-4" style="width: 18rem;">
<img src="https://www.dongee.com/tutoriales/content/images/2023/02/image-48.png" class="card-img-top" alt="...">
<div class="card-body">
<p class="card-text text-center">MongoDB es un sistema de gestión de base de datos (DBMS) no relacional, de código abierto y orientada a documentos, que almacena datos en un formato flexible similar a JSON, ideal para aplicaciones que requieren flexibilidad y escalabilidad.</p>
<button class="btn btn-primary">Más Información</button>
</div>
</div>
</div>

    </div>
    
</div>
 
</div><br><br><br><br><br>

</template>

<style scoped>
/*  ESTILOS CSS*/
h1{
font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
text-align: center;
  color: blue;
  
}
.text{
  text-align: center;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
.text1{
  text-align: center;
  font-family: 'Times New Roman', Times, serif;  text-align: center;
  color: blueviolet;
}
.img {
    border-radius: 20px;
    width: 200px; 
    height: auto; 
    box-shadow: 5px 5px 15px rgba(24, 23, 23, 0.6);
}
.img1 {
    border-radius: 20px;
    width: 150px; 
    height: auto; 
    box-shadow: 5px 5px 15px rgba(24, 23, 23, 0.6);
}
.img2 {
    border-radius: 20px;
    width: 500px; 
    height: auto; 
    box-shadow: 5px 5px 15px rgba(24, 23, 23, 0.6);
}

.card-body {
    display: flex;
    justify-content: center; /* Centra horizontalmente */
    align-items: center; /* Centra verticalmente */
    flex-direction: column; /* Asegura que el texto y la imagen estén en columna */
    text-align: center; /* Centra el texto también */
}
.card-header {
    display: flex;
    justify-content: center; /* Centra horizontalmente */
    align-items: center; /* Centra verticalmente */
    flex-direction: column; /* Asegura que el texto y la imagen estén en columna */
    text-align: center; /* Centra el texto también */
}
</style>
