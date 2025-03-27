# Lista de Compras

Este proyecto es una aplicación web sencilla que permite gestionar una lista de compras. Los usuarios pueden agregar productos a la lista, eliminar productos y ver la lista completa de compras, todo en una interfaz interactiva estilo tienda de supermercados.

## Características

- **Agregar productos**: Los usuarios pueden ingresar productos en un campo de texto y agregarlos a la lista.
- **Eliminar productos**: Los productos pueden ser eliminados de la lista haciendo clic en un botón junto a cada elemento.
- **Sin duplicados**: Los productos no pueden ser agregados si ya existen en la lista.
- **Interfaz atractiva**: El diseño es simple y elegante, simula una tienda de supermercado.

## Requisitos

- Un navegador web moderno (Chrome, Firefox, Edge, Safari).
- No se requieren dependencias externas.

## Instrucciones para usar

1. **Abrir la aplicación**: Solo abre el archivo `index.html` en tu navegador preferido.
2. **Agregar un producto**: Ingresa un producto en el campo de texto y haz clic en el botón **Agregar**.
3. **Eliminar un producto**: Para eliminar un producto, haz clic en el botón **Eliminar** junto al producto.
4. **Ver la lista**: La lista de compras se actualizará automáticamente para reflejar los cambios.

## Tecnologías utilizadas

- **HTML**: Estructura de la página web.
- **CSS**: Diseño y estilo de la interfaz de usuario.
- **JavaScript (ES6)**: Funcionalidad para agregar, eliminar y mostrar productos en la lista.

## Funcionalidades

### `agregarProducto()`
- Esta función permite agregar productos al final de la lista, asegurándose de que no haya duplicados.

### `eliminarProducto()`
- Elimina un producto específico de la lista cuando se hace clic en el botón correspondiente.

### `mostrarLista()`
- Actualiza la vista de la lista de compras cada vez que se agregan o eliminan productos.

## Mejoras y extensiones posibles

- **Persistencia de la lista**: Implementar almacenamiento local para guardar la lista de compras entre sesiones utilizando `localStorage` o `sessionStorage`.
- **Edición de productos**: Agregar la capacidad de editar productos ya existentes en la lista.
- **Precios y total**: Incluir precios de productos y calcular un total de la compra.
- **Validaciones adicionales**: Añadir validaciones para asegurarse de que los productos no estén vacíos o tengan nombres válidos.




