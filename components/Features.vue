<template>
  <section class="bg-white border-b py-8">
    <div class="container max-w-5xl mx-auto m-8">
      <h1
        class="w-full my-2 text-5xl font-bold leading-tight text-center text-gray-800"
      >
        Actividades
      </h1>
      <div class="w-full mb-4">
        <div
          class="h-1 mx-auto gradient w-64 opacity-25 my-0 py-0 rounded-t"
        ></div>
      </div>
      <feature-left
        headline="CLUB DE TAREAS PARA NIÑOS DE PRIMARIA INICIO 01 DE JUNIO 2021"
        content="Inscripciones al teléfono (461) 5140803 ¡CUPO LIMITADO!"
      >
        <img src="~assets/img/children.svg?inline" alt slot="svg" />
        <div slot="tag">
          PREGUNTA POR EL PRECIO DE HERMANOS
        </div>
      </feature-left>
      <feature-right
        headline="TERAPIA PSICOLOGÍCA LUNES A PARTIR DE LAS 10:00 AM "
        content="AGENDA TU CITA YA AL (461) 5140803"
      >
        <img src="~assets/img/conversation.svg?inline" alt slot="svg" />
      </feature-right>
      <feature-left
        headline="NETWORKING"
        content="Únete a nuestra red de trabajo desde tu ciudad. Mayores informes dirección@gintegralb.com"
      >
        <img src="~assets/img/connected-world.svg?inline" alt slot="svg" />
      </feature-left>
    </div>
  </section>
</template>

<script>
import FeatureRight from "@/components/FeatureRight";
import FeatureLeft from "@/components/FeatureLeft";

export default {
  name: "Features",
  components: {
    "feature-right": FeatureRight,
    "feature-left": FeatureLeft,
  },
};
</script>
