## Alfred's Story

Proyecto de Creación Multimedia Interactiva de la  Facultad de Bellas Artes de la Univesidad de Granada



# 1 Datos 



**Titulo** :  Alfred's Story

**Web:**   https://alfredsstory.github.io

**Autor:**  Lola González Prieto

**Resumen** : Alfred's Story es un juego de toma de decisiones con un minijuego incluido. Cuenta el encuentro de un gnomo y un niño o niña (no se especifica en el juego cómo es el protagonista) en un bosque mágico. Para conseguir volver a casa, tendrás que conseguir llevarte bien con las criaturas del bosque, ya que solo ellas saben cómo ayudarte.

**Estilo/género:**  Novela visual/Juego

**Logotipo** : 

![titulo](https://github.com/AlfredsStory/AlfredsStory.github.io/blob/master/medios/t%C3%ADtulo.png)

(insertar imágenes a resolucion de 100px alto)

**Resolución:** 800x600px tamaño fijo (No reescalable. Los diálogos se distorsionan si se cambia el formato)

**Probado en:**   Google Chrome, Firefox, Microsoft Edge y Safari

**Tamaño proyecto:** 53,1MB 

**Licencia** Este proyecto tiene una Licencia CC Reconocimiento Compartir igual (CC BY-SA)

**Fecha** : 17/06/2021

**Medios** (donde se tiene presencia relacionada):

- Github: https://github.com/AlfredsStory/AlfredsStory.github.io
- Youtube: https://youtu.be/yNqY9F0nDGc





# 2. Memoria del proyecto 

### 2.1 Storyboard: 
Después de una intro con una sucesión de dos imágenes, llegamos a un menú con estas opciones:

![menu](https://github.com/AlfredsStory/AlfredsStory.github.io/blob/master/botones/Menu.png)

- Jugar- Al pulsar este botón te lleva al modo historia (el juego). Al principio está todo en negro y sólo se ve a alguien desconocido hablar. A partir de ahí se va desarrollando el juego a través de diálogos con distintos personajes.  Hay tres tomas de decisiones en el diálogo, y un minijuego que también influye a que puedas tener un final bueno o malo.

- Extras- Te da la opción de ir a tres galerías distintas. Una con la información de los personajes, otra de las escenas del juego y una última de multimedia con dos vídeos: uno del proceso de creación de los personajes, y otro de la música utilizada.

![2 extras](https://github.com/AlfredsStory/AlfredsStory.github.io/blob/master/botones/2%20extras.png)

- Creditos- Sucesión de los créditos en scroll de arriba a abajo.


### 2.2. Esquema de navegación 

Esquema de navegación del juego:

![Esquema de navegacion de juego y creditos](https://github.com/AlfredsStory/AlfredsStory.github.io/blob/master/botones/Esquema%20de%20navegacion%20de%20juego%20y%20creditos.jpg)


Esquema de navegación por la galería:

![Esquema de navegacion galeria](https://github.com/AlfredsStory/AlfredsStory.github.io/blob/master/botones/Esquema%20de%20navegacion%20galeria.jpg)







# 3. Metodología

Metodología de desarrollo de productos multimedia basado en una metodología de UX (User Experience)



### Etapa 1: Ideación de proyecto

**Investigación de campo** (propuestas inspiradoras para el proyecto)

- The Arcana: A Mystic Romance - Love Story (https://play.google.com/store/apps/details?id=com.nixhydragames.thearcana&hl=es&gl=US). Me basé en este juego para la creación de un final bueno y uno malo, además de la forma de tomar decisiones en los diálogos.
- Sky: Niños de la Luz (https://play.google.com/store/apps/details?id=com.tgc.sky.android&hl=es&gl=US). De este juego tuve la idea de que el protagonista fuese un niño del que no se sepan apenas sus características ni su género. Es un juego de movil que me gusta mucho por su estética y el hecho de que se vayan investigando distintos "mundos".
- Serie- Las aventuras de Gravity Falls (https://www.disneyplus.com/es-es/series/gravity-falls/HZxayxzMJqed). De esta serie tomé la estética, aplicada a mi forma de ilustrar y también fue la inspiración para el personaje de Alfred.



**Motivación de la propuesta** 

Este  proyecto es interesante porque une la narración de una historia junto con un minijuego. Siempre había querido dar forma a las historias que me invento, y este juego ha sido una buena forma de hacerlo. La gran mayoría de juegos de toma de decisiones suelen estar basados en construir relaciones remánticas como los juegos Otome, en este caso es desarrollar amistad con personajes de fantasía.



**Publico / audiencia**

- Orientado a todos los públicos públicos, aunque es perfecto para niños (10-25 años). 





### Etapa 2: Desarrollo / actividades realizadas



- Juego. Para desarrollar el juego quería hacer varias variables de amistad, una para cada personaje e ir sumando o restando puntos para desbloquear el final bueno o malo. Debido a la falta de tiempo solo utilicé una variable, "amistadAlfred", dependiendo de las repuestas que se elijan, se pueden sumar como máximo tres puntos o quitar también tres puntos. Además el minijuego también influye en la variable, si lo pierdes no puedes desbloquear el final bueno. Me quitó mucho tiempo el hacer que los diálogos fuesen apareciendo poco a poco, y de hecho, depende del ordenador al redimensionarse los bloques que van descubriendo el diálogo funcionan mal. A parte de eso, también costó conseguir pasar el valor de la variable a los tres ficheros html, pero junto al profesor lo solucioné. 

Respecto a la creación de personajes y escribir el guión, fue un proceso rápido y divertido. El minijuego una vez el profesor me explicó algunas funciones de Java Script, fue bastante interesante ir planteándome cómo tenía que programar para que diese el resultado que yo quería.

- Video. Utilicé un video propio del making of y lo incrusté en el apartado de multimedia. También quise poner el video de Youtube de donde obtuve la música, pero al exportarlo y subirlo a Github, no se por qué no se ve. Los controles de parar y continuar el vídeo fueron bastante sencillos añadiendo botnes en Hippani.

- Instrucciones y ayuda al usuario. Para asegurarme de que se entendiese cómo pasar los diálogos, puse un pequeño texto en el primero, explicando que hay que darle al play para continuar. Además, antes del minijuego hay un cuadro de texto que explica qué controles hay que usar para moverse y que se deben de esquivar los objetos.

- Menús y elementos de navegación (botones). Después de la intro, aparece el menú principal, compuesto de botones para jugar, ir a extras y los créditos. También desarrollé otro menú para la galería, con en tres botones, uno para la info de los personajes, otro para las escenas y un tercero para los vídeos. He utilizado los botones para la navegación por los menús y para la toma de decisiones en el juego.



### Etapa 3: Problemas identificados

El problema principal es que se desajustan los bloques que van revelando el texto si se reescala el juego, y en determinados dispositivos, al jugar no puedes ver bien el diálogo, lo que es necesario para jugar. Por mucho que he intentado ajustar los bloques, se vuelve aun más complicado cuando en Hippani la letra se ve de una forma, y exportado de otra. El otro problema es que como he dicho, no se ve un vídeo de youtube al poner el proyecto en github, pero como no es muy importante el video, no me preocupa mucho. Por lo demás, el resto de problemas los he ido solucionando.



# 4. Conclusiones 

Considero que aunque el juego podría estar mejor, estoy muy orgullosa de todo lo que he podido hacer y de haber dado forma a una de mis ideas. Me hubiese gustado haber podido incluir más decisiones, más diálogo y criaturas mágicas, pero no he podido, debido a la falta de tiempo. Se quedará para una futura parte dos. Me gustaría en el futuro hacer más proyectos de este tipo, pero desde luego con otro programa, ya que hippani no es muy adecuado para las novelas visuales, aunque sí para cosas como el minijuego.





# 5 Referencias 

**Artículos y blogs ** 

- Crofts, S., Fox, M., Retsema, A. and Williams, B. (2005) *Podcasting: A new technology in search of viable business models*First Monday, 10(9). https://doi.org/10.5210/fm.v10i9.1273. Recuperado el 8 de abril de 2020 de: https://journals.uic.edu/ojs/index.php/fm/article/view/1273/1193

**Recursos y materiales audiovisuales:**

* Musica:  https://youtu.be/ezfjLfySXf4 
Until the End by Alexander Nakarada
https://www.serpentsoundstudios.com
Music Promoted by oroclick

* Imágenes:  Lola González Prieto
* Tipografía:   libre Baskerville Regular de Google Fonts, Berkshire Swash - Google Fonts y Monotype Type Drawing Office - Patricia Saunders 

**Herramientas utilizadas**

- Hippani Animator 5.1
- Audacity
- Photoshop



![licencia](https://github.com/AlfredsStory/AlfredsStory.github.io/blob/master/botones/licencia.jpg)

https://creativecommons.org/licenses/?lang=es

Mayo 2020
