# Alura-Layout-mobile

<https://www.figma.com/file/Cv9OIfwW20qbM2ywcSXOnK/Apeperia-Mobile-First-preparando-el-ambiente?node-id=15%3A198>

## REM y EM

REM es una unidad relativa a la propiedad font-size de la etiqueta raíz ``<html>``
, por lo tanto si la etiqueta tiene 16px de font-size 1 REM equivale a 16px. EM es relativa a la propiedad font-size de la etiqueta madre, por lo tanto, si la etiqueta madre es un font-size de 16px, 1 EM equivale a 16px.  
REM proviene de “Root ephemeral” que en traducción técnica es la “variable de la raíz”, o sea, es una variable en relación de la propiedad font-size de la etiqueta raiz (HTML). EM proviene de “ephemeral” que significa “variable” y es una variable de la propiedad font-size de la etiqueta madre.

## Formato SVG  

Cuando vamos a trabajar con imágenes, el formato SVG presenta una gran ventaja por ser liviano y no perder la cualidad si es ampliado, ya que es generado por una instrucción de la computadora.  

¿Cuándo es recomendado utilizar imágenes del tipo SVG?

En imágenes simplificadas, íconos y logotipos. Atención: El SVG no mantiene detalles de una imagen compleja.  

<https://developer.mozilla.org/es/docs/Learn/HTML/Multimedia_and_embedding/Adding_vector_graphics_to_the_Web>  

## Conceptos  

Para seguir un concepto de desarrollo, sea mobile-first o sea desktop-first, puedes seguir lo que prefieras porque no existe una regla que indique cual sea primero. Cada uno de ello tiene sus ventajas y desventajas que deben ser evaluadas de acuerdo con las necesidades del proyecto.

Para demostrar, aquí están algunas motivaciones de utilizar el desarrollo mobile-first:

Gran parte de los accesos y ventas son de dispositivos móviles;
El diseño es minimalista y simplificado;
Enfoque en el contenido.
Las motivaciones para utilizar el desarrollo desktop-first:

La interfaz tiene features más ricas;
Mayor capacidad de ejecución de las instrucciones;
El producto es optimizado para desktop (ejemplo: Google Docs).
Así que al desarrollar es importante analizar todos los puntos que influencian en el proyecto. Clientes, features, costo y lenguaje visual son algunos de los puntos que favorecen un abordaje sobre el otro.  

## Para saber más: PageSpeed Insights - Herramienta del contenido

La herramienta "PageSpeed Insights" analiza el contenido de una página web y te sugiere qué hacer para mejorar la velocidad de esa una página.

Puedes acceder en:

PageSpeed Insights
<https://developers.google.com/speed/pagespeed/insights>

Inserta un enlace que la herramienta analizan las versiones mobile y desktop, con cálculos de velocidad y performance, sugestiones de lo que pueden acelerar la carga.

## Media Query

Las media queries permiten crear páginas con estilos diferentes en el mismo archivo CSS por muchas condiciones diferentes, como por ejemplo, la largura de la pantalla de un dispositivo.

Después que terminar de desarrollar todo el layout de la página en la versión mobile, el próximo paso es el diseño en la versión tablet, en este caso empieza a partir de 768px de largura. Para insertar todo el estilo sin cambiar la versión mobile, necesitamos utilizar un media query.

```css
@media (min-width: 768px) { “estilo aquí” }
```  

Está con la condición de las “pantallas con largura a partir de 768px”.  

## Para saber más: Breakpoints

Para saber más sobre los breakpoints y valores genéricos para dispositivos (referencia en inglés), puedes leer este texto:

Media Queries for Standard Devices
<https://css-tricks.com/snippets/css/media-queries-for-standard-devices/>  

## ¿Cómo lidiar con los límites de resolución en sitios responsivos?

<https://www.aluracursos.com/blog/como-lidiar-con-los-limites-de-resolucion-en-sitios-responsivos>  
