---
title: Almacén
subtitle: El almacén es la representación virtual de una tienda o un almacén físico.
tags: [merchant,almacen]
author: Luis Zumaeta
---

La plataforma permite la creación de múltiples **almacenes** conforme sean necesarios para la distribución de diferentes productos y la atención de órdenes.

Las características principales de un **almacén** son:

- Stock de productos.
- Ubicación del almacén.
- Tiempo de preparación (Lead time).
- Horario de corte.
- Tipo de entrega (A domicilio o recojo en tienda)

Hoy en día la omnicanalidad es algo que toma mucha presencia en el mundo digital y es por ello que el **almacén** representa una tienda o almacén físico debido a que es el reflejo de lo que ocurre en la realidad. Esto significa que una tienda/local/almacén/darkstore, etc, puede recibir pedidos para ser distribuidos desde ese punto.

## Segun tipo de sitio

En sitios **singleplace**, el **Sitelogistic** está encargado de la creación y gestión del **almacén** de manera directa.

En sitios **marketplace**, el **MerchantoLogistic** está encargado de la creación y gestión del **almacén** de manera directa.

Esta distinción es debido a que en un sitio **singleplace** el almacenero es dueño del proceso de despacho mientras que en un **marketplace** el responsable del despacho es almacenero del **merchant**.

## Características del almacén

### Definición de campos generales

- **Nombre de almacén**: Es el nombre comercial que se le atribuye al almacén (Este campo no podrá ser editado posteriormente).
- **Código de almacén**: Es un código que se le asigna al almacén para identificarlo de manera interna (Este campo no podrá ser editado posteriormente).
- **ID externo de almacén**: Este campo es utilizado para realizar integraciones a nivel de stock con otros sistemas.
- **Persona encargada**: Son los datos de contacto de la persona responsable del almacén.

### Stock de productos

El stock puede ser ingresado desde el catálogo de productos o desde operaciones masivas para una actualización de varios productos.

La plataforma permite descargar un reporte general del stock de todos los productos.

***La falta de stock no bloquea la visualización del producto***

### Ubicación del almacén

El **almacén** a diferencia de la **tienda** tiene una ubicación física con la finalidad de ser el punto de recojo de productos. Esta característica permite que los productos puedan ser distribuidos desde diferentes ubicaciones.

La ubicación puede ser editada posteriormente en caso la ubicación haya sido ingresada erróneamente.

La ubicación del almacén se geolocaliza con la finalidad de obtener mayor precición. Se puede agregar refrencias como campo opcional.

### Tiempo de preparación

Es el tiempo que un almacén suele demorar en preparar productos en general.

### Horario de corte

Es la hora en la cuál el **almacén** cierra su proceso de recepción de pedidos para no afectar su compromiso de entrega. Esto no significa que se detengan la generación de pedidos, sino que los pedidos aumentan un día adicional para su entrega. Por ejemplo:

Si un almacén puede atender todos los pedidos que ingresen hasta las 17:00 para dejarlos listos en 24 horas, significa que los pedidos que ingresen a las 17:05 serán considerados para el siguiente turno de atención. Con ello evitando prometer fechas de entrega que no podrán cumplir.

### Tipo de entrega

#### A domicilio

Es la opción de habilitar la entrega mediante un transportista que puede ser proporcionado por el Siteowner o por flota propia (**marketplace**).

#### Recojo en tienda

Es la opción de habilitar el recojo en la tienda de manera presencial.
