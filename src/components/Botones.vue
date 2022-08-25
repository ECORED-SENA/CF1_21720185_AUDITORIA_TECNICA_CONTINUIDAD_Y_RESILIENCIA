<template lang="pug">

.row.align-items-center.justify-content-center
  .col-md-5.mb-4.mb-md-0
    .botones
      img.img-a.img-t(src='@/assets/curso/tema1/img23.svg')
      .botones__item(
        v-for="(boton, index) in botones"
      )
        .botones__btn(
          :style="getStyles(boton, index)"
          @mouseover="hover = index"
          @mouseleave="hover = null"
          @click="selected = index"
        )
          .indicador--click(v-if="index === 1 && indicador")
  .col-md-7(:style="{'z-index':'2'}")      
    .BG03-1.p-4(v-if="selected === 0")
      .h5.mb-2 Actuar
      p Aquí se realizan las correcciones de acuerdo con los hallazgos presentados en los anteriores componentes. Esto hace parte de los procesos de mejora continua en la Norma ISO 22301 y que permiten dinamizar sus procesos. En el actuar también se tiene en cuenta las correcciones que se deben realizar para mejorar los procesos de negocio de la organización, es decir, qué aspectos se encuentran bien y cuáles se deben modificar o analizar para que la totalidad de las  funciones de la organización tengan un correcto funcionamiento. 
      p Adicional a ello, se debe registrar en una matriz de riesgo si existen nuevos potenciales riesgos detectados al momento de realizar el análisis; de ahí la importancia de que este proceso sea cíclico y constante, en periodos establecidos, así se mantendrá vigente y actualizado todo lo referente a los riesgos y oportunidades de mejora de la organización.
    .BG03-1.p-4(v-else-if="selected === 1")
      .h5.mb-2 Planear
      p Los procesos que acompañan la ejecución de la Norma ISO 22301 empiezan por una planeación de las actividades, en el que se llevará a cabo un análisis de los procesos de negocio con los que cuenta la organización y se establece si esta tiene una política de continuidad del negocio. Adicional a ello, se estudian los diferentes riesgos a los cuales se encuentra expuesto el negocio y su nivel de complejidad (bajo, medio y alto), referente que dará un parte del tratamiento que estos deben tener y un estimado de lo que podría ser su presupuesto.
      p Por ejemplo, si la mayoría de riesgos se encuentran en la categoría medio y alto quiere decir que el negocio tiene un riesgo bastante considerable y que se debe cambiar el enfoque de funcionamiento tanto a nivel de la tecnología como a nivel estructural en la forma cómo se administran los mismos; pero en caso de detectar que la mayoría de los riesgos están en la escala de bajo impacto se concentrará el proceso en aquellos que pueden generar riesgos de mayor escala y que sumados puedan provocar un proceso de complejidad tan grande que puede realizar un colapso del sistema.
    .BG03-1.p-4(v-else-if="selected === 2")
      .h5.mb-2 Verificar
          p En el componente de verificación se realiza una exhaustiva validación de que las actividades y procesos que se planearon se ejecutaron de manera satisfactoria. Es importante tener en cuenta que la verificación debe estar supervisada, de tal manera que se garantice que los resultados obtenidos de ese análisis sean acordes a los resultados esperados, siendo estos demostrables y no producto de datos inflados o adulterados. 
          p En esta fase se debe crear un comité de verificación para que vigile si se están dando los datos precisos al momento de realizar el proceso de verificación.
    .BG03-1.p-4(v-else-if="selected === 3")   
      .h5.mb-2 Hacer
      p En el proceso del hacer se encuentra la ejecución de las actividades diseñadas para cumplir de manera eficiente todos los procesos que se planearon en el paso anterior. Es de suma importancia tener en cuenta que para la ejecución de dichos procesos o actividades se debe contar con los recursos necesarios para esto, pueden ser humanos, tecnológicos y en algunas ocasiones, servicios de terceros, a los cuales se les involucra, ya que en muchas ocasiones las empresas subcontratan ciertos procesos por temas de costos operacionales. Estos últimos igualmente están involucrados en la ejecución de las actividades y por ende, en los procesos que garanticen la continuidad del negocio.
      p Las normas y estándares garantizan que los procesos cumplan con los protocolos y funciones correctas. En ese sentido, se debe comprender que estas normas no nacen como parte del azar sino como parte de estudios y pruebas que se realizan a los procesos, y de acuerdo con estos resultados obtenidos se realizan ajustes en los mismos para garantizar el cumplimiento y su óptima ejecución. Ahora bien, las normas también son actualizadas de acuerdo con la realidad y procesos que se estén manejando y que requieran mejoras para garantizar que aún se mantienen vigentes en el tiempo. Una organización que utiliza normas y certifica sus procesos tiene mejor oportunidades de negocio, ya que la mayoría de organizaciones a nivel mundial exigen que se garanticen los procesos y que estos se encuentren regidos por estándares internacionales, logrando respaldo, prestigio y unificación de criterios.

</template>

<script>
export default {
  name: 'Botones',
  data: () => ({
    indicador: true,
    selected: 0,
    hover: null,

    botones: [
      {
        img: require('@/assets/curso/temas/img01.svg'),
        pos_x: '19%',
        pos_y: '23%',
        size: '9%',
      },
      {
        img: require('@/assets/curso/temas/img01.svg'),
        pos_x: '79%',
        pos_y: '23%',
        size: '9%',
      },

      {
        img: require('@/assets/curso/temas/img01.svg'),
        pos_x: '19%',
        pos_y: '70%',
        size: '9%',
      },
      {
        img: require('@/assets/curso/temas/img01.svg'),
        pos_x: '79%',
        pos_y: '70%',
        size: '9%',
      },
    ],
  }),
  watch: {
    selected() {
      this.indicador = false
    },
    hover() {
      this.indicador = false
    },
  },
  methods: {
    getStyles(boton, index) {
      const image =
        this.hover === index || this.selected === index
          ? boton.img_h
          : boton.img
      return {
        'background-image': `url(${image})`,
        top: boton.pos_y,
        left: boton.pos_x,
        width: boton.size,
        'padding-top': boton.size,
      }
    },
  },
}
</script>

<style lang="sass" scoped>
.botones
  position: relative

.botones__btn
  background-size: contain
  background-repeat: no-repeat
  position: absolute
  cursor: pointer
  transition: background-image 0.2s ease-in-out

@media (max-width: $bp-max-md)
  .tarjeta-botones:before
    display: none
</style>
