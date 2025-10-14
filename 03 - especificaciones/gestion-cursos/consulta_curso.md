# Especificación del Caso de Uso: Consultar Curso

## 1. Nombre del Caso de Uso
**Consultar Curso**

## 2. Actor Principal
**Administrador**

## 3. Descripción
Permite al Administrador visualizar la lista de cursos existentes y consultar la información detallada de cada uno.

## 4. Precondiciones
- El Administrador debe estar autenticado.
- Debe ingresar a la sección **“Cursos”**.

## 5. Flujo de Eventos

### Flujo Normal

1. El Administrador selecciona la opción **“Listado de cursos”**.
2. El sistema muestra una tabla con los cursos registrados.
3. El Administrador puede aplicar filtros (por nombre, código o profesor).
4. El sistema muestra los resultados que coinciden con los criterios de búsqueda.
5. El Administrador selecciona un curso y el sistema muestra su información detallada.

### Flujo Alternativo
- **4.1** Si no se encuentran resultados, el sistema muestra el mensaje “No se encontraron cursos”.

## 6. Postcondiciones
El Administrador visualiza la información de los cursos registrados en el sistema.
