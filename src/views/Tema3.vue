<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Principios de contabilidad y los estados financieros

    p.mb-5 El analista financiero, para poder llevar a cabo su función, requiere de un conocimiento completo y profundo de la esencia de los estados financieros, las partidas que los forman, sus problemas y limitaciones.

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-down-right")(style="background-color:#B0BDA0") 
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema3/img-01.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p Antes de entrar a definir formalmente los #[b estados financieros,] conviene recordar algunos conceptos básicos con el fin de ubicarse dentro de la materia que se quiere tratar.
        br
        br
        p La disciplina que da origen a los estados financieros es la contabilidad y esta se define como “el arte de registrar, clasificar, resumir e interpretar los datos financieros, con el fin de que éstos sirvan a los diferentes estamentos interesados en las operaciones de una empresa”. Ortiz (2011).

    p.mb-4 La manera más lógica y comúnmente aceptada de cumplir esta tarea, asignada a la contabilidad, es a través de informes contables, denominados estados financieros.

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-3.col-12.mb-3.d-lg-flex.d-none(data-aos="fade-left")
        figure
          img(src='@/assets/curso/temas/tema3/img-16.svg', alt='Imagen decorativa')

      .col-lg-7.col-12.mb-3(data-aos="fade-right")
        .bloque-texto-b.color-primario.py-4
          .bloque-texto-b__texto
            p Los estados financieros se preparan para presentar en un informe periódico acerca de la situación del negocio, los progresos de la administración y los resultados obtenidos durante el período que se estudia. Constituyen una combinación de hechos registrados, convenciones contables y juicios personales.
            br
            br
            p En Colombia, la elaboración y presentación de los estados financieros debe realizarse, de acuerdo con las Normas Internacionales de Información Financiera (NIIF), las cuales garantizan la uniformidad, transparencia y comparabilidad de la información contable. Las convenciones y juicios aplicados los afectan de manera sustancial, y su idoneidad depende esencialmente de la competencia de quienes los formulan y de su respeto por los principios y las convenciones contables de aceptación general.
    
    .row.justify-content-center.align-items-center.mb-4(data-aos="flip-up")
      .col-lg-10.col-12
        p Para aclarar el anterior concepto, se puede decir que:
        
    .row.justify-content-center.align-items-center.mb-0(data-aos="flip-up")
      .col-lg-10.col-12
        .tarjeta.tarjeta--gris2.p-2.mb-4
          .row.justify-content-center.align-items-center
            .col-3.d-none.d-lg-block.order-lg-2.order-2.mb-lg-0
              figure
                img(src='@/assets/curso/temas/tema3/img-17.png', alt='Imagen decorativa')
            .col-lg-6.col-12.mb-3.order-lg-1.order-2.mb-lg-0.p-4
              ol.lista-ol
                li 
                  span.text-bold 1. 
                  | Los hechos registrados se refieren a los datos obtenidos de los registros contables, tales como la cantidad de efectivo o el valor de las obligaciones.

                li 
                  span.text-bold 2. 
                  | Las convenciones contables se relacionan con ciertos procedimientos y supuestos, tales como la forma de valorizar los activos o la capitalización de ciertos gastos.
                li
                  span.text-bold 3.
                  | El juicio personal hace referencia a las decisiones que puede tomar el contador en cuanto a utilizar tal o cual método de depreciación o valoración de inventarios, amortizar el intangible en un término más corto o más largo, etc.
    
    Separador
    
    .titulo-segundo.color-acento-contenido
      h2#t_3_1 3.1 Principios de contabilidad aplicados al análisis financiero  

    .row.justify-content-center.mb-5
      .col-12(data-aos="fade-up")
        figure
          img(src='@/assets/curso/temas/tema3/img-18.png', alt='')

    p.mb-4 Para llevar a cabo un análisis financiero preciso, es fundamental comprender los principios contables básicos que rigen la preparación de los estados financieros. Entre ellos se destacan:

    .row.mb-5(data-aos="flip-up")
      .col-md-6.col-lg.tarjeta--tabla.p-4(style="background-color:#F1F8E9")
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema2/icono-01.svg' alt='AvatarTop')
        h4.text-center Principio de empresa en marcha
        p.text-center Se asume que la empresa continuará operando en el futuro previsible.
      .col-md-6.col-lg.tarjeta--tabla1.p-4(style="background-color:#E5E9FE")
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema2/icono-02.svg' alt='AvatarTop')
        h4.text-center Principio de causación
        p.text-center Los ingresos y gastos se reconocen en el momento en que ocurren, no cuando se recibe o paga efectivo.
      .col-md-6.col-lg.tarjeta--tabla.p-4(style="background-color:#F1F8E9")
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema2/icono-03.svg' alt='AvatarTop')
        h4.text-center Principio de uniformidad
        p.text-center La empresa debe mantener los mismos criterios contables a lo largo del tiempo para garantizar comparabilidad.
      .col-md-6.col-lg.tarjeta--tabla1.p-4(style="background-color:#E5E9FE")
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema2/icono-04.svg' alt='AvatarTop')
        h4.text-center Principio de prudencia
        p.text-center Se debe ser conservador en la estimación de ingresos y gastos para evitar sobrevaloraciones.

    p.mb-0 Estos principios garantizan que la información contable refleje fielmente la situación financiera de la organización.
    
    Separador

    .titulo-segundo.color-acento-contenido
      h2#t_3_2 3.2 Impacto en la interpretación de los estados financieros  

    p.mb-5 Los principios contables afectan directamente la manera en que se presentan y analizan los estados financieros, determinando la confiabilidad y precisión de los informes. Su impacto puede percibirse en los siguientes aspectos:

    .container
      .row.justify-content-start
        .col-lg-10
          LineaTiempoE.color-acento-contenido(data-aos="flip-up")
            .row.justify-content-center(titulo="01")
              .col-lg-2.col-4.mb-lg-0.mb-4
                img(src='@/assets/curso/temas/tema2/icono-05.svg' alt="Imagen decorativa")
              .col-lg-10
                .h4 Comparabilidad
                p.mb-0 La aplicación uniforme de los principios contables, permite comparar la información financiera de diferentes períodos y entre distintas empresas.
            .row.justify-content-center(titulo="02")
              .col-lg-2.col-4.mb-lg-0.mb-4
                img(src='@/assets/curso/temas/tema2/icono-06.svg' alt="Imagen decorativa")
              .col-lg-10
                .h4 Transparencia
                p.mb-0 Garantizan que la información financiera refleje fielmente la situación económica de la empresa, evitando manipulaciones contables.
            .row.justify-content-center(titulo="03")
              .col-lg-2.col-4.mb-lg-0.mb-4
                img(src='@/assets/curso/temas/tema2/icono-07.svg' alt="Imagen decorativa")
              .col-lg-10
                .h4 Toma de decisiones
                p.mb-0 Facilitan la evaluación de la rentabilidad, liquidez y solvencia de la empresa, brindando información clave para inversionistas, acreedores y directivos.
            .row.justify-content-center(titulo="04")
              .col-lg-2.col-4.mb-lg-0.mb-4
                img(src='@/assets/curso/temas/tema2/icono-08.svg' alt="Imagen decorativa")
              .col-lg-10
                .h4 Cumplimiento normativo
                p.mb-0 Aseguran que la empresa cumpla con los estándares contables exigidos por las normativas nacionales e internacionales.
    
    
</template>

<script>
export default {
  name: 'Tema3',
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
