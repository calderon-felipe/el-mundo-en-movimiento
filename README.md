# El mundo en movimiento — Los 5 destinos que todos eligen

**Materia:** Visualización de Datos, UTDT, 2026
**Proyecto final:** narrativa visual interactiva (scrollytelling) basada en datos

---

## Descripción

Proyecto final de la materia: una narrativa visual interactiva tipo
**scrollytelling** (el contenido se revela a medida que el lector hace scroll)
sobre los destinos turísticos más visitados del mundo, con foco en cinco
ciudades: **Bangkok, París, Londres, Dubái y Singapur**.

Combina texto periodístico con visualizaciones hechas a medida en HTML, CSS y
JavaScript (Chart.js, D3.js y TopoJSON para mapas), a partir de un dataset
propio armado con rankings de ciudades más visitadas de distintas fuentes
(Euromonitor y Mastercard Global Destination Cities Index) entre 2015 y 2025 —
incluyendo la caída por la pandemia en 2020 y el rebote posterior.

## Archivos

- `index.html` — la página completa (autocontenida: HTML, CSS y JS en un solo
  archivo, con librerías cargadas desde CDN)
- `data/ciudades_mas_visitadas_mundo.xlsx` — dataset con una hoja por año
  (2015 a 2025), rankings, crecimiento interanual y gasto turístico
- `docs/enunciado.pdf` — consigna original del proyecto final

## Cómo verlo

Simplemente abrí `index.html` en cualquier navegador (no necesita servidor ni
instalación, es una página estática).

También se puede publicar gratis con **GitHub Pages**: en la configuración del
repo, activar Pages apuntando a la rama principal, y quedará disponible en una
URL tipo `https://tu-usuario.github.io/el-mundo-en-movimiento/` — ideal para
linkearlo directamente desde el CV en vez de pedirle a quien lo lea que
descargue el archivo.
