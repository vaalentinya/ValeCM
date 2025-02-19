# clase-09

lunes 13 mayo 2024

instrucciones solemne:

- se empieza hoy
- se entrega el lunes 20 mayo 2024, hasta las 5:20pm, vía GitHub, en tu fork
- si hay un commit posterior, no se tomará en cuenta
- el proyecto es individual
- el proyecto se hace con la tecnología web que quieran (HTML, CSS, JS, p5.js, etc)
- el proyecto es sobre lo que hemos visto en clases (bucles, condicionales, funciones, eventos, etc), aplicados a la modificación de imágenes en la web.

## pauta

la solemne tiene nota máxima 7.0, tienen 1 punto base más estos 6 puntos evaluados, 1 punto por cada uno:

1. 1 punto por aspectos formales: subir los archivos indicados en la carpeta correcta, sin branches extra
2. 1 punto por documentación textual en lenguaje MarkDown en tu archivo README.md sobre el funcionamiento de tu proyecto
3. 1 punto por incluir referentes y citas formales en tu documentación
4. 1 punto por orden y comentarios de tu código
5. 1 punto por interactividad de tu web con ratón y/o teclado
6. 1 punto por investigación y aplicación de bibliotecas (Processing Sound, three.js, API de NYtimes, etc...)

la pauta es:

- 1.0 si el aspecto está realizado impecablemente.
- 0.7 si tiene errores menores
- 0.5 si está incompleto o tiene errores mayores
- 0.3 por el intento
- 0.0 por la ausencia

## requisitos formales de la entrega

- subir a tu carpeta de la clase-04 tu proceso, y luego a la clase-05 tu entrega final, incluyendo TODOS tus archivos index.html, style.css, script.js, y otros archivos necesarios (imágenes, videos, etc) para que corra la web.
- variables y archivos sin espacios, en camelCase o notación camello.
- los comentarios se escriben en la línea de arriba del código
- los comentarios se escriben en español

```js
function setup() {
  createCanvas(windowWidth, windowHeight);
  frameRate(5);
}

function draw() {
  background(255, (5 * 255) / 100);
  stroke(255);

  push();
  translate(random(width), random(height));
  rotate(random(0, 2 * Math.PI));
  textSize(random(10, 100));
  text(':)', 0, 0);
  pop();

  push();
  translate(random(width), random(height));
  rotate(random(0, 2 * Math.PI));
  textSize(random(10, 100));
  text('ustedes pueden!', 0, 0);
  pop();
}
```
