# Especificación del Caso de Uso: Crear Pago

## 1. Nombre del Caso de Uso
**Crear Pago**

## 2. Actor Principal
**Usuario**

## 3. Descripción
Permite al Usuario registrar un nuevo pago de un alumno en el sistema.

## 4. Precondiciones
- El Usuario debe estar autenticado.
- Debe ingresar a la sección **“Pagos”**.
- El alumno debe estar previamente registrado en el sistema.

## 5. Flujo de Eventos

### Flujo Normal

1. El Usuario selecciona la opción **“Nuevo Pago”**.
2. El sistema muestra el formulario de registro de pago.
3. El Usuario completa los datos requeridos (alumno, monto, fecha, método de pago).
4. El Usuario confirma la acción.
5. El sistema valida los datos e ingresa el pago en la base de datos.
6. El sistema confirma que el pago fue registrado correctamente.

### Flujo Alternativo
- **4.1** Si los datos ingresados son incorrectos o incompletos, el sistema muestra un mensaje de error y solicita corrección.

## 6. Postcondiciones
El pago queda registrado en el sistema y disponible para su consulta y reportes.
