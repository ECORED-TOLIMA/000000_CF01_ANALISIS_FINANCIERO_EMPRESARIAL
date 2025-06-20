<template lang="pug">
.curso-main-container.pb-3.tema2
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Usuarios del análisis financiero y toma de decisiones

    .row.justify-content-center.mb-5
      .col-12(data-aos="fade-up")
        figure
          img(src='@/assets/curso/temas/tema2/img-01.png', alt='')

    p.mb-4(data-aos="fade-down-right") El análisis financiero es una herramienta fundamental para la toma de decisiones en una organización y su utilidad se extiende a distintos grupos de interés. Retomando a Ortiz (2011), los usuarios del análisis financiero se pueden clasificar en internos y externos, dependiendo de su relación con la empresa y los objetivos que buscan con la información financiera.

    .titulo1.mb-4(data-aos="zoom-in")
      img(src='@/assets/curso/temas/icono.svg', alt='Imagen decorativa')
      h4.mb-0 Usuarios internos del análisis financiero

    p.mb-5 Son aquellos que forman parte de la empresa y utilizan la información financiera para la gestión y planificación estratégica. Dentro de este grupo se encuentran:

    .tarjeta.tarjeta--BG02.p-md-5.p-4.mb-5(data-aos="flip-up")
      SlyderA(tipo="b")
        .row.justify-content-center.p-4
          .col-lg-6.order-lg-1.order-2
            h4 Alta dirección y gerencia
            p.mb-3 Utiliza el análisis financiero para tomar decisiones estratégicas, evaluar el desempeño de la empresa y establecer planes de crecimiento.
            p Se apoya en indicadores financieros para definir presupuestos, estrategias de inversión y expansión.
          .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
            figure
              img(src='@/assets/curso/temas/tema2/img-06.png', alt='Imagen decorativa')
        
        .row.justify-content-center.p-4
          .col-lg-6.order-lg-1.order-2
            h4 Áreas contables y financieras
            p.mb-3 Evalúan la salud financiera de la empresa, preparando reportes para la gerencia y asegurando el cumplimiento de normativas contables.
            p Analizan la rentabilidad, la liquidez y la eficiencia operativa para optimizar los recursos disponibles.
          .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
            figure
              img(src='@/assets/curso/temas/tema2/img-07.png', style="width: 450px" ,alt='').m-auto
        
        .row.justify-content-center.p-4
          .col-lg-6.order-lg-1.order-2
            h4 Propietarios y accionistas
            p.mb-3 Buscan conocer la rentabilidad y sostenibilidad de la empresa para tomar decisiones sobre nuevas inversiones o distribución de dividendos.
            p Evalúan el desempeño financiero para determinar la viabilidad de reinvertir en el negocio o realizar ajustes estratégicos.
          .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
            figure
              img(src='@/assets/curso/temas/tema2/img-08.png', style="width: 450px" ,alt='').m-auto 
        
        .row.justify-content-center.p-4
          .col-lg-6.order-lg-1.order-2
            h4 Áreas operativas y comerciales
            p.mb-3 Necesitan información financiera para optimizar costos, mejorar la productividad y definir estrategias de ventas.
            p Analizan los márgenes de ganancia y costos operativos para hacer ajustes en la producción o en la oferta de productos y servicios.
          .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
            figure
              img(src='@/assets/curso/temas/tema2/img-09.png', style="width: 450px" ,alt='').m-auto 
    
    .titulo1.mb-4(data-aos="zoom-in")
      img(src='@/assets/curso/temas/icono.svg', alt='Imagen decorativa')
      h4.mb-0 Usuarios externos del análisis financiero

    p.mb-4 Son agentes fuera de la organización que requieren información financiera para evaluar la solidez y estabilidad de la empresa. Entre ellos se encuentran:

    .row.justify-content-center.align-items-center.mb-5(data-aos="flip-up")
      SlyderF(columnas="col-lg-6 col-xl-4")
        .tarjeta.tarjeta--BG01.p-4
          .row.justify-content-center.mb-3
            .col-lg-5.col-sm-4.col-6
              img(src='@/assets/curso/temas/tema2/icono-18.svg' alt='AvatarTop')
          h4.text-center Entidades financieras y prestamistas
          p Bancos e inversionistas analizan los estados financieros para evaluar la capacidad de pago de la empresa, antes de otorgar créditos o financiamiento.
          p Se enfocan en indicadores como el nivel de endeudamiento, la liquidez y el flujo de caja.

        .tarjeta.tarjeta--BG01.p-4
          .row.justify-content-center.mb-3
            .col-lg-5.col-sm-4.col-6
              img(src='@/assets/curso/temas/tema2/icono-19.svg' alt='AvatarTop')
          h4.text-center Proveedores y acreedores
          p Evalúan la solidez financiera de la empresa, para determinar si es confiable otorgarle crédito comercial.
          p Analizan la rotación de cuentas por pagar y la liquidez para medir la capacidad de cumplimiento de obligaciones.

        .tarjeta.tarjeta--BG01.p-4
          .row.justify-content-center.mb-3
            .col-lg-5.col-sm-4.col-6
              img(src='@/assets/curso/temas/tema2/icono-20.svg' alt='AvatarTop')
          h4.text-center Inversionistas potenciales
          p Buscan conocer la rentabilidad y estabilidad de la empresa antes de decidir si invierten en ella.
          p Se enfocan en indicadores como el retorno sobre la inversión (ROI), el margen de utilidad y el crecimiento financiero.

        .tarjeta.tarjeta--BG01.p-4
          .row.justify-content-center.mb-3
            .col-lg-5.col-sm-4.col-6
              img(src='@/assets/curso/temas/tema2/icono-21.svg' alt='AvatarTop')
          h4.text-center Entidades gubernamentales y organismos reguladores
          p Utilizan el análisis financiero para verificar el cumplimiento de normativas contables, fiscales y laborales. 
          p Evalúan la transparencia y veracidad de la información financiera para garantizar la legalidad de las operaciones. 

        .tarjeta.tarjeta--BG01.p-4
          .row.justify-content-center.mb-3
            .col-lg-5.col-sm-4.col-6
              img(src='@/assets/curso/temas/tema2/icono-22.svg' alt='AvatarTop')
          h4.text-center Clientes y socios estratégicos
          p Pueden revisar la información financiera de una empresa, para evaluar su estabilidad y confiabilidad como proveedor o aliado comercial.
          p Empresas que firman contratos a largo plazo necesitan asegurarse de la solvencia de sus socios.

    .row.justify-content-center.mb-0(data-aos="flip-up")
      .col-lg-10.col-12.order-lg-2.order-2
        .cajon.cajon.C01.color-secundario.p-4.mb-0
          h4 Rol del análisis financiero en la gestión empresarial
          p.mb-0 El análisis financiero es una herramienta clave en la gestión empresarial, ya que proporciona información objetiva sobre la situación económica de una organización, permitiendo tomar decisiones estratégicas fundamentadas. Según Ortiz (2011), su papel dentro de la empresa, se extiende a diversas áreas, incluyendo la planificación, el control y la optimización de los recursos.

    Separador

    .titulo-segundo.color-acento-contenido
      h2#t_2_1 2.1 Apoyo en la toma de decisiones estratégicas
    
    p.mb-5 Las empresas requieren información financiera precisa para establecer planes de crecimiento, evaluar riesgos y determinar inversiones. El análisis financiero permite:

    .row.justify-content-center.align-items-center.mb-4(data-aos="flip-up")
      .col-lg-10.col-12
        .cajon.cajon--C01.p-2.mb-4
          .row.justify-content-center.align-items-center
            .col-4.d-none.d-lg-block.order-lg-2.order-2.mb-lg-0
              figure
                img(src='@/assets/curso/temas/tema2/img-10.svg', alt='Imagen decorativa')
            .col-lg-6.col-12.mb-3.order-lg-1.order-2.mb-lg-0.p-4
              ul.lista-ul.mb-0
                li.mb-0
                  i.fas.fa-check(style="color:#BAC36A")
                  | Identificar oportunidades de expansión y diversificación.

                li.mb-0
                  i.fas.fa-check(style="color:#BAC36A")
                  | Evaluar la rentabilidad de nuevos proyectos o líneas de negocio.

                li.mb-0
                  i.fas.fa-check(style="color:#BAC36A")
                  | Establecer estrategias para mejorar la eficiencia operativa y reducir costos.
    
    p.mb-5 Por ejemplo, una empresa que evalúa la viabilidad de abrir una nueva sucursal, utilizará indicadores financieros como la rentabilidad esperada, el flujo de caja y el costo del financiamiento antes de tomar una decisión.

    .titulo1.mb-4(data-aos="zoom-in")
      img(src='@/assets/curso/temas/icono.svg', alt='Imagen decorativa')
      h4.mb-0 Evaluación de la rentabilidad y sostenibilidad

    p.mb-4 Un aspecto fundamental de la gestión empresarial es asegurar la sostenibilidad del negocio en el tiempo. A través del análisis financiero, se puede:

    .row.justify-content-center.mb-4(data-aos="flip-up")
      .col-xl-4.col-lg-8.mb-4.mb-xl-5
        .crd.crd--grayGrad_2(data-aos="flip-left")
          .bottomCircle_2.mb-5
            figure
              img(src="@/assets/curso/temas/tema2/icono-01-1.svg", alt="alt").img90.m-auto
          p.mb-0 Medir la rentabilidad de la empresa mediante indicadores como el ROE (Return on Equity) y el ROA (Return on Assets).
      .col-xl-4.col-lg-8.mb-4.mb-xl-5
        .crd.crd--grayGrad_2(data-aos="flip-left")
          .bottomCircle_2.mb-5
            figure
              img(src="@/assets/curso/temas/tema2/icono-02-1.svg", alt="alt").img90.m-auto
          p.mb-0 Identificar factores que afectan la rentabilidad, como costos operativos elevados o una baja rotación de inventarios.
      .col-xl-4.col-lg-8.mb-4.mb-xl-5
        .crd.crd--grayGrad_2(data-aos="flip-left")
          .bottomCircle_2.mb-5
            figure
              img(src="@/assets/curso/temas/tema2/icono-03-1.svg", alt="alt").img90.m-auto
          p.mb-0 Determinar si los ingresos generados son suficientes para cubrir los costos y generar utilidades sostenibles.

    .titulo1.mb-4(data-aos="zoom-in")
      img(src='@/assets/curso/temas/icono.svg', alt='Imagen decorativa')
      h4.mb-0 Gestión del riesgo financiero

    p.mb-5 Toda empresa está expuesta a riesgos financieros que pueden afectar su estabilidad. El análisis financiero ayuda a:

    .row.justify-content-center.align-items-center.mb-4(data-aos="flip-up")
      .col-lg-10.col-12
        .cajon.cajon--C01.p-2.mb-4
          .row.justify-content-center.align-items-center
            .col-4.d-none.d-lg-block.order-lg-2.order-2.mb-lg-0
              figure
                img(src='@/assets/curso/temas/tema2/img-11.svg', alt='Imagen decorativa')
            .col-lg-6.col-12.mb-3.order-lg-1.order-2.mb-lg-0.p-4
              ul.lista-ul.mb-0
                li.mb-0
                  i.fas.fa-check(style="color:#BAC36A")
                  | Identificar riesgos de liquidez, asegurando que la empresa pueda cumplir con sus obligaciones de corto plazo.

                li.mb-0
                  i.fas.fa-check(style="color:#BAC36A")
                  | Evaluar el endeudamiento y su impacto en la estabilidad financiera.

                li.mb-0
                  i.fas.fa-check(style="color:#BAC36A")
                  | Prever posibles crisis financieras y tomar medidas correctivas a tiempo.

    p.mb-5 Por ejemplo, una empresa con un alto nivel de endeudamiento puede utilizar el índice de cobertura de intereses, para determinar si tiene la capacidad de pagar su deuda sin comprometer su operación.

    .titulo1.mb-4(data-aos="zoom-in")
      img(src='@/assets/curso/temas/icono.svg', alt='Imagen decorativa')
      h4.mb-0 Optimización del uso de los recursos

    p.mb-5 La gestión eficiente de los recursos financieros permite mejorar la productividad y la competitividad de la empresa. El análisis financiero contribuye a:

    .row.justify-content-center.align-items-center.mb-4(data-aos="flip-up")
      .col-lg-10.col-12
        .cajon.cajon--C01.p-2.mb-4
          .row.justify-content-center.align-items-center
            .col-4.d-none.d-lg-block.order-lg-2.order-2.mb-lg-0
              figure
                img(src='@/assets/curso/temas/tema2/img-12.svg', alt='Imagen decorativa')
            .col-lg-6.col-12.mb-3.order-lg-1.order-2.mb-lg-0.p-4
              ul.lista-ul.mb-0
                li.mb-0
                  i.fas.fa-check(style="color:#BAC36A")
                  | Identificar áreas de la empresa donde se pueden reducir costos sin afectar la calidad.

                li.mb-0
                  i.fas.fa-check(style="color:#BAC36A")
                  | Optimizar la gestión del capital de trabajo, asegurando un equilibrio entre cuentas por cobrar, inventarios y cuentas por pagar.

                li.mb-0
                  i.fas.fa-check(style="color:#BAC36A")
                  | Determinar estrategias para mejorar la eficiencia operativa y maximizar los beneficios.

    p.mb-5 Un caso común es el análisis del ciclo de conversión de efectivo, que permite a las empresas gestionar mejor sus flujos de caja y evitar problemas de liquidez.

    .titulo1.mb-4(data-aos="zoom-in")
      img(src='@/assets/curso/temas/icono.svg', alt='Imagen decorativa')
      h4.mb-0 Medición del desempeño financiero

    p.mb-5 El análisis financiero es esencial para evaluar el cumplimiento de los objetivos organizacionales. A través del uso de indicadores de gestión, la empresa puede:

    .row.justify-content-center.align-items-center.mb-4(data-aos="flip-up")
      .col-lg-10.col-12
        .cajon.cajon--C01.p-2.mb-4
          .row.justify-content-center.align-items-center
            .col-4.d-none.d-lg-block.order-lg-2.order-2.mb-lg-0
              figure
                img(src='@/assets/curso/temas/tema2/img-13.svg', alt='Imagen decorativa')
            .col-lg-6.col-12.mb-3.order-lg-1.order-2.mb-lg-0.p-4
              ul.lista-ul.mb-0
                li.mb-0
                  i.fas.fa-check(style="color:#BAC36A")
                  | Comparar su desempeño con períodos anteriores o con empresas del mismo sector.

                li.mb-0
                  i.fas.fa-check(style="color:#BAC36A")
                  | Establecer metas financieras realistas y monitorear su progreso.

                li.mb-0
                  i.fas.fa-check(style="color:#BAC36A")
                  | Implementar acciones correctivas en caso de desviaciones en los resultados esperados.

    p.mb-0 El uso de herramientas como el análisis horizontal y vertical, junto con indicadores como el margen de utilidad y el EBITDA, permite obtener una visión clara del desempeño de la empresa y su evolución a lo largo del tiempo.

    Separador

    .titulo-segundo.color-acento-contenido
      h2#t_2_2 2.2 Aplicaciones del análisis financiero en la toma de decisiones

    p.mb-5 El análisis financiero es una herramienta esencial para la toma de decisiones estratégicas dentro de una organización. A través del estudio detallado de los estados financieros y el uso de diversos indicadores, es posible obtener información valiosa sobre la economía de la empresa, su capacidad para generar utilidades y su sostenibilidad a largo plazo.

    .row.justify-content-center.mb-5(data-aos="flip-up")
      .col-lg-8.col-12.order-lg-2.order-2
        .cajon.cajon.C01.color-primario.p-4.mb-0
          p.mb-0 Este proceso permite evaluar distintos escenarios y alternativas que afectan el desempeño financiero, brindando soporte en la planificación y ejecución de estrategias empresariales. Desde la evaluación de inversiones, hasta la gestión de riesgos, el análisis financiero proporciona una base objetiva para optimizar recursos y mejorar la rentabilidad.
    
    p.mb-5 A continuación, se presentan las principales decisiones que pueden tomarse a partir del análisis financiero:

    .row.justify-content-center(data-aos="fade-down-right")
      .col-lg-4.col-12.mb-3.d-lg-flex.d-none
        figure
          img(src='@/assets/curso/temas/tema2/img-14.png', alt='Imagen decorativa')
      .col-lg-8.col-12.mb-3
        AcordionA.mb-5(tipo="b" clase-tarjeta="tarjeta tarjeta--C01")
          .row(titulo="Decisiones de inversión")
            .col-md-12.mb-4.mb-md-0
              p Permite evaluar la viabilidad de proyectos de inversión, analizando indicadores como el Retorno Sobre la Inversión (ROI) y el Valor Presente Neto (VPN). Con esta información, se puede determinar si una inversión generará beneficios a largo plazo.

          .row(titulo="Decisiones de financiamiento")
            .col-md-12.mb-4.mb-md-0
              p Ayuda a definir la mejor estructura de capital para la empresa, evaluando la conveniencia de obtener recursos, a través de deuda o capital propio. Factores como la tasa de interés, el costo de capital y la capacidad de pago, son analizados para minimizar riesgos financieros.

          .row(titulo="Decisiones operativas")
            .col-md-12.mb-4.mb-md-0
              p Facilita la optimización de costos y gastos, mejorando la eficiencia en el uso de los recursos. A través del análisis financiero, se pueden identificar áreas donde la empresa puede reducir costos, sin afectar la calidad de sus productos o servicios.
          
          .row(titulo="Decisiones de crecimiento y expansión")
            .col-md-12.mb-4.mb-md-0
              p Con base en la evaluación de la rentabilidad y la capacidad de generación de flujo de caja, se pueden tomar decisiones sobre la apertura de nuevas sucursales, la diversificación de productos o la incursión en nuevos mercados.
          
          .row(titulo="Gestión de riesgos financieros")
            .col-md-12.mb-4.mb-md-0
              p Permite anticipar y mitigar riesgos asociados a la volatilidad del mercado, fluctuaciones en las tasas de interés, inflación y cambios en el entorno económico.
              
    
    //- .cronologia.mb-5
    //-   .contenedor
    //-     .tarjeta-evento.tarjeta-evento--paso1(data-aos="fade-left")
    //-       .tarjeta-titulo
    //-         .cajon-numero
    //-           span 01
    //-         h2.p-2.text-white Subtitle
    //-       .tarjeta-cuerpo.p-4
    //-         p Lorem ipsum dolor sit amet, consectetur adipisicing elit. Soluta reiciendis deserunt doloribus consequatur, laudantium odio dolorum laboriosam. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Soluta reiciendis deserunt doloribus consequatur, laudantium odio dolorum laboriosam.
    //-         figure
    //-           img(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
    //-           figcaption Leyenda de la imagen 
    //-     .tarjeta-evento.tarjeta-evento--paso2(data-aos="fade-right")
    //-       .tarjeta-titulo
    //-         .cajon-numero
    //-           span 02
    //-         h2 Subtitle
    //-       .tarjeta-cuerpo
    //-         p.mb-0 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Soluta reiciendis deserunt doloribus consequatur, laudantium odio dolorum laboriosam.
    //-     .tarjeta-evento.tarjeta-evento--paso3(data-aos="fade-left")
    //-       .tarjeta-titulo
    //-         .cajon-numero
    //-           span 03
    //-         h2 Subtitle
    //-       .tarjeta-cuerpo
    //-         p.mb-0 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Soluta reiciendis deserunt doloribus consequatur, laudantium odio dolorum laboriosam.
    //-     .tarjeta-evento.tarjeta-evento--paso4(data-aos="fade-right")
    //-       .tarjeta-titulo
    //-         .cajon-numero
    //-           span 04
    //-         h2 Subtitle
    //-       .tarjeta-cuerpo
    //-         p.mb-0 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Soluta reiciendis deserunt doloribus consequatur, laudantium odio dolorum laboriosam.
    //-     .tarjeta-evento.tarjeta-evento--paso5(data-aos="fade-left")
    //-       .tarjeta-titulo
    //-         .cajon-numero
    //-           span 05
    //-         h2 Subtitle
    //-       .tarjeta-cuerpo
    //-         p.mb-0 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Soluta reiciendis

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
