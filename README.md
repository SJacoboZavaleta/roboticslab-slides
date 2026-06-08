# RoboticsLab Slides Template

Plantilla Quarto / Markdown para presentaciones de congresos internacionales, simposios, presentaciones de papers, charlas técnicas cortas y resultados experimentales.

Esta plantilla está pensada para presentaciones de Robótica, Automatización y Bioingeniería afiliadas al RoboticsLab de la Universidad Carlos III de Madrid.

## Qué incluye

- `template.qmd`: plantilla base para diapositivas Quarto
- `template.html`: layout personalizado para presentaciones
- `_extensions/`: complementos de Reveal.js y soporte de Quarto
- `assets/`: logos, fondos y figuras para la presentación
- `template_files/`: dependencias y recursos de Quarto

## Instalación

Reemplaza `<github-organization>` con tu organización o usuario de GitHub:

```bash
quarto use template <github-organization>/roboticslab-slides
```

## Uso

1. Copia `template.qmd` como punto de partida.
2. Edita los metadatos `title`, `author`, `date` y el resto del contenido.
3. Añade secciones específicas para:
   - congresos internacionales
   - simposios
   - presentaciones de papers
   - charlas técnicas cortas
   - resultados experimentales
   - robótica, automatización y bioingeniería
4. Renderiza la presentación con:

```bash
quarto render template.qmd
```

## Personalización

- Ajusta colores, fuentes y estilo en `custom.scss`.
- Añade gráficos, tablas y resultados experimentales en `assets/figures`.
- Modifica `template.html` si quieres cambiar la estructura o el diseño.

## Licencia

Esta plantilla se distribuye bajo la licencia MIT. Consulta `LICENSE` para más detalles.
