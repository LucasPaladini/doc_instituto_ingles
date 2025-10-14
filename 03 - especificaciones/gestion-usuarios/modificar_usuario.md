# Especificación del Caso de Uso: Modificar Usuario

## 1. Nombre del Caso de Uso
**Modificar Usuario**

## 2. Actor Principal
**Administrador**

## 3. Descripción
Permite al Administrador actualizar la información de un usuario registrado en el sistema.

## 4. Precondiciones
- El Administrador debe estar autenticado.
- Debe ingresar a la sección **“Usuarios”**.
- El usuario a modificar debe existir en el sistema.

## 5. Flujo de Eventos

### Flujo Normal

1. El Administrador selecciona la opción **“Listado de usuarios”**.
2. El sistema muestra la tabla con los usuarios registrados.
3. El Administrador selecciona el usuario que desea modificar.
4. El sistema muestra el formulario con los datos actuales del usuario.
5. El Administrador realiza las modificaciones necesarias.
6. El Administrador confirma la acción.
7. El sistema valida los cambios y actualiza la información del usuario.
8. El sistema confirma que la modificación se realizó correctamente.

### Flujo Alternativo
- **5.1** Si los datos ingresados son incorrectos, el sistema muestra un mensaje de error y solicita corrección.
- **6.1** Si el Administrador cancela la acción, el sistema no realiza cambios.

## 6. Postcondiciones
El usuario seleccionado queda actualizado en el sistema con la nueva información.
