# Volcano Tri

App web de una sola página para seguir un plan de entrenamiento de triatlón olímpico
(1,5 km natación · 40 km bici · 10 km carrera) combinado con gimnasio.

- **Todo está en `index.html`**: HTML, CSS y JavaScript vanilla. No hay build ni servidor.
  La única dependencia externa es Chart.js, cargada desde CDN (si no hay conexión, la app
  funciona igual y solo se ocultan los gráficos).
- **Los datos viven en el `localStorage` del navegador.** No se envía nada a ningún sitio.
  Usa *Ajustes → Exportar JSON* para hacer copias de seguridad y pasar los datos entre el PC
  y el móvil.

## Cómo usarla

Abre `index.html` con doble clic (Chrome, Edge o Firefox). Para tenerla a mano en el móvil,
súbela a cualquier alojamiento estático y añádela a la pantalla de inicio.

## El plan

30 semanas, del lunes 21/09/2026 al domingo 18/04/2027, en cuatro fases (Base,
Construcción, Específica y Taper) con semana de descarga cada cuarta semana y también la
del 21/12. Las plantillas de cada fase y la fecha de carrera se editan desde *Ajustes*.
