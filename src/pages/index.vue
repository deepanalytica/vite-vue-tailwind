<template>
  <div class="bg-gray-50">
    <div class="mx-auto max-w-screen-xl px-4 py-12 sm:px-6 lg:flex lg:items-center lg:justify-between lg:py-16 lg:px-8">
      <h2 class="text-3xl font-extrabold leading-9 tracking-tight text-gray-900 sm:text-4xl sm:leading-10">
        Inicio
        <br />
        <span class="text-indigo-600">Deep Analytica</span>
      </h2>
      <div class="mt-8 flex lg:mt-0 lg:flex-shrink-0">
        <div class="inline-flex rounded-md shadow">
          <router-link to="/"
            class="inline-flex items-center justify-center rounded-md border border-transparent bg-indigo-600 px-5 py-3 text-base font-medium leading-6 text-white transition duration-150 ease-in-out hover:bg-indigo-500 focus:outline-none">
            Volver al Inicio</router-link>
        </div>
        <ButtonRepo />
      </div>
    </div>
<div class="carousel w-full">
  
  <div id="slide1" class="carousel-item relative w-full">
    <img src="https://images.unsplash.com/photo-1588600878108-578307a3cc9d?crop=entropy&cs=tinysrgb&fm=jpg&ixlib=rb-1.2.1&q=80&raw_url=true&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=720&" class="w-full"> / 
    <div class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2">
      <a href="#slide4" class="btn btn-circle">❮</a> 
      <a href="#slide2" class="btn btn-circle">❯</a>
    </div>
  </div> 
 
  <div id="slide3" class="carousel-item relative w-full">
    <img src="https://api.lorem.space/image/car?w=800&h=200&hash=A89D0DE6" class="w-full"> / 
    <div class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2">
      <a href="#slide2" class="btn btn-circle">❮</a> 
      <a href="#slide4" class="btn btn-circle">❯</a>
    </div>
  </div> 
  <div id="slide4" class="carousel-item relative w-full">
    <img src="https://api.lorem.space/image/car?w=800&h=200&hash=225E6693" class="w-full"> / 
    <div class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2">
      <a href="#slide3" class="btn btn-circle">❮</a> 
      <a href="#slide1" class="btn btn-circle">❯</a>
    </div>
  </div>
</div>
    <div class="mx-auto max-w-screen-xl">
      <ul class="list-disc">
        <li>Utilizamos métodos de Inteligencia Artificial e Ingeniería Matemática para Desentrañar patrones
          operacionales ocultos en grandes cantidades de datos (Big Data).</li>
        <li>Impulsamos el desarrollo de ciudades inteligentes y sustentables desde la Participación Ciudadana e
          Innovación Tecnológica.</li>
        <li>
          Realizamos estudios y encuestas de opinión pública para desarrollar estrategias centradas en los usuarios.
        </li>
      </ul>
    </div>
  </div>
</template>

