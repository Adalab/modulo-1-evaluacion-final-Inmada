# Modulo 1. Evaluación.

Este proyecto me ha resultado todo un reto y, me ha motivado mucho poder realizarlo en tiempo y con todas y cada una de las peticiones, incluido el bonus.

En primer lugar, a nivel personal, creo que ha contribuido mucho la forma de organizarme, empezar despacio, descansar y dedicar un poco de tiempo a hacer un repaso general de lo aprendido para tener las ideas claras antes de empezar.

Comencé el viernes por la mañana y, dediqué unas 9horas en total. El sábado decidí desconectar, descansar y dedicar tiempo a mi familia para sentirme con las pilas puestas. El domingo dediqué otras 7horas. El lunes ya sólo me quedaba agregar color al corazoncito del footer, que tras numerosos intentos, lo dejé para pedir soporte, añadir una animación y el readme.

Nada más empezar, cometí el fallo de no guardar correctamente la rama del header y, lo perdí una vez acabado. Por suerte, eso me hizo replantearme cómo lo había organizado y, aunque en un inicio metí ahí el hero, en mi segundo intento decidí que era una sección del main y fue todo un acierto a la hora de darle estilo.

Usé ramas para header y main, en html e hice merge. La verdad, es que me suponía un inconveniente más que una ventaja al estar trabajando sola, así que sólo lo puse para mostrar que sé usar las ramas.

El sass no me dió ningún problema y, lo tuve desde el principio. Creé pocos partials porque trabajo sola, pero me fue útil para estructurarme mentalmente a la hora de hacer cada una de las partes. Header, main y footer, fue mi división del trabajo. Aunque los fuí haciendo por partes, cuando encontraba alguna dificultad, pasaba a otra cosa para no ir retrasándome y, a veces fruto de hacer una cosa, descubría otra que me venía bien para lo que dejé atrás.

Requisitos que se pedían:

La hamburguesa queda visible todo el tiempo y, es un enlace a Adalab que se abre a otra página. Usé z-index, position, displey flex y variables.

El main está dividivo en tres secciones:

La primera es el hero, empleé el display flex, como se solicitaba y para solucionar el problema de que la imagen del hero desaparecía al hacer scroll, añadí background-attachment: scroll, antes probé otros que no funcionaron.
Con el botón, no tuve ningún problema. Usé position: absolute y le dí porcentajes para moverlo y, position:relative a su contenedor padre. Si lo presionas te envía a la sección 3, que es la última del main.

La segunda, como era de libre elección la hice con flex que me parecía más sencillo.

Si presionas el botón te abre en otra página la web de Adalab. Todos los botones tienen title y alt, en este caso, si dejas el cursor encima te explicará a donde te lleva si haces click. Además, añadí el bonus usando una transition, que hace que se mueva la palabra comprar fuera de su contenedor.

La tercera sección está maquetada con grid. En la versión mobile, me resultó muy fácil. En la versión tablet tuve que hacer muchas pruebas e intenté maquetarla con areas y rows, pero finalmente lo conseguí, haciendo una especie de tabla y diciéndole a cada uno el lugar que debían ocupar. En la versión desktop no tuve que cambiar nada de este aspecto, salvo la posición del botón "empezar ahora" para lo que usé transform: translate y %.
Tal como se pedía en el bonus, le añadí al botón "empezar ahora" una transition que consiste en darle color negro al fondo. También, te abre la página de Adalab en otra página y contiene title y alt.

Por último, en el footer, lo dividí en cinco contenedores, uno de ellos para el botón, tres para el texto y uno más, para la animación.
El botón te lleva a sección de arriba. Lo desplacé con position y tranform.
El mayor problema fue darle color al corazón que inserté, pero Yanelis me explicó cómo hacerlo creando un span con su clase y fue de lo más sencillo.

La animación, no tenía ni idea cómo hacerla así que busqué ejemplos en internet y, fui probando muchas características para ver cual me gustaba más y no me destrozaba otros elementos.

En general, estoy agradecida por la experiencia y me ha demostrado que soy muy capaz de maquetar, además de que me encanta. Es como un rompecabezas que no quieres dejar hasta acabarlo. Hace pocas semanas no sabía ni que era hacer scroll. Estoy muy agradecida también a nuestros profesores que nos asisten siempre y, con mucha alegría y paciencia, sin ellos no sería posible.
