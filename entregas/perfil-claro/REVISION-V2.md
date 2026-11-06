# Revisión V2 — vino tinto y más energía

Cambios solicitados por la usuaria: sustituir el verde por vino tinto, música más dinámica y efectos de sonido.

- Acentos de vino tinto `#7A1738`, crema `#F5F2E9` y rosa suave `#F0C5CF`. Se armonizaron también los antiguos acentos azules. Se conservó contraste con texto claro sobre vino y rosa suave sobre fondos oscuros.
- Composición musical nueva de 124 BPM, estilo house/funk instrumental. Bombo desde el inicio, palmas, bajo sincopado, acordes rítmicos, arpegio y rellenos. Música premezcla a −18,08 LUFS y −5 dBTP, bajo la voz a volumen 0,34.
- Catorce efectos sincronizados con entradas de títulos, cambios de b-roll, filas del ejemplo de biografía y cierre. Las capas se pueden editar individualmente en `src/marketing/SoundDesign.tsx`.
- Se conservan los 1403 fotogramas, los once fragmentos de voz, los b-rolls y los subtítulos. No se altera el contenido hablado.

Efectos descargados de la biblioteca recomendada en la documentación de Remotion:

- https://remotion.media/whoosh.wav
- https://remotion.media/switch.wav
- https://remotion.media/mouse-click.wav
- https://remotion.media/ding.wav

Procedencia de la música y generador: `MUSICA-V2.md` y `generate_music_v2.py`. Los b-rolls conservan la procedencia documentada en `BROLL.md`.

Comprobaciones previas a exportación: ESLint y TypeScript, fotogramas de inicio/biografía/fricción, mezcla completa sin muestras saturadas; pico de muestra −0,696 dBFS e integrado aproximado −16 LUFS. No se modificó configuración del entorno.
