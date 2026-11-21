# Plantilla de prompt (acordada con Muse, 2026-11-20; cabeza calva en positivo + hoja de modelo como 2.ª imagen, 2026-11-21)

Cada clip se genera con DOS imágenes: 1) su imagen inicial de input/, 2) ../personaje/hoja-modelo.jpg como referencia obligada del personaje. Revisar antes que la imagen inicial no traiga pelo ni sombra a los lados de la cabeza.

Bloques fijos (CHARACTER, STYLE, FRAMING, END POSE, NO): se copian IDÉNTICOS en todos los clips.
Cambia por clip: Background, SETTING, ACTION, CAMERA.

Reglas: una sola acción (arranque 0-3 s, cambio 3-6 s, reacción 6-9 s, pose final 9-10 s); un solo movimiento de cámara;
imagen inicial = pose de arranque con la boca cerrada; objetos grandes con las dos manos; billetes/monedas en blanco;
sin letreros; máximo un personaje secundario lejos y desenfocado; nada de speaks/talks/shouts/sings/laughs.

```
## CLIP NN — nombre
Image: input/NN-nombre.jpg
Background: PLAIN — off-white | SETTING — [cuál]

CHARACTER (fixed, copy exactly in every clip):
Use ../personaje/hoja-modelo.jpg as the MANDATORY character reference for every frame (second reference image, after the starting image).
The same adult cartoon man in every frame: yellow skin, large PERFECTLY ROUND
black glasses (circles, never square), green argyle diamond-pattern sweater vest
over a white collared shirt, small brown notebook in the vest pocket, brown
trousers, brown shoes. His entire head is smooth bare yellow skin — top, sides
and back, like a yellow billiard ball. In side and three-quarter views the sides
of his head are the same bare yellow skin, with no hair above the ears, exactly
like the side view of the model sheet. Ageless simple cartoon face. Same face,
same proportions, same outfit, never changes.

STYLE (fixed):
Hand-drawn cartoon, soft shadows, subtle paper texture,
clean hand-drawn outline.

SETTING:
[Plain off-white solid background / escenario sin letreros]

FRAMING:
Vertical 9:16. Character in the lower two-thirds of the frame,
head below the top third. Top third is empty, clean space,
nothing enters it.

ACTION (one action only):
0-3s: [ya en movimiento desde el primer cuadro]
3-6s: [el cambio]
6-9s: [reacción exagerada: ojos, cejas, cuerpo; boca cerrada]
9-10s: holds the clean end pose, still.

CAMERA:
[UN movimiento: push-in / pull-back / tracking / static, he walks toward the camera]

END POSE:
In the last second he stops and holds the pose, camera stops,
clean centered frame, full body visible.

NO (fixed, copy exactly in every clip):
Silent video, no audio at all, no music, no sound effects,
no voice, no dialogue, no speech, no lip movement, mouth closed
at all times, character never speaks. No text, no letters,
no numbers, no logos, no watermarks, no extra characters.
No extra hands, no other people's hands or body parts; only his two hands appear.
```
