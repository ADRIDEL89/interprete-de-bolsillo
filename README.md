# Intérprete de Bolsillo

Página web personal para interpretar conversaciones en inglés en tiempo real: escucha con el micrófono del navegador, traduce al español y sugiere respuestas en inglés con pronunciación aproximada. Pensada para reuniones escolares y trámites del día a día de una familia hispanohablante en Baréin.

## Modos

- Reunión: en cada pausa del interlocutor aparece una tarjeta con la traducción y 2 o 3 respuestas sugeridas con su pronunciación.
- Exposición: traducción corrida tipo subtítulos, con botón para copiar la transcripción completa.
- ¿Cómo digo…?: entrada en español que devuelve la frase en inglés con pronunciación.

## Uso

Se sirve con GitHub Pages y se abre en Chrome (Android). En Ajustes se pega una clave API de Anthropic, que se guarda únicamente en el almacenamiento local del navegador y se envía solo a `api.anthropic.com`. Este repositorio no contiene ninguna clave ni dato personal.

El motor por defecto es Claude Haiku (rápido y de costo mínimo); puede cambiarse a Claude Opus desde Ajustes.
