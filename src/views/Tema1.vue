<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 ¿Qué es un SGCN?
    
    p Un sistema de gestión de continuidad del negocio (como indican sus siglas SGCN) es una potente herramienta que permite a las empresas controlar de manera continua los riesgos presentados y que pueden, en algún momento, proveerse de toda la capacidad tecnológica y humana necesaria para poderlos solucionar en el menor tiempo posible; por tanto, en pocas palabras se podría decir que los sistemas de gestión de continuidad del negocio son una herramienta estratégica necesaria para las empresas hoy en día.

    .row.justify-content-center.mb-4
      .col-md-8
        .bloque-texto-g.color-acento-contenido.item-right.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema1/img01.png')})`}"
          )(data-aos="fade-left")
          .bloque-texto-g__texto.p-4
            p.mb-0 Los negocios del Siglo XXI son, en gran manera, dependientes de la tecnología. Muchos de sus procesos dependen en gran parte del buen uso y funcionamiento de la misma.

    p Muchas empresas invierten grandes sumas de dinero en la implementación de infraestructuras y sistemas avanzados que permitan ejecutar sus procesos de negocio; pero no se sientan a estudiar la posibilidad de que esta, por diferentes motivos, pueda llegar a colapsar en algún momento; y aunque existen muchas razones y riesgos que pueden ocurrir, no se trata solo de conocer dichos riesgos sino de estar en la capacidad de recuperar el sistema y por ende, los procesos de negocio, sin que estos causen trauma a tal punto que la empresa se pueda ver perjudicada por dichos sucesos. De ahí la relevancia de la implementación de un SGCN, tal como se describe en el siguiente recurso:     

    .row.justify-content-center.mb-5
      .col-md-3.col-6.mb-md-0.mb-4(data-aos="fade-right")
        .tarjeta--boton.color-primario.p-4
          .row.justify-content-center.mb-3
            .col-md-6.col-8
              img(src='@/assets/curso/tema1/img02.png')
          p.my-5.mb-5 Detectar fallas en los sistemas actuales de la organización.
      .col-md-3.col-6.mb-md-0.mb-4(data-aos="zoom-in")
        .tarjeta--boton.color-primario.p-4
          .row.justify-content-center.mb-3
            .col-md-6.col-8
              img(src='@/assets/curso/tema1/img03.png')
          p.my-5.mb-3 Detectar nuevas amenazas que se puedan presentar en un futuro cercano.
      .col-md-3.col-6.mb-md-0.mb-4(data-aos="zoom-in")
        .tarjeta--boton.color-primario.p-4
          .row.justify-content-center.mb-3
            .col-md-6.col-8
              img(src='@/assets/curso/tema1/img04.png')
          p.my-4.mb-3 Identificar los procesos críticos del negocio, que suelen ser procesos clave para la operación del mismo.
      .col-md-3.col-6.mb-md-0.mb-4(data-aos="fade-left")
        .tarjeta--boton.color-primario.p-4
          .row.justify-content-center.mb-3
            .col-md-6.col-8
              img(src='@/assets/curso/tema1/img05.png')
          p.my-5.mb-3 Crear los mecanismos de respuesta en caso de ocurrir algún incidente.

    p.mb-5 Los procesos de un SGCN permiten aumentar la productividad en las organizaciones debido a la calidad que ofrecen dichos servicios al estar soportados por procesos que garanticen su efectividad y su estabilidad. Las organizaciones del Siglo XXI han comprendido que el mayor desafío que se tiene en los procesos de negocio es garantizar la confianza tanto de inversores como de clientes que estas tienen. Cuando una organización no puede garantizar un servicio o producto se vuelve inestable en los procesos empresariales; esto quiere decir que parte del éxito que pueda tener la organización es la manera en cómo maneja sus procesos de negocio. A continuación se presenta un ejemplo con una entidad bancaria:

    .tarjeta.color-acento-botones.p-4.mb-4(data-aos="zoom-in")
      SlyderA(tipo="b")
        .row.justify-content-center
          .col-md-5.order-md-1.order-2
            p Para una entidad bancaria es de vital importancia los sistemas de información, ya que estos acercan al negocio con las necesidades de los clientes y, permiten que sus procesos funcionen. 
          .col-md-5.col-10.order-md-2.order-1.mb-4.mb-md-0
            img(src='@/assets/curso/tema1/img06.png')
        .row.justify-content-center
          .col-md-5.order-md-1.order-2
            p Si estos servicios se ven interrumpidos por algún agente, externo o interno afectará en la producción de la organización. Si este incidente se vuelve repetitivo, la presión en el cliente será tal que cambiará de servicio o producto ofrecido y si llegase a afectar todo un día completo en recuperarse el sistema,  no solo sería muy mal visto por los clientes sino por los mismos inversionistas, trayendo implicaciones negativas al negocio.
          .col-md-5.col-10.order-md-2.order-1.mb-4.mb-md-0
            img(src='@/assets/curso/tema1/img07.png')
        .row.justify-content-center
          .col-md-5.order-md-1.order-2
            p Por esta razón, las entidades o negocios deben desarrollar estrategias que garanticen el correcto funcionamiento de los procesos y que estos se mantengan operables en el tiempo.
          .col-md-5.col-10.order-md-2.order-1.mb-4.mb-md-0
            img(src='@/assets/curso/tema1/img08.png')
        .row.justify-content-center
          .col-md-5.order-md-1.order-2
            p Adicional a ello, se debe garantizar que una vez suceda un incidente, la recuperación de estos servicios sea de tal forma que los tiempos se acorten y que la estabilidad del mismo servicio sea inmediata para los clientes.
          .col-md-5.col-10.order-md-2.order-1.mb-4.mb-md-0
            img(src='@/assets/curso/tema1/img09.png')

    p.mb-4 Otro ejemplo que se puede tener en cuenta son los servicios de las redes sociales:
    br
    .BG01.mb-5.my-5(data-aos="zoom-in")
      .row.justify-content-center
        .col-md-8.BG02.img01.p-4
          SlyderA(tipo="b")
            .row.justify-content-center
              .col-md-10.mb-4
                img(src='@/assets/curso/tema1/img10.png')
              .col-md-10
                p Las redes sociales hoy no solo prestan los servicios de comunicación, sino también de publicidad y operaciones de comercio electrónico.
            .row.justify-content-center
              .col-md-10.mb-4
                img(src='@/assets/curso/tema1/img11.png')
              .col-md-10
                p Si una empresa tiene sus productos y servicios ofertados en dichas plataformas y estas llegan a quedar inoperables…
            .row.justify-content-center
              .col-md-10.mb-4
                img(src='@/assets/curso/tema1/img12.png')
              .col-md-10
                p Se perjudican los procesos de negocio de esa empresa porque sus clientes van a preferir comprar en otro lugar y su imagen corporativa se verá afectada.
            .row.justify-content-center
              .col-md-10.mb-4
                img(src='@/assets/curso/tema1/img13.png')
              .col-md-10
                p Esto en muchas ocasiones genera no solo desconfianza sino pérdidas en los mercados y clientes en general.
    <br><br>
    p Existen muchas controversias en la implementación de los SGCN debido a la inversión que en muchas ocasiones se debe realizar para que estos funcionen de manera correcta, junto con la contratación de personal calificado que garantice que estos se ejecuten de manera correcta y eficiente; sin embargo, en la mayoría de ocasiones no se tiene en cuenta contar con un respaldo para el negocio que garantice que este se mantenga operable en el tiempo.

    .row.justify-content-center.mb-4
      .col-md-10
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema1/img14.png')})`}"
          )(data-aos="fade-right")
          .bloque-texto-g__texto.p-5
            p.mb-0 La implementación de un SGCN también se puede mirar como un proceso que genera prestigio a la organización, ya que se está garantizando el funcionamiento y continuidad de los procesos y servicios de negocio, hasta cuando este tenga inconvenientes internos, manteniendo la misma calidad y eficacia.

    p La sucursal de un supermercado, por ejemplo, en su área energética es otro caso que se puede estudiar y lo que puede ver a continuación:

    .BG14.p-4.mb-4
      .row.justify-content-center.align-items-end.mb-4
        .col-md-5.col-10.mb-md-0.mb-4(data-aos="fade-right")
          img(src='@/assets/curso/tema1/img45.png')
        .col-md-7.mb-4
          .BG15.p-4.mb-4(data-aos="fade-left")
            .h4 La sucursal de un supermercado no cuenta con un respaldo energético, como una planta de energía o UPS,  que permita mantener los equipos encendidos: neveras, dispositivos de seguridad, la red vigente y los sistemas de información para funcionar en el manejo de inventarios, pedidos, facturación, entre otros procesos internos.
          p La energía eléctrica, entonces, es uno de los recursos que permite que el negocio funcione. Si esta se va, el negocio no podría funcionar. En la implementación del SGCN, entonces, se debe priorizar como riesgo que deja inoperable el negocio, el fluido eléctrico, y por tal razón, se deben hacer todos los esfuerzos para ejecutar un plan de contingencia, el cual podría ser contar con un respaldo eléctrico para que el negocio siga produciendo y funcionando, a pesar de que se carece del servicio de energía eléctrica normal.
          p.mb-0 Este caso evidencia la importancia de garantizar los servicios de una empresa. Pues si este no se toma en serio y dicha situación se vuelve repetitiva, los clientes, muy seguramente, optarán por comprar en otro lugar o dejar de ir al negocio, ya que este no garantiza su funcionamiento. 
        .col-12
          .h4.mt-4 Este ejemplo es muy común en una gran parte de las empresas donde no se realiza un debido análisis del riesgo funcional del negocio para conocer cuáles son los factores de riesgo que pueden generar interrupción en sus procesos empresariales y de esta manera, diseñar planes de contingencia que garanticen su operatividad a pesar de las circunstancias que se presenten.

    .row.justify-content-center.align-items-center.mb-4
      .col-md-7.col-10.order-md-1.order-2
        .cajon-b.color-acento-contenido.p-3
          p.mb-0 Los SGCN cumplen un papel fundamental en las decisiones que se toman dentro del negocio. De hecho, son parte de la coalición administrativa de la organización; es decir, la información que estos sistemas generan permiten conocer el impacto que se puede tener en el negocio de acuerdo con los riesgos establecidos en el análisis del riesgo. Es importante tener en cuenta que los riesgos se establecen de acuerdo con los estudios y auditorías que revelen el estado actual del sistema y qué aspectos se pueden mejorar para evitar que ciertos procesos que colocan en riesgo el correcto funcionamiento del negocio se ejecuten o se pongan en marcha. Dentro de las funciones que tiene el equipo de trabajo que garantiza la continuidad del negocio se encuentran las siguientes.
      .col-md-3.col-6.order-md-2.order-1.mb-md-0.mb-4(data-aos="fade-left")
        img(src='@/assets/curso/tema1/img15.png')

    .row.justify-content-center.align-items-center.mb-4
      .col-md-6.col-10.mb-md-0.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/tema1/img16.png')
      .col-md-6.col-10
        .tarjeta.color-acento-botones.p-4.mb-4
          SlyderA(tipo="b")
            .row.justify-content-center
              .col-11
                p #[strong 01.] Velar porque los planes sean probados constantemente a través de simulaciones de situaciones reales, creando escenarios con los posibles riesgos analizados, los tiempos de reacción y de recuperación del negocio. En dichas situaciones y si estas están conforme a lo estipulado, se comparan los resultados obtenidos para medir si el plan es funcional y si se podría ejecutar sin ningún inconveniente.
            .row.justify-content-center
              .col-11
                p #[strong 02.] Crear escenarios ajustados a la realidad del proceso a analizar para conocer la existencia de fallas o problemas al momento de colocar en marcha el plan de continuidad.
            .row.justify-content-center
              .col-11
                p #[strong 03.] Examinar al equipo de reacción y cómo este soluciona los problemas presentados, rigiéndose por la normatividad y procesos que se requieren en el plan de continuidad. Todo el equipo debe estar en función de los procesos a desarrollar de acuerdo con las actividades que cada uno de ellos debe realizar, siendo esta su responsabilidad individual y grupal.
            .row.justify-content-center
              .col-11
                p #[strong 04.] Se mide el compromiso del equipo con el proceso.
            .row.justify-content-center
              .col-11
                p #[strong 05.] Se analiza cómo el equipo articula las actividades para lograr el objetivo común, que es recuperar los procesos de negocio de la organización lo más pronto posible y de manera eficiente.
    
    p Aunque es de gran importancia que una organización implemente un SGCN, no es una camisa de fuerza que tiene que cumplir para funcionar a diario. Se ven diariamente muchos negocios y empresas que funcionan de manera ajena a los riesgos del mismo negocio; sin embargo, las preguntas que siempre surgen alrededor de estos inconvenientes son: ¿conocen los riesgos que tiene el negocio?, ¿cuáles son los niveles de impacto que pueden tener los incidentes que ocurran en el negocio?, ¿cuánto tiempo máximo puede estar por fuera de operación mi negocio?, ¿qué opinión tienen de los servicios que ofrezco a mis clientes cuando surge algún problema en el negocio? Estos interrogantes son inquietudes o dudas que de alguna manera generan zozobra en algunos negocios; pero las personas que los dirigen no ven la importancia o necesidad de realizar un verdadero análisis que permita establecer y garantizar que el negocio funcione.

    .row.justify-content-center.cajon.color-primario.p-4.mb-4
      .col-md-2.col-4.mb-md-0.mb-4(data-aos="fade-right")
        .row.justify-content-center
          .col-md-10
            img(src='@/assets/curso/tema1/img17.png')
      .col-md-10.col-11
        p.mb-0 Por tanto, no es obligatorio que una organización implemente un SGCN; pero sí es necesario para ser competitivos, eficientes y confiables, ya que se puede garantizar la continuidad de los procesos misionales de una organización. La implementación de un plan de continuidad al negocio trae consigo muchos aspectos positivos que valen la pena analizar y tener en cuenta. Hoy en día las empresas e industrias se han vuelto más competitivas y esto hace que sea necesario el invertir en maquinaria, personas y servicios para lograr mantenerse en los mercados actuales, sin dejar de lado, por supuesto, la calidad y eficiencia en la que se prestan los servicios, los cuales a su vez se fundamentan en las políticas, procesos y estrategias estipuladas por la empresa.      

    separador
    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.1.	Procesos que componen un SGCN
    
    p Son de alguna manera estrategias que permiten establecer un lineamiento seguro y coherente para todas las actividades, que resultan necesarias para que el sistema tenga éxito, en todo el sentido de la palabra. Los componentes deben estar directamente relacionados para que cada uno de ellos pueda desarrollarse de manera plena y así se puedan lograr los objetivos establecidos en la ejecución del mismo. A continuación se describe cada uno de los procesos que componen dicho sistema de gestión:

    TabsA.color-acento-contenido.mb-5(data-aos="zoom-in")
      .tarjeta.color-acento-contenido--borde.p-4(titulo="Planificación de las actividades")
        h4 Planificación de las actividades
        p En este proceso se realiza una exploración inicial de lo que debe contener el sistema de gestión, teniendo en cuenta los procesos que abarca, de acuerdo con las actividades a desarrollar, es decir, se deben establecer todas las actividades que se desarrollarán en el transcurso de la ejecución del SGCN; este paso es fundamental, una vez definido el plan de gestión es complicado realizar modificaciones en el mismo.
        figure
          img(src='@/assets/curso/tema1/img18.jpg')
      .tarjeta.color-acento-contenido--borde.p-4(titulo="Análisis inicial")
        h4 Análisis inicial
        p Al referirse al análisis inicial se está hablando del primer estudio de exploración de las necesidades que puedan surgir en el SGCN. Aquí se realiza una búsqueda de los procesos que demandará el sistema de gestión una vez se encuentre en marcha o listo para ser implementado.  En este paso hay que se muy puntuales en qué es lo que requiere atención primordial y en cuáles de los aspectos de las necesidades del negocio se hará mayor énfasis.  
        p De igual forma, es fundamental en este punto comprometer al equipo de trabajo desde un principio para que cada miembro, de acuerdo con su experiencia y conocimiento, asuma el liderazgo del proceso de manera voluntaria, ya que es responsabilidad de cada uno de ellos hacer que el sistema de gestión funcione de la mejor manera posible.
        figure
          img(src='@/assets/curso/tema1/img19.jpg')
      .tarjeta.color-acento-contenido--borde.p-4(titulo="Evaluación y control de los riesgos")
        h4 Evaluación y control de los riesgos
        p Teniendo en cuenta que la infraestructura de una organización puede recibir diferentes tipos de ataques informáticos que atentan contra su correcto funcionamiento es indispensable dentro de los procesos de un SGCN realizar una constante verificación, categorización y evaluación del riesgo, de acuerdo con el impacto y caos que puedan generar en el negocio. Se denotan de la siguiente manera: riesgo bajo, medio y alto.
        figure
          img(src='@/assets/curso/tema1/img20.jpg')
      .tarjeta.color-acento-contenido--borde.p-4(titulo="Evaluación y control de los riesgos: riesgo bajo")
        h4 Evaluación y control de los riesgos: riesgo bajo
        p Es un riesgo controlable tanto en el tiempo como en el impacto que ocasiona en el negocio (aunque todos los riesgos son para tener en cuenta, ya que dependiendo de su impacto pueden ocasionar retrasos o ejecución correcta de algunos procesos de negocio). No se considera una amenaza que atente contra la integridad del negocio y, su tratamiento y control son muy sencillos. 
        p Por ejemplo, el daño de una impresora o un equipo averiado, estos riesgos se pueden subsanar reemplazando de manera sencilla los dispositivos que afectan el proceso o comparte los recursos con otra división de la empresa, por eso se consideran de bajo impacto.
        figure
          img(src='@/assets/curso/tema1/img21.jpg')
      .tarjeta.color-acento-contenido--borde.p-4(titulo="Evaluación y control de los riesgos: riesgo medio")
        h4 Evaluación y control de los riesgos: riesgo medio
        p Se suelen considerar intermedios porque aunque son riesgos de una mayor escala de valoración se pueden subsanar. Adicional a ello, cabe mencionar que estos riesgos sí causan que el negocio deje de funcionar, es decir, quitan operatividad al negocio; sin embargo, con un buen equipo de respuesta y teniendo las herramientas adecuadas se pueden subsanar fácilmente. Este tipo de riesgos, por lo general, suceden  porque el problema no se solventó a tiempo, adhiriéndose a otros riesgos de la misma escala de valoración, ocasionando un conjunto de riesgo mayor. 
        p Un ejemplo de ello podría ser la interrupción de la conectividad, un daño considerable al sistema electrónico, fallas del sistema de respaldo de energía, ataques informáticos con virus y que este sea producto de una mala política de manejo de la información. Al sumarse algunos de ellos, pueden ocasionar que en algún momento colapse la organización.
      .tarjeta.color-acento-contenido--borde.p-4(titulo="Evaluación y control de los riesgos: riesgo alto")
        h4 Evaluación y control de los riesgos: riesgo alto
        p Es considerada la mayor amenaza de una organización, puesto que está desarrollado por un proceso continuo de riesgos mal controlados y problemas con la política de uso de la información e infraestructura de la organización. Este tipo de riesgo se suele presentar de manera interna, principalmente por empleados que no cumplen con los protocolos o procedimientos que establece la organización para evitar que estos sucesos ocurran.
        p Un ejemplo particular de ello son los empleados que usan memorias USB o dispositivos que pueden ocasionar infección por virus y que pueden borrar datos e información importante de los procesos de negocio de la organización, los empleados que realizan un daño a la infraestructura física de la organización como, por ejemplo, cableado, servidores y sistemas de almacenamiento que por un mal entendimiento con sus jefes o personal, que ya no labora en la organización y que no se les ha dado de baja las credenciales de acceso, son personas que pueden ocasionar daños irreparables en la infraestructura. Son riesgos bastante considerables y son impredecibles, ya que no son visibles o considerados de manera urgente.
      .tarjeta.color-acento-contenido--borde.p-4(titulo="Análisis de impacto del negocio (BIA)")
        h4 Análisis de impacto del negocio (BIA)
        p El proceso de verificación del impacto ocasionado por una situación de riesgo se debe medir de acuerdo con la escala de valoración antes vista. En este proceso se trata de determinar, de acuerdo con el nivel de riesgo, cuál sería el impacto que este podría ocasionar en la organización, por ejemplo, no es lo mismo una computadora infectada con virus que la quema masiva de 10 computadoras por una mala instalación eléctrica realizada en la organización. En ese sentido, el análisis de impacto trata de considerar los riesgos, qué tanto daño pueden ocasionar en el negocio y de esta manera establecer acciones que permitan no solo mitigar los sucesos, sino también crear planes de contingencia para recuperar el negocio una vez suceda el incidente.
        p El análisis de impacto del negocio debe realizarse teniendo en cuenta las consideraciones de los riesgos presentados, ya que en algunas ocasiones se puede cometer el error de considerar el impacto del riesgo con datos estadísticos que pueden ser no actuales, generando falsos riesgos y soluciones no pertinentes.  
        p Siempre se considera una buena práctica realizar un análisis de manera constante para tener información actualizada de la situación del negocio.
      .tarjeta.color-acento-contenido--borde.p-4(titulo="Desarrollo de estrategias para la continuidad del negocio")
        h4 Desarrollo de estrategias para la continuidad del negocio
        p Se puede definir estrategia como la forma en la cual se ejecutan acciones y procesos para tratar problemas presentados y aquellos que se puedan presentar a futuro. Es importante considerar que las estrategias deben estar encaminadas a la detección y solución de los riesgos, y alineadas a los procesos misionales de la organización, es decir, no pueden estar aisladas de lo que la organización quiere lograr o quiere representar en su imagen corporativa.
        p Asimismo, debe satisfacer las necesidades tecnológicas y de negocio de la organización. Un ejemplo de ello podría ser la estrategia para mantener la conectividad y procesos de negocio siempre operables. 
        p Los procesos de negocio de un banco, por ejemplo, dependen 100% de la tecnología. Se podría considerar que la tecnología es un factor importante para que funcione el negocio y que si esta deja de operar o funcionar de manera correcta, el negocio se verá afectado en gran medida, entonces, una estrategia de continuidad es mirar cuáles son los puntos débiles o posibles riesgos que se puedan presentar con este servicio, que es de vital importancia para el negocio, y fortalecerlo implementando estrategias para mantenerlo operable como un sistema de respaldo energético, la instalación de dispositivos de protección de la información como firewalls, IPS e IDS, que alerten en el caso de que suceda alguna instrucción en la infraestructura de la organización, entre otros, y en caso de que esto suceda recuperarla en el menor tiempo posible.
      .tarjeta.color-acento-contenido--borde.p-4(titulo="Respuesta ante emergencias")
        h4 Respuesta ante emergencias
        p Las respuestas a incidentes se pueden comprender como la estimación de tiempos de acuerdo con los procesos que se llevan a cabo en la recuperación del sistema, es decir, de acuerdo con la planeación y ejecución del plan de contingencia, cuánto tiempo se toma el proceso en restablecer el sistema. Es muy importante tener en cuenta que todo este tiempo, la mayoría de veces, tiende a ser relativo porque depende de muchos factores que lo acompañan como experiencia del personal o equipo de trabajo, la tecnología implementada y el BIA o impacto que tuvo el incidente en el negocio. Ahora bien,  lo que sí se debe garantizar es que en ese rango de tiempo se recupere la operatividad del negocio de una manera óptima y efectiva.
        p Se comprende como emergencia a toda situación en la cual se coloca en riesgo la integridad y correcto funcionamiento de los procesos de negocio de la organización. Se debe considerar que los riesgos establecidos pueden generar diferentes protocolos de activación de las respuestas, pues no es lo mismo un proceso de recuperación para un riesgo bajo que para un proceso de riesgo alto. Los tiempos de respuesta y recuperación estarán sujetos a la complejidad que se puede tener en dicho proceso de recuperación.

    separador
    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.2.	La Norma ISO 22301

    p Es una norma internacional que provee los lineamientos y procedimientos para la gestión de continuidad del negocio. Esta norma define todos los procesos a realizar, desde la definición del alcance hasta la implementación del plan y puesta en marcha del mismo. Asimismo, establece cómo administrar, gestionar y garantizar que la recuperación del negocio se realice de la manera adecuada; pues, en algunas ocasiones, se implementan estos procesos pero no son regidos del todo por la normatividad, lo cual es un error, ya que al ser estándares internacionales garantiza que el proceso sea el mismo, independientemente de la ubicación y procesos de negocio de la organización, de esta manera se garantiza la calidad, definición y ejecución de los planes de contingencia con un referente internacional.

    .row.justify-content-center.mb-4
      .col-md-10
        .bloque-texto-g.color-acento-botones.item-right.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema1/img22.jpg')})`}"
          )(data-aos="fade-left")
          .bloque-texto-g__texto.p-4
            p.mb-0 La implementación de la Norma ISO como referente internacional permite desarrollar y fortalecer ejercicios de buenas prácticas que contribuyen a la competitividad, al prestigio de la marca y a la productividad de las organizaciones. La certificación en esta norma permite tener un respaldo tanto a nivel nacional como internacional, ofreciendo ventajas en otras actividades externas como lo son: licitaciones, contratos y vinculación a los mercados internacionales, por ejemplo, trayendo consigo nuevas oportunidades de negocio a la empresa.   

    p En el siguiente interactivo se pueden apreciar los procesos que acompañan la ejecución de la norma ISO 22301:

    .botones-hover.my-5
      Botones(data-aos="fade-right")
    
    p Teniendo en cuenta que las eventualidades que colocan en riesgo los procesos de negocio cambian constantemente, es importante que el proceso de mejora continua contemple la necesidad de darle prioridad a la implementación de los SGCN, ya que esto no es algo que se realiza una vez, sino que hace parte de un proceso continuo que puede cambiar en el tiempo, tal como lo presenta el siguiente recurso:

    .row.justify-content-center.mb-4
      .col-md-3.col-6.mb-md-0.mb-4(data-aos="fade-right")
        figure.mb-4
          img(src='@/assets/curso/tema1/img24.svg')
        p Las amenazas de virus informáticos todos los días van cambiando.
      .col-md-3.col-6.mb-md-0.mb-4(data-aos="zoom-in")
        figure.mb-4
          img(src='@/assets/curso/tema1/img25.svg')
        p Por tanto, surgen nuevos tipos de ataques y virus.
      .col-md-3.col-6.mb-md-0.mb-4(data-aos="zoom-in")
        figure.mb-4
          img(src='@/assets/curso/tema1/img26.svg')
        p Esto trae consigo que las empresas que regulan y crean las protecciones para este tipo de virus estén constantemente desarrollando soluciones. 
      .col-md-3.col-6(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema1/img27.svg')
        p Esta situación aplica para los procesos de negocio, los cuales deben estar constantemente verificando sus procesos y riesgos para mejorarlos y prevenirlos cada día.
 
    separador
    #t_1_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.3.	Propósito de la Norma ISO 22301
    
    p Como se abordó en anteriores conceptos, esta norma permite establecer un plan de seguimiento a los procesos después de realizar un análisis del riesgo donde se visualicen los diferentes escenarios que se pueden presentar. Por tanto, se debe entender que uno de los objetivos principales de la continuidad del negocio es garantizar la estabilidad de sus procesos y generar confianza en la inversión del mismo, tanto para clientes como para la misma empresa en sí. Dentro de estos objetivos también se deben abordar algunas premisas importantes a tener en cuenta, tales como:

    .row.justify-content-center.mb-4
      .col-md-10.mb-md-0.mb-4
        figure(data-aos="zoom-in")
          img(src='@/assets/curso/tema1/img28.svg')
      .col-md-10
        .BG03.p-4(data-aos="fade-right")
          p.mb-0 Gracias a la implementación de esta norma las organizaciones pueden ejecutar los procesos misionales de manera plena, garantizando que estos no tendrán interrupciones en el transcurso de los tiempos establecidos para prestar dichos servicios.

    p Ahora bien, en cuanto a los propósitos de la norma se encuentran los siguientes:

    .row.justify-content-center
      .col-md-10(data-aos="zoom-in")
        img(src='@/assets/curso/tema1/img29.svg')
      .col-md-8.img02.mb-md-0.mb-4
        SlyderF(columnas="col-12")
          .row.justify-content-center.BG03.p-4
            .col-11
              p.mb-0 #[strong 01.] Mejorar la interacción de los equipos de trabajo involucrados en el aseguramiento de dichos procesos, afectando de forma positiva la manera en cómo se visualiza el negocio, tanto para los clientes como para los inversionistas y público en general. 
          .row.justify-content-center.BG03.p-4
            .col-11
              p.mb-0 #[strong 02.] Contar con unas expectativas claras y acertadas sobre cómo se debe realizar el direccionamiento de los procesos estratégicos de la organización. 
          .row.justify-content-center.BG03.p-4
            .col-11
              p.mb-0 #[strong 03.] Garantizar que los objetivos misionales de la organización sean claros para todos los grupos de interés y así garantizar la continuidad del negocio.
          .row.justify-content-center.BG03.p-4
            .col-11
              p.mb-0 #[strong 04.] Diagnosticar de manera adecuada el correcto funcionamiento y gestión de los procesos del negocio.
          .row.justify-content-center.BG03.p-4
            .col-11
              p.mb-0 #[strong 05.] Ser más productivos. Al existir menores interrupciones en los procesos de negocio y contar con un sistema de respaldo que garantice la recuperación del negocio en tiempos razonables la empresa podrá funcionar sin inconvenientes, generando mayor flujo de trabajo y calidad en los servicios y/o productos ofrecidos y garantizando la competitividad. 
          .row.justify-content-center.BG03.p-4
            .col-11
              p.mb-0 #[strong 06.] Realizar procesos de autoevaluación para garantizar los procesos que se encuentran inmersos en el plan de gestión.
          .row.justify-content-center.BG03.p-4
            .col-11
              p.mb-0 #[strong 07.] Fortalecer la interacción de todos los entes que hacen parte del proceso, desde la directiva principal de la organización hasta los involucrados de manera aislada, tales como contratistas o empresas prestadoras de servicio, siempre y cuando se encuentren involucrados en los procesos que tienen que ver con la continuidad del negocio.

    .row.justify-content-center.align-items-center.cajon.color-secundario.p-4.mb-4
      .col-md-2.col-4.mb-md-0.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/tema1/img30.svg')
      .col-md-10
        p.mb-0 Cuando se hace referencia al equilibrio de los procesos se está hablando del punto intermedio en donde todas las partes involucradas en la gestión de la continuidad se juntan y generan nuevos procesos que permiten observar un flujo continuo de mejora, lo que se ve reflejado en la productividad y competitividad del negocio. Lograr este equilibrio no es fácil, ya que requiere de inversión tanto de talento humano como tecnológico; pero es posible encontrar puntos de equilibrio donde cada proceso involucrado en el sistema de gestión de la continuidad aporten de manera equilibrada y efectiva.
    
    .row.justify-content-center.align-items-center.mb-5
      .col-md-3.col-6.mb-md-0.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/tema1/img31.png')
      .col-md-9.col-11
        p De acuerdo con las políticas implementadas en la organización un SGCN busca garantizar de manera fluida que los recursos que se requieran adquieran y encuentren en óptimas condiciones para dar cumplimiento a los procesos que se desean respaldar. Por lo tanto, se hace indispensable realizar un análisis de necesidades para establecer qué se requiere para la implementación del sistema de gestión, no solo a nivel de tecnología, sino también en mano de obra, servicios y contrataciones de terceros en algunas ocasiones.
        p Razones por las cuales también se desarrolla un diagnóstico muy preciso de la inversión a efectuar, la cual debe estar sujeta a los lineamientos de gastos de la organización; esto quiere decir que la implementación de un SGCN debe ir de la mano con los presupuestos que maneja la empresa (dentro de los cuales, aunque no se dice de una manera directa, los sistemas de gestión deberían tener su propio presupuesto de ejecución dentro de las organizaciones, ya que estos garantizan su funcionamiento y necesitan de un constante seguimiento para que siempre se encuentren en óptimas condiciones cuando estos se requieran).

    .row.justify-content-center.mb-5
      .col-md-10
        .bloque-texto-g.color-acento-botones.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema1/img32.jpg')})`}"
          )(data-aos="fade-right")
          .bloque-texto-g__texto.p-5
            p.mb-0 La norma es una necesidad fundamental si se desea tener procesos certificados y con un referente internacional, que genera prestigio y garantiza resultados concretos y efectivos. De ahí que el compromiso que asuma la alta dirección de la organización sea lo suficientemente consolidado para lograr alcanzar no solo la inversión necesaria en su implementación, sino también la cohesión y concienciación de su importancia en todo el personal y miembros de la organización. 

    .row.justify-content-center.align-items-center.cajon.color-acento-botones.p-4.mb-4
      .col-md-2.col-4.mb-md-0.mb-4(data-aos="fade-right")
        img.w-75(src='@/assets/curso/tema1/img33.png')
      .col-md-10.col-11
        .h4 Gestión de la continuidad del negocio - ISO 22301:2019
        p.mb-0 Si se desea explorar un poco más sobre los procesos de la Norma ISO 22301 para la continuidad del negocio, se sugiere consultar el video denominado #[strong Gestión de la continuidad del negocio - ISO 22301:2019 Plan de continuidad del negocio ISO 22301]. Recurso que podrá ubicar en los materiales complementarios del componente.

    p Se puede resumir, de alguna manera, que la Norma ISO 22301 permite garantizar no solo los procesos de negocio, sino también su reactivación en caso de surgir inconvenientes con los mismos. Se debe destacar de esta norma el proveer de los mecanismos y protocolos para realizar de manera no traumática este proceso, y en el que además sea lo más transparente posible para quienes tienen acceso al mismo. 
    p En ejemplos anteriores se había conversado sobre el sistema bancario y lo importante que es la tecnología en su funcionamiento. Ahora se retoma dicho ejemplo con enfoque a las plataformas de transacciones o también llamadas banca virtual, para evidenciar en este caso, la importancia de la transparencia en estos protocolos de recuperación del sistema. Vea esta explicación en el siguiente recurso:

    LineaTiempoE.color-acento-contenido
      .row.align-items-center
        .col-md-2.col-4.img03(data-aos="fade-right")
          img(src='@/assets/curso/tema1/img34.png')
        .col-8.mb-4.img04
          p Imagine que el sistema sufre una falla y se activa el plan de continuidad del negocio con todos los protocolos, actividades y procesos que implica restablecerlo.
      .row.align-items-center
        .col-md-2.col-4.img03(data-aos="fade-right")
          img(src='@/assets/curso/tema1/img35.png')
        .col-8.mb-4.img04
          p Pero este, al momento de restablecerse, no muestra a los clientes su saldo y no genera correos electrónicos o evidencias de las transacciones.  Adicional a ello, sufre retrasos para la entrega del dinero en las cuentas de los clientes
      .row.align-items-center
        .col-md-2.col-4.img03(data-aos="fade-right")
          img(src='@/assets/curso/tema1/img36.png')
        .col-8.mb-4.img04
          p En este punto, entonces, se podría decir que se ha restablecido el servicio pero no está funcionando de manera óptima y por tanto, no fue transparente para los clientes dicho proceso, debido a que se están evidenciando fallas en el proceso de recuperación del mismo.
      .row.align-items-center
        .col-md-2.col-4.img03(data-aos="fade-right")
          img(src='@/assets/curso/tema1/img37.png')
        .col-8.mb-4.img04
          p En ese sentido, aunque no es necesario que el usuario final conozca las razones exactas del porqué de la falla del sistema, esta situación sí genera incertidumbre y descontento en ellos.
      .row.align-items-center
        .col-md-2.col-4.img03(data-aos="fade-right")
          img(src='@/assets/curso/tema1/img38.png')
        .col-8.mb-4.img04
          p El proceso debe buscar no solo garantizar la recuperación del servicio, sino que este se encuentra operable de manera completa para todos los usuarios.

    separador
    #t_1_4.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.4.	Beneficio para las empresas que implementan un SGCN

    p Hoy en día las empresas tratan de destacarse en el ámbito competitivo y en la calidad delos  servicios a sus clientes, permitiendo ingresar a nuevos mercados, manejar una mayor cantidad de clientes, ampliar el portafolio de servicios, y por ende, obtener un mayor crecimiento; lo que a su vez acarrea una gran responsabilidad debido al nivel de calidad de los servicios que se ofrecen en la organización. Por tanto, la contratación de personal, la adquisición de equipos y los procesos requerirán de mayor control y eficiencia, que se incluye y evidencia en el plan de gestión.
    p Adicional a lo anterior, también es importante comprender que para dicho sistema la norma establece ciertos procesos que permiten el aseguramiento de la continuidad del negocio a través de un proceso de mejora continua. Existen diferentes factores que agregan valor a una organización que decide tomar la decisión de certificarse en la Norma ISO 22301, entre ellos se encuentran: 

    TabsC.color-acento-contenido.mb-4(data-aos="zoom-in")
      .py-3.py-md-4(titulo="Mejorar el rendimiento empresarial y la competitividad")
        .row.justify-content-center
          .col-md-6.col-10.mb-4.mb-md-0
            img(src='@/assets/curso/tema1/img39.jpg')
          .col-md-6.col-10
            p En este aspecto se considera que la implementación de la norma es un valor agregado en los procesos de negocio. La competitividad permite a las organizaciones poder ofrecer mejores productos y servicios; pero en este caso se garantiza que dichos productos o servicios estarán avalados por estrategias para su permanencia y estabilidad en el tiempo, lo que a su vez trae confianza de inversión y aprovechamiento de nuevos mercados.
      .py-3.py-md-4(titulo="Disminuir los riesgos, reducción de costes, de tiempos de inactividad")
        .row.justify-content-center
          .col-md-6.col-10.mb-4.mb-md-0
            img(src='@/assets/curso/tema1/img40.jpg')
          .col-md-6.col-10
            p Se garantiza la disminución de los factores de riesgo, ya que la norma permite realizar un diagnóstico de los mismos, que se pueden presentar en un corto, mediano y largo plazo, y un  proceso continuo de seguimiento y control en el tiempo y espacio. 
            p Otro de los aspectos que se encuentra dentro de este factor es la reducción de costos, no solo en la manutención de los procesos del negocio sino en la disminución de la inversión para el control y gestión de los riesgos, ya que la herramienta permite monitorear los riesgos antes de que estos se generen o que puedan afectar los procesos de manera directa. 
            p Finalmente, también disminuye el tiempo de recuperación del sistema debido a la buena planeación del mismo, traduciendo esto en mayor rentabilidad y calidad en los servicios que presta la organización.  
      .py-3.py-md-4(titulo="Mayor eficiencia operativa")
        .row.justify-content-center
          .col-md-6.col-10.mb-4.mb-md-0
            img(src='@/assets/curso/tema1/img41.jpg')
          .col-md-6.col-10
            p La eficiencia operativa se mide en la eficacia en la que se realizan las actividades de la organización. En otras palabras, este factor mide la manera más eficiente de realizar un proceso y que este sea razonable y con el menor esfuerzo operativo. 
            p La norma ayuda a definir las actividades que se deben realizar en caso de ocurrir un suceso y tiene en cuenta los recursos necesarios para la ejecución de la misma, garantizando una eficacia absoluta en su aplicación. 
            p Ahora bien, es importante tener en cuenta que entre mejor sean ejecutados los procesos operativos, la cantidad de recursos financieros disminuye y se vuelven sostenibles en el tiempo, debido a la estandarización de los procesos para dichas actividades.
      .py-3.py-md-4(titulo="Considerar todas las amenazas")
        .row.justify-content-center
          .col-md-6.col-10.mb-4.mb-md-0
            img(src='@/assets/curso/tema1/img42.jpg')
          .col-md-6.col-10
            p Aunque es muy subjetivo decir que se puede tener control en todos los tipos de amenazas y riesgos que puedan surgir en el negocio, es de considerar que cuando se realiza un estudio específico de riesgos y amenazas es mucho más factible establecer mecanismos y estrategias para el control de los mismos, pues se tiene una base de conocimiento y, a partir de allí, se facilita la generación de planes de contingencia para mitigar que estos se puedan presentar.
            p Para ello, se tiene un registro de los presentados y los que posiblemente se puedan presentar en un futuro. Cuando se realiza procesos como estos es probable que la organización se encuentre alerta y gestione de manera responsable estos riesgos. La Norma ISO 22301 establece el diseño y puesta en marcha de los planes de contingencia para los sucesos del negocio y de esta manera garantizar un menor impacto en caso de que estos ocurran.
      .py-3.py-md-4(titulo="Implicar y comprometer a toda la organización")
        .row.justify-content-center
          .col-md-6.col-10.mb-4.mb-md-0
            img(src='@/assets/curso/tema1/img43.jpg')
          .col-md-6.col-10
            p Este factor es fundamental para que un SGCN tenga una implementación adecuada, debido a que se pueden realizar todos los procesos y estatutos de la norma; sin embargo,  si no existe un compromiso real de los dirigentes y personal de la organización, no se podrá realizar un proceso adecuado de implementación de la norma en dicha organización. 
            p Es importante que todos los organismos y dependencias de la empresa estén inmersos y comprometidos, debido a los beneficios que esta le ofrece a la organización. En muchos casos no es visible la ganancia o ventaja que brinda la norma, debido al proceso de maduración de su implementación, lo cual puede llevar un tiempo en realizarse de manera completa y satisfactoria, pero vale la pena la espera e inversión de la misma.

    .row.justify-content-center.align-items-center.BG04.p-4
      .col-md-2.col-4.mb-4.mb-md-0(data-aos="fade-right")
        img.img90(src='@/assets/curso/tema1/img44.png')
      .col-md-10
        .h4 Recuerde que
        p.mb-0 Cada factor es fundamental para el correcto funcionamiento y gestión de un SGCN. Es esencial que todos los entes e involucrados en la organización sean conscientes de la importancia de la implementación de referentes internacionales que garanticen que las actividades y procesos que se realizan en la organización sean ejecutados con calidad y compromiso. El uso de la Norma ISO 22301 garantiza en la organización que la implementación se dé bajo los pilares de seguridad, transparencia y confianza.

</template>

<script>
import Botones from '../components/Botones.vue'
export default {
  name: 'Tema1',
  components: {
    Botones,
  },
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
