<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'2. Derecho a la salud en la primera infancia'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden
    .row.mb-5          
      .col-lg-8.mb-3.mb-lg-0 
        p(data-aos="fade-down") La salud en los primeros años de vida, es determinante para el desarrollo integral. Cada experiencia, cuidado y oportunidad de bienestar en esta etapa, tiene un impacto profundo y duradero. Sin embargo, garantizar este derecho sigue siendo un desafío en muchos contextos colombianos.

        .bg-color-1.p-4.mb-4(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img.img-a.img-t(src="@/assets/curso/temas/8.svg")
            .col-lg
              p.mb-0 Según Camargo y Pinzón (2012), el acceso a servicios médicos de calidad, una nutrición equilibrada, la vacunación oportuna y la prevención de enfermedades son fundamentales para el crecimiento infantil. No obstante, factores como la pobreza, la deficiencia en infraestructura y la falta de información comprometen gravemente este derecho.

      .col-lg-4
        figure
          img.img-a.img-t(src="@/assets/curso/temas/9.png", data-aos="zoom-in") 

    h3(data-aos="fade-down") Cobertura y acceso a servicios de salud                              
    p(data-aos="fade-down") En Colombia, el derecho a la salud infantil, está respaldado normativamente por programas como el Plan de Atención Integral en Salud para la Primera Infancia y la Ruta Integral de Atención en Salud (RIAS), que buscan asegurar atención oportuna, integral y especializada. Sin embargo, la efectividad de estas estrategias enfrenta barreras estructurales.

    .row.align-items-start.mb-5(data-aos="fade-left")
      .col-lg-4.mb-3.mb-lg-0 
        figure
          img.img-a.img-t(src="@/assets/curso/temas/10.png", alt="")      
      .col-lg-8
        AcordionA(tipo="b")
          .div(titulo="Desigualdad territorial")
            p En las ciudades existe mayor cobertura médica, mientras que en zonas rurales e indígenas, las familias deben recorrer largas distancias para acceder a la atención, enfrentando escaso transporte y carencia de personal especializado.  
          .div(titulo="Pobreza extrema")
            p Las familias en situación de mayor vulnerabilidad, enfrentan barreras para acceder a servicios como controles de crecimiento, vacunas, atención nutricional y tratamientos básicos, a pesar de que estos están contemplados como gratuitos.  
          .div(titulo="Falta de información")
            p Muchas familias no conocen los beneficios que ofrece el sistema de salud, lo cual reduce su uso y utilidad. La orientación institucional es limitada, sobre todo en regiones apartadas donde más se requiere acompañamiento.

    h3(data-aos="fade-down") Nutrición y desarrollo infantil temprano                            

    .row.mb-5
      .col-lg-8.mb-3.mb-lg-0
        .bg-color-3.p-4.mb-4(data-aos="fade-left")
          p.mb-0 La nutrición adecuada en la primera infancia, es esencial para el desarrollo físico, cognitivo y emocional. Como plantea Cortez (2002), cada nutriente y cada comida en esta etapa crítica, pueden marcar la diferencia en la vida de un niño o niña. 

        p(data-aos="fade-down") Aunque Colombia cuenta con estrategias como el Plan Nacional de Seguridad Alimentaria y Nutricional, la estrategia Cero Desnutrición y los planes de alimentación escolar, persisten graves problemas:          
      .col-lg-4 
        figure
          img.img-a.img-t(src="@/assets/curso/temas/11.png", data-aos="zoom-in")    

    .bg-full-width.bg-fondo-slider.mb-5(data-aos="fade-right")
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img.img-a.img-t(src="@/assets/curso/temas/12.png")            
            .col-lg-7
              h5 Desnutrición crónica
              p Afecta a miles de niños y niñas menores de cinco años, especialmente en comunidades rurales, indígenas y empobrecidas. Los primeros mil días de vida son fundamentales para el desarrollo cerebral y del sistema inmunológico.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img.img-a.img-t(src="@/assets/curso/temas/12.png")            
            .col-lg-7
              h5 Malnutrición por exceso
              p El aumento en el consumo de alimentos ultraprocesados ha incrementado la obesidad infantil, que convive con la desnutrición, revelando una marcada desigualdad en los patrones alimentarios.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img.img-a.img-t(src="@/assets/curso/temas/12.png")            
            .col-lg-7
              h5 Factores estructurales
              p La falta de acceso a agua potable, el inadecuado saneamiento y las enfermedades gastrointestinales dificultan la absorción de nutrientes. La escasa orientación alimentaria en contextos vulnerables intensifica el problema.

    .bg-full-width-1.bg-fondo-1
      .px-4.px-md-5.pb-md-3
        p(data-aos="fade-down") Un componente clave es la #[b lactancia materna exclusiva, durante los primeros seis meses], seguida de una alimentación complementaria adecuada hasta los dos años o más. Sin embargo, en Colombia, su práctica sigue siendo limitada por: 

        div.row.justify-content-center.align-items-stretch.text-center
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100.br-1
              img.mx-auto.d-block.mb-4(src="@/assets/curso/temas/15.svg" alt="" style="width: 90px")
              h5 Primero
              p.mb-0 Desinformación.

          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100.br-1
              img.mx-auto.d-block.mb-4(src="@/assets/curso/temas/16.svg" alt="" style="width: 90px")
              h5 Segundo 
              p.mb-0 Reincorporación laboral temprana, sin condiciones para lactar.

          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100.br-1
              img.mx-auto.d-block.mb-4(src="@/assets/curso/temas/17.svg" alt="" style="width: 90px")
              h5 Tercero
              p.mb-0 Falta de redes de apoyo familiar y comunitario. 

    p(data-aos="fade-down") Como señala Daza (1997), #[b la nutrición influye directamente en el desarrollo cognitivo, emocional y social], impactando el rendimiento escolar, la capacidad de aprendizaje y la salud emocional.   

    .bg-full-width.bg-color-3.mb-5
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-8.mb-3.mb-lg-0
            h2.mb-4(data-aos="flip-up") Problemáticas en salud infantil: desnutrición, enfermedades prevalentes y mortalidad infantil
            p.mb-4(data-aos="fade-right") Se invita a leer el documento Factores socioeconómicos que impactan el ejercicio de sus derechos, donde se aborda cómo diversas condiciones socioeconómicas, afectan el desarrollo integral y el ejercicio de los derechos de la primera infancia en Colombia. 
            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_1.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Problemáticas en salud infantil: desnutrición, enfermedades prevalentes y mortalidad infantil
          .col-lg-4
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/temas/18.png', alt='')

    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/lc/tecnologicadeloriente/titulos/260385" target="_blank" rel="noopener noreferrer") Souto Galván, C. (2022). El derecho a una educación universal e inclusiva. Dykinson. 
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/lc/tecnologicadeloriente/titulos/106180" target="_blank" rel="noopener noreferrer") Ramos Ramos, P. (Coord.). (2018). Maltrato infantil: conocimiento y prevención (2a ed.). Editorial ICB.              

            p.d-flex.my-4
              img.me-3(src='@/assets/template/book.svg' :style="{'max-width':'16px'}")
              a(href="https://christussinergia.com/blog/programa-de-salud-infantil-por-una-infancia-segura-y-saludable-para-nuestros-hijos/" target="_blank" rel="noopener noreferrer") Christus Sinergia Salud. (s.f.). Programa de Salud Infantil: por una infancia segura y saludable. CHRISTUS Colombia.                              


            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.educo.org/blog/tipos-de-maltrato-infantil-consecuencias-violencia" target="_blank" rel="noopener noreferrer") El Blog de Educo. (2024). Tipos de maltrato infantil y consecuencias de la violencia infantil. Educo educar cura.
            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://consultoriopsicologia.unbosque.edu.co/blog/que-hacer-en-casos-de-violencia-conceptos-y-tips-importantes" target="_blank" rel="noopener noreferrer") Universidad El Bosque. (s.f.).¿Qué hacer en casos de violencia? Conceptos y Tips importantes.


          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
export default {
  name: 'Tema2',
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
