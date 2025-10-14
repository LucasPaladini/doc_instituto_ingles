# Especificación del Caso de Uso: Crear Curso

## 1. Nombre del Caso de Uso
**Crear Curso**

## 2. Actor Principal
**Administrador**

## 3. Descripción
Permite al Administrador registrar un nuevo curso en el sistema con toda la información relevante.

## 4. Precondiciones
- El Administrador debe estar autenticado en el sistema.
- Debe ingresar a la sección **“Cursos”**.

## 5. Flujo de Eventos

### Flujo Normal

1. El Administrador selecciona la opción **“Nuevo curso”**.
2. El sistema muestra un formulario para ingresar los datos del curso (nombre, código, profesor, duración, horario, cupos, etc.).
3. El Administrador completa todos los campos requeridos.
4. El sistema valida los datos ingresados.
5. El Administrador hace clic en **Guardar**.
6. El sistema registra el nuevo curso y muestra un mensaje de confirmación.

### Flujo Alternativo
- **4.1** Si los datos están incompletos o son inválidos, el sistema muestra un mensaje de error y solicita corrección.

## 6. Postcondiciones
El nuevo curso queda registrado en el sistema y disponible en el listado general.
