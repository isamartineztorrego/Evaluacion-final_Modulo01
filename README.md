Evaluación Final Módulo 1
Instrucciones:
- Esta evaluación consta de una serie de preguntas que evalúan tu comprensión y habilidades en
relación con funciones, clases y regex.
- Puedes usar recursos externos, incluyendo internet y materiales de referencia o tus propias
notas.
- Completa los ejercicios en un jupyter notebook.
- Entrega: Tienes que crearte un repositorio en la que tenga el siguiente nombre promo-G-DAmodulo1-
evaluacion-final-vuestronombre.
Ejercicio
- A lo largo de esta evaluación tendrás que crear una clase llamada TiendaOnline que cumpla los
siguientes requisitos:
o La clase TiendaOnline debe tener los siguientes atributos:
1. inventario (lista de diccionarios): Un atributo para almacenar los productos en
el inventario. Cada producto debe ser representado como un diccionario con las
siguientes claves: 'nombre', 'precio', y 'cantidad'. Al principio deberá ser
una lista vacía. Ejemplo de como debería ser:
[{'nombre': 'Camisa', 'precio': 20, 'cantidad': 40},
{'nombre': 'Pantalón', 'precio': 30, 'cantidad': 30}]
2. clientes (diccionario): Un atributo para llevar un registro de los clientes de la
tienda. Cada cliente debe ser representado como un diccionario con las
siguientes claves: 'nombre' y 'email'. Al inicio deberá ser un diccionario vacío.
Además, cada cliente debe tener un historial de compras. Deberá parecerse a:
{'Cliente1': {'email': 'cliente1@email.com', 'compras': []},
'Cliente2': {'email': 'cliente2@email.com', 'compras': []}}
3. ventas_totales (float): Un atributo para llevar un registro de las ventas totales
de la tienda. Inicializalo con valor 0.
o La clase TiendaOnline debe tener los siguientes métodos:
4. agregar_producto(self, nombre, precio, cantidad): Este método agrega
un producto al inventario o actualiza su cantidad si ya existe. Debe recibir el
nombre, precio y cantidad del producto como parámetros.
￿ Itera a través del inventario y compara los nombres de los productos con
el nombre proporcionado.
￿ Si el producto ya existe, actualiza la cantidad.
