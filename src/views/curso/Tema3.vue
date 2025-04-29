<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'3. Derecho a la educación en la primera infancia'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden
    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0 
        figure
          img.img-a.img-t(src="@/assets/curso/temas/19.png", data-aos="zoom-in")    
      .col-lg-8
        p(data-aos="fade-down") La educación en los primeros años de vida va más allá de la transmisión de conocimientos básicos: es un proceso integral que promueve el desarrollo emocional, social, físico y cognitivo. Es un derecho fundamental reconocido internacionalmente, pero en la práctica, persisten desafíos profundos que impiden su ejercicio pleno (de Pisón, 2004).     
        .bg-color-3.p-4.mb-4(data-aos="fade-left")
          p En el caso colombiano, aunque existen políticas y estrategias que buscan garantizar el acceso y la calidad de la educación inicial, aún se observan desigualdades marcadas en #[b cobertura, infraestructura, formación docente y pertinencia educativa], especialmente en contextos rurales y vulnerables.

          h5 Esta reflexión nos invita a preguntarnos:

          p.mb-0 ¿Qué puede hacer cada persona para que la educación sea realmente un derecho accesible y efectivo para todos los niños y las niñas, desde su nacimiento?


    h3(data-aos="fade-down") Accesibilidad y cobertura de la educación inicial en Colombia 

    .row      
      .col-lg-8.mb-3.mb-lg-0 
        p(data-aos="fade-down") A pesar de los esfuerzos institucionales, no todos los niños y las niñas en Colombia, tienen garantizado el acceso a una educación inicial, de calidad. #[b Las desigualdades territoriales y socioeconómicas], siguen generando brechas en el desarrollo infantil.

        .bg-color-2.p-4.mb-4(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img.img-a.img-t(src="@/assets/curso/temas/20.svg")
            .col-lg
              p.mb-0 Como señala Kluwer (1979), el acceso a la educación inicial no depende únicamente de la existencia de instituciones, sino también de factores como la ubicación geográfica, disponibilidad de cupos, calidad de los programas, formación docente y condiciones económicas de las familias.

      .col-lg-4
        figure
          img.img-a.img-t(src="@/assets/curso/temas/21.png", data-aos="zoom-in")  

    .bg-full-width.bg-h85.mb-5
      .px-4.p-md-5
        .row  
          .col-lg-4.mb-3.mb-lg-0.up 
            figure
              img.img-a.img-t(src="@/assets/curso/temas/22.png", data-aos="zoom-in")             
          .col-lg-8.up
            p.mt-5(data-aos="fade-down") Aunque existen programas importantes como los Centros de Desarrollo Infantil (CDI), la modalidad familiar de atención a la primera infancia y la estrategia "De Cero a Siempre", los retos persisten:
            ul.lista-ul--color
              li.mb-3.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Zonas rurales y apartadas, presentan infraestructura deficiente y escaso acceso a servicios educativos.
              li.mb-3.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Falta de docentes especializados y recursos didácticos adecuados.
              li.mb-3.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Dificultades para garantizar la continuidad del proceso educativo y la transición entre etapas. 

    h3(data-aos="fade-down") Calidad educativa: avances y desafíos 
    p(data-aos="fade-down") La educación en la primera infancia, es el punto de partida para construir una sociedad más equitativa.

    .bg-full-width.bg-color-3.mb-5
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-8.mb-3.mb-lg-0
            h2.mb-4(data-aos="flip-up") Estrategias para la inclusión y equidad educativa
            p.mb-4(data-aos="fade-right") Se invita a leer el documento Estrategias para la inclusión y equidad educativa, donde se analiza cómo garantizar que todos los niños y las niñas, sin importar su contexto o condición, tengan acceso a una educación inicial inclusiva y de calidad. 
            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_1.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Estrategias para la inclusión y equidad educativa
          .col-lg-4
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/temas/23.png', alt='')  


    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/lc/tecnologicadeloriente/titulos/66977" target="_blank" rel="noopener noreferrer") Giberti, E. (2005). Abuso sexual y malos tratos contra niños, niñas y adolescentes: perspectiva psicológica y social. Espacio Editorial. 
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://dspace.tdea.edu.co/handle/tda/333" target="_blank" rel="noopener noreferrer") Ramírez Otálvaro, O. P. (2016). El derecho a la educación en la Primera Infancia. Asamblea Anual OMEP Región América Latina. Tecnológico de Antioquia.              

            p.d-flex.my-4
              img.me-3(src='@/assets/template/book.svg' :style="{'max-width':'16px'}")
              a(href="http://www.scielo.org.bo/pdf/rmcmlp/v22n2/v22n2_a14.pdf" target="_blank" rel="noopener noreferrer") Arévalo Barea, A. R. (2016). Abuso infantil. Revista Médica La Paz, 22(2), 87-97.                              


            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=x3CUS4voxM4" target="_blank" rel="noopener noreferrer") La Gaceta. (2015). El problema de la desnutrición y sus consecuencias.
            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=M_-AcKMUjaw" target="_blank" rel="noopener noreferrer") DESDE LA U - CANAL UCR. (2018). Principales Desafíos en educación y salud: derechos impostergables de la Primera Infancia.               

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
