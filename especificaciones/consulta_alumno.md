# Especificación del Caso de Uso: Consulta Alumno

## 2. Actor Principal
**Administrador**

## 3. Descripción
Se permite al Administrador consultar a un alumno.

## 4. Precondiciones
- El Administrador debe estar autenticado en el sistema.
- Debe hacer clic en "Alumnos".

## 5. Flujo de Eventos

### Flujo Normal

1. El sistema muestra una pantalla con los datos de los alumnos ya precargados.  
   - El usuario puede cancelar en cualquier momento.

2. El Administrador puede filtrar a un alumno por **DNI** o por **Apellido**. Luego de ingresar el dato, da clic en **Buscar**.

3. El sistema filtra a los alumnos y muestra a los alumnos que cumplan con esa condición.

### Flujo Alternativo

- **3.2** El sistema no encuentra ningún registro del alumno y vuelve al paso 1.

## 6. Postcondiciones
Un alumno es filtrado con éxito.
