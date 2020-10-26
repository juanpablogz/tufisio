<template>
<div>
<link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css" integrity="sha384-AYmEC3Yw5cVb3ZcuHtOA93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p" crossorigin="anonymous"/>
<nav class="flex items-center justify-between flex-wrap white p-4 border-b-2 border-gray-400">
  <div class="flex items-center flex-shrink-0 text-white mr-6">
    <img src="https://res.cloudinary.com/dutj1bbos/image/upload/c_scale,w_136/v1603461897/logo_ovqxsj.png" alt="">
  </div>
  <div class="block lg:hidden" >
    <button @click="isOpen = !isOpen" class="flex items-center px-3 py-2 border rounded text-teal-200 border-teal-400 ">
      <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><title>Menu</title><path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/></svg>
    </button>
  </div>
  <div class="w-full block flex-grow lg:flex lg:items-center lg:w-auto">
    <div class="text-sm lg:flex-grow lg:flex justify-center" :class="isOpen ? 'block': 'hidden'">
      <a href="#services" class="block mt-4 lg:inline-block lg:mt-0 text-teal-400 hover:text-gray mr-4">
        Servicios
      </a>
      <a href="#responsive-header" class="block mt-4 lg:inline-block lg:mt-0 text-teal-400 hover:text-gray mr-4">
        Preguntas frecuentes
      </a>
      <a href="#responsive-header" class="block mt-4 lg:inline-block lg:mt-0 text-teal-400 hover:text-gray mr-4">
        Nuestro equipo
      </a>
      <button href="" class="hidd2 bg-teal-400 hover:bg-teal-500 text-white font-bold rounded-full py-2 px-4">
        <a class="hidd2" href="https://pacientes-lab.web.app/auth/sign-in" >Ingresar</a>
      </button>
    </div>
    <div>
      <button href="" class="hidd bg-teal-400 hover:bg-teal-500 text-white font-bold rounded-full py-2 px-4">
        <a class="hidd" href="https://pacientes-lab.web.app/auth/sign-in" >Ingresar</a>
      </button>
    </div>
  </div>
</nav>
  <div class="flex bg-gray-100 border-b-2 border-gray-400">
  <div class="contenedor">
    <img class="object-cover h-screen w-full pt-18" src="https://res.cloudinary.com/dutj1bbos/image/upload/v1603658959/fhd_runwst.jpg">
    <p class="top font-sans text-3xl text-white text-center sm:mb-12">Cita Fisioterapia desde casa </p>
    <p class="centrado font-sans text-lg text-white text-center mt-12">Analizamos tu caso, te brindaremos un plan de ejercicios para tu recuperación</p>
         <button class="centrado bg-teal-400 mt-32 hover:bg-teal-500 text-white font-bold rounded-full py-2 px-4 mt-8 sm:mt-32">
        Reservar Ahora
      </button>
  </div>
  </div>

<p class="text-center text-2xl p-6 mt-24">¿Como funciona?</p>

<Functioning/>
<p class="text-center text-2xl p-6 font-sans">¿Que dicen nuestros pacientes?</p>
<Testimonials/>
<p class="text-center text-2xl p-6 font-sans">¿Por que deberian elegirnos?</p>
<Choice/>
<p class="text-center text-2xl p-6 font-sans">Evidencia cientifica</p>
<p class="text-center text-2xl p-6 font-sans">Nuestros planes</p>

  <Pricing/>

    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css">
  <a href="https://api.whatsapp.com/send?phone=51955081075&text=Hola%21%20Quisiera%20m%C3%A1s%20informaci%C3%B3n%20sobre%20Varela%202." class="float" target="_blank">
  <i class="fa fa-whatsapp my-float"></i>
  </a>
  <Footer/>
</div>
</template>

<script>
export default {
  data() {
    return {
      isOpen: false,
    }
  }
}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.links {
  padding-top: 15px;
}
.float{
	position:fixed;
	width:60px;
	height:60px;
	bottom:40px;
	right:60px;
	background-color:#25d366;
	color:#FFF;
	border-radius:50px;
	text-align:center;
  font-size:30px;
	box-shadow: 2px 2px 3px #999;
  z-index:100;
}
.float:hover {
	text-decoration: none;
	color: #25d366;
  background-color:#fff;
}

.my-float{
	margin-top:16px;
}
.contenedor{
    position: relative;
    display: inline-block;
    text-align: center;
}
 
.texto-encima{
    position: absolute;
    top: 10px;
    left: 10px;
}
.centrado{
    position: absolute;
    top: 40%;
    left: 50%;
    transform: translate(-50%, -50%);
}
.top {
    position: absolute;
    top: 30%;
    left: 50%;
    transform: translate(-50%, -50%);
}
@media (min-width: 1024px) {
.top {
    position: absolute;
    top: 40%;
    left: 50%;
    transform: translate(-50%, -50%);
}
}
@media (max-width: 800px) {
.hidd {
  display: none !important;
  margin-top: -500px;
}
}
@media (min-width: 800px) {
.hidd2 {
  display: none !important;
}
.float {
  right:80px;
}
}
body {
  overflow-x: hidden;
}

</style>
