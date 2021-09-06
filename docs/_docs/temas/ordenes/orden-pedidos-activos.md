---
title: Pedidos activos
subtitle: Pedidos que aún se encuentran en gestión.
tags: [Pedidos activos]
author: Luis Zumaeta
---

Los pedidos activos son todos aquellos que aún se encuentran en proceso de gestión. Principalmente abarcan los estados `confirmado`, `listo para despacho` y `en tránsito`.

Todos los pedidos se muestran en grillas y pueden ser filtrados por estados mediante las pestañas.

Al hacer clic en el número del pedido, se podrá ingresar a la sección de mayor detalle del pedido.

## General

La grilla de pedidos contiene un buscado con filtros de:

- **Número de pedido**: Es el número del pedido a buscar.
- **Fecha de creación**: Fecha que se creó el pedido.
- **Fecha máxima de envío**: Fecha máxima prometida al cliente.
- **Tranportista**: La empresa transportista que traslada el pedido.
- **Método de pago**: El medio de pago por el cuál se realizó la compra.
- **Usuario**: Es el nombre del usuario de la cuenta que realizó la compra.
- **Correo electrónico**: Es el correo electrónico del usuario que realizó la compra.
- **Nombre de la tienda**: El nombre de la tienda donde se realizó la compra.
- **Almacén**: Es el nombre del almacén de donde se despacha el pedido.

## Pedido confirmado

Los pedidos con estado `confirmado` reflejan aquellos pedidos que han pasado el filtro o proceso de cobro para poder asegurar el primer paso de atención.

Este estado es previo a `listo para despacho`. Cambiar el estado de `confirmado` a `listo para despacho` implica **asegurar que el pedido ya se encuentra empacado y etiquetado para su despacho**.

Dependiendo del **rol**, se podrán ejecutar diferentes acciones en el detalle del pedido.

### Edición de cantidad de productos

La edición de cantidad de productos únicamente se puede realizar en el estado confirmado. Esta edición, permite cambiar la cantidad de cada producto en caso `el usuario desista`, `falta de stock`, `retrasos`, `error en precios`, etc.

La cantidad a editar del producto **no puede ser mayor a la cantidad original**. En pocas palabras, no se puede agregar más cantidades al producto.

### Edición de la dirección de entrega

La edición de la dirección de entrega únicamente se puede realizar en el estado confirmado. Esta edición permite modificar la geolocalización de la entrega (Coordenadas).

### Edición de referencias

La edición de las referencias se pueden realizar en el estado `confirmado` y `listo para despacho`. Esta edición permite agregar o modificar una referencia para ubicar con mayor facilidad la dirección de entrega.

### Edición de datos del destinatario

La edición de datos del destinatario permite modificar lo siguiente:

- **Nombre** y **Apellido**: El nombre y apellido de la persona que recibe el pedido.
- **Teléfono**: El número de contacto quien recibe el pedido.
- **Documento de identidad**: El tipo y número de documento de la persona que recibirá el pedido.

## Pedido listo para despacho

Los pedidos en estado `listo para despacho` reflejan aquellos pedidos que se encuentran listos para ser despachados y ser entregados al transportista (entrega a domicilio) o al usuario final (recojo en tienda).

Este estado es previo a `en tránsito`. Cambiar el estado de `listo para despacho` a `en transito` implica **asegurar que el pedido ya se encuentra en posesión del transportista**.

Dependiendo del **rol**, se podrán ejecutar diferentes acciones en el detalle del pedido.

### Imprimir

Desde el detalle del pedido, se podrán imprimir 2 tipos de documentos:

- **Orden**: Es el resumen del pedido para ser impreso como evidencia de la compra al usuario final.
- **Etiqueta de envío**: Es la etiqueta o guía de transporte que se genera para poder tener el seguimiento correcto del pedido.

### Edición de referencias

La edición de las referencias se pueden realizar en el estado `confirmado` y `listo para despacho`. Esta edición permite agregar o modificar una referencia para ubicar con mayor facilidad la dirección de entrega.

### Edición de datos del destinatario

La edición de datos del destinatario permite modificar lo siguiente:

- **Nombre** y **Apellido**: El nombre y apellido de la persona que recibe el pedido.
- **Teléfono**: El número de contacto quien recibe el pedido.
- **Documento de identidad**: El tipo y número de documento de la persona que recibirá el pedido.

## Pedido en tránsito

Los pedidos en estado `en tránsito` reflejan aquellos pedidos que están en posesión de un transportista.

Este estado es previo a `entregado`. Cambiar el estado de `en tránsito` a `entregado` implica **asegurar que el pedido se encuentra en manos del cliente o ha sido entregado en la dirección de destino**.
