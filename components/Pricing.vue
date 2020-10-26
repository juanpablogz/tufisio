<template>
  <div class="container mx-auto">
<section>
  <div class="lg:flex bg-white sm:inline md:block">
    <div class="color card xl:flex-1 text-gray-700 text-center bg-gray-400 px-4 py-2 m-2 font-roboto sm:display:inline">
      <i class="icon fas fa-heartbeat"></i>
      <ul>
        <li class="title">1 mes</li>
        <li class="price"><i class="fas fa-dollar-sign"></i>59.900</li>
        <li> <i class="fas fa-check"></i> Cita de valoración</li>
        <li> <i class="fas fa-check"></i> plan de ejercicios</li>
        <li> <i class="fas fa-check"></i> Seguimiento evolución</li>
        <li> <i class="fas fa-times"></i> Cita de seguimiento</li>
      </ul>
    <button class="payment">Comprar Ahora</button>
    </div>
    <div class="color-two card xl:flex-1 text-gray-700 text-center bg-gray-400 px-4 py-2 m-2 font-roboto sm:display:inline">
      <i class="icon fas fa-heartbeat"></i>
      <ul>        
        <li class="title">2 meses</li>
        <li class="price"><i class="fas fa-dollar-sign"></i>89.900</li>
        <li> <i class="fas fa-check"></i> Cita de valoración</li>
        <li> <i class="fas fa-check"></i> plan de ejercicios</li>
        <li> <i class="fas fa-check"></i> Seguimiento evolución</li>
        <li> <i class="fas fa-times"></i> Cita de seguimiento</li>
      </ul>
    <button class="payment">Comprar Ahora</button>
    </div>
    <div class="color-three card xl:flex-1 text-gray-700 text-center bg-gray-400 px-4 py-2 m-2 font-roboto  sm:display:inline">
      <i class="icon fas fa-heartbeat"></i>
      <ul>
        <li class="title">3 meses</li>
        <li class="price"><i class="fas fa-dollar-sign"></i>109.900</li>
        <li> <i class="fas fa-check"></i> Cita de valoración</li>
        <li> <i class="fas fa-check"></i> plan de ejercicios</li>
        <li> <i class="fas fa-check"></i> Seguimiento evolución</li>
        <li> <i class="fas fa-times"></i> Cita de seguimiento</li>
      </ul>
    <button class="payment">Comprar Ahora</button>
    </div>
  </div>
</section>
  </div>
</template>

<script>
export default {

}
</script>

<style>
section {
  width: 100%;
  box-sizing: border-box;
  padding: 100px 0;
}
.card {
  position: relative;
  max-width: 300px;
  height: auto;
  border-radius: 15px;
  margin: 0 auto;
  padding: 40px 20px;
  box-shadow: 0 10px 15px rgba(0,0,0,0.5);
  transition: 0.5s;
}
.color {
background:linear-gradient(-45deg, #51f3e3, #7e7e7e);
margin-bottom: 18px;
}
.color-two {
  background:linear-gradient(-45deg, #51f3e3, #7d7d7d);
  margin-bottom: 18px;
}
.color-three {
  background:linear-gradient(-45deg, #51f3e3, #7e7e7e);
  margin-bottom: 18px;
}
.card:before {
  content: '';
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  height: 40%;
  background: rgba(255,255,255,.1);
  z-index: 1;
  transform: skewY(-5deg) scale(1.5);
}
.icon {
  color: #fff;
  font-size: 30px;
}
.title {
  position: relative;
  margin: 20px 0 0;
  padding: 0;
  color: #fff;
  font-size: 28px;
  z-index: 2;
}
.price {
  position: relative;
  z-index: 2;
  margin: 0;
  padding: 20px 0;
  color: #fff;
  font-size: 40px;
}
ul li {
  margin: 0 0 10px;
  padding: 0;
  list-style: none;
  color: #fff;
  font-size: 16px;
}
.payment {
  position: relative;
  z-index: 2;
  background: #fff;
  color: #263621;
  border-radius: 40px;
  width: 150px;
  height: 40px;
  display: block;
  text-align: center;
  margin: 20px auto;
  font-size: 16px;
  cursor: pointer;
  text-decoration: none;
  box-shadow: 0 5px 10px rgba(0,0,0,0.5);
}
.payment:hover {
  text-decoration: none;
}
@media (max-width: 1024px) { 
  .card {
    padding: 40px;
  }
 }
</style>
    