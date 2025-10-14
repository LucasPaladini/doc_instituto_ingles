# Especificación del Caso de Uso: Crear Usuario

## 1. Nombre del Caso de Uso
**Crear Usuario**

## 2. Actor Principal
**Administrador**

## 3. Descripción
Permite al Administrador registrar un nuevo usuario en el sistema.

## 4. Precondiciones
- El Administrador debe estar autenticado.
- Debe ingresar a la sección **“Usuarios”**.

## 5. Flujo de Eventos

### Flujo Normal

1. El Administrador selecciona la opción **“Nuevo Usuario”**.
2. El sistema muestra el formulario de registro de usuario.
3. El Administrador completa los datos requeridos (nombre, correo, rol, contraseña).
4. El Administrador confirma la acción.
5. El sistema valida los datos e ingresa al usuario en la base de datos.
6. El sistema confirma que el usuario fue registrado correctamente.

### Flujo Alternativo
- **4.1** Si los datos ingresados son incorrectos o incompletos, el sistema muestra un mensaje de error y solicita corrección.

## 6. Postcondiciones
El usuario queda registrado en el sistema y puede autenticarse según su rol.

