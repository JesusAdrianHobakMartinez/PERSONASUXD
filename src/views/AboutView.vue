<template>
  <div class="bg-white">
    <div class="mx-auto grid max-w-2xl grid-cols-1 items-center gap-x-8 gap-y-16 px-4 py-24 sm:px-6 sm:py-32 lg:max-w-7xl lg:grid-cols-2 lg:px-8">
      <div>
        <h2 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">¿Que es la personalidad?</h2>
        <p class="mt-4 text-gray-500">
          La personalidad es un conjunto de características psicológicas y patrones de comportamiento que determinan cómo una persona percibe, piensa, siente y actúa. Es la forma única en que cada individuo se presenta al mundo y se relaciona con los demás.
        </p>

        <dl class="mt-16 grid grid-cols-1 gap-x-6 gap-y-10 sm:grid-cols-2 sm:gap-y-16 lg:gap-x-8">
          <div v-for="feature in features" :key="feature.name" class="border-t border-gray-200 pt-4">
            <dt class="font-medium text-gray-900">{{ feature.name }}</dt>
            <dd class="mt-2 text-sm text-gray-500">{{ feature.description }}</dd>
          </div>
        </dl>
      </div>
      <div class="grid grid-cols-2 grid-rows-2 gap-4 sm:gap-6 lg:gap-8">
        <img src="https://plustatic.com/663/conversions/tipos-personalidad-large.jpg" alt="Walnut card tray with white powder coated steel divider and 3 punchout holes." class="rounded-lg bg-gray-100" />
        <img src="https://www.sicologiahoy.com/wp-content/uploads/2018/05/personalidad.jpg" alt="Top down view of walnut card tray with embedded magnets and card groove." class="rounded-lg bg-gray-100" />
        <img src="https://daraespinaco.files.wordpress.com/2017/08/typefinder-squared.png" alt="Side of walnut card tray with card groove and recessed card area." class="rounded-lg bg-gray-100" />
        <img src="https://www.soycest.mx/hubfs/cest-tipos-de-personalidades.jpg" alt="Walnut card tray filled with cards and card angled in dedicated groove." class="rounded-lg bg-gray-100" />
      </div>
    </div>
  </div>
</template>

<script setup>
const features = [
  { name: 'Pensamiento introvertido', description: 'Le interesa más las ideas que los hechos, estar en su realidad interior ante que las demás personas. Es decir, están mucho más enfocadas en sus propios pensamientos que en lo que ocurre en el mundo exterior.' },
  { name: 'Sentimental introvertido', description: 'Al ser de tipo introvertidas, son poco habladoras, pero a la vez pueden ser simpáticas y empáticas y pueden tener cierta facilidad para crear vínculos afectivos con un círculo pequeño, aunque no demostrarán su apego.' },
  { name: 'Sensación - introvertido', description: 'Quienes tienen una personalidad sensible introvertida están enfocados a los fenómenos subjetivos más que a los objetivos que ocurren a su alrededor, como el resto de las personalidades introvertidas.' },
  { name: 'Intuitivo - introvertido', description: 'Son muy soñadores y fantasean bastante acerca del futuro, al punto de dejar casi de lado el presente. Puedes reconocerlos por su carácter soñador.' },
  { name: 'Pensamiento extrovertido', description: 'Crean explicaciones del mundo y de lo que los rodea a partir de lo que ven a su alrededor, creándose reglas casi inamovibles sobre la realidad. Estas personas no suelen cambiar muy fácilmente su forma de ver las cosas y además intentarán imponer su visión a los demás.' },
  { name: 'Sentimental-extrovertido', description: 'Son personas muy empáticas y tienen gran facilidad para conectar con los demás, a la vez que disfrutan mucho de la compañía. Es un perfil muy bueno para las relaciones humanas ya que cuentan con grandes habilidades sociales. En contrapartida, en general presentan baja inclinación a la reflexión y el pensamiento abstracto.'},
  { name: 'Sensación - extrovertido', description: 'En este tipo de personalidad se mezclan la búsqueda de las sensaciones tangibles con la vivencia con el entorno y con los demás. Las personas con este tipo de personalidad se sienten muy bien en interacción con los demás, y necesitan cambiar de estímulos de manera casi constante.' },
  { name: 'Intuición- extroversión', description: 'La personalidad de tipo intuitivo – extrovertido tiene tendencia a emprender todo tipo de proyectos y aventuras de duración media a larga, queriendo siempre empezar devuelta cuando una termina.' },
]
</script>
