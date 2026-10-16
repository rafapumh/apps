# rpuertoumh.github.io

Repositorio público con una selección de aplicaciones web (HTML de archivo único, sin build ni backend) pensadas para el aula. Cada app vive en su propia carpeta y se publica automáticamente vía GitHub Pages en:

`https://rpuertoumh.github.io/<categoría>/<app>/`

Las claves de API de los proveedores de IA (Anthropic, OpenAI, Google, fal.ai, etc.) nunca van incrustadas en el código: cada usuario introduce la suya y se guarda únicamente en el `localStorage` de su propio navegador.

## Apps incluidas

### Moda (`moda/`)

- **[GenImOda](moda/genimoda/)** — Generador de imágenes de moda (versión para alumnos de GenImOd). Genera imágenes de moda con Claude, OpenAI o Gemini + FLUX, con modelos y parámetros limitados por el profesor.
- **[GenOutFitS](moda/genoutfits/)** — Generador de outfits con IA (versión para alumnos de GenOutFit). A partir de la foto de una prenda, genera con IA los prompts y las imágenes de un outfit completo a juego.
- **[GenPatModa](moda/genpatmoda/)** — Generador de patrones de corte de moda (versión para alumnos de GenPatMod). Genera patrones de corte en SVG a partir de una idea y los exporta a PDF A4.

## Añadir más apps

Para añadir una nueva app, crea una carpeta `<categoría>/<nombre-app>/index.html` autocontenida y enlázala desde este README. GitHub Pages la publicará automáticamente al hacer push a `main`.
