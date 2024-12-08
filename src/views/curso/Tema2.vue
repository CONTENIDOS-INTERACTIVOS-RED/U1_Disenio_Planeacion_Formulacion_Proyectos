<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'2. Fases del ciclo de vida del proyecto.'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .row.mb-5
      .col-lg-4.order-lg-2
        figure
          img(src="@/assets/curso/tema2/2.png", data-aos="zoom-in").mb-4.mb-lg-0
      .col-lg-8.order-lg-1
        .bg-color-2.p-4(data-aos="fade-left").mb-4
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema2/1.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Cuando hablamos del ciclo de vida nos referimos a aquellas fases en las cuales estructuramos todo aquello que necesitamos hacer a lo largo del proyecto, pasando de la identiﬁcación, al diseño o planiﬁcación, posteriormente a su implementación y ﬁnalizando en la evaluación y difusión de los resultados. (Cerezuela y Ollé, 2018). 

        p(data-aos="fade-left") El ciclo de vida de un proyecto es un marco que describe las etapas que atraviesa un proyecto desde su inicio hasta su cierre. Este ciclo ayuda a los gerentes de proyectos a planificar, ejecutar y evaluar proyectos de manera más efectiva.

        p(data-aos="fade-left") #[strong En términos generales las etapas del ciclo de vida de un proyecto comprenden:]

    p(data-aos="fade-left") #[strong Figura 2.] Ciclo de vida de un proyecto 

    figure(data-aos="zoom-in")
      img(src="@/assets/curso/tema2/figura2.png", alt="")

    p(data-aos="fade-left") La gestión de proyectos comienza al transformar ideas en iniciativas concretas, evaluando su viabilidad y alineación con los objetivos organizacionales.

    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-lg-7
              h5 Diagnóstico y conceptualización
              p La idea del proyecto puede surgir de diversas maneras, ya sea como reacción a cambios en políticas o directrices, o de forma interna dentro de la organización. En esta etapa, se identifica y registra el problema o la oportunidad que podría originar el proyecto. Se recomienda el uso de técnicas como diagramas de causa-efecto, encuestas de calidad y técnicas creativas para la generación de ideas.
            .col-lg-5
              figure
                img(src="@/assets/curso/tema2/slider-1.png")
          .row.align-items-center.p-4.p-md-5
            .col-lg-7
              h5 Análisis de viabilidad
              p Una vez detectadas las oportunidades, se evalúa su viabilidad técnica y económica para facilitar la toma de decisiones. Este análisis permite identificar limitaciones, descubrir oportunidades, definir requisitos, evaluar opciones y alcanzar un consenso sobre el rumbo del proyecto, utilizando metodologías cuantitativas y cualitativas.
            .col-lg-5
              figure
                img(src="@/assets/curso/tema2/slider-2.png")

          .row.align-items-center.p-4.p-md-5
            .col-lg-7
              h5 Selección del proyecto
              p Una vez detectadas las oportunidades, se evalúa su viabilidad técnica y económica para facilitar la toma de decisiones. Este análisis permite identificar limitaciones, descubrir oportunidades, definir requisitos, evaluar opciones y alcanzar un consenso sobre el rumbo del proyecto, utilizando metodologías cuantitativas y cualitativas.
            .col-lg-5
              figure
                img(src="@/assets/curso/tema2/slider-3.png")

          .row.align-items-center.p-4.p-md-5
            .col-lg-7
              h5 Definición formal y aprobación
              p Tras seleccionar el proyecto, se realiza una definición inicial a alto nivel. Esto incluye establecer la visión, objetivos alineados con la estrategia organizacional y objetivos SMART. También se define el alcance, los entregables, plazos y recursos necesarios, además de identificar a los interesados, sus expectativas e influencia en el proyecto.
            .col-lg-5
              figure
                img(src="@/assets/curso/tema2/slider-4.png")

    #t_2_1.titulo-segundo(data-aos="flip-up")
      h2 #[span 2.1] Planeación  

    p(data-aos="fade-left") La planificación de un proyecto implica concretar los objetivos a alcanzar y detallar las actividades necesarias para lograrlos. Esto incluye desglosar el trabajo en paquetes y asignarles los recursos adecuados, estimar su duración y costo, e integrarlas en un cronograma, estableciendo su relación con otras tareas. También se debe planificar la gestión de la calidad, la interacción con todas las partes interesadas, la comunicación de avances y resultados, así como la administración del equipo y los recursos materiales.

    .bg-full-width.bg-color-4
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg
            .row.justify-content-center.align-items-center(data-aos="fade-up").mb-3
              .col-auto
                figure
                  img(src='@/assets/bullets/icon-1.svg' alt='' style="width: 20px;")
              .col
                p.mb-0 #[strong Documentación del proyecto:] registro claro de las fases, objetivos y requerimientos.
            .row.justify-content-center.align-items-center(data-aos="fade-up").mb-3
              .col-auto
                figure
                  img(src='@/assets/bullets/icon-1.svg' alt='' style="width: 20px;")
              .col
                p.mb-0 #[strong Estrategias de comunicación:] definir cómo y cuándo se informará a las partes interesadas.
            .row.justify-content-center.align-items-center(data-aos="fade-up").mb-3
              .col-auto
                figure
                  img(src='@/assets/bullets/icon-1.svg' alt='' style="width: 20px;")
              .col
                p.mb-0 #[strong Identificación de actividades:] descripción detallada de las tareas a realizar.
            .row.justify-content-center.align-items-center(data-aos="fade-up").mb-3
              .col-auto
                figure
                  img(src='@/assets/bullets/icon-1.svg' alt='' style="width: 20px;")
              .col
                p.mb-0 #[strong Duración:] estimación de tiempo para cada actividad.
            .row.justify-content-center.align-items-center(data-aos="fade-up").mb-3
              .col-auto
                figure
                  img(src='@/assets/bullets/icon-1.svg' alt='' style="width: 20px;")
              .col
                p.mb-0 #[strong Recursos (costos y presupuestos):] asignación de presupuesto y recursos humanos y materiales.
            .row.justify-content-center.align-items-center(data-aos="fade-up")
              .col-auto
                figure
                  img(src='@/assets/bullets/icon-1.svg' alt='' style="width: 20px;")
              .col
                p.mb-0 #[strong Posibles riesgos:] identificación y evaluación de posibles obstáculos o problemas.
          .col-lg-auto
            figure
              img(src='@/assets/curso/tema2/3.png')
</template>

<script>
import BannerInterno from '../../components/plantilla/BannerInterno'
export default {
  name: 'Tema2',
  components: {
    BannerInterno,
  },
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
