# Valeria — FiorDi, sin voz añadida

Se editó únicamente el archivo `Valeria .mov` compartido en Drive. `Referencia.mp4` se utilizó para estudiar ritmo, combinación tipográfica, etiquetas y collage; no se reutiliza su audio, voz, imágenes ni mensajes.

Formato: 1080 × 1920, 30 fps, 600 fotogramas (20 segundos). Se priorizan los planos de comida, la llegada de Valeria, el ambiente y un collage con imágenes extraídas de su propio material. La navegación repetitiva del menú se resume; el plano horizontal con bandas negras se recorta y se integra en el collage.

Estilo adaptado: títulos blancos de sans con acentos serif en cursiva, pequeñas etiquetas, collage crema con tarjetas inclinadas y detalles vino tinto. Los textos se colocan fuera del rostro; el brindis queda sin texto para conservar visibles la copa y la cara.

Voz: no se añade narración, TTS, doblaje ni diálogos del referente. El audio original de Valeria contiene silencio digital. La banda sonora final contiene solamente música instrumental original y ocho acentos sonoros discretos, a volumen moderado para que Valeria pueda colocar después su propia voz. No se inventan subtítulos de una narración aún no recibida.

Textos limitados a lo visible o a títulos editoriales: FiorDi, cocina internacional, sushi, pizza, ambiente y detalles. No se anuncian precios, descuentos, dirección, sucursal ni nombres específicos de platos no confirmados.

Tipografías: DM Sans y DM Serif Display Italic de Google Fonts (licencias OFL conservadas en `public/restaurante/`). Música original de 117 BPM; procedencia y generador en `MUSICA.md`. Efectos de la biblioteca recomendada de Remotion: whoosh, switch y mouse-click.

Composición editable `ValeriaFiorDi` en `src/RestaurantReel.tsx`; componentes en `src/restaurant/EditorialElements.tsx`. Abrir desde `/workspace/EDITODEVIDEOS/closet-reel` con `npm run dev -- --no-open --port=3000`.

El montaje está preparado para que la usuaria grabe su voz después. Si posteriormente entrega esa grabación, podrá sincronizarse y generar subtítulos fieles a su narración.

Validación final: TypeScript y ESLint pasaron. Se revisaron fotogramas del hook, llegada, collage, sushi y cierre para comprobar legibilidad, encuadres y posición de textos. El MP4 H.264/AAC completo se decodifica sin errores y conserva 600 fotogramas. Su audio se contrasta con la mezcla que contiene únicamente la música instrumental original y los ocho efectos: correlación superior a 0,995, sin saturación y sin pistas de voz.
