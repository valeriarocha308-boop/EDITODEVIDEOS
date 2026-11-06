# Música original — versión energética

`music-energetic-v2.wav` es una composición instrumental nueva, sintetizada localmente para la revisión del reel. No contiene voces ni grabaciones o muestras de terceros.

- Duración: 55 segundos, estéreo, 44,1 kHz, PCM24.
- Tempo: **124 BPM**.
- Estilo: pop / house / funk moderno, con bombo a negras desde el inicio, palmas en contratiempo de caja, hi-hats, bajo sincopado, acordes cortos y arpegio discreto.
- Armonía original: Am9 / Fmaj9 / Cmaj9 / G6/9.
- Cambios de energía: apertura rítmica inmediata, capa de arpegio después de cuatro compases, percusión más densa y rellenos cada ocho compases, dos descansos breves.
- No utiliza muestras o bibliotecas musicales externas; no requiere atribución a terceros.

Generador: `generate_music_v2.py`, con NumPy y SoundFile. El nivel final se ajusta con FFmpeg mediante normalización en dos pasadas para un objetivo de −18 LUFS y un techo de pico verdadero de −5 dBTP, antes de la mezcla debajo de la voz.

Medición final del archivo entregado: **−18,08 LUFS integrados**, **−5,00 dBTP**, LRA 1,3 LU. Archivo final verificado por FFmpeg, 55,000 s.
