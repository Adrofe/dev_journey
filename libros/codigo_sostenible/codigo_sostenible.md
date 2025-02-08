# [Código Sostenible](https://savvily.es/libros/codigo-sostenible/)
- Autor: Carlos Blé Jurado
- Sinopsis: Cómo programar código fácil de mantener. El libro que nos hubiera gustado tener entre nuestras manos cuando estábamos aprendiendo a programar. Una guía para quienes buscan la satisfacción del código bien hecho. ¿Te has planteado alguna vez cómo sería programar sin prisas, sin parches y sin chapuzas? Tras veinte años de carrera como programador, consultor, conferenciante y formador, Carlos Blé plasma lo mejor de sus enseñanzas en este libro.
- [Drive](https://drive.google.com/drive/u/0/folders/1IWfBkgh8gPGC7-m5iiatyzs_T8UY_1Fy)

## Índice:
- [Código Sostenible](#código-sostenible)
  - [Índice:](#índice)
  - [1. ¿Qué es código sostenible?](#1-qué-es-código-sostenible)
    - [La degeneración del código](#la-degeneración-del-código)
    - [¿Por qué es tan importante la sostenibilidad?](#por-qué-es-tan-importante-la-sostenibilidad)
    - [Las personas primero](#las-personas-primero)
  - [2. Refactorización](#2-refactorización)

## 1. ¿Qué es código sostenible?

El código sostenible es **aquel que se puede mantener fácilmente a lo largo del tiempo**. Para ello, es necesario que su diseño sea **intuitivo**, que su **complejidad sea la mínima** imprescindible y que esté **bien cubierto por pruebas automatizadas**.

### La degeneración del código
Cuanto **más retorcida es la solución** implementada, **más degenera el código y más cuesta revertir la situación**. Puede llegar el momento en que todo el equipo se dé por vencido y entonces decida que la mejor solución es tirarlo todo abajo y empezar el desarrollo desde cero, volviendo al glorioso estado de greenfiel (o proyecto vacío).

¿Cómo evitar la degeneración? Hace **falta que el código sea sostenible**, lo cual requiere, entre otras cosas, que tenga una **cobertura de test** decente. *Sin test no hay gloria*.

¿Es posible reconducir un proyecto en el que hemos perdido el control? **Perder el control** significa **no tener ni idea de lo que vamos a tardar en hacer cambios**, ni en lo que va a **dejar de funcionar** cuando los hagamos o tan siquiera **dónde hay que aplicarlos**.

### ¿Por qué es tan importante la sostenibilidad?
Primero, porque se espera que hagamos un trabajo técnico de excelente calidad. La **mejor manera de ofrecer soluciones ágiles y adaptadas** a sus problemas es mediante el **asesoramiento**, el **acompañamiento** y la **entrega continua de software que funciona**. Es **imposible entregar software robusto** con la cadencia adecuada, **si su diseño y su código son insostenibles**.

**Por más rápido que queramos ir**, cuando alcanzamos varios miles de líneas de código que **no están respaldadas por test**, **cuesta entender y cambiar**; nos volvemos lentos e impredecibles. El tiempo se esfuma depurando bugs o intentando comprender código. Cuanto más queremos correr, más empeoramos el código y más tardamos en dar respuesta al negocio. Lo que al principio tomaba días, ahora supone meses, y cada modificación del código tiene efectos secundarios insospechados, rompiendo con funcionalidades existentes sin que nos demos ni cuenta de ello.

Hoy los equipos de desarrollo de las tecnológicas de éxito programan con test automáticos de calidad, diseñan arquitecturas adaptadas a su contexto y escriben el
código para que cualquier persona del equipo lo pueda modifica. **Cuando escribo código con la intención de ser explícito, simple y conciso**, siento que contribuyo al bienestar de la empresa, de las personas que trabajan en ella y de las que vendrán en el futuro.

### Las personas primero
La calidad del código es importantísima para la sostenibilidad del desarrollo, aunque me gustaría resaltar que **la calidad de la relación
entre las personas es todavía más importante**. Un grupo de personas que trabaja en equipo siempre llegará más lejos que un individuo, por más voluntad que este le ponga. **El cuidado del código no puede estar por encima del cuidado de las relaciones y las personas**.

La falta de **inteligencia emocional, de empatía, de actitud, de conocimiento, de capacitación**… son las **principales amenazas** de los proyectos; son incluso la principal amenaza para cualquier organización. Un lema que me gusta recordar es, *«firme con el asunto, pero flexible con la persona»*.

## 2. Refactorización
Estas **pequeñas mejoras de legibilidad** que aplicamos al código se conocen como **refactorización o refactoring**.
  - Conforme he terminado de escribir un bloque y funciona, **lo vuelvo a leer** buscando si se puede escribir de forma más explícita.
  - Cada día al empezar la jornada,** dedico diez minutos a leer el código del día anterior**, y para mi sorpresa, a veces me da la sensación de que lo hubiera escrito otra persona. Lleva muy poco tiempo aplicar cambios pequeños y seguros con el apoyo de un IDE.
  - **Conforme he terminado la funcionalidad** (tarea, requisito, historia de usuario…), **repaso todo el código de la misma**, buscando posibles sorpresas que haya podido dejar.
  - Generalmente, programo con otra persona (pair programming). Si la persona que escribió el código necesita explicárselo a la otra, ella
misma se da cuenta de cómo lo puede mejorar. Por otro lado, si la persona que está leyendo el código de la compañera no lo entiende, aprovecha para preguntar y juntas lo mejoran.

Si en un proyecto nuevo **practicas refactorización a diario**, podrás seguir dedicando la mayor parte del tiempo a implementar la funcionalidad. El tiempo refactorizando no será significativo. La táctica que recomiendo para aplicar refactorización es **priorizar aquellos cambios que producen el máximo retorno de inversión con el menor riesgo.**
  - **Sustituir un nombre** por otro más apropiado aumenta significativamente la expresividad, además de ser un cambio trivial con mínimo riesgo.
  
Piensa en la refactorización como en una tarea cotidiana tal como dejar tu escritorio recogido, en lugar de abordarla como una macro reforma de una casa.
El código que ha sido desarrollado sin el apoyo de test, es típicamente difícil o imposible de testar, con lo cual entramos en un círculo vicioso de ausencia de refactorización y de test. **Borrar y volver a escribir hasta que el código sea legible es mucho más barato que seguir adelante con un código enrevesado**.
