<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Administración y gestión

    .row.justify-content-center.align-items-center.mb-5
      figure
        img(src='@/assets/curso/temas/tema4/img1.png', alt='Imágen decorativa')    

      .col-lg-11
        .tarjeta.tarjeta-gris-degrade.p-3
          p.mb-0 El desgaste físico con el paso del tiempo y la acción de los elementos ambientales es inevitable, tanto en el caso de las instalaciones como de los equipos. El objetivo del mantenimiento es prolongar la vida de los equipos/sistemas y aumentar el tiempo medio entre fallos (MTBF) Algunosde los objetivos generales de un programa de gestión del mantenimiento son:

    .row.justify-content-center.align-items-center.mb-5
      SlyderF(columnas="col-lg-6 col-xl-4")
        .tarjeta.tarjeta-gris4.p-4
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema4/img2.svg' alt='Imágen decorativa')
          p.text-center Garantizar el máximo tiempo de funcionamiento de los equipos, con el mínimo coste de mantenimiento.

        .tarjeta.tarjeta-gris4.p-4
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema4/img3.svg' alt='Imágen decorativa')
          p.text-center Proporcionar un medio de recogida de datos, incluidos los costes, etc., para analizar y mejorar el mantenimiento.

        .tarjeta.tarjeta-gris4.p-4
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema4/img4.svg' alt='Imágen decorativa')
          p.text-center Establecer métodos de evaluación del rendimiento del trabajo de los técnicos, útiles como retroalimentación para el director de mantenimiento.

        .tarjeta.tarjeta-gris4.p-4
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema4/img5.svg' alt='Imágen decorativa')
          p.text-center Ayudar a establecer condiciones de trabajo seguras tanto para el departamento de operaciones como para el personal de mantenimiento. 

        .tarjeta.tarjeta-gris4.p-4
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema4/img6.svg' alt='Imágen decorativa')
          p.text-center Mejorar las competencias de los supervisores y técnicos mediante programas de formación y educación continua.

        .tarjeta.tarjeta-gris4.p-4
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema4/img7.svg' alt='Imágen decorativa')
          p.text-center Minimizar el tiempo de inactividad.

    .row.justify-content-center.align-items-center.mb-5
      .cajon.color-primario.p-4
        p.mb-0 Una mejor organización del mantenimiento, de controles adecuados y de una planificación y programación eficaces, debe apoyarse en un mayor uso de las nuevas tecnologías y en un enfoque sistemático.

    separador
    #t_4_1.titulo-segundo.color-acento-contenido
       h2 4.1 Residuos ambientales

    .row.justify-content-center.align-items-center.mb-5
      .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5
        .bloque-texto-g__img(
          :style="{'background-image': `url(${require('@/assets/curso/temas/tema4/img8.svg')})`}"
        )
        .bloque-texto-g__texto.p-4
          p.mb-0 Con la introducción de equipos electrónicos en casi todos los campos de actividad, se considera esencial que las organizaciones desarrollen una política sólida de mantenimiento de equipos para garantizar la continuidad del servicio de los mismos. Los objetivos de la gestión del mantenimiento de los equipos son los siguientes:

      .row.justify-content-center.align-items-center.mb-5
        .col-11.col-lg-8
          .tarjeta-gris1.p-4
            .row.align-items-center
              .col-3.col-md-2.col-lg-1
                figure
                  img(src='@/assets/curso/temas/tema2/img3.svg', alt='Imágen decorativa').img3-4-tm2
              
              .col-lg-10.col-md-10
                b Un sistema de mantenimiento manejable y económico, minimizando el tiempo necesario para el mantenimiento. 

          .tarjeta-gris2.p-4
            .row.align-items-center
              .col-3.col-md-2.col-lg-1
                figure
                  img(src='@/assets/curso/temas/tema2/img4.svg', alt='Imágen decorativa').img3-4-tm2
              
              .col-lg-10.col-md-10
                b Documentación esencial necesaria para todos los equipos.

        .col-8.col-lg-4
          figure
            img(src='@/assets/curso/temas/tema4/img9.svg', alt='Imágen decorativa').img9-tm4

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-10.mb-5
        .tarjeta-titulo2.p-2
          h4.mb-0.text-center.texto-blanco Normalmente, los fabricantes de equipos electrónicos de renombre ofrecen un servicio posventa eficiente y eficaz, que podría clasificarse como sigue:


    .row.justify-content-center.align-items-center.mb-5
      .col-lg-5
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/tema2/img3.svg' alt='AvatarTop')
          .tarjeta.color-primario--borde
            .p-3
              p.mt-lg-4 Servicio de averías, que se presta cuando el equipo se avería y no funciona satisfactoriamente.

      .col-lg-5
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/tema2/img4.svg' alt='AvatarTop')
          .tarjeta.color-acento-contenido--borde
            .p-3
              p Servicio por contrato, en el que el proveedor del equipo y el usuario acuerdan las condiciones del contrato para los servicios de mantenimiento preventivo y correctivo.

    .row.justify-content-center.align-items-center.mb-5
      .col-7.col-lg-4
        figure
          img(src='@/assets/curso/temas/tema4/img10.svg', alt='Imágen decorativa')

      .col-lg-8
        .tarjeta-verde.p-5
          p.mb-0 Los grandes establecimientos como los servicios de defensa, los departamentos de telecomunicaciones y los hospitales no pueden depender únicamente de los servicios ofrecidos por los fabricantes. A menudo, estos servicios suelen ser caros y pueden no estar disponibles cuando se necesitan durante una avería de emergencia del sistema. Por lo tanto, es necesario crear instalaciones de servicio internas y sólo en el caso de una avería muy compleja se solicitan los servicios de los fabricantes .

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8
        p En algunas situaciones, en las que los equipos son pesados y no pueden ser transportados al centro de reparación, es imprescindible disponer de unas instalaciones de servicio móviles. Mientras que en algunos casos es suficiente con llevar una caja de herramientas y una buena gama de componentes electrónicos para atender las necesidades de mantenimiento correctivo y preventivo, en otros casos puede ser necesario transportar equipos de prueba como un osciloscopio, fuentes de alimentación, generador de impulsos y multímetro digital, etc. Las furgonetas de mantenimiento móvil especialmente diseñadas pueden estar dotadas de equipos de prueba electrónicos adecuados y de instalaciones de taller mecánico para atender estos requisitos especializados.

        .cajon.color-primario.p-4
          p.mb-0 La política de mantenimiento aplicable a una situación concreta dependerá obviamente de varios factores. Algunos de estos son:

      .col-10.col-lg-4
        figure
          img(src='@/assets/curso/temas/tema4/img11.svg', alt='Imágen decorativa')

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-10
        figure
          img(src='@/assets/curso/temas/tema4/img12.svg', alt='Imágen decorativa')

    .row.justify-content-center.align-items-center.mb-5
      figure
        img(src='@/assets/curso/temas/tema4/img13.svg', alt='Imágen decorativa')

      .col-lg-6
        .tarjeta.tarjeta-azul3.p-4
          p.mb-0.texto-blanco Para la localización de averías en los equipos electrónicos, se debe emplear personal cualificado. A diferencia de los equipos mecánicos, en los que a veces basta con aceitar y engrasar para restablecer el funcionamiento del sistema defectuoso, los equipos electrónicos necesitan una comprensión profunda de la teoría de funcionamiento del sistema y el conocimiento de las pruebas de los componentes activos y pasivos antes de poder ser manipulados. También hay que tener en cuenta que cualquier intento de reparación de un equipo electrónico por parte de personas no cualificadas puede acarrear mayores problemas por su mala manipulación y dificultaría el trabajo del técnico cualificado si posteriormente se le remite .

    separador
    #t_4_2.titulo-segundo.color-acento-contenido
       h2 4.2 Elementos de protección

    p.mb-5 Las organizaciones suelen tener la opción de establecer instalaciones internas para el mantenimiento de los equipos o depender de los proveedores/fabricantes para el mantenimiento programado y por avería. A continuación, se explica cada uno de los posibles servicios.

    .row.justify-content-center.align-items-center.mb-5
      .tarjeta.tarjeta--blanca.bg-linea-tiempo.p-5
        SlyderA(tipo="b")
          .row.justify-content-center.align-items-center
            .col-md-4
              figure
                img(src='@/assets/curso/temas/tema4/img14.svg', alt='Imágen decorativa')

            .col-md-6.mb-4.mb-md-0
              h4.mb-5 <b style= 'color:#5573C6;'>Servicio interno</b>
              p Proporciona el servicio más rentable y oportuno para el mantenimiento de los equipos. Sin embargo, es esencial que el personal haya recibido formación de los fabricantes o de alguna organización independiente. Además, el soporte técnico de los manuales de servicio y la disponibilidad de las piezas siguen siendo las principales preocupaciones. La frecuencia de las reparaciones y la cantidad de equipos similares tendrán un impacto directo en la competencia del personal técnico que mantiene los equipos.

          .row.justify-content-center.align-items-center
            .col-md-4
              figure
                img(src='@/assets/curso/temas/tema4/img15.svg', alt='Imágen decorativa')

            .col-md-6.mb-4.mb-md-0
              h4.mb-5 <b style= 'color:#5573C6;'>Servicio del fabricante</b>
              p El servicio del fabricante/proveedor es a veces la única opción disponible en el caso de muchos tipos de equipos, especialmente del tipo complejo. Normalmente, los fabricantes están en la mejor posición para proporcionar una gama completa de servicios, tanto de mantenimiento preventivo como correctivo, a sus equipos. Además, las modificaciones de campo y algunas actualizaciones del sistema pueden realizarse como parte del contrato del fabricante.

          .row.justify-content-center.align-items-center
            .col-md-4
              figure
                img(src='@/assets/curso/temas/tema4/img16.svg', alt='Imágen decorativa')

            .col-md-6.mb-4.mb-md-0
              h4.mb-5 <b style= 'color:#5573C6;'>Servicio de terceros</b>
              p Puede ser una alternativa al servicio prestado por el fabricante. Este servicio se suele utilizar para los equipos más comunes, especialmente los productos electrónicos de consumo, para los que las empresas han creado un gran número de centros de mantenimiento. En el caso de los equipos profesionales, la disponibilidad de piezas de repuesto, software y equipos de prueba especializados debe tenerse en cuenta antes de entregar cualquier equipo al servicio de terceros, ya que el apoyo del fabricante puede ser una cuestión importante.

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-7.mb-5
        .tarjeta-titulo3.p-2
          h4.mb-0.text-center.texto-blanco Lo anterior va de la mano con los tipos de contrato base del mercado. 

    .row.justify-content-center.align-items-center.my-5
      .col-lg-10
        ImagenInfografica
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/temas/tema4/img17.svg', alt='Imágen decorativa')

          .tarjeta.color-adicional-1.p-4(x="15%" y="94%" numero="")
            h5.texto-blanco Contrato de servicio completo
            p.texto-blanco Incluye tanto el servicio programado (mantenimiento preventivo) como el no programado (reparación). Este tipo de contrato requiere la menor participación del personal de servicio interno o de los operadores.

          .tarjeta.color-adicional-1.p-4(x="51%" y="94%" numero="")
            h5.texto-blanco Contrato de sólo reparación
            p.texto-blanco Este tipo de contrato es viable cuando existe la capacidad de realizar un mantenimiento preventivo interno. En algunos campos críticos, como los equipos hospitalarios, se recomienda un mínimo de un mantenimiento preventivo anual.

          .tarjeta.color-adicional-1.p-4(x="86%" y="94%" numero="")
            h5.texto-blanco Contrato de sólo mantenimiento preventivo
            p.texto-blanco En el caso de equipos de gran complejidad técnica en los que se necesita un servicio externo para el mantenimiento preventivo, es preferible suscribir un contrato de sólo mantenimiento preventivo. Este tipo de contratos se justifica cuando la frecuencia de las reparaciones y/o los costes no justifican la necesidad de un contrato de servicio completo.

    .row.mb-5
      .col-lg-6
        ul.lista-ul--color.fa-ul2
          li 
            i.fas.fa-check-circle
            p.mb-0 #[b Alcance del servicio:] mantenimiento preventivo, reparación de equipos, mejoras de ingeniería, sustitución rutinaria de piezas, etc.
          li 
            i.fas.fa-check-circle
            p.mb-0 #[b Tiempo de respuesta:] tiempo de desplazamiento, gastos de dietas.
          li 
            i.fas.fa-check-circle
            p.mb-0 #[b Condiciones de pago:] plazos.
          li 
            i.fas.fa-check-circle
            p.mb-0 #[b Duración del contrato:] fecha de inicio y finalización del contrato.
          li 
            i.fas.fa-check-circle
            p.mb-0 #[b Limitaciones del servicio:] elementos de servicio/reparación/reemplazos no incluidos en el contrato.
          li 
            i.fas.fa-check-circle
            p.mb-0 #[b Rescisión del contrato:] condiciones para definir las situaciones que exigen la rescisión del contrato, como el impago de los honorarios acordados, la inadecuación de los servicios de mantenimiento, etc.
          li 
            i.fas.fa-check-circle
            p.mb-0 #[b Seguro de responsabilidad civil:] cobertura de la responsabilidad civil contratada, productos y operaciones.

          li 
            i.fas.fa-check-circle
            p.mb-0 #[b Garantías:] la empresa proporcionará una garantía para que todos los productos o servicios cumplan con todas las leyes, reglamentos y normas locales, estatales y federales aplicables.

      .col-lg-6
        ul.lista-ul--color.fa-ul2
          li 
            i.fas.fa-check-circle
            p.mb-0 #[b Indemnización:] la responsabilidad del proveedor de servicios de indemnizar y mantener a la instalación y a sus empleados por cualquier reclamación, pérdida, daño, responsabilidad o gasto que la instalación pueda sufrir como resultado de los actos u omisiones de la empresa contratante o sus empleados.
          li 
            i.fas.fa-check-circle
            p.mb-0 #[b Documentación:] todas las actividades contempladas en el contrato con las acciones periódicas realizadas deben estar bien documentadas en el informe de servicio.
          li 
            i.fas.fa-check-circle
            p.mb-0 #[b Garantía de tiempo de funcionamiento:] debe estar bien definida y se debe especificar la penalización en caso de incumplimiento.
          li 
            i.fas.fa-check-circle
            p.mb-0 #[b Conflictos:] autoridad competente para decidir los casos de litigio.
          li 
            i.fas.fa-check-circle
            p.mb-0 #[b Firmantes autorizados:] a especificar por ambas partes.

    .row.justify-content-center.align-items-center.mb-5
      .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5
        .bloque-texto-g__img(
          :style="{'background-image': `url(${require('@/assets/curso/temas/tema4/img18.svg')})`}"
        )
        .bloque-texto-g__texto.p-4
          p.mb-0 Luego, de comprender las opciones de servicio se hace necesario también entender los elementos de protección personal, ya que unas condiciones de trabajo seguras ayudan a evitar lesiones a las personas y daños a los equipos informáticos. Un espacio de trabajo seguro está limpio, organizado y adecuadamente iluminado. Por tanto, todo el mundo debe entender y seguir los procedimientos de seguridad. El siguiente recurso expone algunas precauciones básicas, pautas de seguridad y herramientas esenciales que suelen usarse cuando se trabaja con un computador son:

    .row.justify-content-center.align-items-center.my-5
      .bg-tarjeta3      
        .row.justify-content-center.align-items-center.mb-3
          .col-md-6.col-lg-2.mb-3
            .tarjeta.tarjeta-azul4.p-2
              .row.justify-content-center.align-items-center.mb-5
                .col-6
                  figure.mb-3
                    img(src='@/assets/curso/temas/tema4/img19.svg', alt='Imágen decorativa')

                h4.text-center.texto-blanco Precauciones básicas de seguridad

          .col-md-6.col-lg-2.mb-3
            .tarjeta.tarjeta-gris5.p-2
              .row.justify-content-center.align-items-center.mb-5
                .col-6
                  figure.mb-3
                    img(src='@/assets/curso/temas/tema4/img20.svg', alt='Imágen decorativa')

                p.text-center Quítese el reloj y las joyas y asegure la ropa suelta.

          .col-md-6.col-lg-2.mb-3
            .tarjeta.tarjeta-gris5.p-2
              .row.justify-content-center.align-items-center.mb-5
                .col-6
                  figure.mb-3
                    img(src='@/assets/curso/temas/tema4/img21.svg', alt='Imágen decorativa')

                p.text-center Apague el equipo y desenchúfelo antes de realizar el mantenimiento

          .col-md-6.col-lg-2.mb-3
            .tarjeta.tarjeta-gris5.p-2
              .row.justify-content-center.align-items-center.mb-5
                .col-6
                  figure.mb-3
                    img(src='@/assets/curso/temas/tema4/img22.svg', alt='Imágen decorativa')

                p.text-center Cubra los bordes afilados del interior de la caja del ordenador con cinta adhesiva.

          .col-md-6.col-lg-2.mb-3
            .tarjeta.tarjeta-gris5.p-2
              .row.justify-content-center.align-items-center.mb-5
                .col-6
                  figure.mb-3
                    img(src='@/assets/curso/temas/tema4/img23.svg', alt='Imágen decorativa')

                p.text-center No abra nunca una fuente de alimentación o un monitor CRT.

        .row.justify-content-center.align-items-center.mb-3
          .col-md-6.col-lg-2.mb-3
            .tarjeta.tarjeta-gris5.p-2
              .row.justify-content-center.align-items-center.mb-5
                .col-6
                  figure.mb-3
                    img(src='@/assets/curso/temas/tema4/img24.svg', alt='Imágen decorativa')

                p.text-center No toque las zonas de las impresoras que estén calientes o que utilicen alta tensión.

          .col-md-6.col-lg-2.mb-3
            .tarjeta.tarjeta-gris5.p-2
              .row.justify-content-center.align-items-center.mb-5
                .col-6
                  figure.mb-3
                    img(src='@/assets/curso/temas/tema4/img25.svg', alt='Imágen decorativa')

                p.text-center Sepa dónde se encuentra el extintor de incendios y cómo utilizarlo.

          .col-md-6.col-lg-2.mb-3
            .tarjeta.tarjeta-gris5.p-2
              .row.justify-content-center.align-items-center.mb-5
                .col-6
                  figure.mb-3
                    img(src='@/assets/curso/temas/tema4/img26.svg', alt='Imágen decorativa')

                p.text-center Mantenga los alimentos y las bebidas fuera de su espacio de trabajo.

          .col-md-6.col-lg-2.mb-3
            .tarjeta.tarjeta-gris5.p-2
              .row.justify-content-center.align-items-center.mb-5
                .col-6
                  figure.mb-3
                    img(src='@/assets/curso/temas/tema4/img27.svg', alt='Imágen decorativa')

                p.text-center Mantenga su espacio de trabajo limpio y libre de desorden.

          .col-md-6.col-lg-2.mb-3
            .tarjeta.tarjeta-gris5.p-2
              .row.justify-content-center.align-items-center.mb-5
                .col-6
                  figure.mb-3
                    img(src='@/assets/curso/temas/tema4/img28.svg', alt='Imágen decorativa')

                p.text-center Dobla las rodillas cuando levantes objetos pesados para no lesionarte la espalda.

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-10
        p Siga las pautas de seguridad eléctrica para evitar incendios, lesiones y muertes por electricidad en el hogar y en el lugar de trabajo. Las fuentes de alimentación y los monitores CRT contienen alta tensión.

        .tarjeta-amarilla.p-4.mb-3
          p.mb-0 <b>PRECAUCIÓN:</b> no utilice la muñequera antiestática cuando repare fuentes de alimentación o monitores CRT. Sólo los técnicos experimentados deben intentar reparar las fuentes de alimentación y los monitores CRT. Los dispositivos eléctricos tienen ciertos requisitos de energía. Por ejemplo, los adaptadores de CA se fabrican para ordenadores portátiles específicos. Intercambiar los cables de alimentación con un tipo diferente de portátil o dispositivo puede causar daños tanto en el adaptador de CA como en el portátil.

      h4.text-center Algunas herramientas más esenciales

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-10
        .tarjeta.bg-tarjeta.p-4.mb-3
          .row.justify-content-center.align-items-center
            .col-2
              h1.texto-blanco 01
            .col-10
              p Un multímetro digital: se utiliza para comprobar las tensiones de alimentación y la conectividad de los cables. Muchos procedimientos de resolución de problemas requieren que se compruebe la tensión y la resistencia. Los valores se miden con un multímetro manual. El medidor puede tener una lectura analógica o digital (LCD) y utilizará un par de sondas para conectarse al dispositivo que se está probando.

        .tarjeta.bg-tarjeta.p-4.mb-3
          .row.justify-content-center.align-items-center
            .col-2
              h1.texto-blanco 02
            .col-10
              p Equipos y materiales de limpieza: por ejemplo, productos químicos de limpieza de contacto, aire comprimido, cepillo de cerdas, aspirador de mano.

        .tarjeta.bg-tarjeta.p-4.mb-3
          .row.justify-content-center.align-items-center
            .col-2
              h1.texto-blanco 03
            .col-10
              p Enchufes de envoltura: se utilizan para diagnosticar los problemas de los puertos serie y paralelo.

        .tarjeta.bg-tarjeta.p-4.mb-3
          .row.justify-content-center.align-items-center
            .col-2
              h1.texto-blanco 04
            .col-10
              p Muñequeras, alfombrillas y bolsas antiestáticas: La descarga estática puede dañar las placas de circuitos, por lo que el equipo antiestático es vital. Los componentes de repuesto del PC deben guardarse siempre en bolsas antiestáticas de protección, como las que utilizan los fabricantes para suministrar las tarjetas de interfaz.

    separador
    #t_4_3.titulo-segundo.color-acento-contenido
       h2 4.3 Normativa

    p.mb-5 La norma ISO 20000 puede ayudar a su organización a evaluar su ITSM, mejorar los servicios, demostrar su capacidad para cumplir los requisitos de los clientes y crear un marco para la evaluación independiente. Ventajas de la certificación ISO 20000 para los proveedores de servicios son:

    .bg-fondo3
      .row.justify-content-center.align-items-center.mb-5
        .col-10.col-lg-4
          figure
            img(src='@/assets/curso/temas/tema4/img29.svg', alt='Imágen decorativa')















</template>

<script>
export default {
  name: 'Tema4',
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
