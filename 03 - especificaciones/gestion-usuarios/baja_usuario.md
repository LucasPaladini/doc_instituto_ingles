# Especificación del Caso de Uso: Baja Usuario

## 1. Nombre del Caso de Uso
**Baja Usuario**

## 2. Actor Principal
**Administrador**

## 3. Descripción
Permite al Administrador eliminar o marcar como inactivo a un usuario del sistema.

## 4. Precondiciones
- El Administrador debe estar autenticado.
- Debe ingresar a la sección **“Usuarios”**.
- El usuario a eliminar debe existir en el sistema.

## 5. Flujo de Eventos

### Flujo Normal

1. El Administrador selecciona la opción **“Listado de usuarios”**.
2. El sistema muestra una tabla con los usuarios registrados.
3. El Administrador selecciona el usuario que desea eliminar.
4. El sistema solicita confirmación de la acción.
5. El Administrador confirma la acción.
6. El sistema elimina al usuario o lo marca como inactivo según la política del sistema.
7. El sistema confirma que la acción se realizó correctamente.

### Flujo Alternativo
- **4.1** Si el Administrador cancela la acción, el sistema no realiza cambios.

## 6. Postcondiciones
El usuario seleccionado queda eliminado o inactivo en el sistema y no puede autenticarse.
