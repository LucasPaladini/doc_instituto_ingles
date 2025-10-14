# Especificación del Caso de Uso: Modificar Curso

## 1. Nombre del Caso de Uso
**Modificar Curso**

## 2. Actor Principal
**Administrador**

## 3. Descripción
Permite al Administrador modificar la información de un curso ya existente en el sistema.

## 4. Precondiciones
- El Administrador debe estar autenticado.
- Debe acceder a la sección **“Cursos”** y visualizar la lista de cursos.

## 5. Flujo de Eventos

### Flujo Normal

1. El Administrador selecciona el curso a modificar desde el listado.
2. El sistema muestra un formulario con los datos actuales del curso.
3. El Administrador realiza los cambios necesarios (por ejemplo: nombre, profesor, horario, duración, etc.).
4. El Administrador hace clic en **Guardar**.
5. El sistema valida y actualiza los datos del curso.
6. El sistema muestra un mensaje de confirmación indicando la modificación exitosa.

### Flujo Alternativo
- **4.1** Si los datos son inválidos o faltan campos requeridos, el sistema muestra un mensaje de error y no guarda los cambios.
- **X.1** El Administrador puede cancelar en cualquier momento.

## 6. Postcondiciones
El curso es actualizado con la nueva información proporcionada.
