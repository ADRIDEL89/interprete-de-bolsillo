# Intérprete de Bolsillo

Página web personal para seguir conversaciones en inglés en tiempo real: escucha, traduce al español y sugiere respuestas en inglés con pronunciación aproximada. Pensada para hispanohablantes que viven y trabajan en inglés.

## Modos

- Reunión: en cada pausa del interlocutor aparece una tarjeta con la traducción y 2 o 3 respuestas sugeridas con su pronunciación.
- Exposición: traducción corrida tipo subtítulos, con botón para copiar la transcripción completa.
- ¿Cómo digo…?: entrada en español que devuelve la frase en inglés con pronunciación.

## Fuentes de audio

- Teléfono (Chrome en Android): micrófono, para conversaciones presenciales.
- Computador (Chrome): botón «Escuchar la reunión del computador», que capta el audio de una pestaña (Meet, Zoom o Teams en el navegador) o de todo el sistema (Zoom o Teams instalados) sin usar el micrófono.

## Ajustes

- Tipo de conversación: colegio y día a día, reunión técnica o entrevista de trabajo; cambia el registro de las respuestas sugeridas.
- Perfil profesional y tema de la reunión: opcionales, para que las sugerencias encajen con la conversación.
- Motor: Claude Haiku (rápido, por defecto), Claude Sonnet o Claude Opus.

La clave API de Anthropic, el perfil y el tema se guardan únicamente en el almacenamiento local del navegador. La clave se envía solo a `api.anthropic.com`. Este repositorio no contiene ninguna clave ni dato personal.
