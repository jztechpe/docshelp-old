---
title: Operaciones masivas
subtitle: Crea y actualiza múltiples productos.
tags: [Cargas_masivas,Operaciones_masivas]
author: Luis Zumaeta
---

La plataforma permite realizar **operaciones masivas** con cargas de excel para crear y actualizar múltiples productos en un breve periodo de tiempo.

Las operaciones masivas disponibles son:

- Creación masiva de productos.
- Creación masiva completa de productos.
- Actualización masiva completa de productos.
- Actualización masiva de productos.
- Actualización masiva de imágenes.
- Actualización masiva de stocks.
- Actualización masiva de precios bases.
- Actualización masiva de precios promocionales.
- Activación y desactivación masiva de productos.
- Actualización masiva de imágenes externas de variaciones.
- Activación y desactivación masiva de variaciones.
- Actualización de boost.

Cada opción permite la descarga de una plantilla excel que sirve como modelo para completar la información requerida y para realizar la carga masiva.

***Recomendaciones generales para las operaciones masivas:***

- Siempre descarga la última versión de la plantilla.
- No modifiques el nombre de las cabeceras de las columnas.
- No modifiques el nombre de las pestañas
- No agregues pestañas, ni columnas adicionales.
- Revisa el glosario de cada plantilla para respetar las reglas y condiciones de cada campo.
- Revisa este manual (Siempre actualizaremos la información).

## Descripción de campos

Los campos mayoritariamente utilizados están mencionados en la sección de producto. Para entender los campos en la plantilla de excel, es necesario revisar la documentación mencionada.

## Creación masiva de productos

La **creación masiva de productos** permite crear muchos productos o variaciones de producto desde un archivo excel. Esta plantilla solo permite la creación de productos y/o variaciones.

Para crear productos masivamente, es necesario completar los campos obligatorios.

### Crear productos con una sola variación:

Para crear productos con una sola variación es necesario dejar en blanco el campo **variaciones** y completar todos los campos obligatorios.

### Crear productos con múltiples variaciones:

Para crear 1 producto con muchas variaciones, se deben seguir los siguientes pasos:

- Las variaciones son representadas en varias filas.
- Todas las variaciones deben utilizar el mismo nombre.
- Todas las variaciones deben tener la misma marca.
- Todas las variaciones deben tener el mismo código de categoría.
- Todas las variaciones deben tener diferentes SKU's.
- El campo variaciones debe contener y respetar los valores: Color, Capacidad, Talla y Estilo.

Ejemplo:

El producto sería `Pantalon XYZ` y las variaciones serían:

- `Pantalon XYZ Color Rojo Talla S`
- `Pantalon XYZ Color Rojo Talla M`
- `Pantalon XYZ Color Rojo Talla L`
- `Pantalon XYZ Color Azul Talla S`
- `Pantalon XYZ Color Azul Talla M`
- `Pantalon XYZ Color Azul Talla L`

## Actualización masiva completa de productos

La **actualización masiva de productos** permite actualizar múltiples productos desde un archivo excel. Esta plantilla utiliza principalmente el campo **ProductId** para realizar la actualización.

La **actualización** puede ser utilizada de manera parcial. Esto significa que solo las celdas que se ingrese información serán actualizadas.

Por ejemplo:

`Si el campo "Nombre del producto" se ingresa un nuevo valor y el campo "Descripción del producto" se encuentra vacío`
`Entonces solo se actualizará el campo "Nombre el producto"`

## Actualización masiva de stocks

La **actualización masiva de stocks** permite actualizar el stock de varios productos de varios **almacenes** desde un archivo excel. Esta plantilla utiliza principalmente el campo **SKU** y **Código de almacén** para realizar la actualización.

***El stock a actualizar, reemplazará al stock existente***

Por ejemplo:

`Si 1 producto tiene un stock de 250 y se realiza una carga masiva con el mismo producto con stock 10`
**`El stock final será 10`**

## Actualización masiva de precios bases

La **actualización masiva de precios base** permite actualizar el precio de muchas variaciones desde un archivo excel. Esta plantilla utiliza principalmente el campo **SKU** para realizar la actualización.

La **actualización** solo realiza la actualización del precio base siempre y cuando sea **mayor** al precio especial final.

## Actualización masiva de precios especiales

La **actualización masiva de precios especiales** permite actualizar el precio especial final de muchas variaciones desde un archivo excel. Esta plantilla utiliza principalmente el campo **SKU** para realizar la actualización.

La **actualización** solo realiza la actualización del precio especial final siempre y cuando sea **menor** al precio base.

## Activación y desactivación masiva de productos.

La **activación y desactivación masiva de productos** permite actualizar la visualización, búsqueda y venta de varios productos desde un archivo excel. Esta plantilla utiliza principalmente el campo **ProductId** para realizar la actualización.

La **actualización** puede ser utilizada de manera parcial. Esto significa que solo las celdas que se ingrese información serán actualizadas; sin embargo, la `Habilitación de la búsqueda` está condicionada a la `habilitación de la visualización`.

Por ejemplo:

`Si el campo "Habilitar venta" se ingresa un nuevo valor y el campo "Habilitar búsqueda" se encuentra vacío`
`Entonces solo se actualizará el campo "Habilitar venta"`

## Actualización masiva de boost

El **boost** hace referencia al valor sugerido de **ordenamiento** del producto en el catálogo. Este valor permite que el catálogo pueda sugerir un ordenamiento especial.

