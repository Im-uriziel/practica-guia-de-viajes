# Memoria interactiva — Práctica 4: Conoce Valdemoro

Esta carpeta **no sustituye las versiones anteriores de la guía turística**. Contiene una **web nueva de presentación de la práctica**, basada en el PDF, con su proceso de creación y sus capturas originales.

## Publicación en GitHub Pages

1. Abre el repositorio `Im-Uriziel/Practica_web_pueblo` y entra en la rama `main`.
2. Sube **`index.html`**, los PNG y `practica_4_web_guia_de_viajes.pdf` a la **raíz** del repositorio (todos al mismo nivel).
3. **Conserva, sin cambiar nombres**, estos cuatro archivos que ya tienes publicados:
   - `valdemoro_webv1.html` — primera web, segunda etapa de la memoria.
   - `valdemoro_webv2.html` — correcciones y calendario, tercera etapa.
   - `valdemoro_webv3.html` — rediseño y fuentes, cuarta etapa.
   - `valdemoro_web.html` — web final con fotografías, quinta etapa.
4. En `Settings > Pages`, confirma que el origen de publicación sea `Deploy from a branch`, rama `main` y carpeta `/ (root)`.
5. Abre `https://im-uriziel.github.io/Practica_web_pueblo/` tras la publicación. Allí aparecerá **esta nueva memoria interactiva**, no la guía turística (que seguirá disponible mediante el botón «Ver las webs»).

## Capturas incluidas

Extraídas directamente de los elementos gráficos del PDF:

| Archivo | Contenido | Página PDF |
| --- | --- | --- |
| `prompt_1.png` | Primera idea/prompt | 4 |
| `prompt_2.png` | Segundo prompt / generación | 5 |
| `web_version_1.png` | Portada de primera web | 6 |
| `web_version_1_restaurantes.png` | Restaurantes primera web | 6 |
| `prompt_3.png` | Tercer prompt / correcciones | 7 |
| `web_version_2.png` | Nueva portada | 8 |
| `web_version_2_noticias.png` | Noticias | 8 |
| `web_version_2_calendario.png` | Calendario de fiestas | 9 |
| `prompt_4.png` | Cuarto prompt / fuentes oficiales | 10 |
| `web_version_3.png` | Portada renovada | 11 |
| `web_version_3_calendario.png` | Agenda / calendario | 11 |
| `prompt_5.png` | Quinto prompt / fotos reales | 12 |
| `web_version_4.png` | Portada final | 12 |
| `web_version_4_restaurantes.png` | Restaurantes y mapas finales | 13 |
| `web_version_4_ocio.png` | Ocio y lugares finales | 13 |
| `web_version_4_mapa.png` | Mapa general final | 14 |

**Si quieres sustituir una captura**, exporta tu imagen a PNG con el mismo nombre y súbela al repositorio, reemplazando la antigua. No hace falta modificar `index.html`.

## Funciones interactivas

- Selector desplegable de las cuatro webs publicadas.
- Cronología de cinco etapas con pestañas, navegación por flechas del teclado y capturas del prompt y resultado.
- Comparador de primera y última portada con deslizador.
- Galería filtrable por versión y ampliación de las capturas en un visor (teclas ←, → y Escape).
- Menú adaptado a móvil, barra de progreso y animaciones suaves al desplazarse.
- Preferencia del sistema `prefers-reduced-motion` respetada.

## Notas

- La **etapa 1 es la idea inicial**, no una web HTML; hay **cinco etapas** y **cuatro versiones web**.
- Los enlaces a las versiones son rutas relativas, por lo que los archivos deben conservar sus nombres en la misma carpeta de GitHub Pages.
- Las capturas reproducen el aspecto documentado en noviembre de 2026. Su contenido no implica que las noticias o calendarios sigan actualizados.
- Se han mantenido los nombres y enlaces de las versiones del repositorio original; esta memoria no introduce cambios en el contenido de dichas versiones.
