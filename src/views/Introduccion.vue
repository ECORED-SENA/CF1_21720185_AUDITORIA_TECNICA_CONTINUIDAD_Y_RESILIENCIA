<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    p Hoy día el respaldo de la información y la infraestructura tecnológica son de vital importancia para los procesos de negocio de la organización. En el siguiente video se puede apreciar la relevancia de estos sistemas de gestión, temática a desarrollar en este componente formativo:

    figure.mb-5(data-aos="zoom-in")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    .row.justify-content-center
      .col-md-10
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/intro/img01.png')})`}"
          )(data-aos="fade-right")
          .bloque-texto-g__texto.p-4
            p.mb-0 La apertura de los mercados actuales requiere que las organizaciones no solo inviertan en infraestructura y equipos para lograr los procesos misionales, sino que también aseguren esos servicios y productos para mantenerse vigentes, pues se sabe que los mercados cambian de manera frecuente y son competitivos en la generación de confianza para los inversionistas .
    
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
