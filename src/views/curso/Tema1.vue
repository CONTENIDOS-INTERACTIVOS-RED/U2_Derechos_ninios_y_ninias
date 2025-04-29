<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'1. Declaración Universal de los Derechos Humanos'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden
    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0 
        figure
          img.img-a.img-t(src="@/assets/curso/temas/3.png", data-aos="zoom-in")                
      .col-lg-8
        p(data-aos="fade-down") ¿Realmente, todos los niños y las niñas en Colombia, tienen garantizados sus derechos en salud, educación y protección? Aunque la primera infancia ha sido reconocida como una etapa clave en el desarrollo integral y el país ha avanzado en políticas y normativas para su protección, #[b persisten desafíos significativos], especialmente en comunidades vulnerables, donde el acceso a servicios esenciales sigue siendo insuficiente.

        .bg-color-3.p-4.mb-4(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img.img-a.img-t(src="@/assets/curso/temas/4.svg")
            .col-lg
              p.mb-0 En el ámbito de la salud, existen programas de atención materno-infantil y control del desarrollo, pero las brechas en cobertura y calidad, #[b afectan especialmente a zonas rurales y marginales]. Problemas como la #[b desnutrición], la falta de controles médicos periódicos y la escasez de infraestructura sanitaria, continúan siendo alarmantes. 
        p(data-aos="fade-down") En cuanto a #[b la educación], el derecho a una educación inicial de calidad, enfrenta dificultades relacionadas con la #[b cobertura, la calidad pedagógica y la formación docente]. A pesar de esfuerzos por ampliar el acceso, #[b persisten barreras económicas, geográficas y culturales] que limitan la inclusión educativa desde los primeros años.

    .row.mb-5
      .col-lg-8.mb-3.mb-lg-0 
        p(data-aos="fade-down") ¿Realmente, todos los niños y las niñas en Colombia, tienen garantizados sus derechos en salud, educación y protección? Aunque la primera infancia ha sido reconocida como una etapa clave en el desarrollo integral y el país ha avanzado en políticas y normativas para su protección, #[b persisten desafíos significativos], especialmente en comunidades vulnerables, donde el acceso a servicios esenciales sigue siendo insuficiente.

        .bg-color-1.p-4.mb-4(data-aos="fade-left")
          p.mb-0 #[b La protección contra la violencia y el abuso], es otro ámbito crítico. El maltrato infantil, el abuso sexual y la negligencia parental, siguen afectando a miles de menores. La falta de mecanismos de denuncia efectivos, la #[b revictimización] y la #[b impunidad], agravan esta situación, dejando a muchos niños expuestos a entornos inseguros.
        p(data-aos="fade-down") A pesar de los avances normativos, las brechas en salud, educación y protección, siguen siendo profundas. Cada cifra y testimonio evidencian una realidad compleja que interpela a toda la sociedad, especialmente a quienes forman a las nuevas generaciones. La pobreza, la desigualdad y la debilidad institucional en ciertos territorios, hacen que muchos infantes no cuenten con las condiciones mínimas para su desarrollo integral.
      .col-lg-4
        figure
          img.img-a.img-t(src="@/assets/curso/temas/5.png", data-aos="zoom-in")         

    h3(data-aos="fade-down") Principales desafíos en la protección de la primera infancia
    p.mb-5(data-aos="fade-down") La etapa de la primera infancia (0 a 6 años), es crucial para establecer las bases del desarrollo físico, cognitivo, emocional y social. Sin embargo, múltiples desafíos estructurales, siguen afectando el bienestar de los niños y niñas en Colombia (Girón, 2023).

    .row.align-items-start.mb-5(data-aos="fade-left")
      .col-lg-4.mb-3.mb-lg-0 
        figure
          img.img-a.img-t(src="@/assets/curso/temas/6.png", alt="")      
      .col-lg-8
        AcordionA(tipo="b")
          .div(titulo="Salud y nutrición")
            p Aunque la mortalidad infantil ha disminuido, persisten barreras de acceso, especialmente en zonas rurales. La desnutrición crónica sigue siendo una amenaza para el desarrollo cognitivo y físico. Es fundamental fortalecer las políticas públicas y fomentar una alimentación saludable desde el hogar y la comunidad.
          .div(titulo="Educación inicial")
            p A pesar de los avances normativos, persisten profundas desigualdades en el acceso y la calidad, sobre todo en zonas rurales e indígenas. La educación en esta etapa, aún se percibe en algunos contextos como un privilegio, lo que impide su expansión y limita su impacto.
          .div(titulo="Violencia y abuso")
            p Miles de niños y niñas continúan siendo víctimas de violencia física, psicológica y sexual, frecuentemente dentro del entorno familiar. La falta de respuestas institucionales oportunas y la impunidad perpetúan el problema. Se requieren medidas preventivas, atención inmediata y un fortalecimiento de los sistemas de protección.
          .div(titulo="Pobreza y exclusión social")
            p La inseguridad económica, el déficit habitacional y la precariedad en servicios básicos crean entornos adversos para el desarrollo infantil. La pobreza no solo restringe recursos materiales, sino también oportunidades para el aprendizaje y la estimulación temprana.
          .div(titulo="Corresponsabilidad social")
            p La garantía de los derechos de la infancia no es solo responsabilidad del Estado. Familias, comunidades, escuelas y organizaciones, deben actuar de forma conjunta. Es clave promover la crianza positiva, la educación emocional y una cultura comunitaria de protección.

    .bg-full-width.bg-color-3.mb-5
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-8.mb-3.mb-lg-0
            h2.mb-4(data-aos="flip-up") Factores socioeconómicos que impactan el ejercicio de sus derechos
            p.mb-4(data-aos="fade-right") Se invita a leer el documento Factores socioeconómicos que impactan el ejercicio de sus derechos, donde se aborda cómo diversas condiciones socioeconómicas, afectan el desarrollo integral y el ejercicio de los derechos de la primera infancia en Colombia. 
            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_1.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Factores socioeconómicos que impactan el ejercicio de sus derechos 
          .col-lg-4
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/temas/7.png', alt='')

    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/lc/tecnologicadeloriente/titulos/86355" target="_blank" rel="noopener noreferrer") Calvo Foxley, M. & Harrison, M. (Dir.). (2013). La muñeca del bosque: el proceso arte terapéutico con una niña víctima de vulneraciones de derecho grave. D - Universidad de Chile. 
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/lc/tecnologicadeloriente/titulos/69299" target="_blank" rel="noopener noreferrer") Quintero Mosquera, D. P. (2011). La salud como derecho: estudio comparado sobre grupos vulnerables. Siglo del Hombre Editores.               

            p.d-flex.my-4
              img.me-3(src='@/assets/template/book.svg' :style="{'max-width':'16px'}")
              a(href="https://www.unicef.org/colombia/informes/el-derecho-la-educacion?gad_source=1&amp;gclid=EAIaIQobChMIosmcgfyrjAMVMIFaBR00KDIpEAAYASAAEgK6dPD_BwE" target="_blank" rel="noopener noreferrer") Turbay Restrepo, C. (2000). El Derecho a la Educación. Desde el marco de la protección integral de los derechos de la niñez y de la política educativa. Unicef Colombia.                              


            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=HnksFN-IIkg" target="_blank" rel="noopener noreferrer") CAF -banco de desarrollo de Latam y el Caribe-. (2025). Webinar "El derecho a la salud de la niñez. Aportes desde las evidencias y las prácticas" 
            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=mZWjXyLoIZA" target="_blank" rel="noopener noreferrer") The Alliance. (2023). «El nuevo trabajo de Hannah» - Profesional de la protección de la niñez en entornos humanitarios.              

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({}),

  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
