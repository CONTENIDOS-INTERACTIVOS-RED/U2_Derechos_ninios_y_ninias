<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'4. Violencia y abuso infantil en la primera infancia'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden
    .row.mb-5
      .col.mb-3.mb-lg-0 
        p(data-aos="fade-down") La violencia hacia los niños y las niñas, no se limita solamente a lo físico. Existen múltiples formas de maltrato, algunas normalizadas socialmente o invisibilizadas, pero todas igualmente perjudiciales para su desarrollo integral. Conocer sus manifestaciones es fundamental para prevenir, detectar y actuar.     
      .col-lg-auto
        figure
          img.img-a.img-t(src="@/assets/curso/temas/24.svg", data-aos="zoom-in")

    .bg-full-width.bg-fondo-slider.mb-5(data-aos="fade-right")
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img.img-a.img-t(src="@/assets/curso/temas/25.png")            
            .col-lg-7
              h5 Violencia física
              p Comprende golpes, empujones, quemaduras, pellizcos o sacudidas. Aunque algunos aún justifican el castigo físico como disciplina, este resulta perjudicial. El síndrome del bebé sacudido es un caso extremo, con posibles consecuencias neurológicas irreversibles, ceguera o muerte. 

          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img.img-a.img-t(src="@/assets/curso/temas/25.png")            
            .col-lg-7
              h5 Violencia psicológica 
              p Es silenciosa pero destructiva. Se manifiesta en insultos, humillaciones, amenazas, burlas o indiferencia. Frases negativas afectan la autoestima y el bienestar emocional. Sus consecuencias incluyen inseguridad, miedo, dificultades para relacionarse, bajo rendimiento escolar, ansiedad o depresión.

          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img.img-a.img-t(src="@/assets/curso/temas/25.png")            
            .col-lg-7
              h5 Abuso sexual infantil 
              p Implica contacto sexual, exposición a contenido sexual o conductas inapropiadas de parte de adultos o mayores. Suele ocurrir en el entorno cercano, dificultando la denuncia. Genera consecuencias duraderas como depresión, desconfianza y revictimización. Se previene enseñando el respeto al cuerpo, creando entornos de confianza, capacitando adultos e implementando protocolos escolares. 

          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img.img-a.img-t(src="@/assets/curso/temas/25.png")            
            .col-lg-7
              h5 Negligencia 
              p Se refiere a la omisión de cuidados básicos como alimentación, higiene, salud, supervisión y afecto. Aunque menos visible, sus efectos son profundos y sostenidos. Incluye dejar al niño sin supervisión, no ofrecer una dieta adecuada, omitir controles médicos o ignorar su necesidad de afecto.

    h3(data-aos="fade-down") Factores de riesgo y estrategias de prevención en la primera infancia  

    .row.mb-5          
      .col-lg-8.mb-3.mb-lg-0 
        p(data-aos="fade-down") La primera infancia es una etapa crítica en el desarrollo humano, durante la cual se sientan las bases del bienestar emocional, social y cognitivo. Garantizar entornos seguros y protectores es una prioridad, especialmente en contextos donde muchos niños y las niñas enfrentan situaciones que comprometen su desarrollo y vulneran sus derechos fundamentales.

        .bg-color-1.p-4.mb-4(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img.img-a.img-t(src="@/assets/curso/temas/29.svg")
            .col-lg
              p.mb-0 Un factor de riesgo se define como cualquier circunstancia que aumenta la probabilidad de que un niño o niña sufra daños físicos, emocionales o sociales. Estos factores pueden originarse en el entorno familiar, comunitario, social o, incluso, en características individuales del menor. Reconocerlos es clave para diseñar estrategias de prevención y promover el desarrollo integral en entornos seguros y afectivos.

      .col-lg-4
        figure
          img.img-a.img-t(src="@/assets/curso/temas/30.png", data-aos="zoom-in") 

    h3(data-aos="fade-down") Factores familiares  
    p(data-aos="fade-down") La familia es el primer espacio de socialización, pero cuando está marcada por disfunción o carece de condiciones adecuadas, puede convertirse en un entorno riesgoso:

    .bg-full-width.bg-color-info.mb-5(data-aos="fade-right")
      .p-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-10
            ImagenInfografica.color-secundario
                template(v-slot:imagen)
                  figure
                    img(src='@/assets/curso/temas/31.svg', alt='', style="max-width: 800px;").mx-auto

                .bg-color-white.box-shadow.p-3(x="63%" y="34%" numero="+")
                  h5 1. Violencia intrafamiliar 
                  p Presenciar o ser víctima de agresiones físicas o verbales en el hogar, afecta de forma profunda el desarrollo emocional y la percepción de seguridad en los niños y las niñas. 
                  
                .bg-color-white.box-shadow.p-3(x="85%" y="33%" numero="+")
                  h5 2. Negligencia 
                  p La omisión en la atención de necesidades básicas como salud, alimentación y educación puede provocar retrasos en el desarrollo físico, cognitivo y emocional. 

                .bg-color-white.box-shadow.p-3(x="63%" y="78%" numero="+")
                  h5 3. Pobreza 
                  p La carencia de recursos limita el acceso a servicios esenciales, lo cual impacta negativamente tanto el crecimiento físico como el bienestar emocional. 

                .bg-color-white.box-shadow.p-3(x="85%" y="79%" numero="+")
                  h5 4. Crianza inadecuada 
                  p Prácticas que recurren al castigo o carecen de afecto generan inseguridad, temor y dificultades en la construcción de vínculos saludables.

    .bg-full-width-1.bg-fondo-1
      .px-4.px-md-5.pb-md-3
        h3(data-aos="fade-down") Factores comunitarios
        p(data-aos="fade-down") El entorno donde vive un niño también influye en su seguridad y oportunidades:

        div.row.justify-content-center.align-items-stretch.text-center
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100.br-1
              img.mx-auto.d-block.mb-4(src="@/assets/curso/temas/32.svg" alt="" style="width: 90px")
              h5 Inseguridad y violencia comunitaria
              p.mb-0 La exposición a conflictos, delincuencia o violencia armada, genera estrés y ansiedad.

          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100.br-1
              img.mx-auto.d-block.mb-4(src="@/assets/curso/temas/33.svg" alt="" style="width: 90px")
              h5 Carencia de servicios básicos 
              p.mb-0 La falta de instituciones educativas, centros de salud y espacios recreativos, limita el desarrollo integral.

          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100.br-1
              img.mx-auto.d-block.mb-4(src="@/assets/curso/temas/34.svg" alt="" style="width: 90px")
              h5 Trabajo infantil
              p.mb-0 Obligar a los niños a trabajar, vulnera sus derechos y afecta su salud física y emocional. 

    h3(data-aos="fade-down") Factores individuales   
    p(data-aos="fade-down") Algunas características personales pueden aumentar la vulnerabilidad de un niño o niña:   

    .row.align-items-start.mb-5(data-aos="fade-left")
      .col-lg-4.mb-3.mb-lg-0 
        figure
          img.img-a.img-t(src="@/assets/curso/temas/35.png", alt="")      
      .col-lg-8
        AcordionA(tipo="b")
          .div(titulo="Discapacidad o enfermedades crónicas")
            p Pueden enfrentar discriminación, negligencia y falta de acceso a servicios adaptados.
          .div(titulo="Dificultades en el desarrollo emocional o del lenguaje")
            p Pueden generar aislamiento y aumentar el riesgo de abuso. 
          .div(titulo="Baja autoestima")
            p Facilita situaciones de exclusión, acoso o violencia emocional.

    .row.mb-5
      .col-lg-8.mb-3.mb-lg-0
        h3(data-aos="fade-down") Estrategias de prevención
        .bg-color-3.p-4.mb-4(data-aos="fade-left")
          p.mb-0 Frente a estos factores de riesgo, es necesario implementar estrategias preventivas integrales que involucren a la familia, la comunidad, las instituciones educativas y las políticas públicas.

        h5(data-aos="fade-down") Fortalecimiento familiar y crianza positiva

        p(data-aos="fade-down") Este eje busca promover vínculos familiares saludables y entornos protectores, mediante acciones que acompañen a las familias en sus procesos de crianza.         
      .col-lg-4 
        figure
          img.img-a.img-t(src="@/assets/curso/temas/36.png", data-aos="zoom-in") 

    .bg-full-width-1.bg-fondo-1
      .px-4.px-md-5.pb-md-3
        div.row.justify-content-center.align-items-stretch.text-center
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100.br-1
              img.mx-auto.d-block.mb-4(src="@/assets/curso/temas/37.svg" alt="" style="width: 90px")
              h5 Parentalidad positiva
              p.mb-0 Proporcionar herramientas a los cuidadores, para fomentar una crianza respetuosa, basada en la comunicación, el afecto y límites sin violencia.

          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100.br-1
              img.mx-auto.d-block.mb-4(src="@/assets/curso/temas/38.svg" alt="" style="width: 90px")
              h5 Apoyo psicológico 
              p.mb-0 Acompañamiento emocional para familias en situaciones de estrés o conflicto.

          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100.br-1
              img.mx-auto.d-block.mb-4(src="@/assets/curso/temas/39.svg" alt="" style="width: 90px")
              h5 Programas sociales integrales
              p.mb-0 Acceso a buena alimentación, salud y educación, para familias en condiciones de vulnerabilidad. 

        .row.mb-5
          .col.mb-3.mb-lg-0 
            h5(data-aos="fade-down") Intervención comunitaria y educativa

            p(data-aos="fade-down") Este eje impulsa el compromiso colectivo en la construcción de entornos protectores, equitativos e inclusivos.    
          .col-lg-auto
            figure
              img.img-a.img-t(src="@/assets/curso/temas/40.svg", data-aos="zoom-in") 

        div.row.justify-content-center.align-items-stretch.text-center
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100.br-1
              img.mx-auto.d-block.mb-4(src="@/assets/curso/temas/41.svg" alt="" style="width: 90px")
              h5 Sensibilización comunitaria
              p.mb-0 Promover entornos libres de violencia y con acceso a servicios básicos.

          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100.br-1
              img.mx-auto.d-block.mb-4(src="@/assets/curso/temas/42.svg" alt="" style="width: 90px")
              h5 Educación inicial inclusiva
              p.mb-0 Espacios educativos que fomenten el desarrollo emocional y la autoestima, desde los primeros años.

          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100.br-1
              img.mx-auto.d-block.mb-4(src="@/assets/curso/temas/43.svg" alt="" style="width: 90px")
              h5 Participación activa de la comunidad
              p.mb-0 Redes de apoyo que fortalezcan la corresponsabilidad en la protección infantil.

    h3(data-aos="fade-down") Educación como herramienta de prevención 
    p(data-aos="fade-down") A través de acciones pedagógicas, formación docente y enfoques inclusivos, se busca empoderar a niños, niñas y adolescentes para que crezcan en entornos seguros y respetuosos.

    .bg-full-width.bg-fondo-slider.mb-5(data-aos="fade-right")
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img.img-a.img-t(src="@/assets/curso/temas/44.png")            
            .col-lg-7
              h5 Prevención en escuelas 
              p Desarrollar programas que enseñen a niños y niñas sobre sus derechos, el respeto a su cuerpo y la comunicación emocional, desde los primeros años.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img.img-a.img-t(src="@/assets/curso/temas/45.png")            
            .col-lg-7
              h5 Capacitación docente en riesgos 
              p Formar a los educadores para identificar señales de violencia o maltrato infantil y actuar con responsabilidad y conocimiento para proteger a la niñez.  
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img.img-a.img-t(src="@/assets/curso/temas/46.png")            
            .col-lg-7
              h5 Educación inclusiva 
              p Asegurar el acceso universal a una educación de calidad, como estrategia para reducir desigualdades y promover el desarrollo integral de todos los niños y las niñas.

    .bg-full-width-1.bg-fondo-1
      .px-4.px-md-5.pb-md-3
        h3(data-aos="fade-down") Creación de entornos comunitarios protectores       
        p(data-aos="fade-down") A través de infraestructuras adecuadas, políticas públicas y redes comunitarias, se busca garantizar el cuidado y la protección desde lo colectivo.

        div.row.justify-content-center.align-items-stretch.text-center
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100.br-1
              img.mx-auto.d-block.mb-4(src="@/assets/curso/temas/47.svg" alt="" style="width: 90px")
              h5 Espacios seguros
              p.mb-0 La construcción de parques, bibliotecas y centros comunitarios fortalece el desarrollo infantil en ambientes protegidos, promoviendo el juego, el aprendizaje y la convivencia pacífica..

          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100.br-1
              img.mx-auto.d-block.mb-4(src="@/assets/curso/temas/48.svg" alt="" style="width: 90px")
              h5 Políticas públicas de protección 
              p.mb-0 El Estado debe implementar y hacer cumplir programas orientados a prevenir la violencia y garantizar la protección infantil en todos los territorios.

          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100.br-1
              img.mx-auto.d-block.mb-4(src="@/assets/curso/temas/49.svg" alt="" style="width: 90px")
              h5 Redes de apoyo comunitarias
              p.mb-0 La conformación de grupos entre familias, educadores y líderes locales favorece la creación de entornos seguros y solidarios para el cuidado y desarrollo de la niñez. 

    .bg-full-width.bg-color-3.mb-5
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-8.mb-3.mb-lg-0
            h2.mb-4(data-aos="flip-up") La escuela como espacio protector: el rol del docente frente a la violencia infantil
            p.mb-4(data-aos="fade-right") Se invita a leer el documento La escuela como espacio protector: el rol del docente frente a la violencia infantil, donde se examina cómo la escuela y los docentes pueden convertirse en agentes fundamentales para la detección, prevención y atención de situaciones de violencia contra niños y niñas en la primera infancia.
            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_4.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> La escuela como espacio protector: el rol del docente frente a la violencia infantil
          .col-lg-4
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/temas/50.png', alt='') 


    .bg-full-width.border-top.actividad.bg-color-actividad
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
              a(href="https://openurl.ebsco.com/EPDB%3Agcd%3A1%3A9627425/detailv2?sid=ebsco%3Aplink%3Ascholar&id=ebsco%3Agcd%3A141088754&crl=c&link_origin=scholar.google.es" target="_blank" rel="noopener noreferrer") Albornoz Zamora, E. J., Macías Merizalde, A. & del Carmen Guzmán, M. (2019). Inclusión preescolar desde el enfoque de la diversidad cultural. Roca: Revista Científico-Educacional de la Provincia de Granma, 15(3) p. 98. 
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="http://upnblib.pedagogica.edu.co/handle/20.500.12209/10870" target="_blank" rel="noopener noreferrer") Muñoz Bohórquez, Á. & Simmons Ortiz, P. E. (2019). La constitución subjetiva de la niñez: posibilidades desde la transformación de prácticas educativas con primera infancia en contexto rural. 
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="http://www.scielo.org.bo/pdf/rmcmlp/v22n2/v22n2_a14.pdf" target="_blank" rel="noopener noreferrer") Arévalo Barea, A. R. (2016). Abuso infantil. Revista Médica La Paz, 22(2), 87-97.                              

            p.d-flex.my-4
              img.me-3(src='@/assets/template/book.svg' :style="{'max-width':'16px'}")
              a(href="http://www.scielo.org.bo/pdf/rmcmlp/v22n2/v22n2_a14.pdf" target="_blank" rel="noopener noreferrer") Arévalo Barea, A. R. (2016). Abuso infantil. Revista Médica La Paz, 22(2), 87-97.                              


            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=Ckh4Z-aOw-4" target="_blank" rel="noopener noreferrer") San Telmo Museoa. (2018). Pilar Polo / Memoria, olvido, relato y reconocimiento en víctimas abuso sexual en la infancia.

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')
  
</template>

<script>
import Actividad from '@/components/actividad/Actividad.vue'
export default {
  name: 'Tema4',
  components: {
    Actividad,
  },
  data() {
    return {
      cuestionario: {
        tema:
          'Estado de los derechos referidos a la salud, la educación, la violencia y el abuso sexual en Colombia',
        titulo: 'Ponte a prueba',
        introduccion:
          'Demuestra lo que aprendiste en esta unidad y pon a prueba tus conocimientos.',
        barajarPreguntas: true,
        preguntas: [
          {
            id: 1,
            texto:
              '¿Cuál de los siguientes factores representa una de las principales barreras para el acceso a la educación en la primera infancia en Colombia?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'La sobrepoblación en las zonas rurales.',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto:
                  'La falta de cobertura y calidad en los programas educativos.',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto: 'El uso de metodologías activas en el aula.',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto:
                  'La sobreprotección de los niños y niñas por parte de sus familias.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 2,
            texto:
              '¿Qué entidad en Colombia es responsable de la garantía y protección de los derechos de la infancia?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Instituto Colombiano de Bienestar Familiar (ICBF).',
                esCorrecta: true,
              },
              {
                id: 'b',
                texto: 'Ministerio de Transporte.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto: 'Fiscalía General de la Nación.',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Superintendencia de Industria y Comercio.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 3,
            texto:
              '¿Cuál de las siguientes situaciones constituye una forma de violencia infantil?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'El castigo físico como método disciplinario.',
                esCorrecta: true,
              },
              {
                id: 'b',
                texto:
                  'La participación de los niños en actividades recreativas.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto: 'El acceso a servicios de salud de calidad.',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'La educación inclusiva en la primera infancia.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 4,
            texto:
              '¿Cuál es uno de los principales riesgos de la desnutrición infantil en la primera infancia?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Mejora en la capacidad de aprendizaje.',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Mayor resistencia a enfermedades.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto: 'Retraso en el desarrollo físico y cognitivo.',
                esCorrecta: true,
              },
              {
                id: 'd',
                texto: 'Aumento en la tasa de natalidad.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 5,
            texto:
              '¿Qué derecho fundamental se vulnera cuando un niño o niña no tiene acceso a servicios de salud adecuados?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Derecho a la identidad.',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Derecho a la recreación.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto: 'Derecho a la vida y a la salud.',
                esCorrecta: true,
              },
              {
                id: 'd',
                texto: 'Derecho a la participación.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
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
