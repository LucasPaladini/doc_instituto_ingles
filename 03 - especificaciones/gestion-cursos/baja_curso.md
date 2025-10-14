# Especificación del Caso de Uso: Baja Curso

## 1. Nombre del Caso de Uso
**Baja Curso**

## 2. Actor Principal
**Administrador**

## 3. Descripción
Se permite al Administrador del Sistema dar de baja un curso existente.

## 4. Precondiciones
- El Administrador debe estar autenticado en el sistema.
- Debe hacer clic en la sección **“Cursos”**.

## 5. Flujo de Eventos

### Flujo Normal

1. El Administrador filtra por nombre o código el curso que desea dar de baja.
2. El sistema muestra una pantalla con los cursos disponibles que coinciden con el filtro aplicado.
3. El Administrador hace clic en el ícono del **cesto de basura** junto al curso correspondiente.
4. El sistema muestra un mensaje solicitando confirmación para eliminar el curso seleccionado.
5. El Administrador hace clic en **Confirmar**.
6. El sistema marca el curso como **inactivo** y lo retira de las listas activas.

### Flujo Alternativo
- **X.1** El Administrador puede cancelar la acción en cualquier momento.
- **4.1** El Administrador hace clic en **Cancelar**, y el sistema vuelve al paso 1.

## 6. Postcondiciones
El curso es marcado como **inactivo** en el sistema y deja de estar disponible para inscripciones o visualización pública.
