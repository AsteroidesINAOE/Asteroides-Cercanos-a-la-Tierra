# Curvas de luz

Una de las cosas más importantes que podemos estudiar de los objetos que observamos en el cielo es su luz que nos llega, tanto si es producida por ellos mismos (como en el caso de las estrellas) o si es reflejada (como los asteroides). Un astrónomo es un experto en la detección y el estudio de la luz, en todo tipo de longitud de onda (la longitud de onda es la distancia entre dos crestas o valles consecutivos de una onda). Es decir, es capaz de detectar luz en radiofrecuencia (>1 m), microondas (1 m-10^-2 m), luz en infrarrojo (10^-3 m-2.5*10^-6 m), luz visible (780*10^-9 m-380*10^-9 m), ultravioleta (380*10^-9 m- 200*10^-9), luz en rayos X (200*10^-9 m-10*10^-9 m) hasta los rayos gamma (<10*10^-12).

Uno de los aspectos que es de gran interés es observar cómo cambia esta luz que nos llega de un objeto, como varía la luz que observamos con el tiempo. Por ejemplo, imagine que observamos un faro lejano de una playa. La luz del faro da vueltas, por lo que no siempre observaremos la misma cantidad de luz; si estamos en la zona que está iluminada observaremos muchísima luz, pero cuando da media vuelta la fuente, estaremos observando muy poca luz, casi nada. Algo similar ocurre con muchos objetos en el espacio.

Un caso similar se tiene cuando se mide la luz de un asteroide. Un asteroide es parte de lo que se conoce como un cuerpo menor del sistema solar. A diferencia de los planetas, por ejemplo, no tienen una forma regular o simétrica. Más bien, un asteroide es como una papa, tiene formas irregulares, con algunas caras más grandes que otras, algunos son más alargadas que otros, etc, etc. Además, un asteroide no emite luz propia, es más como un espejo que refleja la luz del Sol. Por eso, dependiendo que cara refleje luz del Sol hacia nosotros, notaremos que recibimos más o menos luz del asteroide. Así, si graficamos la luz reflejada conforme avanza el tiempo, notaremos un comportamiento curioso. La gráfica sube y baja de maneras distintas, hasta que después de un cierto tiempo se repiten estas mismas formas de subir y bajar. Ese tiempo en el que el comportamiento de la luz se repite se llama **periodo** del asteroide.

Determinar el **periodo** de un asteroide es de los aspectos más importantes que se pueden encontrar si se estudia su curva de luz. Pero ¿Qué es una curva de luz? Una **curva de luz** es una gráfica que muestra cómo cambia el brillo de un objeto al pasar el tiempo. Este brillo puede recibir un valor numérico el cual se denomina **magnitud**. Debido a la atmósfera, el campo de visión, el Sol, la distancia asteroide-Tierra y asteroide Sol, entre otros factores, esta magnitud será **aparente**, es decir, no es el brillo propio del objeto. Además, por otros factores como el instrumento que se usa para medir la magnitud, el clima, etc, cuando se tienen imágenes del objeto, éstas deben pasar por un proceso que elimine todos los efectos no deseados antes de ser estudiadas.

Cuando ya se tienen las imágenes finales, es necesario identificar el asteroide, pues en la imagen se ven muchos puntos brillantes y es difícil determinar cuál es el asteroide si el observador no recuerda exactamente cuál era. Se puede recurrir a una técnica sofisticada para saber cuál es el asteroide de un conjunto de imágenes. Dicha técnica se llama hacer un “GIF”. Como un asteroide está más cerca de nosotros que los demás objetos brillantes (estrellas, quizá planetas, etc.), su movimiento es más notable, por lo que al poner en secuencia las imágenes se podrá identificar a simple vista donde está e incluso que camino siguió durante la noche en que se observó. 

Mediante algún software se mide su magnitud en cada imagen y se puede graficar finalmente en función del tiempo. Una gráfica como estas se puede observar a continuación (note que la fecha está dada en formato Juliano).

![alt text](771_Libera.png)

Como las observaciones que se hacen a un objeto pueden variar en tiempo por días, semanas, meses e incluso años, es conveniente poner los datos en “fase”. Es decir, todas las observaciones de cada fecha que coincidan con una de las caras que nos dé el asteroide corresponderán a un solo valor o estarán alrededor de un solo valor en el eje x. De esta forma, si se observó una cara del asteroide en un momento dado y meses después se observó de nuevo, ambos datos coincidirán alrededor de un punto. Cuando se llega a la última cara del asteroide no se tendrán datos más allá, pues se volvería a estar en la cara que se graficó al inicio. Es por esta razón que los valores en el eje x van desde 0 hasta 1, pues en este extremo final el asteroide habrá dado una vuelta, es decir, habrá completado un periodo de rotación.

Otro aspecto que señalar es que las observaciones en diferentes fechas tienen una diferencia pequeña en su magnitud entre ellas. Por ejemplo, en una noche se observó que la mayor magnitud que se recibió de un asteroide fue de 14 y otra noche fue de 14.5. Esto no supone mayor problema que restar o sumar valores a los datos de una u otra noche para hacerlos coincidir.

## Construcción de una curva de luz

A continuación, se presenta la traducción de una actividad en la que podrá realizar su propia curva de luz. La actividad original se puede encontrar en el siguiente enlace: [](https://lco.global/education/activities/plotting-an-asteroid-light-curve/)

### Graficando una Curva de Luz de un Asteroide

### Resumen

Una de las cosas que esperamos que aprenda a través de la observación de objetos cercanos a la Tierra es su periodo exacto de rotación. Podemos hacerlo tomando una serie de observaciones del objeto a lo largo del tiempo, y trazando el cambio en el brillo. Usando [Asteroid Tracker](https://asteroidtracker.lco.global/) puede ayudar a colectar observaciones de objetos NEO interesantes, luego trazar e interpretar sus datos para medir el periodo de rotación de un asteroide.

###Objetivos

Los estudiantes trazarán y analizarán datos observacionales colectados por miembros del público usando *Asteroid Tracker*, y tratarán de medir el periodo de rotación del asteroide.

**Objetivos de Aprendizaje**

- Familiarizarse con asteroides y objetos cercanos a la Tierra
- Participar en el proyecto de ciencia ciudadana *Asteroid Tracker* y contribuir a ampliar nuestra comprensión del Sistema Solar
- Trazar una curva fotométrica usando datos observacionales
-	Interpretar graficas y reconocer la periodicidad en un conjunto de datos
-	Entender como y por qué los astrónomos estudian el periodo de rotación de un asteroide

###Planeación

**Materiales**

- Una computadora con software de hoja de cálculo y acceso a Internet
- Datos observacionales de asteroides tomados usando Asteroid Tracker, por ejemplo [2002 KL6](https://s3.us-west-2.amazonaws.com/www.lco.global/documents/2002_kl6.txt?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA6FT4CXR4ZJRYWHNN%2F20220419%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220419T005107Z&X-Amz-Expires=3600&X-Amz-SignedHeaders=host&X-Amz-Signature=de6c5de397f96b983613d533f9e5e1920d237e2bdbf784d4dd53ee67b91c23b4)
- Opcional: [hoja de cálculo de actividades de 2002 KL6] (https://drive.google.com/file/d/1yPsU6ZDOwSuAHSx5PZvicfp_vDXsvJ3d/view)

###Trasfondo




























