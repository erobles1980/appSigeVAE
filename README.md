 # appSigeVAE
EduStore Guayaquil es una iniciativa orientada a la creación de una plataforma de venta y gestión de artículos escolares en la ciudad de Guayaquil. El proyecto tiene como objetivo principal ofrecer una solución eficiente para la compra y administración de materiales educativos, facilitando tanto a los padres como a las instituciones educativas el acceso a productos de calidad a precios competitivos.

# Catalogo de Productos

* Útiles básicos: cuadernos, lápices, bolígrafos, borradores, sacapuntas, reglas, tijeras.
* Material didáctico: cartulinas, papeles de colores, pegamentos, plastilinas.
* Equipos tecnológicos: calculadoras, tabletas, laptops.
* Accesorios escolares: mochilas, loncheras, estuches.
* Libros y cuadernos: libros de texto, cuadernos especializados.
* Mobiliario escolar: escritorios, sillas, estanterías.

# Modelo Relacional
![Modelo](img/modelorelacional.jpg)

**Tablas Principales:**

* Usuarios: Almacena información sobre los usuarios registrados (padres, estudiantes, personal educativo).
* Productos: Contiene detalles sobre los artículos escolares disponibles para la venta.
* Pedidos: Registra los pedidos realizados por los usuarios.
* DetallesPedidos: Detalles específicos de cada pedido, incluyendo los productos y cantidades.
* Inventario: Gestión del inventario de productos.
* Transacciones: Información sobre las transacciones de pago realizadas.

NOTE: Podrá descargar el scrip con el modelo fisico [Modelo Fisico](BD/educaStore.sql).

