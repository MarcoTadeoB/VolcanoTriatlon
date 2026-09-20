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

## Cómo se adapta a ti

El plan no es fijo. De las marcas que metes en la pestaña **Marcas** (carreras y tests
de 5 K, 400 y 200 m de natación, 20′ en bici) salen tus ritmos, tu CSS de natación y tu
FTP, y con ellos cada sesión muestra a qué ritmo o a cuántos vatios hacerla. Cuando
mejoras una marca, todas las prescripciones se recalculan solas.

Además:

- El **volumen de la semana siguiente** sube o baja según lo que hayas cumplido las
  semanas anteriores, tu RPE medio, tus sensaciones y tus horas de sueño. Cada ajuste
  se explica en la app; las semanas que ya han empezado no se tocan.
- Los **metros seguidos** que toca intentar en el agua suben con tu récord.
- En el **gimnasio**, si la última sesión de ese ejercicio la cerraste con RIR ≥ 2 en
  todas las series, aparece el peso ya subido (2,5 kg, o 5 kg en los básicos de pierna).
- Los **hitos** se marcan solos en cuanto los datos los cumplen.
- Y también cambia **qué sesiones** tocan: quita las opcionales si llevas dos semanas
  por debajo del 75 %, añade una sesión de natación continua si vas por detrás del
  próximo hito de natación, y mueve de día una sesión que lleves tres semanas
  saltándote (si hay hueco libre en la plantilla; si no, te lo dice).

Nada de esto se aplica sin datos: una semana sin nada registrado cuenta como «no sé»,
no como un cero. Los dos motores —volumen y sesiones— se apagan por separado en
*Ajustes*, y los cambios solo entran en semanas que todavía no han empezado.

## El plan

30 semanas, del lunes 21/09/2026 al domingo 18/04/2027, en cuatro fases (Base,
Construcción, Específica y Taper) con semana de descarga cada cuarta semana y también la
del 21/12. Las plantillas de cada fase y la fecha de carrera se editan desde *Ajustes*.
