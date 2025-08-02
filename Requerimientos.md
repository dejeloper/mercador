Problema:Optimizar el proceso de compra de despensa
Datos:

- estatus actual(producto y cantidad en la despensa,ultima fecha de compra,fehca de revision )
- checklist(producto,cuanto quiero comprar y cuanto voy a comprar)
- lista_compra(nombre_producto, precio_producto,unidad_medida_producto,lugar_compra,tipo_producto,total del producto,,total de la compra, fecha)
- historico de compras(lista_compra(fecha))

Products
Id Int PK
Producto Text
Precio Decimal
Total Decimal
Lugar Int UK
Unidad Int UK
Tipo Int UK
Fecha Vencimineto Date
Porciones Int

Places
ID Int PK
Lugar Text

Units
ID Int PK
Unidades Text

Types
ID Int PK
Tipos Int
