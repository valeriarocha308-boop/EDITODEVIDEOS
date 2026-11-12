# Valeria · vlog de profesora

Edición vertical de 1080 × 1920 a 30 fps, realizada con Remotion. Duración final: **50,133 segundos**.

Se conserva la voz original a velocidad normal y en su orden. Se retiran únicamente tres silencios comprobados: 23,8667–24,0667 s; 24,4333–24,7667 s; y 46,7333–47,0667 s de la fuente. Suman 26 fotogramas, equivalentes a 0,8667 segundos. Se conservan las repeticiones, comentarios espontáneos y la acción final con las gafas. Los intervalos dudosos no se recortan.

Subtítulos blancos con respaldo oscuro discreto, situados debajo del rostro. La frase «Siento que esta blusa me hace ver gorda» se transcribe exactamente como confirmó la autora, sin añadir énfasis gráfico. Los cambios de encuadre, títulos animados y gráficos de apoyo mantienen el ritmo sin acelerar ni cortar palabras. Se utilizan los planos de apoyo del propio video. Los nombres y participantes visibles en las pantallas de clase se difuminan.

Música instrumental original de 124 BPM por debajo de la voz y efectos breves en cambios de plano y palabras destacadas. Acentos de color vino tinto; la letra de los subtítulos permanece blanca. No se añade voz en off.

Fuente: archivo de Google Drive facilitado por la autora, 51 segundos; se conserva sin modificar. El proyecto editable está en `src/VlogNov12.tsx` y `src/vlog/`. El montaje y los subtítulos se generan desde `scripts/build-vlog-nov12.py`; los subtítulos separados, desde `scripts/export-vlog-captions.mjs`. `edit-decisions.json` registra los tramos retenidos y los efectos.

El SRT acompaña al MP4, que ya incluye los subtítulos incrustados.

Verificación: 1.504 fotogramas H.264 y audio AAC estéreo; decodificación completa sin errores. Los 138 intervalos de palabras aparecen una vez y en orden. El audio exportado coincide con una referencia de montaje independiente con correlación superior a 0,9996. El ajuste final de volumen de −1 dB deja el pico verdadero en −2,0 dBFS y el volumen integrado en −17,0 LUFS. No se modifica la velocidad de la voz ni se recortan palabras.
