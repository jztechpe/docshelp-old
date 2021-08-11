---
title: Tarifas
subtitle: Las sección de tarifas nos permite editar el precio de envío hacia los usuarios finales.
tags: [envios,cobertura]
author: Luis Zumaeta
---

## Tarifas

La plataforma permite configurar 2 tarifas por cada método de envío.

Las tarifas están conformadas por un número ilimitado de rutas tarifarias.

## Rutas tarifarias

Son todas las combinaciones posibles que se realizan entre zonas.

Para crear una ruta tarifaria se requiere:

- Selecccionar la tarifa a editar `Tarifa 1` o `Tarifa 2`.
- Dar click "Crear ruta tarifaria".
- Escoger la `Zona de origen`, `Zona de destino` y el tiempo de distribución entre ambas zonas.

Las rutas tarifarias permiten realizar todas las combinaciones entre zonas para crear las condiciones necesarias del precio de envío.

Cada ruta tarifaria puede contener infinitas condiciones especiales con la finalidad de ser altamente estratégico.

### Condiciones especiales

Las condiciones especiales están sujetas por:

- Tamaño de envío.
- Monto del ticket de la orden.

Con esta flexibilidad se pueden crear varios precios de envíos, por ejemplo:

Imaginemos que queremos segmentar nuestros precios según tamaños:

| N° | Tamaño | Subtotal desde | Subtotal Hasta | Precio |
|---|---|---|---|---|
| 1 | XXS, XS | - | - | $10 |
| 2 | S | - | - | $20 |
| 3 | M, L | - | - | $30 |
| 4 | XL, XXL | - | - | $40 |

Tal vez querramos segmentar por tamaños y por ticket de compra:

|Tamaño | Subtotal desde | Subtotal Hasta | Precio |
|---|---|---|---|
| XXS, XS | 0 | 150 | $20 |
| XXS, XS | 150 | - | $0 |
| S | 0 | 350 | $15 |
| S | 350 | - | $10 |
| M, L | 0 | 150 | $20 |
| M, L | 150 | 350 | $15 |
| M, L | 350 | - | $5 |
| XL, XXL | - | - | $ |

Tal vez querramos que nuestros precios sean flat:
|Tamaño | Subtotal desde | Subtotal Hasta | Precio |
|---|---|---|---|
| - | - | - | $15 |

Ó

|Tamaño | Subtotal desde | Subtotal Hasta | Precio |
|---|---|---|---|
| XXS, XS, S, M, L, XL, XXL | - | - | $15 |


Con estos ejemplos, es claro que podemos crear varias condiciones de precios de envío entre 2 zonas.

Por último, es muy importante recalcar que cualquier cambio para que se vea reflejado en la web, es necesario **"Pubicar coberturas"**

Esta acción la podemos realizar desde la sección de "Coberturas y tarifas" en el botón de acciones.

El estado de publicación, siempre nos informará si el método de envío está actualizado con el estado **Publicada** o si se encuentra **Pendiente**.