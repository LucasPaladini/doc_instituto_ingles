# Especificación del Caso de Uso: Baja Pago

## 1. Nombre del Caso de Uso
**Baja Pago**

## 2. Actor Principal
**Usuario**

## 3. Descripción
Permite al Usuario marcar un pago como inválido o anulado sin eliminarlo del sistema.

## 4. Precondiciones
- El Usuario debe estar autenticado.
- Debe ingresar a la sección **“Pagos”**.

## 5. Flujo de Eventos

### Flujo Normal

1. El Usuario selecciona la opción **“Listado de pagos”**.
2. El sistema muestra una tabla con los pagos registrados.
3. El Usuario selecciona el pago que desea inhabilitar.
4. El sistema solicita confirmación de la acción.
5. El Usuario confirma la acción.
6. El sistema marca el pago como inhabilitado y lo excluye de los reportes activos.
7. El sistema confirma que la acción se realizó correctamente.

### Flujo Alternativo
- **4.1** Si el Usuario cancela la acción, el sistema no realiza cambios.

## 6. Postcondiciones
El pago seleccionado queda marcado como inhabilitado y no se considera en los reportes activos del sistema.
