# Hoshi Pop · ficha de Facebook (Instant Games)

Textos e imágenes para rellenar en el panel de Meta (developers.facebook.com → tu app → Instant Games → Detalles).
Nada de premios, dinero, PayPal ni Telegram: esta versión es solo para jugar.

## Datos básicos
- **Nombre del juego:** Hoshi Pop
- **Categoría:** Puzzle (Rompecabezas)
- **Idioma:** Español
- **Orientación:** Vertical (ya va en `fbapp-config.json` dentro del zip)
- **Correo de contacto:** kikozazplays@gmail.com
- **Política de privacidad (URL):** `https://jfap1986.github.io/hoshi-pop/privacidad.html`
- **Instrucciones de borrado de datos (URL):** `https://jfap1986.github.io/hoshi-pop/privacidad.html#borrado`

## Lema / descripción corta (máx. ~80 caracteres)
Combina estrellas kawaii, crea cometas y supernovas y supera tu récord.

## Descripción larga
¡Bienvenido al festival de las estrellas! En Hoshi Pop combinas a los hoshis, unas estrellitas kawaii que viven en un cielo lleno de farolillos, auroras y estrellas fugaces.

⭐ Desliza un hoshi para hacer 3 o más en línea.
☄️ Haz 4 en línea y crea un cometa que limpia toda la fila o columna.
💥 Forma una L o una T y consigue una supernova.
🌈 Con 5 en línea nace la estrella arcoíris, que se lleva todos los hoshis de un color.
✨ Junta dos poderes para efectos enormes.
🌠 Combina las estrellas fugaces rosas para subir el multiplicador de puntos.
🪨 A partir del nivel 4 aparecen rocas lunares, y desde el 6, hielo.

Cada nivel te da movimientos extra. ¿Hasta dónde llegarás? Supera tu récord y reta a tus amigos.

Gráficos, personajes y música originales.

## Imágenes (carpeta `store/`)
| Archivo | Para qué |
|---|---|
| `icono-1024.png` | Icono de la app (1024×1024) |
| `portada-1920x1080.png` | Imagen de portada / banner grande |
| `portada-1200x627.png` | Imagen para compartir / portada pequeña |
| `captura-1-menu.png`, `captura-2-partida.png`, `captura-3-record.png` | Capturas (1080×1920, vertical) |

Si Meta pide otro tamaño, se regeneran con `node tools/store.mjs` (cambiando las medidas en `tools/store.html`).
