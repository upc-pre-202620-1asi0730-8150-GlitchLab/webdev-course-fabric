# Guion · Lección 4: Introducción a CSS (10 min)

**Objetivo:** escribir reglas CSS, conectar CSS con HTML y usar selectores de etiqueta, clase e id.
**Editor:** CodePen (pen con `starter-files/leccion-04`).
**Tema añadido:** formas de conectar CSS con HTML y selectores de clase e id.

| Tiempo | Pantalla / Texto en pantalla | Narración (voz en off) |
|---|---|---|
| 0:00 – 0:30 | Página de la lección 3 en blanco y negro. Texto: **"Hoy: ¡color!"** | "Tu página ya tiene contenido, pero se ve aburrida. Hoy aprenderás CSS para darle color y personalidad." |
| 0:30 – 2:00 | Regla `h1 { color: purple; }` con anotaciones: selector, llaves, propiedad, valor, punto y coma. | "CSS se escribe con **reglas**. Primero el **selector**, que dice a qué elemento le damos estilo. Entre llaves van las **propiedades** con su **valor**, separados por dos puntos, y al final un punto y coma." |
| 2:00 – 3:30 | Tres opciones en pantalla: `style="..."`, `<style>` en el `<head>`, `<link rel="stylesheet" href="styles.css">`. Se marca la tercera con ✅. | "Hay tres formas de conectar CSS con HTML: dentro de la etiqueta con `style`, en una etiqueta `<style>`, o en un archivo aparte enlazado con `<link>`. La mejor práctica es el archivo aparte: separa el contenido del estilo. En CodePen, el panel CSS funciona como ese archivo." |
| 3:30 – 5:00 | Demostración en vivo: `color`, `background-color`, `font-family`, `font-size`. Colores por nombre y en hexadecimal (`#6c5ce7`). | "Probemos propiedades. `color` cambia el color del texto y `background-color`, el del fondo. Puedes usar nombres en inglés como `tomato` o códigos como `#6c5ce7`. `font-family` cambia la letra y `font-size`, el tamaño en píxeles." |
| 5:00 – 7:30 | HTML con `class="destacado"` e `id="titulo"`. CSS con `.destacado` y `#titulo`. Anotación: **". = clase · # = id"** | "¿Y si quiero pintar solo un párrafo y no todos? Uso una **clase**: le pongo `class="destacado"` en el HTML y en CSS escribo punto destacado. Las clases se pueden repetir en muchos elementos. Un **id** usa numeral y es único: solo un elemento por página." |
| 7:30 – 9:30 | Ícono ⏸️. Texto: **"Pausa y practica: elige tu paleta"** | "Pausa el video. En la práctica: cambia el color de fondo de la página, elige una fuente para los títulos y crea una clase `.favorito` para resaltar tu cosa favorita de la lista." |
| 9:30 – 10:00 | Antes y después de la página. | "¡Mira el cambio! En la siguiente lección aprenderás a centrar, poner bordes y organizar los elementos en la página." |

**Notas de producción**
- Mostrar la paleta de colores de CodePen al hacer clic en un color.
