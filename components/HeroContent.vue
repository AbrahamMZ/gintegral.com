<template>
  <div class="pt-24">
    <div
      class="container px-3 mx-auto flex flex-wrap flex-col md:flex-row items-center"
    >
      <!--Right Col-->
      <div class=" text-center w-full md:w-2/5 justify-center">
        <img class="w-full md:w-4/5 z-50" src="~/assets/img/logo.png" alt />
      </div>
      <!--Left Col-->
      <div
        class="flex flex-col w-full md:w-3/5 py-6 items-start text-center md:text-left"
      >
        <p class="uppercase tracking-loose w-full">
          Encuentra tu desarrollo integral
        </p>
        <h1 class="my-4 text-5xl font-bold leading-tight">
          Nosotros te ayudamos a Desarrollar tu potencial
        </h1>
        <p class="leading-normal text-2xl mb-8">
          Servicios profesionales, publicidad, tu sitio web y muchos mas...
        </p>

        <!-- <button
          class="mx-auto lg:mx-0 hover:underline bg-white text-gray-800 font-bold rounded-full my-6 py-4 px-8 shadow-lg"
        >
          Subscribe
        </button> -->
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeroContent'
}
</script>
