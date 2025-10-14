# Especificación del Caso de Uso: Consultar Usuario

## 1. Nombre del Caso de Uso
**Consultar Usuario**

## 2. Actor Principal
**Administrador**

## 3. Descripción
Permite al Administrador visualizar la lista de usuarios registrados y consultar la información detallada de cada uno.

## 4. Precondiciones
- El Administrador debe estar autenticado.
- Debe ingresar a la sección **“Usuarios”**.

## 5. Flujo de Eventos

### Flujo Normal

1. El Administrador selecciona la opción **“Listado de usuarios”**.
2. El sistema muestra una tabla con los usuarios registrados.
3. El Administrador puede aplicar filtros (por nombre, correo o rol).
4. El sistema muestra los resultados que coinciden con los criterios de búsqueda.
5. El Administrador selecciona un usuario y el sistema muestra su información detallada.

### Flujo Alternativo
- **4.1** Si no se encuentran resultados, el sistema muestra el mensaje “No se encontraron usuarios”.

## 6. Postcondiciones
El Administrador visualiza la información de los usuarios registrados en el sistema.

