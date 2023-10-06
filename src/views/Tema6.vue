<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 6
      h1 Documentación técnica

    .row.justify-content-center.align-items-center
      .col-lg-3
        figure
          img(src='@/assets/curso/temas/tema6/img1.svg', alt='imagen decorativa')
      .col-lg-8
        p Todas las empresas de todos los sectores necesitan documentación técnica. No importa si está orientada al consumidor, como las instrucciones para montar una cómoda, o a su personal interno sobre las mejores prácticas para archivar facturas: todo proceso estandarizado necesita una documentación adecuada. Los documentos técnicos muestran al usuario una descripción del producto o proceso, le explican lo que hay por delante y le enseñan a superar cada paso o reto, lo que le lleva al resultado deseado.

        .cajon.color-acento-contenido.p-4
          p Todos los tipos de documentación técnica se dividen en tres categorías principales: documentación de productos, documentación de procesos y documentos de ventas y marketing. A continuación, se detallan los dos primeros.

    TabsB.color-primario.mt-5
      .py-4.py-md-5(titulo="Documentación de producto")
        .row
          .col-md-4
            figure
              img(src='@/assets/curso/temas/tema6/img2.svg', alt='Texto que describa la imagen')

          .col-md-8.mb-4.mb-md-0
            p La documentación del producto abarca las guías detalladas, los manuales de formación y la información que muestra a los usuarios cómo debe funcionar un producto o cómo utilizarlo.

            p Cuando la mayoría de la gente dice “documentación técnica”, se refiere a la documentación del producto. Los documentos de producto suelen incluir instrucciones y tutoriales para ayudar a los usuarios finales a realizar una tarea. Incluyen guías, ilustraciones y hojas de referencia que cubren:

        .row.justify-content-center.align-items-center
          ul.lista-ul--color.lista-ul--separador
            li 
              i.fas.fa-check-circle
              | Información sobre los requisitos o las especificaciones del sistema que los usuarios necesitan para que el producto funcione eficazmente.

            li 
              i.fas.fa-check-circle
              | Instrucciones de instalación y uso.

            li 
              i.fas.fa-check-circle
              | Preguntas frecuentes (FAQ) o base de conocimientos.

          .cajon.color-acento-contenido.p-4
            p Para la documentación del producto, se recomienda aprovechar el software de escritura técnica y las herramientas de documentación de software para crear una documentación fácil de usar y de ayuda.

      .py-4.py-md-5(titulo="Documentación de procesos")
        .row
          .col-md-4.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/temas/tema6/img3.svg', alt='Texto que describa la imagen')

          .col-md-8
            p La documentación de procesos, por otro lado, es un documento que muestra a un equipo interno lo que necesita saber para ejecutar correctamente una tarea. Abarca información que ayuda a crear consistencia y responsabilidad dentro de su organización, incluyendo:

            ul.lista-ul--color.lista-ul--separador
              li 
                i.fas.fa-check-circle
                | Planes, calendarios y notas que establecen normas y patrones para diferentes procesos.

              li 
                i.fas.fa-check-circle
                | Informes y métricas que hacen un seguimiento del proyecto, el personal y el rendimiento de los recursos.

              li 
                i.fas.fa-check-circle
                | Wiki interno

    separador
    #t_6_1.titulo-segundo.color-acento-botones
       h2 6.1 Fichas técnicas

    .row.justify-content-center.align-items-center
      .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5
        .bloque-texto-g__img(
          :style="{'background-image': `url(${require('@/assets/curso/temas/tema6/img4.svg')})`}"
        )
        .bloque-texto-g__texto.p-4
          p.mb-0 Una hoja de datos técnicos (TDS), es un documento proporcionado con un producto que enumera varios elementos de información sobre el mismo. A menudo, las hojas de datos técnicos incluyen la composición del producto, los métodos de uso, los requisitos de funcionamiento, las aplicaciones habituales, las advertencias y las imágenes del producto.

    .bg-fondo3.mt-5
      .row.justify-content-center.align-items-center.mb-5
        .col-lg-5.mb-5
          .tarjeta-titulo2.p-2
            h4.mb-0.text-center.texto-blanco Ejemplo de una ficha técnica. Tomado de Yumpu (2015)

      .row.justify-content-center.align-items-center.mb-5
        .col-lg-8
          figure
            img(src='@/assets/curso/temas/tema6/img5.svg', alt='imagen decorativa')


    .row.justify-content-center.align-items-center
      .col-lg-3
        figure
          img(src='@/assets/curso/temas/tema6/img6.svg', alt='imagen decorativa')
      .col-lg-8
        .cajon.color-acento-contenido.p-4
          p Una hoja de datos técnicos (TDS) se utiliza tanto con fines informativos como publicitarios. Desde el punto de vista informativo, una TDS contiene consejos útiles sobre el producto, por ejemplo: cómo utilizarlo, de qué está hecho, qué cosas hay que tener en cuenta al utilizar el producto, y su nombre oficial y las especificaciones estándar de la industria. Desde el punto de vista del marketing, puede contener fotos e ilustraciones en color, así como secciones enteras en las que se describen los beneficios que el producto aportará al usuario final .

        p.mt-3 Una TDS no debe confundirse con una hoja de datos de seguridad de los materiales (MSDS). El objetivo de la MSDS es informar específicamente al usuario final de los peligros que puede presentar el producto. Este no es el objetivo de la TDS, aunque puede incluir varias consideraciones de seguridad. Además, las hojas de datos de seguridad de los materiales deben seguir una plantilla determinada guiada por una norma industrial, mientras que una hoja de datos técnicos puede presentarse a discreción del fabricante del producto y contener la información que considere oportuna. Muchos países exigen que un material o producto tenga una ficha de datos de seguridad; la mayoría no exige una ficha técnica.

    separador
    #t_6_2.titulo-segundo.color-acento-botones
       h2 6.2 Hoja de vida

    .row.justify-content-center.align-items-center
      p La hoja de vida para un equipo de cómputo es un formato en donde se registra la información del equipo y se lleva un registro del tiempo de utilización del mismo, tal como se muestra en el ejemplo visual.

      .col-10
        .titulo-sexto.color-acento-botones.mb-3
          h5 Figura 2.
          span Ejemplo de una hoja de vida para un equipo de computo  
        figure
          img(src='@/assets/curso/temas/tema6/img7.svg', alt='imagen decorativa')
          figcaption <b>Nota.</b> Tomado de ICBF (2022)

    .row.justify-content-center.align-items-center.mt-5.mb-3
      .col-lg-7
        .tarjeta-titulo2.p-2
          h4.mb-0.text-center.texto-blanco Este formato o registro sirve para medir la obsolescencia tecnológica.

    .row.justify-content-center.align-items-center
      .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5
        .bloque-texto-g__img(
          :style="{'background-image': `url(${require('@/assets/curso/temas/tema6/img8.svg')})`}"
        )
        .bloque-texto-g__texto.p-4
          p.mb-0 A grandes rasgos, la obsolescencia tecnológica puede considerarse como una devaluación de un artículo debido al progreso tecnológico y, por lo tanto, suele producirse cuando una nueva tecnología o producto sustituye a otro más antiguo que no tiene por qué ser necesariamente disfuncional. La literatura tiene muchos ejemplos: el telégrafo, la máquina de vapor y los faxes, entre otros.

      p.mt-5 Uno de los retos de la literatura es medir adecuadamente la obsolescencia tecnológica. El flujo de conocimientos no deja ningún rastro que seguir, lo que puede suponer un grave problema para medir la obsolescencia tecnológica más allá de los estudios de casos. Sin embargo, las citas de patentes son una excepción a este problema. Por lo tanto, la literatura ha utilizado las citas de patentes para relacionar la relevancia de la difusión del conocimiento con las tecnologías pasadas. En este sentido, el número de citas que recibe una patente en un periodo de tiempo determinado puede reflejar su utilidad e impacto en la generación de nuevas innovaciones.

    .row.justify-content-center.align-items-center.mt-3
      .col-10
        .row.justify-content-center.align-items-center.mt-3
          .col-lg-4
            figure
              img(src='@/assets/curso/temas/tema6/img9.svg', alt='imagen decorativa')

          .col-lg-8.bg1-tema6
            p.p-5.text-small Lo ideal sería que una medida de este tipo captará no sólo el stock tecnológico existente en una empresa en un momento determinado, sino también el esfuerzo de un competidor en investigación y desarrollo (I+D), la aparición de nuevas industrias y la canibalización de una empresa a través de productos más nuevos. Lamentablemente, la naturaleza multifacética de la obsolescencia tecnológica se ha medido indirectamente en la literatura a través de las citas de patentes.

    separador
    #t_6_3.titulo-segundo.color-acento-botones
       h2 6.3 Planes

    .row.justify-content-center.align-items-center
      p El proceso de programación de un plan de mantenimiento puede dividirse en ocho pasos manejables. 

    .bg-fondo_tema6 
      .row.justify-content-center.align-items-center
        ImagenInfograficaB.color-acento-botones
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/temas/tema6/img10.svg', alt='Texto que describa la imagen')
        
          div(x="14%" y="42%" )
            .h5.mb-2 titulo
            p 
        
          div(x="38%" y="8%" )
            .h5.mb-2 titulo
            p 

          div(x="62%" y="42%" )
            .h5.mb-2 titulo
            p 
        
          div(x="86%" y="8%" )
            .h5.mb-2 titulo
            p 

          div(x="14%" y="92%" )
            .h5.mb-2 titulo
            p 
        
          div(x="38%" y="56%" )
            .h5.mb-2 titulo
            p 

          div(x="62%" y="92%" )
            .h5.mb-2 titulo
            p 
        
          div(x="86%" y="56%" )
            .h5.mb-2 titulo
            p 

    
       
    

        

</template>

<script>
export default {
  name: 'Tema6',
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
