---
title: Coberturas
subtitle: Las coberturas definen el rango de distribución por cada método de envío.
tags: [envios,cobertura]
author: Luis Zumaeta
---

Las coberturas son independientes por cada método de envío con la finalidad de atender los rangos de distribución según los recursos que se tengan disponibles.

Para entender el funcionamiento de las coberturas es necesario entender los siguientes conceptos:

- Zonas
- Polígonos

## Zonas

Una zona es el conjunto de 1 o varios polígonos. Las zonas pueden ser personalizadas por el nombre y por el color.

Las zonas permiten agrupar varios polígonos para una gestión más sencilla de edición de coberturas. Es como trabajar por capas.

Una zona como mínimo debe contener 1 polígono y puede tener ilimitados polígonos.

Una vez creada la zona, es posible:

- Editar el nombre.
- Agregar más polígonos.
- Eliminar la zona (Incluye todos los polígonos)

Ejemplo de como usar **Zonas** con varios polígonos:

`Digamos que nuestra cobertura son zonas Urbanas cuya posición geográfica son polos opuestos.`
`Podríamos poner un polígono en el extremos A y otro polígono en el extremo B.`
`De esta manera representan 1 misma zona apesar de estar separados por 2 polígonos.`

## Polígonos

Es la unidad más pequeña de edición de una cobertura. Los polígonos no pueden ser nombrados y adaptan el color de la zona a la que pertenece.

Los polígonos permiten una flexibilidad muy grande para poder definir claramente los límites de cada posición geográfica.

Los polígonos pueden sobreponerse/traslaparse entre ellos sin ningún inconveniente, siempre y cuando, sean polígonos diferentes.

Una vez creado el polígono, es posible:

- Editar el polígono.
- Eliminar el polígono.

***Un polígono no puede traslaparse a sí mismo debido a que puede generar conflicto.***

Por último, es muy importante recalcar que cualquier cambio para que se vea reflejado en la web es necesario **"Pubicar coberturas"**

Esta acción la podemos realizar desde la sección de "Coberturas y tarifas" en el botón de acciones.

El estado de publicación, siempre nos informará si el método de envío está actualizado con el estado **Publicada** o si se encuentra **Pendiente**.
