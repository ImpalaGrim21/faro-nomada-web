# Faro Nómada

[Jugar en el navegador](https://impalagrim21.github.io/faro-nomada-web/)

Orienta un deflector físico, distribuye luz entre impulso y protección y prepara un faro ambulante para restaurar estaciones. La campaña reúne tres zonas, doce misiones y veintidós tramos, con piezas, oficios, taller y apariencias.

## Cómo jugar

Pulsa **Jugar** para cargar el motor y habilitar el sonido. En **Preparar ruta**, lee el pronóstico, escoge trayecto y orienta el deflector con el ratón, la pantalla táctil o el deslizador. Pulsa **Liberar luz** y sigue ajustándolo durante la emisión. Confirma el reparto, elige una pieza o conserva tu construcción y completa el viaje. **Restaurar estación** confirma el depósito de premios.

La guía y los ajustes están dentro del juego. Se puede modificar volumen, contraste, movimiento, orientación asistida y mano de control.

## Requisitos y guardado

Usa un navegador con WebAssembly y WebGL 2. La exportación de Godot 4.7.2 utiliza un solo hilo y funciona en GitHub Pages sin encabezados especiales de aislamiento. La primera carga descarga aproximadamente 50 MB antes de la compresión HTTP; las siguientes cargas aprovechan la caché del navegador.

El progreso se guarda en el almacenamiento local del sitio, en este navegador y dispositivo. Espera unos segundos después de confirmar una operación antes de cerrar la pestaña. Borrar los datos del sitio, bloquear almacenamiento o utilizar navegación privada puede eliminar o impedir el guardado. No hay cuenta online ni sincronización entre dispositivos.

## Publicación

Este repositorio independiente contiene la exportación web del juego y sus avisos de terceros. GitHub Pages publica la raíz de la rama `main`; `.nojekyll` conserva los archivos estáticos. Para actualizarlo, vuelve a exportar desde el proyecto Godot y sustituye juntos los archivos `index.*`, conservando sus nombres. El proyecto editable y los documentos de investigación no forman parte de este repositorio.

## Licencias y procedencia

El motor Godot se distribuye bajo MIT; sus avisos se encuentran en [licenses/Godot-LICENSE.txt](licenses/Godot-LICENSE.txt) y [licenses/Godot-COPYRIGHT.txt](licenses/Godot-COPYRIGHT.txt). La tipografía Space Grotesk utiliza [SIL Open Font License](licenses/Space-Grotesk-OFL.txt).

El contenido, las escenas, la campaña, el arte y la música fueron creados para Faro Nómada. Esta publicación permite acceder al juego; no concede una licencia de reutilización de sus recursos originales. Las licencias expresas de terceros mantienen sus propios términos.
