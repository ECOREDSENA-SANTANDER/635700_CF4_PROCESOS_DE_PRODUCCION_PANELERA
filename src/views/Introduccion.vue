<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    .row.mb-5
      .col-12.col-lg-7
        p Apreciado aprendiz, bienvenido a este componente formativo, orientado a los requerimientos técnicos y normativos sobre las buenas prácticas de la manufactura (BPM), técnicas estas de limpieza de la materia prima con normativa legal y procesos de generación de residuos, todos ellos asociados al proceso de producción de la panela. Lo anterior, con el propósito de reconocer las normas técnicas que establecen los requisitos de higiene desde la fabricación, hasta la comercialización de la panela, lo que garantiza la calidad del producto final.
        p En el siguiente video conocerá de forma general, la temática que estudiará a lo largo de este componente formativo:

      .col-5.d-none.d-lg-flex.align-self-center
        figure
          img(src='@/assets/curso/introduccion/img-1.png', alt='Texto que describa la imagen')
    
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/BPxOWz7uS_Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
