# Proyector Vigía

Planificador geo-espacial *offline-first* para videovigilancia, radio y planificación 5G.

## Módulos
- Video: límites OSM/Nominatim, red vial/ferrov., POIs, proyección por niveles, mezcla por tipos, exports CSV/KML/KMZ.
- Radio: ubicación, topografía (SRTM/terrarium cuando esté habilitado), enlaces, visibilidad simbólica.
- 5G: colocación de celdas, capas de torres, cobertura aproximada y exportes.

## Dev rápido
Abrir `index.html` o servir localmente:
```bash
python -m http.server 8000
# o
npx serve
