<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Contexto de la organización y liderazgo
    
    .row.justify-content-center.align-items-center.mb-4
      .col-md-3.col-6.mb-md-0.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/tema2/img01.png')
      .col-md-9
        p Antes de iniciar en la temática vale la pena resaltar que los sistemas de gestión de continuidad del negocio permiten garantizar la ejecución de servicios que requiere la organización para cumplir con sus procesos misionales, brindando de esta forma un parte de tranquilidad a los socios y clientes de la misma, evitando además, pérdidas económicas y de imagen corporativa en un periodo de tiempo corto o de mediano plazo.
        .cajon.color-acento-contenido.p-4(data-aos="fade-left")
          p.mb-0 La empresa como gestora de procesos e implementadora de sistemas necesita mantener dentro de su entidad una alineación integral entre sus procesos de servicio, las necesidades de la organización, el alcance de sus planes y los objetivos misionales de la misma, contribuyendo a equipos de trabajo cohesionados, en donde el liderazgo y los roles que desempeña cada uno son aspectos primordiales.
    
    separador
    #t_2_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.1.	Necesidades del negocio 
    
    p Existen diferentes tipos de necesidades en una organización desde el enfoque de un SGCN. A continuación se desarrollan dichos aspectos.

    ImagenInfograficaB.color-terciario.mb-5
      template(v-slot:imagen)
        figure(data-aos="zoom-in")
          img(src='@/assets/curso/tema2/img02.svg')
      div(x="9%" y="68.5%" tooltip="Contexto de la organización")
        h5 Contexto de la organización
        p Tiene como objetivo ubicar a la empresa no solo en los aspectos de funcionamiento y jerarquía organizacional, sino también verificar que los procesos que esta lidera sean correspondientes a la realidad de la organización. Uno de los pilares de estos componentes es la meta o propósito misional de la organización donde se deben definir de manera clara cuál es el papel de la empresa dentro de su razón de ser, es decir, para qué se crea la compañía y cuál es su misión, lo que a su vez genera varios interrogantes, los cuales están enmarcados dentro de la siguiente pregunta: ¿qué requiere la organización para lograr dichos objetivos?.
        p Aquí también entra el diagnóstico para determinar cuáles son los recursos humanos, financieros, herramientas y servicios necesarios para lograr ese objetivo misional. Desde esta primera instancia se hace necesario que exista un compromiso sincero de la dirección de la organización, puesto que se deben calcular los montos de dichos recursos.
      div(x="35.5%" y="33.5%" tooltip="Liderazgo")
        h5 Liderazgo
        p Este componente se encuentra direccionado al compromiso que se debe asumir la dirección de la organización para velar y garantizar los recursos necesarios para la implementación y gestión del plan de continuidad del negocio. Se debe visualizar el proceso como una estrategia que permite generar mayor productividad y eficiencia en su ejecución. 
        p También es importante resaltar que uno de los factores que pueden generar el éxito o fracaso de un SGCN, aunque en la mayoría de ocasiones gana la necesidad del negocio, es que dichos procesos estén ajustados a los lineamientos misionales y operativos de la organización.
      div(x="32%" y="68.5%" tooltip="Planeación")
        h5 Planeación
        p En esta etapa se estipulan las actividades que se deben realizar para el cumplimiento de la implementación del SGCN. Es importante tener presente que todas estas actividades tienen un contexto de continuidad específica, de tal manera que cada una de estas garantice la ejecución de la otra, permitiendo que la gestión del proceso no se lleve a cabo de manera traumática tratando de encajar cada proceso dentro de otro de forma obligada, sino que fluyan de manera continua.
        p La planeación juega un papel fundamental en el éxito de un SGCN, ya que también permite establecer los actores del proceso que en realidad son las personas que se encargarán de implementar y mantener los planes de contingencia en cada escenario de riesgo potencial que se pueda presentar; aunque no es un secreto que en muchas ocasiones lo que se termina planeando puede llegar a ser modificado cuando se establezcan los costos y necesidades reales de la organización. 
        p Es necesario dejar por escrito en un informe lo que se plantea inicialmente, para luego realizar un diagnóstico y dar prioridad a aquellos componentes que tienen mayor peso y relevancia dentro del SGCN.
      div(x="58%" y="33.5%" tooltip="Soporte")
        h5 Soporte
        p Cualquier producto o servicio requiere de un proceso de asesoría, mantenimiento y, por supuesto, soporte, garantizando que se dé cumplimiento a lo planteado inicialmente por parte de quienes realizan la instalación o puesta en marcha del proceso. El soporte es fundamental para que se garantice un correcto funcionamiento de los procesos. Está ligado a muchos factores que de manera positiva aportan a la calidad y eficiencia en que se brindan los servicios en la organización. Un ejemplo sencillo que se puede traer a colación sería la compra de una nevera, hasta cierto punto, el fabricante puede elogiar el producto como uno de los mejores del mercado, se pueden tener todas las certificaciones para su producción y manufactura, lo cual está bien desde un principio al utilizar estándares o referentes internacionales; pero será el soporte el que garantizará que el producto durante un tiempo determinado pueda ser probado, evitando la pérdida de prestigio del mismo. Si el producto en particular sufre alguna avería o tiene un mal funcionamiento se puede garantizar que puede seguir siendo usado en un tiempo si se le brinda los procesos de mantenimiento y diagnósticos necesarios.
      div(x="53.5%" y="68.5%" tooltip="Operación")
        h5 Operación
        p El proceso de operación debe estar acompañado de una vigilancia estricta por parte del equipo ejecutor y de los responsables del mismo. Este aspecto implica que se realice un adecuado análisis del impacto en los riesgos que se puedan presentar, ya que la operación debe garantizar que todos los procesos que estarán respaldados por el SGCN generen la seguridad de poder resolver dichos riesgos de manera correcta y efectiva, aunque por otro lado se deben suscribir las estrategias y protocolos a tener en cuenta para dar respuesta a las amenazas que se puedan presentar a lo largo de la puesta en marcha del proceso de continuidad del negocio, sin dejar de lado las pruebas a realizar de manera periódica para garantizar que sí se están ejecutando de manera correcta los procesos.
      div(x="80.2%" y="33.5%" tooltip="Evaluación y desempeño")
        h5 Evaluación y desempeño
        p Una vez implementado el SGCN es indispensable que se realice un seguimiento para verificar el correcto funcionamiento del mismo, aunque en la mayoría de los casos se delegan personas o a un grupo, para realizar dicha tarea se debe tener en cuenta algunos de los siguientes aspectos a considerar para la ejecución correcta del proceso.
        ul.lista-ul
          li 
            i.lista-ul__vineta
            | Verificar si el SGCN está conectado con los objetivos y las metas de la organización, es decir, si este permite plenamente que no se generen interrupciones en los procesos de negocio y si en realidad está aportando a que esto se vea reflejado en un corto plazo.
          li 
            i.lista-ul__vineta
            | Realizar un diagnóstico para verificar el nivel de desempeño que ha tenido el SGCN y si las actividades que hacen parte del mismo se están ejecutando de manera satisfactoria.
          li 
            i.lista-ul__vineta
            | Comprobar que el SGCN está ajustado a la norma o referente internacional, es decir, que se esté ejecutando tal cual está establecido en la ISO 22301 y que todas sus actividades y procesos giren en torno a la misma, sin realizar cambios o acomodos a esta.
          li 
            i.lista-ul__vineta
            | Llevar un registro de cada evaluación realizada al SGCN para tener un histórico de las veces y momentos en los que se verificaron dichas actividades y, si es necesario realizar ajustes a la misma.
          li 
            i.lista-ul__vineta
            | Realizar un plan de auditoría para establecer las fechas y verificación de procesos que se someterán a verificación y emitir el informe respectivo con los cambios que requiere el sistema para operar de manera equilibrada y segura.
          p <span style="color:#000">Se pueden solicitar dos tipos diferentes de auditoría: interna o externa, dependiendo de la necesidad que se tenga en ese momento. Cada una de ellas entra a realizar una revisión mucho más al detalle de la operación de los procesos, en el que también se incluye una evaluación por parte de la dirección con el objetivo de verificar si se están cumpliendo los objetivos planteados en el SGCN. Se debe garantizar que esa inversión si esté generando los frutos esperados; aquí se confrontan los resultados operativos en medición de la inversión realizada para su implementación.</span>

      div(x="76.3%" y="68.5%" tooltip="Mejora continua")
        h5 Mejora continua
        p Los procesos de mejora continua están relacionados con garantizar que aquellas fallas o inconvenientes presentados se puedan corregir para evitar en un futuro que se repitan los mismos problemas o circunstancias que coloquen en riesgo los procesos de continuidad del negocio. Un ejemplo de ello podrían ser las amenazas en temas de seguridad de la información que puede recibir una organización, las cuales pueden repetirse o pueden evolucionar cambiando las reglas del juego de los procesos de negocio. En el caso de la mejora continua permite corregir dichos problemas y visualizar a futuro cuáles otros  derivados del mismo pueden ocurrir, es decir, realizar un análisis completo de nuevas amenazas o situaciones de riesgo que se puedan presentar.

    p Se puede decir, entonces, que las necesidades del negocio deben estar encaminadas a la mejora de los procesos de la organización. Los sistemas de gestión de la continuidad del negocio, como ente transformador de cambio organizacional, permite que todos los procesos del negocio estén respaldados; sin embargo, en la mayoría de los casos esto no es posible debido a los recursos con los que cuentan las empresas para la implementación de dichos planes; razón por la cual se hace necesario, antes que nada, el establecimiento de un diagnóstico que permita priorizar aquellos procesos que son de carácter crítico para el negocio y así, enfocarse de manera prioritaria en ellos.

    separador
    #t_2_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.2.	Definición del alcance de un SGCN
    
    p En este punto se debe comprender que un SGCN está determinado por la cantidad de procesos y necesidades que tenga la organización. Por tanto, se hace necesario, un estudio sobre cuáles son los puntos críticos, definir el alcance del sistema de gestión, en otras palabras, hasta dónde se ejecutará el SGCN y qué procesos están amparados bajo ese alcance. Vea lo que representa este alcance:
    
    


    .BG14.p-4.mb-4
      .row.justify-content-center.align-items-end.mb-4
        .col-md-4.col-8.mb-md-0.mb-4(data-aos="fade-right")
          img(src='@/assets/curso/tema2/img10.png')
        .col-md-8.mb-4
          .row.mb-4(data-aos="fade-left")
            .col-auto.BG16.p-2
              .h4.mb-0  Para ilustrar mejor este aspecto del alcance, vea el siguiente ejemplo:
          p Suponga una situación en la que se desea adquirir un producto en un lugar específico. Sin embargo, cuando ya se va a tomar la decisión se piensa inmediatamente en el presupuesto para no cometer un error en invertir más de lo que se tiene. Este mismo principio se aplica a los sistemas de gestión de la continuidad de un negocio. Se tienen múltiples procesos, pero se debe definir cuáles son los que requieren mayor atención para darles prioridad.
          .row.justify-content-center
            .col-md-5.col-10.tarjeta-avatar.mb-md-0.mb-4
              img(src='@/assets/curso/tema2/img11.png' alt='AvatarTop')
              .BGR17.p-4
                p.mt-4 Procesos que pueden generar caos
            .col-md-5.col-10.tarjeta-avatar
              img(src='@/assets/curso/tema2/img12.png' alt='AvatarTop')
              .BGR17.p-4
                p.mt-4 Procesos que se pueden prevenir
      p Regularmente, se toman aquellos procesos que su interrupción genera algún caos o coloca en riesgo la correcta ejecución de los procesos de la organización. También se consideran aquellos que dependiendo de su alcance y lo que se busque prevenir, el presupuesto, los recursos humanos y tecnológicos están cubiertos y por tanto, son factibles para ponerlos en marcha. Definir el alcance de manera correcta es indispensable para conocer las prioridades que se tienen dentro de la organización, en el que el estudio de presupuesto es la base para que las acciones a realizar estén conectadas con la realidad. 
      p #[strong El alcance, entonces, es la descripción de todos los procesos y acciones a priorizar, teniendo en cuenta sus recursos y limitaciones; información de entendimiento en común para todo el equipo empresarial].



    p Las necesidades del negocio se deben considerar como la oportunidad de poder potenciar aquellos procesos y servicios que son de vital importancia para el funcionamiento de la organización. Cualquiera que sea su actividad económica siempre se tendrá como factor decisivo qué se debe priorizar dentro de la organización. En la mayoría de los casos no se puede realizar una implementación completa de los procesos, por ello es necesario definir una serie de etapas que permitan ejecutar con mayor rapidez aquellos con prioridad alta y los que no requieran de una atención prioritaria serán aplazados en el cronograma de implementación, tal como se ilustra en el siguiente recurso.
  
    .row.justify-content-center.align-items-center.mb-4
      .col-md-9.order-md-1.order-2
        .BG05.p-4.mb-4(data-aos="fade-right")
          p.mb-0 Retomando el ejemplo anterior del supermercado, si este realizará un proceso de valoración de necesidades #[strong ¿escogería cambiar las actuales computadoras, suponiendo que sea necesario, o adquirir un respaldo eléctrico?]
        .cajon.color-secundario.p-4(data-aos="fade-right")
          p.mb-0 En este caso se le dará prioridad al respaldo eléctrico porque este sí puede ocasionar interrupciones en el negocio y esto acarrea pérdidas y caos en la imagen corporativa y en muchos otros factores. Siempre es necesario mirar cuál es la prioridad que estos representan en el negocio para ejecutarlos de acuerdo con esos criterios de evaluación.
      .col-md-3.col-6.mb-md-0.mb-4.order-md-2.order-1(data-aos="fade-left")
        img(src='@/assets/curso/tema2/img03.png')

    separador
    #t_2_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.3.	Liderazgo
    
    p Siempre se ha escuchado que las empresas requieren líderes y procesos que permitan llevar a cabo ciertos componentes dentro de las organizaciones; pero la mayoría de veces el enfoque que se utiliza para el liderazgo es más llevado a una cadena de mando en donde existen personas que generan la creación de los procesos y otros que los ejecutan.
    
    .row.justify-content-center.mb-4
      .col-md-10
        .bloque-texto-g.color-acento-botones.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema2/img04.jpg')})`}"
          )(data-aos="fade-right")
          .bloque-texto-g__texto.p-5
            p.mb-0 En realidad un buen proceso de liderazgo es aquel que involucra tanto a los administrativos como a la parte operacional de la organización, no existen culpables sino un equipo de trabajo que procura sacar los procesos adelante y tiene como objetivo principal la colaboración entre los miembros de la organización.

    p En un proceso de implementación de un SGCN se debe contar con un líder que permita gestionar todos los procesos esenciales de la misma, tener unas competencias y conocimientos específicos para este caso, para ello debe tener presente lo siguiente:

    .row.justify-content-center.align-items-center.mb-4
      .col-md-4.col-10.order-md-1.order-2
        .BG06.p-4.mb-4(data-aos="fade-right")
          p Tener un amplio conocimiento en los procesos administrativos.
        .BG07.p-4.mb-4(data-aos="fade-right")
          p Guiar de manera técnica y operativa el equipo de trabajo.
        .BG08.p-4.mb-4(data-aos="fade-right")
          p Saber liderar los procesos de implementación.
        .BG09.p-4.mb-4(data-aos="fade-right")
          p El líder debe tener competencias en las áreas afines a los temas de sistemas de información y seguridad informática.
      .col-md-5.col-10.order-md-2.order-1.mb-md-0.mb-4(data-aos="fade-left")
        img(src='@/assets/curso/tema2/img05.png')

    separador
    #t_2_4.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.4.	Roles y responsabilidades
    
    p Los roles y responsabilidades son aspectos a considerar al momento de diseñar e implementar un SGCN. Se deben crear diferentes equipos que realizarán la ejecución y velarán por el cumplimiento de las actividades que se reflejan en el sistema de continuidad; para ello es necesario nombrar representantes y personal que ejecute dichas actividades. Ahora, siendo un poco más específicos, es necesario considerar algunas habilidades que deben cumplir los miembros del equipo para realizar un trabajo adecuado en la implementación y ejecución de un SGCN, los cuales se presentan en el siguiente recurso:
  
    .row.justify-content-center.align-items-center.mb-4
      .col-md-4.col-8.BG10.p-4.mb-md-0.mb-4(data-aos="fade-right")
        .h4 Habilidades básicas 
        p Conocimientos y experiencia en el manejo de procesos que incluyan la continuidad del negocio, preferiblemente con certificación en la Norma ISO 22301.
        p Habilidades en la detección de problemas y solución de los mismos, preferiblemente teniendo en cuenta la normatividad y marco de referencia internacional.
        p Comunicación efectiva y liderazgo para realizar el trabajo en equipo.
        p Manejo y gestión de proyectos y manejo de presupuestos.  
      .col-md-4.col-8.mb-md-0.mb-4(data-aos="zoom-in")
        img(src='@/assets/curso/tema2/img06.png')
      .col-md-4.col-8.BG11.p-4.mb-md-0.mb-4(data-aos="fade-left")
        .h4 Habilidades específicas
        p Habilidad para el BIA, que por sus siglas significa análisis de impacto del negocio.
        p Desarrollar planes para implementar planes BCM, que por sus siglas significa administración de la continuidad del negocio.
        p Diseño y desarrollo de escenarios de prueba para la verificación de los planes de continuidad del negocio.
        p Habilidades y conocimientos de procesos empresariales para presentar y lograr negociaciones y comprometer a la alta dirección en los procesos de continuidad del negocio.


    .BG12.p-4.mb-4(data-aos="fade-right")
      p.mb-0 En algunas ocasiones es necesario crear grupos y comités de dirección para que estos realicen asesorías, guías y supervisión de los procesos. Crear equipos de trabajo con el propósito estratégico de resolver los incidentes que se puedan presentar y contribuir a dar soluciones concretas en los tiempos asignados en el SGCN.

    .row.justify-content-center.align-items-center.mb-4
      .col-md-3.col-6.mb-md-0.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/tema2/img07.png')
      .col-md-7.col-11.mb-md-0.mb-4
        .cajon-b.color-primario.p-3
          p Todo esto requiere de una coordinación adecuada y compromiso de todas las partes involucradas. Es necesario en gran manera que la alta dirección comprenda la importancia de estos procesos para la organización, puesto que son los que se encuentran de manera visible y  quienes pueden garantizar que el compromiso que se adquiere en la planeación, diseño e implementación de un SGCN sea responsabilidad de todos en la empresa. Asimismo, se deben comprometer en estar cuando se requiera para garantizar que la empresa no tenga interrupciones porque en caso de ser así también se vería perjudicado todo el personal en general.
          p.mb-0 Ahora bien, para que lo anterior también se dé en las mejores condiciones se hace necesario poder comprender a cabalidad lo que se entiende como roles y responsabilidades en un SGCN; la siguiente lo explica de manera específica:

    .row.justify-content-center.align-items-center.mb-4
      .col-md-4.col-8.mb-md-0.mb-4(data-aos="fade-right")
        figure.mb-4
          img(src='@/assets/curso/tema2/img08.svg')
        .BG03.p-4
          p.mb-0 Son funciones asignadas de acuerdo con las competencias que tiene cada miembro del equipo.
      .col-md-4.col-8.mb-md-0.mb-4(data-aos="fade-left")
        figure.mb-4
          img(src='@/assets/curso/tema2/img09.svg')
        .BG03.p-4
          p.mb-0 Son aquellos compromisos asignados al momento que asume el rol dentro del equipo de trabajo.

    .row.justify-content-center.mb-4(data-aos="fade-right")
      .col-md-10.cajon.color-secundario.p-4
        p #[strong Las responsabilidades existen en dos ámbitos en un SGCN]: responsabilidades individuales y grupales.
        p Aunque todo en un sistema de SGCN está ligado de manera integrada, es responsabilidad de cada miembro cumplir con las funciones que se requieren; sin embargo, al estar ligado en un sistema de gestión, los procesos que no ejecuten algunos miembros del equipo recaerán de manera directa en los objetivos del equipo en general. Es por eso que el equipo debe asumir, de manera integrada, la responsabilidad conjunta para que se cumplan los objetivos.
        p.mb-0 Si un miembro del equipo está teniendo dificultad en cumplir el objetivo por cualquier motivo los demás miembros deben prestar ayuda para que este pueda ser implementado de manera adecuada. Siempre debe primar el objetivo común y no el individual.




    


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
