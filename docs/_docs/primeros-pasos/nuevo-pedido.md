---
title: Nuevo pedido
subtitle: 
tags: [nuevo_pedido]
author: ivan
---
## ¿Qué estados tienen los pedidos?

> **Nuevo**: Es el primer
> 
> **Pendiente de pago**
> 
> **Rechazado**
> 
> **Confirmado**
> 
> **Listo para despacho**
> 
> **En tránsito**
> 
> **Entregado**
> 
> **Cancelado**
> 
> **Retenido**

## Pedidos
Ingresando a la opción **Pedidos** podrás encontrar todos los pedidos que se han realizado las últimas 24 horas. También podrás visualizar algunas opciones como **Iniciar descarga**, la cual permite obtener un archivo Excel con todos los registros necesarios de los pedidos y también existe otra opción de **Filtros**, en donde se puede filtrar estos pedidos por: 
 * **Filtro dado un rango de fechas:** Para obtener todos los pedidos que han sido efectuados dentro de un rango específico de fechas.
 * **Filtro por un código identificador de un usuario:** Para obtener todos los pedidos que han sido efectuados por un usuario en particular.
 * **Filtro por un correo electrónico:** Para obtener todos los pedidos que estan relacionados en un correo.
 * **Filtro por una campaña:** Para obtener todos los pedidos a los que se le ha aplicado una campaña.
 * **Filtro por cupón:** Para obtener todos los pedidos a los que se le ha aplicado un cupón.
 * **Filtro por estados:** Para obtener todos los pedidos de acuerdo a uno o más estados.

{% include image.html img="../docs/primeros-pasos/pedidos.jpg" alt="Alt for image" caption="Pedidos" %}

## Sincronizar Orden
Dentro de un pedido se podrá visualizar una vista como la que se mostrará a continuación, en donde se puede sincronizar una orden en caso de que se tenga una integración con una pasarela de pagos de terceros.

{% include image.html img="../docs/primeros-pasos/pedidos-sincronizar.jpg" alt="Alt for image" caption="Sincronizar Orden" %}

## ¿Cómo se agrupan los pedidos?
Cada pedido puede tener uno o más subpedidos, los cuales son agrupados de acuerdo al almacén desde donde se recolectan los productos. Es decir si se tiene un pedido con 2 productos diferentes, el producto A1 se obtiene desde el almacén B1 y el producto A2 se obtiene desde el almacén B2, entonces se creará un pedido con 2 subpedidos. Caso contrario de que ambos productos se encuentren en el mismo almacén entonces solo se crearía un subpedido que contendría estos 2 productos.

{% include image.html img="../docs/primeros-pasos/pedidos-agrupamiento.jpg" alt="Alt for image" caption="Pedidos Agrupamiento" %}

## Pedidos activos
Ingresando a la sección **Pedidos activos** podrás encontrar los pedidos que tengan los estados *Pendiente de Pago*, *Confirmado*, *Listo para despacho*, *En tránsito*, *Últimos Entregados* y *Retenidos*, para esto solo deberás hacer click en la pestaña correspondiente.

{% include image.html img="../docs/primeros-pasos/pedidos-activos-1.jpg" alt="Alt for image" caption="Pedidos Activos" %}

También podrás visualizar algunas opciones como **Iniciar descarga**, la cual permite obtener un archivo Excel con todos los registros necesarios de los pedidos y también existe otra opción de **Filtros**, en donde se puede filtrar estos pedidos por: 
 * **Filtro por fecha de creación dado un rango de fechas:** Para obtener todos los pedidos que han sido creados dentro de un rango específico de fechas.
 * **Filtro por fecha máxima de envío dado un rango de fechas:** Para obtener todos los pedidos que han sido o serán entregados dentro de un rango específico de fechas.
 * **Filtro por transportisata:** Para obtener todos los pedidos que han sido o serán entregados por un transportista en particular.
 * **Filtro por método de pago:** Para obtener todos los pedidos que han sido pagados con un método de pago correspondiente.
 * **Filtro por un código identificador de un usuario:** Para obtener todos los pedidos que han sido efectuados por un usuario en particular.
 * **Filtro por un correo electrónico:** Para obtener todos los pedidos que estan relacionados en un correo.
 * **Filtro por una tienda:** Para obtener todos los pedidos que estan relacionados a una tienda.
 * **Filtro por un almacén:** Para obtener todos los pedidos que estan relacionados a un almacén.

{% include image.html img="../docs/primeros-pasos/pedidos-activos-filtros-1.jpg" alt="Alt for image" caption="Filtros de Pedidos Activos" %}

## Cambio de estado
Para cambiar de estado un pedido se deberá ingresar a la sección **Pedidos activos** y seleccionar un subpedido en particular, luego en la parte superior derecha se mostrará un botón para cambiar al estado siguiente de acuerdo a los estado mencionados<a href="#qué-estados-tienen-los-pedidos">previamente</a>.

{% include image.html img="../docs/primeros-pasos/pedidos-activos-cambio-estado.jpg" alt="Alt for image" caption="Cambio de estado de un Pedido" %}

## Revertir estado
Para revertir el estado de un pedido se deberá ingresar a la sección **Pedidos activos** y seleccionar un subpedido en particular, luego en la parte superior central existe un botón de **opciones** el cual posee una opción para revertir el pedido a su estado anterior de acuerdo a los estado mencionados<a href="#qué-estados-tienen-los-pedidos">previamente</a>.

{% include image.html img="../docs/primeros-pasos/pedidos-activos-revertir.jpg" alt="Alt for image" caption="Revertir el estado de un Pedido" %}

## Cancelar pedido
Para cancelar un pedido se deberá ingresar a la sección **Pedidos activos** y seleccionar un subpedido en particular, luego dentro del botón de opciones que se muestran en la parte superior central se muestra una opción para cancelar el pedido.

{% include image.html img="../docs/primeros-pasos/pedidos-activos-cancelar.jpg" alt="Alt for image" caption="Cancelar un Pedido" %}

Al seleccionar esta opción se mostrará un pop up en donde se deberá colocar de manera obligatoria una razón por la cual el subpedido será cancelado.
{% include image.html img="../docs/primeros-pasos/pedidos-activos-cancelar-1.jpg" alt="Alt for image" caption="Opciones de razones para cancelar un Pedido" %}

Una vez seleccionada la razón, el pedido se podrá cancelar y la vista del subpedido se actualizará mostrando la diferencia como negativo debido a que se deberá realizar una devolución al usuario del valor de los productos sin contar el valor del costo de envío.
{% include image.html img="../docs/primeros-pasos/pedidos-activos-cancelar-2.jpg" alt="Alt for image" caption="Pedido cancelado"%}

## Retener pedido
Para retener un pedido se deberá ingresar a la sección **Pedidos activos** y seleccionar un subpedido en particular, luego dentro del botón de opciones que se muestran en la parte superior central se muestra una opción para retener el pedido. 

{% include image.html img="../docs/primeros-pasos/pedidos-activos-retener.jpg" alt="Alt for image" caption="Retener un Pedido" %}

Una vez seleccionada la opción de retener pedido este pedido pasará a una nueva vista en donde se encuentran todos los pedidos retenidos.

{% include image.html img="../docs/primeros-pasos/pedidos-activos-retener-2.jpg" alt="Alt for image" caption="Retener un Pedido" %}

Al retener un pedido no podrá ser procesado dentro del flujo normal de los pedidos, ya que quedará fuera hasta que sea liberado. Para liberar un pedido, se deberá ingresar al subpedido en cuestión y se deberá seleccionar la opción de liberar pedido. Al liberar un pedido este volverá al estado anterior con el que se encontraba antes de ser retenido.
Es decir si un pedido se encontraba con el estado de **Confirmado** antes de ser retenido, luego al retenerlo paso al estado de **Retenido**, pero una vez que se libero pasa nuevamente al estado **Confirmado**.
{% include image.html img="../docs/primeros-pasos/pedidos-activos-retener-1.jpg" alt="Alt for image" caption="Liberar un Pedido" %}