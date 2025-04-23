# Especificación del Caso de Uso: Crear Nuevo Alumno

## 2. Actor Principal
**Administrador**

## 3. Descripción
Permite al Administrador del Sistema añadir un nuevo alumno al sistema. El Administrador puede ingresar información sobre el alumno y guardar estos datos en el sistema.

## 4. Precondiciones
- El Administrador debe estar autenticado en el sistema.
- El sistema debe estar funcionando correctamente.
- Debe hacer clic en "Alumnos" y luego en "Añadir nuevo alumno".

## 5. Flujo de Eventos

1. El sistema muestra una pantalla con el formulario para ingresar un alumno nuevo.
   - El usuario puede cancelar en cualquier momento.

2. El Administrador completa el formulario con la información requerida del alumno (nombre, apellidos, fecha de nacimiento, dirección, teléfono, teléfono de emergencia, etc.) y da clic en "Guardar".

3. El sistema valida si los campos y datos son correctos y pide confirmación al usuario.
   - **3.2** Si el sistema valida y encuentra datos inválidos o incompletos, muestra un mensaje de error y vuelve al paso 2.

4. El usuario confirma los cambios.

5. El sistema añade un nuevo alumno.

## 6. Postcondiciones
Un nuevo alumno es añadido al sistema con la información proporcionada.

