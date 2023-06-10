<template>
  <div class="bg-white">
    <div class="mx-auto grid max-w-2xl grid-cols-1 items-center gap-x-8 gap-y-16 px-4 py-24 sm:px-6 sm:py-32 lg:max-w-7xl lg:grid-cols-2 lg:px-8">
      <div>
        <h2 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">¿De que trata ISCLAB?</h2>
        <p class="mt-4 text-gray-500">
          Creamos aplicaciones con fines de práctica, investigación y responsabilidad social

Buscamos el desarrollo de nuestros estudiantes a través de la creación de proyectos que sean útiles a la sociedad*
        </p>

        <dl class="mt-16 grid grid-cols-1 gap-x-6 gap-y-10 sm:grid-cols-2 sm:gap-y-16 lg:gap-x-8">
          <div v-for="feature in features" :key="feature.name" class="border-t border-gray-200 pt-4">
            <dt class="font-medium text-gray-900">{{ feature.name }}</dt>
            <dd class="mt-2 text-sm text-gray-500">{{ feature.description }}</dd>
          </div>
        </dl>
      </div>
      <div class="grid grid-cols-2 grid-rows-2 gap-4 sm:gap-6 lg:gap-8">
        <img src="https://isclab.dcc.uchile.cl//assets/img/logo.png" alt="Walnut card tray with white powder coated steel divider and 3 punchout holes." class="rounded-lg bg-gray-100" />
        <img src="https://ingenieria.uchile.cl/dam/jcr:9b60b21c-e39a-4208-a2b8-b64cb0d58eb4/2-lab-dcc-alexandre-bergel2.jpg" alt="Top down view of walnut card tray with embedded magnets and card groove." class="rounded-lg bg-gray-100" />
        <img src="https://isclab.it/wp-content/uploads/2022/06/ISC_LAB_01.png" alt="Side of walnut card tray with card groove and recessed card area." class="rounded-lg bg-gray-100" />
        <img src="https://www.soycest.mx/hubfs/cest-tipos-de-personalidades.jpg" alt="Walnut card tray filled with cards and card angled in dedicated groove." class="rounded-lg bg-gray-100" />
      </div>
      <ul class="list-disc">
        <p>Sitio Web</p>
  <li>promover servicios o productos</li>
  <li>presentar contenidos o información al público</li>
  <li>promover un negocio</li>
  <!-- ... -->
</ul>
    </div>
  </div>
</template>

<script setup>
const features = [
  { name: '¿Qué hacemos en isclab?', description: 'Claro que necesitamos saber en qué consiste el sitio que necesitas y tu historia para valorar el apoyo gratuito en la creación y publicación de tu sitio.' },
  { name: '¿pueden crear un sitio web gratuito para mi proyecto?', description: 'Averigua las condiciones de un sitio web gratuito para nosotros será un placer apoyarte.' },
  { name: '¿Pero que clase de proyectos realizan', description: 'Nuestro laboratorio está conformado por programadores por lo que los productos que creamos se categorizan como software.' },
  { name: 'Intuitivo - introvertido', description: 'Son muy soñadores y fantasean bastante acerca del futuro, al punto de dejar casi de lado el presente. Puedes reconocerlos por su carácter soñador.' },
]

</script>
