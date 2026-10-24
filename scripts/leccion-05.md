# Guion · Lección 5: Estilos simples: centrar, bordes y diseño (10 min)

**Objetivo:** centrar contenido, usar bordes y espacios con el modelo de caja, y organizar elementos en fila.
**Editor:** CodePen (pen con `starter-files/leccion-05`).
**Tema añadido:** modelo de caja y una introducción a Flexbox para el diseño (layout).

| Tiempo | Pantalla / Texto en pantalla | Narración (voz en off) |
|---|---|---|
| 0:00 – 0:30 | Texto: **"Hoy: orden y diseño"** | "Ya sabes dar color. Hoy aprenderás a ordenar: centrar cosas, poner bordes y acomodar elementos uno al lado del otro." |
| 0:30 – 2:30 | Animación del modelo de caja: contenido → `padding` → `border` → `margin`. | "Para CSS, cada elemento es una **caja**. Adentro está el contenido. El `padding` es el relleno entre el contenido y el borde. El `border` es el borde. Y el `margin` es el espacio entre esta caja y las demás. Piensa en un cuadro colgado: la foto, el paspartú, el marco y la pared." |
| 2:30 – 4:00 | `border: 3px solid #6c5ce7;` y `border-radius: 12px;`. Se ve la tarjeta con esquinas redondeadas y una foto circular con `border-radius: 50%`. | "Un borde necesita tres cosas: grosor, estilo y color. Con `border-radius` redondeas las esquinas, y si le pones 50 % a una imagen cuadrada, ¡queda un círculo perfecto!" |
| 4:00 – 5:30 | `text-align: center;` en un título y `max-width: 600px; margin: 0 auto;` en un contenedor. | "Para centrar texto usa `text-align: center`. Para centrar una caja completa, dale un ancho máximo y `margin: 0 auto`: el navegador reparte el espacio sobrante a ambos lados." |
| 5:30 – 7:30 | Tres tarjetas en columna. Se agrega `display: flex; gap: 16px;` al contenedor y se ponen en fila. Luego `justify-content: center;`. | "¿Y si quiero tres tarjetas una al lado de la otra? Le ponemos `display: flex` al contenedor, ¡y listo! `gap` deja espacio entre ellas y `justify-content: center` las centra. Esto se llama **Flexbox** y es la forma moderna de organizar elementos." |
| 7:30 – 9:30 | Ícono ⏸️. Texto: **"Pausa y practica: crea una tarjeta"** | "Pausa el video. En la práctica: centra la página, convierte tu sección de favoritos en una tarjeta con borde, relleno y esquinas redondeadas, y pon tus tres favoritos en fila con Flexbox." |
| 9:30 – 10:00 | Resumen: caja, bordes, centrar, flex. | "Ya tienes todas las herramientas. En la próxima lección las juntamos para construir tu página de perfil completa." |

**Notas de producción**
- Activar temporalmente `outline: 1px dashed red` en todos los elementos para que se vean las cajas.
