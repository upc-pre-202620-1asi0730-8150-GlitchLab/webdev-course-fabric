# Guion · Lección 2: Estructura HTML básica (8 min)

**Objetivo:** escribir el "esqueleto" de una página y entender qué son etiquetas, elementos y atributos.
**Editor:** CodePen (pen con `starter-files/leccion-02`).

| Tiempo | Pantalla / Texto en pantalla | Narración (voz en off) |
|---|---|---|
| 0:00 – 0:30 | Texto: **"Hoy: tu primera página HTML"** | "En la lección anterior viste que HTML es el contenido de una página. Hoy vas a escribir tu primera página, línea por línea." |
| 0:30 – 2:00 | Código grande: `<p>Hola</p>`. Anotaciones: "etiqueta de apertura", "contenido", "etiqueta de cierre", "elemento completo". | "HTML se escribe con **etiquetas**: palabras entre los signos menor y mayor. `<p>` abre un párrafo y `</p>`, con la barra, lo cierra. Todo junto, apertura, contenido y cierre, se llama **elemento**. Regla de oro: lo que se abre, se cierra." |
| 2:00 – 3:30 | Código: `<a href="https://developer.mozilla.org">MDN</a>`. Se resalta `href="..."` con la etiqueta **"atributo"**. | "Algunas etiquetas necesitan información extra. Eso se llama **atributo** y va dentro de la etiqueta de apertura, con un nombre, un igual y un valor entre comillas. Aquí `href` le dice al enlace a dónde ir." |
| 3:30 – 5:30 | Se escribe en vivo la estructura completa: `<!DOCTYPE html>`, `<html lang="es">`, `<head>`, `<meta charset="UTF-8">`, `<title>`, `<body>`. Anotación de sangría. | "Toda página tiene la misma estructura. `<!DOCTYPE html>` le avisa al navegador que es HTML moderno. `<html>` envuelve todo. En `<head>` va información que no se ve en la página, como el título de la pestaña y `charset`, que permite tildes y eñes. En `<body>` va todo lo que sí se ve." |
| 5:30 – 6:30 | Se muestra la pestaña con el título y el cuerpo con un `<h1>` y un `<p>`. Texto: **"Usa sangría para ordenar tu código"** | "Fíjate que dejamos espacios al inicio de cada línea. Se llama sangría y ayuda a ver qué elemento está dentro de cuál. Al navegador no le importa, pero a ti y a quien lea tu código, sí." |
| 6:30 – 7:30 | Ícono ⏸️. Texto: **"Pausa y practica: completa el esqueleto"** | "Pausa el video. En el enlace de práctica hay un esqueleto incompleto: agrega el `<title>` con el nombre de tu página y, dentro de `<body>`, un `<h1>` con tu nombre y un `<p>` contando qué te gusta hacer." |
| 7:30 – 8:00 | Resumen con 3 viñetas: etiqueta, elemento, atributo. | "Ya conoces la estructura básica de cualquier página. En la siguiente lección le agregaremos listas, imágenes y enlaces." |

**Notas de producción**
- En CodePen el panel HTML solo necesita el contenido de `<body>`; explicar que la estructura completa es la que se usaría en un archivo `index.html` real.
