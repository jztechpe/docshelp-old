---
title: Pedidos finalizados
subtitle: Pedidos que se encuentran en un estado final.
tags: [Pedidos_finalizados]
author: Luis Zumaeta
---

Los pedidos finlizados son todos aquellos que han llegado a un estado final y no poseen un estado posterior. Principalmente abarcan los estados `entregado` y `cancelado`.

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

## Pedido cancelado

Los pedidos en estado `cancelado`, no pueden ser modificados debido a que es un estado **final**.

***Se tiene que estar completamente seguro para cancelar un pedido***.

## Pedido entregado

Los pedidos en estado `entregado` reflejan aquellos pedidos que se encuentran en el destino del usuario final o después de que el usuario recoja el producto.

Cambiar el estado de `en tránsito` a `entregado` implica **asegurar que el pedido se encuentra en manos del cliente o ha sido entregado en la dirección de destino**..

Dependiendo del **rol**, se podrán ejecutar diferentes acciones en el detalle del pedido.

### Crear disputas

Las **disputas** es un módulo *nuevo* y separado de los pedidos, que permite el seguimiento de *tickets* o *casos* sobre reclamos de pedidos ya entregados con la finalidad de generar algún reembolso o revisión

Para mayor información del flujo de ***disputas***, revisar la documentación del módulo.

### Revertir

La reversión es una acción que puede ser ejecutada en la mayoría de estados dependiendo del rol, con la finalidad de regresar al **estado anterior** debido a un cambio de estado erróneo.
