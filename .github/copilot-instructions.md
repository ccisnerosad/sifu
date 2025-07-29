# Copilot Instructions for Sifu Project

## Propósito y Arquitectura General
Este repositorio documenta la producción teatral "Sifu", centrada en la fusión de artes marciales, narrativa de videojuego y tragedia griega. El código base es principalmente documental, orientado a la planeación, ejecución y comercialización del espectáculo.

- **Estructura principal:**
  - `README.md`: Documento central con visión, concepto, equipo, plan de gira, cronograma y modelo de negocio. Es la referencia principal para cualquier agente y el contenido principal de la web.
  - `doc/`: Archivos Markdown que detallan niveles y el dossier del proyecto. Deben usarse como fuente para secciones narrativas y de estructura en la web.
  - `img/`: Carpeta reservada para recursos gráficos.
  - `index.html`: Página web estática generada con Tailwind CSS para presentar el dossier. Debe seguir las mejores prácticas de HTML y CSS, priorizando la adaptabilidad móvil y accesibilidad.

## Flujos y Convenciones Clave
- **No hay código ejecutable ni scripts de automatización.**
- **Toda la lógica y estructura está en Markdown y HTML.**
- **Las convenciones de formato siguen el estilo de guion teatral y dossier de producción.**
- **Los nombres de roles, recintos y fases son específicos y deben respetarse en cualquier automatización o generación de contenido.**
- **Las cifras, cronogramas y ubicaciones son críticas para la planeación y deben preservarse fielmente.**
- **La web debe ser responsiva y accesible, usando clases de Tailwind como `sm:`, `md:`, `lg:` y asegurando buen contraste y legibilidad.**
- **El contenido de la web debe provenir de `README.md` y `doc/*`, respetando la narrativa y estructura original.**

## Ejemplos de patrones relevantes
- Listados de equipo y roles en formato de viñetas, con descripciones detalladas.
- Cronogramas y presupuestos en secciones separadas, usando encabezados y subencabezados claros.
- Referencias a locaciones y recintos reales (teatros, ciudades) para giras y presentaciones.
- Modelo de negocio con fuentes de ingreso y análisis de rentabilidad.
- Uso de tarjetas, grids y componentes visuales para presentar información clave en la web.
- Gráficos interactivos para finanzas (ejemplo: Chart.js en `index.html`).

## Recomendaciones para agentes
- Priorizar la edición y generación de contenido en `README.md`, `doc/` y `index.html`.
- Mantener la coherencia narrativa y el formato Markdown y HTML.
- No agregar código, scripts ni automatizaciones salvo que se solicite explícitamente.
- Cualquier integración o automatización debe documentarse en `README.md`.
- Referenciar siempre los nombres y convenciones tal como aparecen en los documentos fuente.
- Garantizar que la web sea responsiva y accesible en móviles y escritorio.

## Ejemplo de edición
- Para agregar una nueva ciudad al plan de gira, seguir el formato de viñeta y descripción como en la sección "Gira Nacional".
- Para actualizar el presupuesto, modificar la sección correspondiente y mantener el desglose porcentual.
- Para actualizar la web, extraer el contenido de `README.md` y `doc/*` y presentarlo usando componentes visuales adaptativos de Tailwind CSS.

---

Si alguna sección es ambigua o falta información relevante, solicita retroalimentación antes de proceder con cambios automáticos.
