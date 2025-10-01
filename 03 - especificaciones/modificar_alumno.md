# Especificación del Caso de Uso: Modificar Alumno

## 1. Nombre del Caso de Uso
**Modificar Alumno**

## 2. Actor Principal
**Administrador**

## 3. Descripción
Se permite al Administrador del Sistema modificar un alumno.

## 4. Precondiciones
- El Administrador debe estar autenticado en el sistema.
- Debe ingresar en "Alumnos".
## 5. Flujo de Eventos

### Flujo Normal

1. Seleccionar al alumno que se quiere modificar.

2. El sistema muestra una pantalla con los datos del alumno a modificar ya precargados.

3. El Administrador debe cambiar los datos del alumno clickeando en la celda y reescribiendo ese dato. Luego dará clic en **Aceptar**.

4. El sistema valida los datos y pregunta si desea confirmar los cambios.

5. El Administrador acepta los cambios clickeando en **Confirmar**.

6. El sistema modifica los datos del alumno.

### Flujo Alternativo

- **X.1** El usuario puede cancelar en cualquier momento.
- **4.1** El sistema valida los datos y encuentra datos inválidos o incompletos. Muestra un mensaje de error y vuelve al punto 1.

## 6. Postcondiciones
El alumno es modificado en el sistema con la información proporcionada.

