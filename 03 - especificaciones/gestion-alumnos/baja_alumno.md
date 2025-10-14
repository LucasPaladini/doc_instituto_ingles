# Especificación del Caso de Uso: Baja Alumno

## 1. Nombre del Caso de Uso
**Baja Alumno**

## 2. Actor Principal
**Administrador**

## 3. Descripción
Se permite al Administrador del Sistema dar de baja un alumno.

## 4. Precondiciones
- El Administrador debe estar autenticado en el sistema.
- Debe hacer clic en "Alumnos".

## 5. Flujo de Eventos

### Flujo Normal

1. El administrador debe filtrar por nombre o apellido al alumno.

1. El sistema muestra una pantalla con los datos de los alumnos ya precargados, que coincidan con el filtrado.  

2. El Administrador hace clic en el ícono del cesto de basura junto a los datos. Luego da clic en **Aceptar**.

3. El sistema muestra una pantalla que indica si desea eliminar al alumno seleccionado.

4. El Administrador da clic en **Confirmar**.

5. El sistema marca como **inactivo** al alumno.

### Flujo Alternativo
- **X.1** El usuario puede cancelar en cualquier momento.
- **4.1** El Administrador hace clic en **Cancelar** y vuelve al paso 1.

## 6. Postcondiciones
El alumno es marcado como inactivo en el sistema.

