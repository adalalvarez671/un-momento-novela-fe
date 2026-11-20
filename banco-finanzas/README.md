# Banco de clips — Observador Financiero

Proyecto SEPARADO de la novela (`proyectos/`). Banco de clips cortos del personaje amarillo para usar en la edición
de videos de finanzas personales (TikTok y Facebook).

- Cada clip es independiente, dura exactamente 10 s, vertical 9:16.
- Sin audio de ningún tipo: sin música, sin efectos, sin voz, sin labios. El audio y los textos se agregan en la edición.
- El personaje siempre está haciendo una acción. Tercio de arriba libre para textos.
- Mezcla: ~40 % fondo liso blanco hueso, ~60 % escenarios.

Estructura:
```
banco-finanzas/
  personaje/        hoja-modelo.jpg, frente.jpg, tres-cuartos.jpg
  PLANTILLA.md      plantilla de cada prompt
  lote-NN-tema/
    prompts.md      primera línea: STATUS: READY_FOR_MUSE
    input/          01-nombre.jpg … (máx. 6 por lote)
    output/         01-nombre.mp4 … (mismo nombre que su imagen)
```
