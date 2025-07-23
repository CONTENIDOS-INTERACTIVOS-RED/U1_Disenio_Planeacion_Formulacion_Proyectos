<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'3. Objetivos, indicadores y resultados esperados'")
  .container.tarjeta.tarjeta--blanca.px-4.pt-4.px-md-5.pt-md-5.pb-0.overflow-hidden

    .bg-color-5.mb-5(data-aos="fade-up")
      .row.justify-content-center.align-items-center
        .col-lg
          .p-4
            p.mb-0(data-aos="fade-up") En la estructuración de un proyecto, los objetivos son declaraciones que describen los resultados que se espera lograr mediante la implementación del proyecto. Se dividen en objetivo general y objetivos específicos, cada uno con un propósito distinto pero complementario.
        .col-lg-auto
          figure
            img(src='@/assets/curso/tema3/1.png', alt='')

    h2.mb-5(data-aos="fade-up") Objetivos
    p(data-aos="fade-up") Basado en la formulación clara del problema a través de preguntas que aborden síntomas, causas, consecuencias y posibles soluciones, los objetivos (general y específicos) de un proyecto se formulan para responder a estas preguntas y guiar las acciones hacia una solución efectiva.

    h2.mb-5(data-aos="fade-up") Objetivo general
    p(data-aos="fade-up").mb-5 Este objetivo responde a la pregunta central que guía el proyecto y es una declaración amplia del propósito principal, alineado con la necesidad de resolver el problema planteado. Debe ser lo suficientemente concreto para que sea operativo, pero lo bastante flexible para permitir distintas soluciones.

    .row.justify-content-center.align-items-start.mb-5
      .col-lg-8
        h3.mb-3(data-aos="fade-up") Ejemplo
        p(data-aos="fade-up").mb-4 Si el problema planteado es: #[strong ¿Cómo podemos optimizar el proceso XYZ para reducir costos en un 10%?,] el objetivo general podría ser: #[strong optimizar el proceso XYZ para reducir los costos operativos en un 10% en los próximos 12 meses.]

        .bg-color-4.p-4(data-aos="fade-left").mb-4
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema3/3.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Los objetivos específicos descomponen el objetivo general en metas concretas, enfocadas en los diferentes aspectos identificados durante la formulación del problema: síntomas, causas y posibles soluciones. Estos objetivos responden preguntas clave como: ¿Qué se necesita mejorar?, ¿Qué cambios deben implementarse?, ¿Cómo se medirán los avances?
        
        p(data-aos="fade-up").mb-0 Cada objetivo específico debe estar diseñado para abordar una parte específica del problema y debe ser medible, permitiendo evaluar el progreso hacia el cumplimiento del objetivo general.
      .col-lg-4
        figure
          img(src="@/assets/curso/tema3/2.png", data-aos="zoom-in").mb-4.mb-lg-0


    h3.mb-3(data-aos="fade-up") Ejemplo
    p(data-aos="fade-up").mb-4 Partiendo del mismo problema, los objetivos específicos podrían ser:

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-6
        .bg-color-1.p-4(data-aos="fade-left")
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema3/4.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Identificar y reducir los tiempos muertos en el proceso XYZ en un 15% mediante la implementación de un sistema automatizado.

      .col-lg-6
        .bg-color-2.p-4(data-aos="fade-left")
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema3/5.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Reducir el consumo de materias primas en el proceso XYZ en un 5% mediante la optimización de las técnicas de producción.

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-6
        .bg-color-2.p-4(data-aos="fade-left")
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema3/6.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Capacitar al personal en el uso de las nuevas tecnologías implementadas, alcanzando un nivel de competencia del 90% en los primeros 3 meses.

      .col-lg-6
        .bg-color-2.p-4(data-aos="fade-left")
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema3/7.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Evaluar y modificar el flujo de trabajo para mejorar la eficiencia operativa en un 8%.

    h2.mb-5(data-aos="fade-up") Justificación, resultados e indicadores

    .row.mb-5
      .col-lg-4
        figure
          img(src="@/assets/curso/tema3/8.png", data-aos="zoom-in")
      .col-lg-8
        p(data-aos="fade-left")  La justificación, los resultados e indicadores de un proyecto es fundamental para garantizar su coherencia y efectividad. La justificación permite contextualizar la relevancia del proyecto, identificando las necesidades o problemas que se desean abordar y estableciendo su importancia en un ámbito específico. Los resultados, por su parte, representan las metas concretas que se pretenden alcanzar, sirviendo como guía para las acciones y asegurando que el esfuerzo esté alineado con los objetivos propuestos. Finalmente, los indicadores se convierten en herramientas esenciales para medir el progreso y evaluar el impacto del proyecto, proporcionando datos claros que respaldan la toma de decisiones y la mejora continua. Este enfoque integral asegura no solo la viabilidad, sino también la sostenibilidad y relevancia del proyecto a lo largo del tiempo.

    .bg-full-width.bg-color-4
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-7
            h2.mb-4(data-aos="flip-up") Justificación, resultados e indicadores
            p.mb-4(data-aos="fade-right") En el documento Justificación, resultados e indicadores se presentan tres elementos clave que estructuran y orientan el desarrollo de un proyectos. Lo invitamos a consultar el documento para ampliar esta información.

            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_3.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Justificación, resultados e indicadores

          .col-lg-5
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema3/9.png', alt='')



    .bg-full-width.border-top.actividad.bg-color-actividad.mb-0
      .p-4.p-md-5
        #Actividad                
          <Actividad :cuestionario="cuestionario"/>


    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.


            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/lc/tecnologicadeloriente/titulos/69169" target="_blank" rel="noopener noreferrer") Córdoba Padilla, M. (2011). Formulación y evaluación de proyectos: ( ed.). Ecoe Ediciones.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://youtu.be/DQlp0DvPBwU?si=K_NvIE68OEsIoJUI" target="_blank" rel="noopener noreferrer") LA PROFE MÓNICA (18 de febrero 2023) ¡Superfórmula! para redactar OBJETIVOS / Objetivos generales / objetivos específicos. Video Youtube.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://asana.com/es/resources/how-project-objectives" target="_blank" rel="noopener noreferrer") Asana. Cómo redactar objetivos de un proyecto que sean eficaces (incluye ejemplos).


          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
import Actividad from '@/components/actividad/Actividad.vue'
export default {
  name: 'Tema3',
  components: {
    Actividad,
  },
  data() {
    return {
      cuestionario: {
        tema: 'Pensamiento estratégico y prospectivo',
        titulo: 'Ponte a prueba',
        introduccion:
          'Demuestra lo que aprendiste en esta unidad y pon a prueba tus conocimientos.',
        barajarPreguntas: true,
        preguntas: [
          {
            id: 1,
            texto:
              'En la fase de planificación, ¿qué herramienta se utiliza para desglosar las tareas y asignarles recursos?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Gráficos de Gantt',
                esCorrecta: true,
              },
              {
                id: 'b',
                texto: 'Análisis de viabilidad',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto: 'Diagrama de causa-efecto',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Encuestas de calidad',
                esCorrecta: false,
              },
            ],
            mensaje_correcto:
              '¡Correcto! Los gráficos de Gantt son la herramienta utilizada para desglosar las tareas y asignarles recursos en la fase de planificación.',
            mensaje_incorrecto:
              'Incorrecto. Revisa las herramientas utilizadas en la fase de planificación de proyectos.',
          },
          {
            id: 2,
            texto:
              '¿Qué incluye la etapa de cierre en un proyecto de inversión?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Capacitar al cliente en el uso de los entregables',
                esCorrecta: true,
              },
              {
                id: 'b',
                texto: 'Establecer el alcance',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto: 'Gestionar recursos humanos',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Documentar los objetivos',
                esCorrecta: false,
              },
            ],
            mensaje_correcto:
              '¡Correcto! La etapa de cierre incluye capacitar al cliente en el uso de los entregables.',
            mensaje_incorrecto:
              'Incorrecto. Revisa qué actividades incluye la etapa de cierre en un proyecto de inversión.',
          },
          {
            id: 3,
            texto:
              '"Durante la operación se verifica que el proyecto cumpla con las expectativas de rendimiento y se ajustan procesos para maximizar la eficiencia, asegurando que genere los beneficios previstos".',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Falso',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Verdadero',
                esCorrecta: true,
              },
            ],
            mensaje_correcto:
              '¡Correcto! Durante la operación se verifica que el proyecto cumpla con las expectativas de rendimiento y se ajustan procesos para maximizar la eficiencia.',
            mensaje_incorrecto:
              'Incorrecto. Revisa las actividades que se realizan durante la etapa de operación del proyecto.',
          },
          {
            id: 4,
            texto:
              '"La planificación de la comunicación es necesaria para mantener a las partes interesadas informadas y alineadas con los avances del proyecto, promoviendo una relación colaborativa y fluida."',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Falso',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Verdadero',
                esCorrecta: true,
              },
            ],
            mensaje_correcto:
              '¡Correcto! La planificación de la comunicación es necesaria para mantener a las partes interesadas informadas y alineadas con los avances del proyecto.',
            mensaje_incorrecto:
              'Incorrecto. Revisa la importancia de la planificación de la comunicación en proyectos.',
          },
          {
            id: 5,
            texto:
              'En una sustentación final te piden escoger un enfoque que permita definir objetivos específicos, medibles, alcanzables, realistas y con un plazo definido, que facilite la gestión clara y estructurada de un proyecto ¿Qué metodología recomendarías para definir los objetivos en la fase de definición formal?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Metodología Ágil',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Smart',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto: 'Diagrama de Gantt',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Evaluación de riesgos',
                esCorrecta: false,
              },
            ],
            mensaje_correcto:
              '¡Correcto! La metodología SMART es la recomendada para definir objetivos específicos, medibles, alcanzables, realistas y con un plazo definido.',
            mensaje_incorrecto:
              'Incorrecto. Revisa las metodologías para definir objetivos en la fase de definición formal de proyectos.',
          },
        ],
        mensaje_final_aprobado:
          '¡Felicidades! Has superado la prueba con éxito.',
        mensaje_final_reprobado:
          'Te recomendamos repasar nuevamente la unidad para reforzar los conceptos clave antes de volver a intentarlo.',
      },
    }
  },
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass">
.bg-color-actividad
  background-color: #EBF1F5
</style>
