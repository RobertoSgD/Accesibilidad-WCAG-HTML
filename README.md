# PROMPT

Modifica este código HTML para que cumpla con los estándares de accesibilidad WCAG 2.2 (WAI) en nivel AA y, opcionalmente, AAA. Asegúrate de:

1. **Especificar el idioma de la página web** con `lang="es"` en la etiqueta `<html>`.
2. **Añadir atributos ARIA adecuados** en formularios, botones, enlaces e imágenes.
3. **Usar etiquetas semánticas HTML5** como `<header>`, `<main>`, `<section>`, `<article>` en lugar de `<div>` genéricos.
4. **Incluir descripciones significativas** en los atributos `alt` de todas las imágenes.
5. **Asegurar jerarquía correcta de encabezados** (`<h1>` para títulos principales, `<h2>`, `<h3>` para subsecciones).
6. **Garantizar accesibilidad en formularios**, asociando etiquetas `<label>` correctamente con los inputs.
7. **Implementar accesibilidad en la navegación por teclado**, asegurando que todos los elementos interactivos sean accesibles con `Tab` y tengan `:focus` visible.
8. **Asegurar un contraste de colores suficiente** para el texto y los fondos.
9. **Agregar descripciones accesibles** en enlaces con `aria-label` cuando el texto del enlace sea ambiguo (ejemplo: "haz clic aquí").
10. **Verificar que los mensajes de error y validación en formularios sean accesibles**, utilizando `aria-describedby`.
11. **Mejorar la experiencia de usuario** mediante roles adecuados y puntos de referencia accesibles (`role="navigation"`, `role="banner"`, etc.).

Genera código HTML optimizado que cumpla con estos requisitos y mantenga una estructura clara y limpia.



# Accesibilidad-WCAG-HTML

Proceso de Desarrollo del Prompt para Mejorar la Accesibilidad en HTML (WCAG 2.2)
1. Análisis del Problema.
   
El objetivo principal era crear un prompt efectivo para asistentes de programación como GitHub Copilot que transforme código HTML estándar en un código accesible según las normativas WCAG 2.2 (WAI), asegurando al menos el nivel AA y, opcionalmente, nivel AAA.


Para ello, se identificaron los principales problemas de accesibilidad en los archivos index1.html, index2.html e index3.html:


* Uso de div en lugar de etiquetas semánticas como header, main, section.

* Falta de etiquetas alt en imágenes.

* Formularios sin etiquetas label.

* Tablas sin encabezados th.

* Botones sin aria-label o texto significativo.

* Enlaces sin contexto accesible.

* Falta de roles ARIA para navegación.

* Problemas de contraste y navegación por teclado.


Lista detallada de cambios que el asistente debe realizar:

- Especificar el idioma de la página web con lang="es" en la etiqueta html.
- Añadir atributos ARIA (aria-label, role, aria-describedby).
- Usar etiquetas semánticas (header, nav, main, section).
- Asegurar textos alternativos descriptivos en imágenes (alt="").
- Corregir la jerarquía de encabezados h1, h2, h3.
- Mejorar formularios con label y aria-describedby.
- Garantizar accesibilidad por teclado (tabindex, focus).
- Ajustar contraste de colores.
- Incluir roles de navegación (role="navigation", role="banner").

# Accessibility-WCAG-HTML
Development Process of the Prompt to Improve HTML Accessibility (WCAG 2.2)

Problem Analysis
The main objective was to create an effective prompt for programming assistants like GitHub Copilot that transforms standard HTML code into accessible code according to WCAG 2.2 (WAI) guidelines, ensuring at least Level AA and optionally Level AAA.

To achieve this, the main accessibility issues were identified in the files index1.html, index2.html, and index3.html:

- Use of div instead of semantic tags like header, main, section.
- Missing alt attributes in images.
- Forms without label tags.
- Tables without th headers.
- Buttons without aria-label or meaningful text.
- Links without accessible context.
- Missing ARIA roles for navigation.
- Contrast issues and keyboard navigation problems.

Detailed List of Changes the Assistant Should Make:

- Specify the language of the webpage with lang="es" in the <html> tag.
- Add ARIA attributes (aria-label, role, aria-describedby).
- Use semantic tags (header, nav, main, section).
- Ensure descriptive alternative text for images (alt="").
- Correct header hierarchy (h1, h2, h3).
- Improve forms with label and aria-describedby.
- Ensure keyboard accessibility (tabindex, focus).
- Adjust color contrast.
- Include navigation roles (role="navigation", role="banner").

Capturas

Index 1 :

original: 
![IND1SIN](https://github.com/user-attachments/assets/e0cf28ad-ff11-475a-9efd-0e14607cfac4)

modificado:
![IND1CON](https://github.com/user-attachments/assets/bbbc1876-5133-49b7-aee2-4a7c34a68c3d)

Index 2 :

original:
![IND2SIN](https://github.com/user-attachments/assets/8f0afb0c-b3be-45b6-a040-08a9e8164e4d)

modificado:
![IND2CON](https://github.com/user-attachments/assets/184a00a4-04fa-462d-b44b-7c0e6a83aacc)

Index 3 :

original:
![IND3SIN](https://github.com/user-attachments/assets/e69c7f01-d83b-4481-becd-25c4b496b25d)

modificado:
![IND3CON](https://github.com/user-attachments/assets/781d1d4e-1c0c-45be-87dd-70134fb99ab2)

