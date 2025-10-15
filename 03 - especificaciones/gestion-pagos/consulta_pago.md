# Especificación del Caso de Uso: Consultar Pago

## 1. Nombre del Caso de Uso
**Consultar Pago**

## 2. Actor Principal
**Usuario**

## 3. Descripción
Permite al Usuario visualizar los pagos registrados y consultar su información detallada.

## 4. Precondiciones
- El Usuario debe estar autenticado.
- Debe ingresar a la sección **“Pagos”**.

## 5. Flujo de Eventos

### Flujo Normal

1. El Usuario selecciona la opción **“Listado de pagos”**.
2. El sistema muestra una tabla con los pagos registrados.
3. El Usuario puede aplicar filtros (por alumno, fecha o estado del pago).
4. El sistema muestra los resultados que coinciden con los criterios de búsqueda.
5. El Usuario selecciona un pago y el sistema muestra su información detallada.

### Flujo Alternativo
- **4.1** Si no se encuentran resultados, el sistema muestra el mensaje “No se encontraron pagos”.

## 6. Postcondiciones
El Usuario visualiza la información de los pagos registrados en el sistema.
