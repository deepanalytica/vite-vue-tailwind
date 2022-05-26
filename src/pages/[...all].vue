<template>
  <div class="bg-gray-50">
    <div
      class="mx-auto max-w-screen-xl px-4 py-12 sm:px-6 lg:flex lg:items-center lg:justify-between lg:py-16 lg:px-8"
    >
      <h2
        class="text-3xl font-extrabold leading-9 tracking-tight text-gray-900 sm:text-4xl sm:leading-10"
      >Servicios</h2>
      <div class="mt-8 flex lg:mt-0 lg:flex-shrink-0">
        <div class="inline-flex rounded-md shadow">
          <router-link
            to="/"
            class="inline-flex items-center justify-center rounded-md border border-transparent bg-indigo-600 px-5 py-3 text-base font-medium leading-6 text-white transition duration-150 ease-in-out hover:bg-indigo-500 focus:outline-none"
          >Ir al inicio</router-link>
        </div>
        <ButtonRepo />
      </div>
    </div>
   
</div> 
  
<div>

  <div
      class="mx-auto max-w-screen-xl px-4 py-12 sm:px-6 lg:flex lg:items-center lg:justify-between lg:py-16 lg:px-8"
    >
  <div class="card w-96 bg-base-100 shadow-xl image-full">
  <figure><img src="https://api.lorem.space/image/shoes?w=400&h=225" alt="Shoes" /></figure>
  <div class="card-body">
    <h2 class="card-title">Data Science</h2>
    <p>Necesitas marcar la diferencia con un proyecto de Ciencia de Datos exitoso?</p>
    <div class="card-actions justify-end">
      <button class="btn btn-primary">Leer más</button>
    </div>
  </div>
</div>

  <div class="card w-96 bg-base-100 shadow-xl image-full">
  <figure><img src="https://api.lorem.space/image/shoes?w=400&h=225" alt="Shoes" /></figure>
  <div class="card-body">
    <h2 class="card-title">Inteligencia Artificial</h2>
    <p>Quieres utilizar las capacidades de la IA a tu favor?</p>
    <div class="card-actions justify-end">
      <button class="btn btn-primary">Leer más</button>
    </div>
  </div>
</div>

  <div class="card w-96 bg-base-100 shadow-xl image-full">
  <figure><img src="https://api.lorem.space/image/shoes?w=400&h=225" alt="Shoes" /></figure>
  <div class="card-body">
    <h2 class="card-title">Transformación Digital</h2>
    <p>Deseas que tu organización alcance el próximo nivel?</p>
    <div class="card-actions justify-end">
      <button class="btn btn-primary">Leer más</button>
    </div>
  </div>
</div>
    </div>



</div>


</template>
