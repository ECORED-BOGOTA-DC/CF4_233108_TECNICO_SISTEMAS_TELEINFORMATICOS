<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Mantenimiento preventivo

    .row.justify-content-center.align-items-center.mb-5
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
        .col-11.col-lg-8
          .tarjeta-gris1.p-4
            .row.align-items-center
              .col-3.col-md-2.col-lg-1
                figure
                  img(src='@/assets/curso/temas/tema2/img3.svg', alt='Imágen decorativa').img3-4-tm2
              
              .col-lg-11.col-md-10
                b Aumentar la fiabilidad del sistema disminuyendo las posibilidades de fallo.

          .tarjeta-gris2.p-4
            .row.align-items-center
              .col-3.col-md-2.col-lg-1
                figure
                  img(src='@/assets/curso/temas/tema2/img4.svg', alt='Imágen decorativa').img3-4-tm2
              
              .col-lg-11.col-md-10
                b Proporcionar un mejor rendimiento funcional. 

          .tarjeta-gris3.p-4
            .row.align-items-center
              .col-3.col-md-2.col-lg-1
                figure
                  img(src='@/assets/curso/temas/tema2/img3.svg', alt='Imágen decorativa').img3-4-tm2
              
              .col-lg-11.col-md-10
                b Garantizar un equipo de aspecto presentable en todo momento.

        .col-8.col-lg-4
          figure
            img(src='@/assets/curso/temas/tema2/img2.svg', alt='Imágen decorativa').img2-tm2

      .row.justify-content-center.align-items-center.mb-5
        .col-4.col-lg-2
          .bg-6.p-4
            .row
              .col-9.col-lg-7
                figure
                  img(src='@/assets/curso/temas/tema2/img5.svg', alt='Imágen decorativa')
            
        .col-lg-9
          .bg-7.p-4
            .row
              .col-1
              .col-11
                p.mb-0.texto-blanco El mantenimiento preventivo implica una política de sustitución de componentes de un sistema antes de que el componente falle realmente. Se trata de una acción anticipada y a menudo exige la predicción fiable de los componentes que se desgastan. 

    p.mb-5 En algunos casos, cuando los componentes están sometidos a un desgaste continuo, es posible hacerlo, por ejemplo, en el caso de los rodillos de un accionamiento de papel en los registradores gráficos, los servi potenciadores, los motores, las lámparas de filamento y los contactos de los relés. Si se actúa a tiempo, la fiabilidad de un sistema puede mejorar considerablemente.

    .row.justify-content-center.align-items-center.mb-5
      .col-7.col-lg-4
        figure
          img(src='@/assets/curso/temas/tema2/img6.svg', alt='Imágen decorativa')

      .col-lg-6
        .tarjeta-azul2.p-5
          p.mb-0.texto-blanco La frecuencia del mantenimiento viene determinada por la severidad del entorno al que está sometido el equipo durante su funcionamiento. Por lo general, un momento conveniente para realizar el mantenimiento preventivo es el que precede a los ajustes eléctricos del equipo si son necesarios.


    p.mb-5 Las rutinas de mantenimiento preventivo incluyen los siguientes pasos:

    .row.justify-content-center.align-items-center.mb-5
      .col-md-6.col-xl.mb-4.mb-xl-0
        .tarjeta-numerada.color-primario.p-4(style="height:110px")
          .tarjeta-numerada__numero
            .h2 a
          p.text-center.mt-3
            b Inspección.
          p.text-center

      .col-md-6.col-xl.mb-4.mb-xl-0
        .tarjeta-numerada.color-acento-contenido.p-4(style="height:110px")
          .tarjeta-numerada__numero
            .h2 b
          p.text-center.mt-3
            b Revisión.
          p.text-center

      .col-md-6.col-xl.mb-4.mb-xl-0
        .tarjeta-numerada.color-primario.p-4(style="height:110px")
          .tarjeta-numerada__numero
            .h2 c
          p.text-center
            b Reparación y sustitución de piezas defectuosas. 
          p.text-center

      .col-md-6.col-xl.mb-4.mb-xl-0
        .tarjeta-numerada.color-acento-contenido.p-4(style="height:110px")
          .tarjeta-numerada__numero
            .h2 d
          p.text-center.mt-3
            b Validación y comprobación.
          p.text-center

    p.mb-5 Básicamente, el mantenimiento preventivo implica la sustitución planificada de los componentes, diseñada en torno a la siguiente información:

    .bg-fondo3
      .row.justify-content-center.align-items-center.mb-5
        .col-lg-10
          figure
            img(src='@/assets/curso/temas/tema2/img7.svg', alt='Imágen decorativa')

    separador
    #t_2_1.titulo-segundo.color-acento-botones
       h2 2.1 Precauciones y recomendaciones


    p.mb-5 Además de las rutinas de mantenimiento programadas, se utilizan muchos tipos de dispositivos para proporcionar indicadores que ayuden a los técnicos de mantenimiento a identificar o adelantarse a los problemas que puedan estar desarrollándose. Algunos de ellos son:

    .row.justify-content-center.align-items-center.mb-5
      figure
        img(src='@/assets/curso/temas/tema2/img8.svg', alt='Imágen decorativa')

    .bg-fondo4          
      .row.justify-content-center.align-items-center.mb-5
        figure
          img(src='@/assets/curso/temas/tema2/img9.png', alt='Imágen decorativa')    

        .col-lg-11
          .tarjeta.tarjeta-gris-degrade.p-3
            p.mb-0 Las tareas en estas áreas están relacionadas con las partes mecánicas y eléctricas del equipo electrónico. Por lo tanto, el técnico debe conocer el funcionamiento del sistema mecánico empleado habitualmente en los equipos electrónicos. Es importante conocer y ser capaz de identificar la información relativa al desmontaje y sustitución de los componentes mecánicos en la literatura técnica. Dicha información suele figurar en el manual de servicio del equipo.

      .row.justify-content-center.align-items-center.mb-5
        .col-lg-10.mb-5
          .tarjeta-titulo2.p-2
            h4.mb-0.text-center.texto-blanco De igual forma, dentro de este proceso preventivo se establecen ciertas recomendaciones como las siguientes:

      .row.justify-content-center.align-items-center.mb-5
        .tarjeta.tarjeta--blanca.bg-linea-tiempo.p-5
          SlyderA(tipo="b")
            .row.justify-content-center.align-items-center
              .col-md-4
                figure
                  img(src='@/assets/curso/temas/tema2/img10.svg', alt='Imágen decorativa')

              .col-md-6.mb-4.mb-md-0
                h4.mb-5 <b style= 'color:#5573C6;'>Inspección visual</b>
                p La inspección visual suele conducir a la detección de defectos como conexiones rotas, semiconductores mal asentados, placas de circuito y piezas dañadas por el calor. El procedimiento de corrección de la mayoría de los defectos visibles es sencillo y puede intentarse inmediatamente. 

            .row.justify-content-center.align-items-center
              .col-md-4
                figure
                  img(src='@/assets/curso/temas/tema2/img11.svg', alt='Imágen decorativa')

              .col-md-6.mb-4.mb-md-0
                h4.mb-5 <b style= 'color:#5573C6;'>Sobrecalentamiento</b>
                p No se recomienda realizar comprobaciones periódicas de los dispositivos semiconductores. La mejor comprobación del rendimiento de estos dispositivos es el funcionamiento real en el equipo. Para garantizar la precisión de las mediciones, con algunos de los equipos electrónicos de prueba y medición suele ser necesario comprobar los ajustes eléctricos después de cada 1.000 horas de funcionamiento o cada seis meses, si se utilizan con poca frecuencia. Además, la sustitución de componentes puede hacer necesario a veces el ajuste de los circuitos afectados. 

                p Los manuales de servicio del equipo suelen ofrecer información sobre las comprobaciones de funcionamiento y los ajustes que pueden ser útiles para localizar ciertos problemas en el equipo y corregirlos.

            .row.justify-content-center.align-items-center
              .col-md-4
                figure
                  img(src='@/assets/curso/temas/tema2/img12.svg', alt='Imágen decorativa')

              .col-md-6.mb-4.mb-md-0
                h4.mb-5 <b style= 'color:#5573C6;'>Periodicidad en las comprobaciones</b>
                p No se recomienda realizar comprobaciones periódicas de los dispositivos semiconductores. La mejor comprobación del rendimiento de estos dispositivos es el funcionamiento real en el equipo. Para garantizar la precisión de las mediciones, con algunos de los equipos electrónicos de prueba y medición suele ser necesario comprobar los ajustes eléctricos después de cada 1.000 horas de funcionamiento o cada seis meses, si se utilizan con poca frecuencia. Además, la sustitución de componentes puede hacer necesario a veces el ajuste de los circuitos afectados. 

                p Los manuales de servicio del equipo suelen ofrecer información sobre las comprobaciones de funcionamiento y los ajustes que pueden ser útiles para localizar ciertos problemas en el equipo y corregirlos.


    separador
    #t_2_2.titulo-segundo.color-acento-botones
       h2 2.2 Manejo de la electricidad

    .row.justify-content-center.align-items-center.mb-5
      .col-10.col-lg-4
        figure
          img(src='@/assets/curso/temas/tema2/img13.svg', alt='Imágen decorativa')

      .col-lg-8
        p La suciedad y el polvo son grandes enemigos de los circuitos electrónicos. La acumulación de polvo en las placas de circuitos impresos, formadas por dispositivos integrados y otros dispositivos de estado sólido, provoca el mal funcionamiento de los circuitos de varias maneras.

        .cajon.color-primario.p-4
          p.mb-0 La suciedad puede ocasionar un sobrecalentamiento y la rotura de los componentes. Actúa como una manta aislante y provoca una disipación de calor ineficaz. También proporciona una vía de conducción eléctrica que puede provocar fallos en el equipo. Por lo tanto, el equipo debe limpiarse periódicamente tanto en el exterior como en el interior. El siguiente video presenta aspectos a tener en cuenta en la limpieza del equipo.

    .row.justify-content-center.align-items-center.mb-5(data-aos="flip-down")
      figure
        .video
          iframe(width="560" height="315" src="https://www.youtube.com/embed/123456789" title="Comunicación de marketing digital" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-11
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5
          .bloque-texto-g1__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema2/img14.svg')})`}"
          )
          .bloque-texto-g1__texto.p-4
            p.mb-0 Llevar un plan de trabajo siempre es buena idea a la hora de realizar los mantenimientos preventivos, sobre todo con la manipulación de los componentes electrónicos, los cuales pueden generar una descarga electrostática. 

    .row.justify-content-center.align-items-center.mb-5
      .col-10.col-lg-4
        figure
          img(src='@/assets/curso/temas/tema2/img15.svg', alt='Imágen decorativa')

      .col-lg-8
        p La protección contra las descargas electrostáticas (ESD) forma parte de los requisitos de Inmunidad CEM (Compatibilidad Electromagnética) Se trata de la capacidad de los equipos de funcionar correctamente en su entorno electromagnético limitando la recepción de energía electromagnética que pueda causar daños físicos. La ESD puede ser conducida bajo la forma de un voltaje transitorio o puede ser radiada debido a su rápido tiempo de subida: los armónicos potentes generarán un comportamiento errático por parte de la aplicación al acoplarse con otras señales. Las placas de circuito impreso deben estar protegidas contra los efectos de las descargas electrostáticas.

        p A medida que el área de funcionamiento seguro de los procesos CMOS actuales se hace más estrecha, son cada vez más sensibles a la ESD. Los fabricantes de silicio suelen utilizar el modelo de cuerpo humano (HBM) para caracterizar la susceptibilidad a la ESD en un entorno controlado; sin embargo, esta es mucho mayor en el mundo real a nivel de sistema.

        .cajon.color-primario.p-4
          p.mb-0 Para proteger las piezas eléctricas o electrónicas, los conjuntos y los equipos susceptibles de sufrir daños por ESD, los dispositivos de protección externa contra ESD deben respetar dos puntos principales para cumplir con las normativas y los estándares de seguridad nacionales e internacionales:

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-10.mb-5
        .tarjeta-titulo2.p-2
          h4.mb-0.text-center.texto-blanco Para garantizar el cumplimiento de los requisitos más estrictos, los dispositivos de protección ESD deben combinar:

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-10
        ImagenInfografica
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/temas/tema2/img16.svg', alt='Imágen decorativa')

          .tarjeta.color-adicional-1.p-4(x="5%" y="42%" numero="")
            p.texto-blanco Eficacia de la protección con una baja tensión de cerrado (VCL).

          .tarjeta.color-adicional-1.p-4(x="19.5%" y="75%" numero="")
            p.texto-blanco Transparencia de la protección con una baja corriente de fuga (IRM).

          .tarjeta.color-adicional-1.p-4(x="50%" y="92%" numero="")
            p.texto-blanco Integridad de la señal con una capacitancia baja y un ancho de banda amplio.

          .tarjeta.color-adicional-1.p-4(x="79%" y="76%" numero="")
            p.texto-blanco El dispositivo de protección ESD externo no debe afectar al rendimiento del sistema, incluyendo la tensión de funcionamiento, el ancho de banda y el consumo de energía.

          .tarjeta.color-adicional-1.p-4(x="95%" y="42%" numero="")
            p.texto-blanco El dispositivo de protección ESD externo debe proteger el circuito contra eventos ESD a nivel de sistema mediante el bloqueo de los transitorios de sobretensión ESD.








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
