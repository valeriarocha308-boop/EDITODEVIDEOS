# Revisión V3 — frase completa e inicio gráfico

- Se recupera íntegra la frase «y todo eso tiene que estar optimizado en tu biografía, en el perfil». El fragmento de contacto y biografía ahora conserva el original desde el fotograma 1222 hasta el 1394 (40,73–46,47 s); «perfil» termina aproximadamente a 46,32 s, antes del corte.
- Duración nueva: 1433 fotogramas a 30 fps, 47,77 s. Se desplazaron un segundo las capas posteriores para mantener voz, imágenes, gráficos y efectos sincronizados.
- Se retiraron los b-rolls del móvil y el portátil de la primera parte. Los reemplazan tarjetas cinéticas con iconos para NEGOCIO, SERVICIO y REDES SOCIALES; un gran 3 con las tres preguntas y un gráfico de TU DIFERENCIA.
- Se añaden palabras destacadas y acentos sonoros asociados a su pronunciación, incluidos TU PERFIL, PROBLEMA, CONTACTARTE, BIOGRAFÍA y EN EL PERFIL. Se mantiene libre la zona del rostro y se reserva otra zona para los subtítulos.
- Se conservan vino tinto, crema y rosa suave, la música de 124 BPM aprobada y el b-roll posterior de notas.

Archivos editables: `src/marketing/OpeningGraphics.tsx`, `src/marketing/SoundDesign.tsx`, `src/ReelMarketing.tsx`. Las decisiones de corte y los subtítulos fuente continúan en `src/marketing/`.

Validación final: ESLint y TypeScript correctos; revisión visual de las tarjetas de inicio, las tres claves, tu diferencia y EN EL PERFIL. La transcripción de comprobación del segmento recuperado reconoce íntegra la frase «y todo eso tiene que estar optimizado en tu biografía, en el perfil». El MP4 completo se decodifica sin errores, contiene 1433 fotogramas y su audio coincide con la mezcla de referencia (correlación 0,9997). Se aplicó −1,5 dB de margen al máster sin recodificar el video; pico de muestra final −1,58 dBFS, sin muestras saturadas.
