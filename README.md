# Tutor de Realidad Nacional

Asistente de estudio con IA para la asignatura **Realidad Nacional**, carrera de Medicina, 3.er nivel, Universidad Técnica de Ambato (ciclo julio–diciembre 2026).

Incluye:

- **Tutor IA** con tres modos: Explícame, Guíame paso a paso (socrático) y Evalúame.
- **Contenidos por semana** (semanas 1 a 4): conceptos clave, cadenas causales, tablas, casos y actividades.
- **Talleres PAE 1 a 4**: objetivo, instrucciones y preguntas de autoevaluación con retroalimentación de la IA.
- **Autoevaluación**: 19 preguntas de opción múltiple y generación de preguntas nuevas con IA.
- **Fichas de conceptos** para repaso.

Es un solo archivo (`index.html`), sin servidor ni base de datos.

## Publicar en GitHub Pages (docente)

1. Inicie sesión en [github.com](https://github.com) y cree un repositorio nuevo, **público**, por ejemplo `tutor-realidad-nacional`.
2. En el repositorio, pulse **Add file → Upload files**, arrastre `index.html`, `README.md`, `.nojekyll` y la carpeta `assets`, y pulse **Commit changes**.
3. Vaya a **Settings → Pages**. En **Source** elija **Deploy from a branch**, rama `main`, carpeta `/ (root)`, y pulse **Save**.
4. Espere 1 a 2 minutos. La URL quedará así: `https://SU-USUARIO.github.io/tutor-realidad-nacional/`
5. Comparta esa URL en el aula virtual.

Para actualizar el contenido, edite `index.html` en GitHub y confirme el cambio; la página se actualiza sola en unos minutos.

## Activar la IA (estudiantes)

Cada estudiante usa su propia clave gratuita de Google Gemini:

1. Entrar a [aistudio.google.com/apikey](https://aistudio.google.com/apikey) con una cuenta de Google.
2. Pulsar **Create API key** y copiar la clave.
3. En el tutor, pegarla en el panel **Conectar la IA** y pulsar **Guardar y probar**.

La clave se guarda solo en el navegador del estudiante y se envía únicamente a Google. No escriba datos personales ni de pacientes en el chat.

## Notas

- El tutor está instruido para no redactar informes completos: orienta, hace preguntas y da retroalimentación.
- Las cifras y artículos de ley deben verificarse en fuentes oficiales (INEC, MSP, OPS/OMS, Constitución 2008, MAIS-FCI).
- Los logos están en la carpeta `assets/`; súbala junto con `index.html`.
- Si la página se abre dentro de claude.ai, usa automáticamente Claude en lugar de Gemini.
