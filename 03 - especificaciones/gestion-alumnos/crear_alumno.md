# Especificación del Caso de Uso: Crear Nuevo Alumno

## 2. Actor Principal
**Administrador**

## 3. Descripción
Permite al Administrador del Sistema añadir un nuevo alumno al sistema. El Administrador puede ingresar información sobre el alumno y guardar estos datos en el sistema.

## 4. Precondiciones
- El Administrador debe estar autenticado en el sistema.
- El sistema debe estar funcionando correctamente.
- Debe seleccionar "Alumnos".

## 5. Flujo de Eventos

### Flujo Normal

1. El administrador debe seleccionar en "añadir nuevo alumno".

2. El sistema muestra una pantalla con el formulario para ingresar un alumno nuevo.

3. El Administrador completa el formulario con la información requerida del alumno (nombre, apellidos, fecha de nacimiento, dirección, teléfono, teléfono de emergencia, etc.) y da clic en **Guardar**.

4. El sistema valida si los campos y datos son correctos y pide confirmación al usuario.

5. El usuario confirma los cambios.

6. El sistema añade un nuevo alumno.

### Flujo Alternativo
- **X.1** El usuario puede cancelar en cualquier momento.
- **4.1** Si el sistema valida y encuentra datos inválidos o incompletos, muestra un mensaje de error y vuelve al paso 2.

## 6. Postcondiciones
Un nuevo alumno es añadido al sistema con la información proporcionada.

