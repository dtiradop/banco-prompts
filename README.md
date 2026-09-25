# Banco de Prompts IA

Organizador de prompts de marketing para estudiantes del **Curso de Creación de Contenido con IA** de [Daniela Tirado Studio](https://danielatirado.com).

Trae **56 prompts listos para usar** en 15 categorías. Cada estudiante los busca, los copia, los adapta a su marca y guarda los suyos.

## Qué incluye

| Categoría | Para qué sirve |
|---|---|
| **Pauta** | Meta Ads, TikTok Ads, Google Ads, ángulos de venta, UGC, segmentación, retargeting, métricas, testeo y escalado |
| **Hooks** | Primeras frases que detienen el scroll |
| **Estrategia** | Pilares, calendario, fechas comerciales, buyer persona |
| **Reels / Guiones** | Guiones de video corto por formato |
| **Copywriting** | Captions, carruseles, copy de venta, testimonios |
| **Historias** | Secuencias con encuestas, lanzamientos, detrás de cámaras |
| **Respuestas DM** | Precio, seguimiento, reclamos |
| **Email marketing** | Bienvenida, carrito abandonado, asuntos |
| **WhatsApp** | Difusión y guion de venta por chat |
| **Lanzamientos** | Plan de lanzamiento y promociones con urgencia |
| **Branding** | Propuesta de valor, competencia, bio de Instagram |
| **Web y SEO** | Páginas de producto, blog, landing pages |
| **Influencers** | Contacto y brief para creadores |
| **Imágenes IA** | Fotos de producto, fondos, mockups |
| **Análisis** | Auditoría, voz de marca, reportes para clientes |

## Cómo se usa

1. **Busca** por palabra o **filtra** por categoría.
2. Toca **Copiar** y pega el prompt en ChatGPT, Claude o Gemini.
3. Reemplaza lo que está entre `[CORCHETES]` con los datos de tu marca.
4. Marca con **★** los que más uses y activa **Solo favoritos** para verlos juntos.
5. Crea tus propios prompts con **+ Nuevo prompt**, o ajusta cualquiera con **Editar**.

### Dónde se guarda tu información

Tus cambios (favoritos, ediciones y prompts nuevos) se guardan **solo en tu navegador**. No se comparten con nadie y no los ve nadie más.

Se pierden si:

- borras los datos del navegador, o
- cambias de computador o de celular.

**Para no perderlos:**

- Usa **Exportar backup** y guarda ese texto en una nota o archivo.
- Para recuperarlos, usa **Importar backup**. Puedes pegar el texto o subir el archivo `.json`.

**Restaurar originales** vuelve al banco inicial y borra tus cambios.

## Tecnología

Es un solo archivo `index.html` con HTML, CSS y JavaScript. No usa frameworks, no necesita instalar nada y no requiere un paso de compilación.

- Tipografías: Source Code Pro (títulos) y Poppins (textos), desde Google Fonts.
- Datos: `localStorage` del navegador.
- Modo claro y oscuro automático.
- Adaptado para celular.

## Publicarlo

**Vercel**
1. En [vercel.com](https://vercel.com) ve a **Add New → Project**.
2. Importa este repositorio y dale a **Deploy**.

**GitHub Pages**
1. En el repositorio ve a **Settings → Pages**.
2. En *Branch* elige `main` / `root` y guarda.

**En local**
Abre `index.html` directamente en el navegador.

## Editar los prompts base

Los prompts iniciales están en el arreglo `SEED`, dentro de `index.html`. Cada prompt sigue este formato:

```js
["Categoría", "Título", "Texto del prompt con [VARIABLES]", "etiqueta1, etiqueta2"]
```

- **Prompts nuevos:** a quien ya tenía el banco abierto le aparecen automáticamente, sin perder sus cambios.
- **Colores de categoría:** se asignan en el objeto `CATCOL`.

---

Hecho por **Daniela Tirado Studio**: diseño y desarrollo web que conecta personas, ideas y marcas con el mundo digital.
