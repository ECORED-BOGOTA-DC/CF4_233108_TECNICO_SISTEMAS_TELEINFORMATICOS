<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .bloque-texto-a.color-primario.p-3.p-md-3.mb-5 
      .row.justify-content-center.align-items-center
        .col-lg-3.mb-4.mb-lg-0
          figure
            img(src='@/assets/curso/temas/introduccion/img1.svg', alt='Imágen decorativa')
        .col-lg-8
          .bloque-texto-a__texto.p-4(data-aos="flip-down")
            p Al igual que muchos otros usuarios de computadores, es probable que haya utilizado el computador personal para jugar, actualizar el perfil de Facebook, escribir trabajos o crear hojas de cálculo de Excel. Esta suposición que se hace aquí indica que se es un usuario de computadores, es decir, que puede encender su máquina, cargar un paquete de <i>software</i> y utilizarlo para realizar una tarea. Este componente le llevará de ser un usuario final del computador a convertirse en un técnico de soporte de tecnologías de la información (TI). Es por ello que antes de profundizar en cada temática se reflexione sobre la importancia de este rol en la actualidad, a través de este video.

    .row.justify-content-center.align-items-center.mb-5(data-aos="flip-down")
      figure
        .video
          iframe(width="560" height="315" src="https://www.youtube.com/embed/123456789" title="xxxxxxx" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)










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
