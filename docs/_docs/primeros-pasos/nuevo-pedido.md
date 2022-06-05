---
title: Nuevo pedido
subtitle: 
tags: [nuevo_pedido]
author: ivan
---
## ¿Qué estados tienen los pedidos?

> **Nuevo**
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

## ¿Como se agrupan los pedidos?
Cada pedido puede tener uno o más subpedidos, los cuales son agrupados de acuerdo al almacén desde donde se recolectan los productos. Es decir si se tiene un pedido con 2 productos diferentes, el producto A1 se obtiene desde el almacén B1 y el producto A2 se obtiene desde el almacén B2, entonces se creará un pedido con 2 subpedidos. Caso contrario de que ambos productos se encuentren en el mismo almacén entonces solo se crearía un subpedido que contendría estos 2 productos.

{% include image.html img="../docs/primeros-pasos/pedidos-agrupamiento.jpg" alt="Alt for image" caption="Pedidos Agrupamiento" %}

## Pedidos activos
Ingresando a la opción **Pedidos activos** podrás encontrar los pedidos que tengan los estados *Pendiente de Pago*, *Confirmado*, *Listo para despacho*, *En tránsito*, *Últimos Entregados* y *Retenidos*, para esto solo deberás hacer click en la pestaña correspondiente.

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
Para cambiar de estado un pedido se debe ingresar a un subpedido en particular y en la parte superior derecha se mostrará un botón para cambiar al estado <a href="#que-estados-tienen-los-pedidos">siguiente</a>

{% include image.html img="../docs/primeros-pasos/pedidos-activos-cambio-estado.jpg" alt="Alt for image" caption="Filtros de Pedidos Activos" %}

## Revertir estado

## Cancelar pedido

