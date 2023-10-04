<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Mantenimiento preventivo

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-11
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema2/img1.svg')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 El mantenimiento preventivo es una actividad organizada para evitar el desgaste o el fallo repentino de los componentes de los equipos. Los fallos mecánicos, de proceso, de control o de cualquier otro tipo del equipo pueden tener efectos adversos tanto en términos humanos como económicos. Además del tiempo de inactividad y de los costes que supone reparar y/o sustituir las piezas o componentes del equipo, existe el riesgo de que los operarios se lesionen y de que se exponen a agentes químicos y/o físicos. Por lo tanto, el mantenimiento preventivo es muy importante y la actividad de prevención de accidentes en los lugares de trabajo debe integrarse en el proceso de operación/fabricación del producto.

    p.mb-5 El mantenimiento preventivo de los equipos debe realizarse, por tanto, para:

    .bg-fondo3
      .row.justify-content-center.align-items-center.mb-5
        .col-lg-4.mb-5
          .tarjeta-titulo2.p-2
            h4.mb-0.text-center.texto-blanco Propósito del mantenimiento

      .row.justify-content-center.align-items-center.mb-5
        .col-lg-8
          




















</template>

<script>
export default {
  name: 'Tema2',
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
