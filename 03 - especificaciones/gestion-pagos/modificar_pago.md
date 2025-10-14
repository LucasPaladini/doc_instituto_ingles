# Especificación del Caso de Uso: Modificar Pago

## 1. Nombre del Caso de Uso
**Modificar Pago**

## 2. Actor Principal
**Usuario**

## 3. Descripción
Permite al Usuario actualizar la información de un pago registrado en el sistema.

## 4. Precondiciones
- El Usuario debe estar autenticado.
- Debe ingresar a la sección **“Pagos”**.
- El pago a modificar debe existir en el sistema.

## 5. Flujo de Eventos

### Flujo Normal

1. El Usuario selecciona la opción **“Listado de pagos”**.
2. El sistema muestra la tabla con los pagos registrados.
3. El Usuario selecciona el pago que desea modificar.
4. El sistema muestra el formulario con los datos actuales del pago.
5. El Usuario realiza las modificaciones necesarias.
6. El Usuario confirma la acción.
7. El sistema valida los cambios y actualiza la información del pago.
8. El sistema confirma que la modificación se realizó correctamente.

### Flujo Alternativo
- **5.1** Si los datos ingresados son incorrectos, el sistema muestra un mensaje de error y solicita corrección.
- **6.1** Si el Usuario cancela la acción, el sistema no realiza cambios.

## 6. Postcondiciones
El pago seleccionado queda actualizado en el sistema con la nueva información.

