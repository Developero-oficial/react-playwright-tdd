# **Historias de Usuario (User Stories)**

## **Existencia y Especificación del Formulario de Pre-Inscripción**

**Como** aspirante,
**Quiero** ver un formulario claramente etiquetado y organizado,
**Para** entender y completar fácilmente mi pre-inscripción.

**Criterios de Aceptación:**

- Al acceder a la página de pre-inscripción, debe existir un formulario visible con el título "Formulario de Pre-Inscripción".
- El formulario debe contener los siguientes campos con sus respectivas etiquetas (labels):

  1. **Nombre:** Campo de texto. Etiqueta: "Nombre".
  2. **Apellido:** Campo de texto. Etiqueta: "Apellido".
  3. **Fecha de Nacimiento:** Campo de fecha (calendario). Etiqueta: "Fecha de Nacimiento".
  4. **Correo Electrónico:** Campo de texto específico para email. Etiqueta: "Correo Electrónico".
  5. **Número de Teléfono:** Campo de texto numérico. Etiqueta: "Teléfono".
  6. **Programa o Curso de Interés:** Lista desplegable (dropdown). Etiqueta: "Selecciona el programa o curso de tu interés".
  7. **Términos y Condiciones:** Caja de verificación (checkbox). Junto a ella debe haber un texto que diga: "He leído y acepto los términos y condiciones", y un enlace o modal para ver los términos completos.
  8. **Botón para enviar** el formulario con el label "Preinscribirse".

Consideraciones:

- Todos los campos deben tener un espacio o margen adecuado entre ellos para que la visualización sea clara y no estén apretados.

---

## **Campos Vacíos o No Válidos**

**Como** aspirante,
**Quiero** que se me notifique cuando no complete un campo o ingrese datos inválidos,
**Para** corregir los errores antes de enviar el formulario.

**Criterios de Aceptación:**

- Si dejo un campo requerido vacío y intento enviar, debe aparecer un mensaje indicando qué campos faltan.
- Si ingreso datos no válidos (por ejemplo, un correo electrónico mal formateado), debe aparecer un mensaje específico sobre el error.
- No se debe permitir el envío del formulario hasta que todos los campos estén completos y válidos.

---

#### **Campos Válidos y Envío del Formulario**

**Como** aspirante,
**Quiero** completar todos los campos correctamente y enviar el formulario,
**Para** preinscribirme exitosamente.

**Criterios de Aceptación:**

- Todos los campos deben ser validados al momento de ingresar los datos.
- Al ingresar datos válidos en todos los campos y enviar, debe aparecer un mensaje de confirmación indicando que la pre-inscripción fue exitosa.
- Posterior al envío, debería recibir un correo de confirmación con un resumen de la información enviada.
