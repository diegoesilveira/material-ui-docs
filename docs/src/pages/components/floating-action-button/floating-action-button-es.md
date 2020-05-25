---
title: Componente de React Fab
components: Fab
---

# Botón de acción flotante

<p class="description">Un botón de acción flotante (FAB) realiza la acción principal, o la más común, en una pantalla.</p>

## Botón de acción flotante

Un [botón de acción flotante](https://material.io/design/components/buttons-floating-action-button.html)aparece delante de todo el contenido de la pantalla, típicamente como una forma circular con un icono en su centro. Los FABs vienen en dos tipos: regulares y extendidos.

Sólo usa un FAB si es la forma más adecuada de presentar la acción principal de una pantalla.

Se recomienda solo un botón flotante por pantalla para representar la acción más común.

{{"demo": "pages/components/floating-action-button/FloatingActionButtons.js"}}

## Size

Use the `size` prop for larger or smaller floating action buttons.

{{"demo": "pages/components/floating-action-button/FloatingActionButtonSize.js"}}

## Animation

El botón de acción flotante aparece en la página animado como un pedazo de material en expansión, por defecto.

Un botón de acción flotante que aparece en varias páginas laterales (como páginas en pestañas) debe desaparecer por un momento, y luego aparecer de nuevo si su acción cambia.

La transición Zoom se puede usar para lograr esto. Ten en cuenta que ya que las animaciones de salida y de entrada son desencadenados al mismo tiempo, usamos `enterDelay` para permitir que termine la animación del Botón de Acción Flotante saliente antes de que entre el nuevo.

{{"demo": "pages/components/floating-action-button/FloatingActionButtonZoom.js", "bg": true}}
