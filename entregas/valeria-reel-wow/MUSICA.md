# Música y efectos originales — Reel WOW

`public/reel-wow/music.mp3` es una composición nueva de **44 segundos a 132 BPM**, sintetizada para este montaje. Tiene bombo y palmas definidos desde el inicio, bajo sincopado con respuestas de octava, acordes funk cortos, pequeños plucks en registro medio y variaciones de percusión cada cuatro u ocho compases. El arreglo deja espacio a la voz densa del vlog; no hay voces ni melodía aguda continua.

Todo el material sonoro se creó localmente con osciladores y ruido filtrado. No contiene muestras de terceros, audio de referencia ni pistas reutilizadas de los reels anteriores. No requiere atribución a bibliotecas externas.

Efectos originales, todos WAV mono PCM24 a 44,1 kHz, pico aproximado −8 dBFS:

- `sfx/pop.wav`: 0,16 s, acento de aparición.
- `sfx/boing.wav`: 0,44 s, reacción elástica ligera.
- `sfx/success.wav`: 0,58 s, confirmación musical breve de tres notas.
- `sfx/soft-error.wav`: 0,33 s, error/reacción suave descendente, sin voz.

Reproducción: `/workspace/scratch/closet-tools/bin/python docs/reel-wow/generate_music.py`. Usa NumPy, SoundFile y FFmpeg. La música se normaliza en dos pasadas hacia −18 LUFS, con margen de techo para el códec MP3; `music-measurements.json` conserva la medición final. Ajustar volumen y fundido final según la duración del reel, sin depender del final de la pista a los 44 s.

Medición final del MP3: **−18,17 LUFS**, **−5,37 dBTP**, LRA **2 LU**. Archivo estéreo a 44,1 kHz y 192 kbit/s; contenido musical de 44 s (el contenedor MP3 incluye su pequeño relleno técnico del códec).
