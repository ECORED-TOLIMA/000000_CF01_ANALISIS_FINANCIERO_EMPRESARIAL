<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Estados financieros obligatorios   

    .row.justify-content-center.mb-5
      .col-12(data-aos="fade-up")
        figure
          img(src='@/assets/curso/temas/tema4/img-01.png', alt='')

    p.mb-5 En Colombia, los #[b estados financieros básicos obligatorios] que debe presentar una empresa están definidos por la #[b Ley 222 de 1995,] el #[b Código de Comercio] y las #[b Normas de Información Financiera (NIIF),] adoptadas según la Ley 1314 de 2009. Según estos marcos, toda empresa obligada a llevar contabilidad debe presentar al menos los siguientes: 

    .row.mb-5(data-aos="flip-up")
      .col-md-6.col-lg.tarjeta--tabla.p-4(style="background-color:#F1F8E9")
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema4/icono-01.svg' alt='AvatarTop')
        h4.text-center Estado de situación financiera (antes balance general)
        p.text-center Presenta activos, pasivos y patrimonio a una fecha determinada.
      .col-md-6.col-lg.tarjeta--tabla1.p-4(style="background-color:#E5E9FE")
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema4/icono-02.svg' alt='AvatarTop')
        h4.text-center Estado de resultado integral (antes estado de resultados)
        p.text-center LMuestra ingresos, costos, gastos y utilidad o pérdida del ejercicio.
      .col-md-6.col-lg.tarjeta--tabla.p-4(style="background-color:#F1F8E9")
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema4/icono-03.svg' alt='AvatarTop')
        h4.text-center Estado de cambios en el patrimonio
        p.text-center Refleja los movimientos en las cuentas del patrimonio en el periodo.
      .col-md-6.col-lg.tarjeta--tabla1.p-4(style="background-color:#E5E9FE")
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema4/icono-04.svg' alt='AvatarTop')
        h4.text-center Estado de flujos de efectivo
        p.text-center Expone el origen y uso del efectivo clasificado en operación, inversión y financiación.

    .row.justify-content-center.mb-5(data-aos="flip-up")
      .col-lg-10.col-12.order-lg-2.order-2
        .cajon.cajon.C01.color-secundario.p-4.mb-0
          p.mb-0 Se consideran básicos, dentro de los estados financieros, el #[b estado de situación financiera] (balance general) y el #[b estado de resultados] (estado de resultados). Aunque las normas legales también toman por básicos al estado de flujo de efectivo y al estado de cambios en el patrimonio, #[b para efectos del análisis financiero, solo se toman el balance general y el estado de resultados.]

    .row.justify-content-center.align-items-center
      .col-lg-4.col-12.mb-3.d-lg-flex.d-none(data-aos="fade-left")
        figure
          img(src='@/assets/curso/temas/tema4/img-02.svg', alt='Imagen decorativa')

      .col-lg-6.col-12.mb-3(data-aos="fade-right")
        p Al respecto, se debe tener en cuenta lo siguiente: 
        ul.lista-ul.mb-0
          li.mb-2
            i.fas.fa-check(style="color:#BAC36A")
            | Estos estados deben elaborarse al cierre del ejercicio contable (generalmente el 31 de diciembre).

          li.mb-2
            i.fas.fa-check(style="color:#BAC36A")
            | Son obligatorios para todas las empresas que lleven contabilidad, incluidas personas naturales obligadas a llevarla.

          li.mb-2
            i.fas.fa-check(style="color:#BAC36A")
            | Empresas clasificadas en los Grupos 1, 2 o 3 según el marco técnico contable (NIIF plenas, NIIF para Pymes, Contabilidad simplificada), deben seguir el formato que aplique según su grupo.
    
    Separador
    
    .titulo-segundo.color-acento-contenido
      h2#t_4_1 4.1 Elementos fundamentales de la contabilidad 

    p.mb-5 Los elementos fundamentales de la contabilidad: activos, pasivos, patrimonio, ingresos y gastos, están interconectados y forman la estructura de los estados financieros. Comprender su relación es vital para interpretar la situación económica y financiera de una empresa y evaluar su desempeño en el corto y largo plazo. Su explicación es la siguiente:

    .row.fondo2-t2.justify-content-center.align-items-center.py-3.px-lg-5.px-4.ordenar_tarjeta.mb-4(data-aos="zoom-in")
      .col-lg-6.order-lg-1.order-2(data-aos="fade-right")
        ul.lista-ul.mb-0
          li(style="margin-bottom: 2px")
            i.fas.fa-angle-right
            p Los #[b activos] representan los bienes y derechos que posee la empresa y que le generan beneficios económicos futuros. Se clasifican en activos corrientes, aquellos de rápida conversión en efectivo y activos no corrientes, que tienen un uso a largo plazo.

          li(style="margin-bottom: 2px")
            i.fas.fa-angle-right
            p Los #[b pasivos], por su parte, corresponden a las obligaciones financieras adquiridas por la empresa, como deudas y compromisos de pago. Estos pueden ser de corto o largo plazo y reflejan el nivel de apalancamiento financiero.
          
          li(style="margin-bottom: 2px")
            i.fas.fa-angle-right
            p El #[b patrimonio] es la diferencia entre los activos y los pasivos, representando la inversión de los propietarios en la empresa. Es un indicador clave de la estabilidad financiera y del valor neto de la organización.
          
          li(style="margin-bottom: 2px")
            i.fas.fa-angle-right
            p Los #[b ingresos] reflejan los recursos obtenidos por la empresa a través de sus operaciones principales, como la venta de bienes o la prestación de servicios. Su correcto reconocimiento y medición influyen en la rentabilidad del negocio.

          li(style="margin-bottom: 2px")
            i.fas.fa-angle-right
            p Por otro lado, los #[b gastos] representan las erogaciones necesarias para la operación de la empresa, como costos de producción, pago de salarios y servicios. Su adecuada gestión permite mantener un equilibrio financiero y maximizar la utilidad.

      .col-lg-4.col-8.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
        img(src='@/assets/curso/temas/tema2/img-02.svg' alt="Imagen decorativa")

    p.text-center.mb-4(data-aos="fade-down-right") La interacción entre estos elementos se evidencia en la ecuación contable fundamental:

    .row.justify-content-center.p-4.mb-4(data-aos="fade-right")
      .col-md-6.tarjeta.color-primario.p-4(style="background-color:#F1F8E9")
        p.text-bold.text-center.mb-0 #[b Activos = Pasivos + Patrimonio]

    .row.justify-content-center.mb-5(data-aos="fade-down-right") 
      .col-10
        p.mb-4 Esta ecuación refleja que los activos de una empresa son financiados a través de recursos propios (patrimonio) o de terceros (pasivos). Además, los ingresos y gastos impactan directamente en la estructura patrimonial, ya que los beneficios generados aumentan el patrimonio, mientras que las pérdidas lo reducen.
        .cajon.color-secundario.p-4
          p.mb-0 En consecuencia, un adecuado análisis de estos elementos, permite comprender la estabilidad financiera, la capacidad de endeudamiento, la rentabilidad y el crecimiento sostenible de la empresa.
    
    .titulo1.mb-5(data-aos="zoom-in")
      img(src='@/assets/curso/temas/icono.svg', alt='Imagen decorativa')
      h4.mb-0 Relación entre los elementos contables

    p.mb-5(data-aos="fade-down-right") Se da por medio de los siguientes procesos:

    .row.justify-content-center.ali.mb-0(data-aos="flip-up")
      .tarjeta--container.row.mb-5
        .col-xl.col-md-6.tarjeta.color-primario.p-5(data-aos="fade-right")
          .row.justify-content-center.mb-3
            .col-lg-4.col-6
              figure
                img(src='@/assets/curso/temas/tema2/icono-09.svg' alt="Imagen decorativa")
          .h4.text-center La ecuación contable fundamental
          p La interconexión entre estos elementos se expresa en la ecuación contable básica:
          p.text-center #[b Activo = Pasivo + Patrimonio]
          p Esto significa que todos los recursos (activos) son financiados, ya sea por terceros (pasivos) o por los dueños del negocio (patrimonio).
        
        .col-xl.col-md-6.tarjeta.color-secundario.p-5(data-aos="fade-left")
          .row.justify-content-center.mb-3
            .col-lg-4.col-6
              figure
                img(src='@/assets/curso/temas/tema2/icono-10.svg' alt="Imagen decorativa")
          .h4.text-center Impacto de los ingresos y gastos en la ecuación contable
          p Cuando la empresa genera ingresos y obtiene ganancias, su patrimonio aumenta. Por el contrario, si incurre en más gastos que ingresos, su patrimonio se reduce.
          p.text-center #[b Utilidad Neta = Ingresos - Gastos]
          p Las utilidades netas pueden ser reinvertidas en la empresa (aumentando el patrimonio) o distribuidas entre los socios como dividendos.
    
    Separador

    .titulo-segundo.color-acento-contenido
      h2#t_4_2 4.2 Relación en los estados  financieros 

    p(data-aos="fade-down-right") El #[b balance general] muestra la relación entre activos, pasivos y patrimonio en un momento determinado.
    p.mb-5(data-aos="fade-down-right") El #[b estado de resultados] refleja los ingresos y gastos en un período de tiempo, determinando la utilidad o pérdida.

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-6.col-8.mb-4(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema2/img-02.png', alt='Texto que describa la imagen')
      .col-lg-6
        p.mb-0 #[b Ejemplo práctico]
        p Una empresa inicia con un capital de $50,000 y obtiene un préstamo de $20,000. Con estos recursos adquiere maquinaria por $40,000 y mantiene $30,000 en caja. Su ecuación contable sería:
        p #[b Activos (40,000+30,000) = Pasivos (20,000) + Patrimonio (50,000)]
        p Si durante el año la empresa genera $10,000 en ingresos y tiene $6,000 en gastos, su utilidad neta será de $4,000, lo que aumentará el patrimonio.
        p #[b Nuevo patrimonio = 50,000 + 4,000 = 54,000]
    
    .titulo1.mb-5(data-aos="zoom-in")
      img(src='@/assets/curso/temas/icono.svg', alt='Imagen decorativa')
      h4.mb-0 Definición de los estados financieros principales

    p.mb-5(data-aos="fade-down-right")  Los estados financieros son informes contables fundamentales que permiten evaluar la situación económica y el desempeño de una empresa. Proporcionan información clave para la toma de decisiones y se elaboran con base en principios contables generalmente aceptados. A continuación, se describen los tres estados financieros principales:   

    .h4.tcvo.mb-4(data-aos="fade-down-right") ● A) Estado de situación financiera (balance general)
    
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-6.col-8.mb-4(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema2/img-03.png', alt='Texto que describa la imagen')
      .col-lg-6
        p.mb-0 #[b Definición]
        p El estado de situación financiera, también conocido como balance general, presenta la posición económica de la empresa en un momento determinado, mostrando lo que posee (activos), lo que debe (pasivos) y el valor que corresponde a los propietarios (patrimonio).
        p #[b Estructura]
        p Se basa en la ecuación contable fundamental:
        p #[b Activos = Pasivos + Patrimonio]
    
    .row.justify-content-center.mb-5
      .col-lg-4.col-8.mb-lg-0.mb-4(data-aos="fade-right")
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema2/icono-11.svg' alt="Imagen decorativa")
          .tarjeta--boton.color-secundario.p-4.py-5.h-100(style="background-color:#E5E9FE")
            h4.text-center.mt-5.mb-0 Activos
            p.text-center.mt-4.mb-0 Recursos controlados por la empresa, como efectivo, cuentas por cobrar, inventarios y propiedades.

      .col-lg-4.col-8.mb-lg-0.mb-4(data-aos="fade-left")
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema2/icono-12.svg' alt="Imagen decorativa")
          .tarjeta--boton.color-secundario.p-4.py-5.h-100(style="background-color:#E5E9FE")
            h4.text-center.mt-5.mb-0 Pasivos
            p.text-center.mt-4.mb-0 Obligaciones financieras con terceros, como préstamos y cuentas por pagar.

      .col-lg-4.col-8.mb-lg-0.mb-4(data-aos="fade-right")
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema2/icono-13.svg' alt="Imagen decorativa")
          .tarjeta--boton.color-secundario.p-4.py-5.h-100(style="background-color:#E5E9FE")
            h4.text-center.mt-5.mb-0 Patrimonio
            p.text-center.mt-4.mb-0 Aportes de los socios y utilidades retenidas.

    .row.justify-content-center.mb-5
      .col-lg-12
        .p-4.bg-c18(data-aos="fade-left")
          p.text-center #[b Importancia]
          .row.justify-content-center
            .col-md-6.col-lg-4.mb-4.mb-lg-0
              .p-3.bg-c19
                .row.align-items-center
                  .col-auto
                    figure
                      img(src='@/assets/curso/temas/tema3/icono-01.svg', alt='', style='width: 80px').m-auto
                  .col
                    .row.h-100.align-items-center
                      .col-12
                        p.mb-0 Permite conocer la estabilidad financiera de la empresa.

            .col-md-6.col-lg-4.mb-4.mb-lg-0
              .p-3.bg-c19
                .row.align-items-center
                  .col-auto
                    figure
                      img(src='@/assets/curso/temas/tema3/icono-02.svg', alt='', style='width: 80px').m-auto
                  .col
                    .row.h-100.align-items-center
                      .col-12
                        p.mb-0 Indica la capacidad de pago a corto y largo plazo.

            .col-md-6.col-lg-4
              .p-3.bg-c19
                .row.align-items-center
                  .col-auto
                    figure
                      img(src='@/assets/curso/temas/tema3/icono-03.svg', alt='', style='width: 80px').m-auto
                  .col
                    .row.h-100.align-items-center
                      .col-12
                        p.mb-0 Es utilizado por inversionistas y bancos para evaluar la solidez económica.

    .h4.tcvo.mb-4(data-aos="fade-down-right")  ● B) Estado de resultados (estado de pérdidas y ganancias)

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-6.col-8.mb-4(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema2/img-04.png', alt='Texto que describa la imagen')
      .col-lg-6
        p.mb-0 #[b Definición]
        p El estado de resultados muestra el desempeño financiero de la empresa durante un período específico, reflejando sus ingresos, costos, gastos y la utilidad o pérdida neta.
        p #[b Estructura]
        p Se basa en la ecuación contable fundamental:
        p #[b Utilidad neta = Ingresos - (Costos + Gastos)]

    .row.justify-content-center.mb-4(data-aos="flip-up")
      .col-xl-3.col-lg-8.mb-4.mb-xl-5
        .crd.crd--grayGrad_3(data-aos="flip-left")
          .bottomCircle_3.mb-5
            figure
              img(src="@/assets/curso/temas/tema4/icono-05.svg", alt="alt").img90.m-auto
          h4.text-center Ingresos
          p.mb-0 Ventas de bienes o servicios.
      .col-xl-3.col-lg-8.mb-4.mb-xl-5
        .crd.crd--grayGrad_3(data-aos="flip-left")
          .bottomCircle_3.mb-5
            figure
              img(src="@/assets/curso/temas/tema4/icono-06.svg", alt="alt").img90.m-auto
          h4.text-center Costos
          p.mb-0 Gastos directamente relacionados con la producción o adquisición de bienes y servicios vendidos.
      .col-xl-3.col-lg-8.mb-4.mb-xl-5
        .crd.crd--grayGrad_3(data-aos="flip-left")
          .bottomCircle_3.mb-5
            figure
              img(src="@/assets/curso/temas/tema4/icono-07.svg", alt="alt").img90.m-auto
          h4.text-center Gastos
          p.mb-0 Desembolsos operativos como sueldos, alquileres y publicidad.
      .col-xl-3.col-lg-8.mb-4.mb-xl-5
        .crd.crd--grayGrad_3(data-aos="flip-left")
          .bottomCircle_3.mb-5
            figure
              img(src="@/assets/curso/temas/tema4/icono-08.svg", alt="alt").img90.m-auto
          h4.text-center Utilidad o pérdida
          p.mb-0 Resultado final tras restar costos y gastos de los ingresos..
    
    .row.justify-content-center.mb-5
      .col-lg-12
        .p-4.bg-c18(data-aos="fade-left")
          p.text-center #[b Importancia]
          .row.justify-content-center
            .col-md-6.col-lg-4.mb-4.mb-lg-0
              .p-3.bg-c19
                .row.align-items-center
                  .col-auto
                    figure
                      img(src='@/assets/curso/temas/tema3/icono-04.svg', alt='', style='width: 80px').m-auto
                  .col
                    .row.h-100.align-items-center
                      .col-12
                        p.mb-0 Permite evaluar la rentabilidad del negocio.

            .col-md-6.col-lg-4.mb-4.mb-lg-0
              .p-3.bg-c19
                .row.align-items-center
                  .col-auto
                    figure
                      img(src='@/assets/curso/temas/tema3/icono-05.svg', alt='', style='width: 80px').m-auto
                  .col
                    .row.h-100.align-items-center
                      .col-12
                        p.mb-0 Ayuda a identificar áreas donde se pueden reducir costos o aumentar ingresos.

            .col-md-6.col-lg-4
              .p-3.bg-c19
                .row.align-items-center
                  .col-auto
                    figure
                      img(src='@/assets/curso/temas/tema3/icono-06.svg', alt='', style='width: 80px').m-auto
                  .col
                    .row.h-100.align-items-center
                      .col-12
                        p.mb-0 Es clave para determinar el pago de impuestos y dividendos.
    
    .h4.tcvo.mb-4(data-aos="fade-down-right") ● C) Estado de flujo de efectivo

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-5.col-8.mb-4(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema2/img-05.png', alt='Texto que describa la imagen')
      .col-lg-7
        p.mb-0 #[b Definición]
        p El estado de flujo de efectivo muestra cómo la empresa genera y utiliza el efectivo en un período determinado.
        p.mb-0 #[b Estructura]
        p Se tienen las siguientes actividades:
        ul.lista-ul
          li(style="margin-bottom: 2px")
            i.fas.fa-angle-right
            p.mb-0 #[b Actividades de operación:] flujo de efectivo derivado de la actividad principal de la empresa, como cobros a clientes y pagos a proveedores.

          li(style="margin-bottom: 2px")
            i.fas.fa-angle-right
            p.mb-0 #[b Actividades de inversión:] movimientos relacionados con la compra o venta de activos a largo plazo, como propiedades o equipos.

          li(style="margin-bottom: 2px")
            i.fas.fa-angle-right
            p.mb-0 #[b Actividades de financiamiento:] incluye la obtención y pago de préstamos, emisión de acciones y distribución de dividendos.

    .row.justify-content-center.mb-5
      .col-lg-12
        .p-4.bg-c18(data-aos="fade-left")
          p.text-center #[b Importancia]
          .row.justify-content-center
            .col-md-6.col-lg-4.mb-4.mb-lg-0
              .p-3.bg-c19
                .row.align-items-center
                  .col-auto
                    figure
                      img(src='@/assets/curso/temas/tema3/icono-07.svg', alt='', style='width: 80px').m-auto
                  .col
                    .row.h-100.align-items-center
                      .col-12
                        p.mb-0 Indica la liquidez real de la empresa.

            .col-md-6.col-lg-4.mb-4.mb-lg-0
              .p-3.bg-c19
                .row.align-items-center
                  .col-auto
                    figure
                      img(src='@/assets/curso/temas/tema3/icono-08.svg', alt='', style='width: 80px').m-auto
                  .col
                    .row.h-100.align-items-center
                      .col-12
                        p.mb-0 Ayuda a prever problemas de flujo de caja.

            .col-md-6.col-lg-4
              .p-3.bg-c19
                .row.align-items-center
                  .col-auto
                    figure
                      img(src='@/assets/curso/temas/tema3/icono-09.svg', alt='', style='width: 80px').m-auto
                  .col
                    .row.h-100.align-items-center
                      .col-12
                        p.mb-0 Es clave para evaluar la capacidad de pago de deudas y la sostenibilidad del negocio.
    
  
    
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
