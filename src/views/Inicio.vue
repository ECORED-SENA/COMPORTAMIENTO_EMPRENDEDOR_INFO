<template lang="pug">
section
  .banner-principal.mb-5
    .container.tarjeta.p-4.p-sm-5(
      :style="{'background-image': `url(${require('@/assets/curso/fondo-banner-principal.svg')})`}"
    )
      .row.justify-content-around.align-items-center
        .col-lg-7.col-xxl-6.banner-principal__info
          .banner-principal__programa
            .h1.mb-0 Comportamiento emprendedor
          
          .h2 Información del programa
          .banner-principal__datos
            ul
              li.mb-3.banner-principal__datos__item
                p.h4.mb-0.me-3.banner-principal__datos__item__titulo Nombre del programa: 
                p.banner-principal__datos__item__texto Comportamiento emprendedor
              li.mb-3.banner-principal__datos__item
                p.h4.mb-0.me-3.banner-principal__datos__item__titulo Código: 
                p.banner-principal__datos__item__texto 13410022
              li.mb-3.banner-principal__datos__item
                p.h4.mb-0.me-3.banner-principal__datos__item__titulo Total: 
                p.banner-principal__datos__item__texto 48 horas
              li.mb-3.banner-principal__datos__item
                p.h4.mb-0.me-3.banner-principal__datos__item__titulo Duración: 
                p.banner-principal__datos__item__texto 4 semanas
              li.mb-3.banner-principal__datos__item
                p.h4.mb-0.me-3.banner-principal__datos__item__titulo Modalidad: 
                p.banner-principal__datos__item__texto virtual              

        .d-none.d-lg-block.col-lg-5
          //- img(src="@/assets/curso/banner-princiapal.svg")
          .video
            | <iframe data-v-1f9e4816="" width="560" height="315" src="https://www.youtube.com/embed/ng9clBjG4nQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="allowfullscreen"></iframe>              
                      

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 1. Presentación

    p.mb-0 ¡Hola!, ¿tiene un sueño por cumplir?, no es el único, todas las personas tienen sueños, por eso el Servicio Nacional de Aprendizaje - SENA lo acompañará a explorar y descubrir todas las herramientas necesarias para desarrollar su comportamiento emprendedor.


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 2. Justificación<br>del programa

    p.mb-4 Dentro del diagnóstico realizado en el Plan Estratégico 2015 – 2018 a la gestión misional de emprendimiento y empresarismo se encontró que no existía una formación específica dirigida al desarrollo de la actitud y comportamiento emprendedor en los aprendices SENA. En su lugar, se encontraron 474 programas que decían contener elementos relacionados con el emprendimiento, pero una vez analizados a fondo, los programas se enfocan en la formación de competencias contables, financieras y administrativas.
      br
      br
      | Lo anterior, aunque no es erróneo, limita la comprensión del emprendimiento únicamente a la creación de empresas. Es importante comprender como lo menciona Hernández (2014) que la actividad emprendedora inicia desde el individuo y, por tanto, el desafío es desarrollar y fortalecer a las personas antes que a las empresas.
      br
      br
      | En efecto, el emprendimiento tradicionalmente ha estado relacionado con el empresarismo y la creación de empresas; sin embargo, es posible extraer una definición mucho más profunda del concepto si se toma en su sentido más amplio: la capacidad que tienen las personas para realizar esfuerzos orientados hacia una meta o un objetivo. El éxito de dichos esfuerzos requiere de tres elementos:

    ol.lista-ol--cuadro
      li.mb-4
        .lista-ol--cuadro__vineta
          span 1
        | Un análisis consciente de las tareas que se deben desempeñar para llegar a alcanzar el fin.
      li.mb-4
        .lista-ol--cuadro__vineta
          span 2
        | Una evaluación de las aptitudes y actitudes asociadas a dichas tareas.
      li.mb-4
        .lista-ol--cuadro__vineta
          span 3
        | Una actitud responsable con la persona misma y con aquello que se ha propuesto.

    p.mb-0 Lo anterior define el comportamiento emprendedor, el cual se encuentra en mayor o menor medida dentro de la estructura de personalidad de los individuos, condicionado por sus fortalezas y debilidades. El fortalecimiento del comportamiento emprendedor permite obtener resultados cada vez más eficaces en tareas diarias, lo que lleva a las personas a ser más competitivas en los diferentes ámbitos de la vida cotidiana. 
      br
      br
      | El propósito del presente programa de formación es ayudar al aprendiz a identificar su comportamiento emprendedor a partir de tres elementos, características emprendedoras personales (CEP’s), triángulo de la responsabilidad y competencias emprendedoras; aplicados a cuatro temas que son de especial relevancia para el día a día: proceso de toma de decisiones, creatividad, estrategia y negociación.  


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 3. Competencias <br>a desarrollar

    p 240201533 - Fomentar cultura emprendedora según habilidades y competencias personales.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 4. Perfil de ingreso.

    ul.lista-ul--color.mb-0
      li
        i.fas.fa-check
        | Cumplir el trámite de selección definido por el Centro.
      li
        i.fas.fa-check
        | Personas naturales mayores de 15 años.  


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 5. Estrategia metodológica

    p Centrada en la construcción de autonomía para garantizar la calidad en el marco de la formación por competencias, el aprendizaje por proyectos y el uso de técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y reales; soportadas en la utilización de las Tecnologías de la Información y la Comunicación (TIC), integradas en ambientes virtuales de aprendizaje, que en todo caso recrean el contexto productivo y, vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias. 
      br
      br
      | Igualmente, debe estimular de manera permanente la autocrítica y la reflexión del aprendiz sobre el quehacer y los resultados de aprendizaje que logra, a través de la vinculación activa de las cuatro fuentes de información para la construcción de conocimiento:
    
    ul.lista-ul--color.mb-0
      li
        i.fas.fa-chevron-right
        | El instructor – Tutor
      li
        i.fas.fa-chevron-right
        | El entorno
      li
        i.fas.fa-chevron-right
        | Las TIC
      li
        i.fas.fa-chevron-right
        | El trabajo colaborativo


  //- Créditos
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 Créditos

    
    .creditos
      div(
        v-for="(creditoKey, index) of Object.keys(creditosData)"
        :class="index != Object.keys(creditosData).length -1 ? 'mb-4' : ''" 
      )
        .creditos__titulo {{configTitulos[creditoKey]}}
        table
          tbody
            tr(
              v-for="(item, idx) of creditosData[creditoKey]" 
              :key="creditoKey+idx"
            )
              td.text-bold(colspan='2' v-html="renderText(item.nombre)")
              td(colspan='2' v-html="renderText(item.cargo)")
              td(colspan='3' v-html="renderText(item.centro)")

  Footer

</template>
<script>
export default {
  name: 'Inicio',
  data: () => ({
    configTitulos: {
      liderEquipo: 'ECOSISTEMA DE RECURSOS EDUCATIVOS DIGITALES',
      contenidoInstruccional: 'CONTENIDO INSTRUCCIONAL',
      desarrolloProducto:
        'DISEÑO Y DESARROLLO DE RECURSOS EDUCATIVOS DIGITALES',
      gestoresRepositorio: 'GESTORES DE REPOSITORIO',
    },
  }),
  computed: {
    creditosData() {
      return this.$config.creditos
    },
  },
  methods: {
    renderText(textObj) {
      let newText = ''
      if (Array.isArray(textObj)) {
        textObj.forEach((texto, index) => {
          newText += (index ? '<br/>' : '') + texto
        })
      } else {
        newText += textObj
      }
      return newText
    },
  },
}
</script>

<style lang="sass">
.creditos
  td, th
    border-color: $color-sistema-c
</style>
