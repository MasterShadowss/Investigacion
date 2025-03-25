# Investigacion
Que Aprendi
# Explicación de Etiquetas HTML Investigadas

## ¿Qué etiquetas nuevas investigaste?
1. `<popover>`
2. `<dialog>`
3. `<details>` y `<summary>`

## ¿Para qué sirven y cómo las apliqué en mi currículum?

### 1. <popover>
   - Sirve para mostrar contenido emergente.
   - Lo utilicé en mi currículum para mostrar información adicional de forma dinámica.

### 2. <dialog>
   - Se usa para crear cuadros de diálogo en HTML.
   - Lo agregué para mostrar un mensaje emergente en mi formulario de contacto.

### 3. <details> y <summary>
   - Permiten crear secciones colapsables de contenido.
   - Lo usé en mi currículum para mostrar información extra de mis proyectos.

## Ejemplo de Código en HTML donde las utilicé:

```html
<!-- Ejemplo de popover -->
<button popovertarget="info">Mostrar Información</button>
<div id="info" popover>
    <p>Esta es una funcionalidad nueva en HTML para mostrar información emergente.</p>
    <button onclick="document.getElementById('info').hidePopover()">Cerrar</button>
</div>

<!-- Ejemplo de dialog -->
<dialog id="miDialogo">
    <p>Este es un cuadro de diálogo emergente.</p>
    <button onclick="document.getElementById('miDialogo').close()">Cerrar</button>
</dialog>
<button onclick="document.getElementById('miDialogo').showModal()">Abrir Diálogo</button>

<!-- Ejemplo de details y summary -->
<details>
    <summary>Ver más sobre mi experiencia</summary>
    <p>Detalles adicionales sobre mis proyectos y experiencia laboral.</p>
</details>
