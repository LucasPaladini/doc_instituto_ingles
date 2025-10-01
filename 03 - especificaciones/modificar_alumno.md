# Especificación del Caso de Uso: Modificar Alumno

## 1. Nombre del Caso de Uso
**Modificar Alumno**

## 2. Actor Principal
**Administrador**

## 3. Descripción
Se permite al Administrador del Sistema modificar un alumno.

## 4. Precondiciones
- El Administrador debe estar autenticado en el sistema.
- Debe hacer clic en "Alumnos", filtrar por nombre o apellido al alumno que desea buscar, y luego hacer clic en el ícono de lápiz junto a los datos del alumno.

## 5. Flujo de Eventos

### Flujo Normal

1. El sistema muestra una pantalla con los datos del alumno a modificar ya precargados.

2. El Administrador debe cambiar los datos del alumno clickeando en la celda y reescribiendo ese dato. Luego dará clic en **Aceptar**.

3. El sistema valida los datos y pregunta si desea confirmar los cambios.

4. El Administrador acepta los cambios clickeando en **Confirmar**.

5. El sistema modifica los datos del alumno.

### Flujo Alternativo

- **X.1** El usuario puede cancelar en cualquier momento.
- **3.1** El sistema valida los datos y encuentra datos inválidos o incompletos. Muestra un mensaje de error y vuelve al punto 1.

## 6. Postcondiciones
El alumno es modificado en el sistema con la información proporcionada.

