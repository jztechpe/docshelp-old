---
title: Operaciones masivas
subtitle: Crea y actualiza múltiples productos.
tags: [Cargas_masivas,Operaciones_masivas]
author: Luis Zumaeta
---

La plataforma permite realizar **operaciones masivas** con cargas de excel para crear y actualizar múltiples productos en un breve periodo de tiempo.

Las operaciones masivas disponibles son:

- Creación masiva de productos.
- Actualización masiva de productos.
- Actualización masiva de stocks.
- Actualización masiva de precios bases.
- Actualización masiva de precios urgentes.
- Activación y desactivación masiva de productos.
- Actualización masiva de variaciones de producto.
- Activación y desactivación masiva de variaciones.
- Actualización de boost.

Cada opción permite la descarga de una plantilla excel que sirve como modelo para completar la información requerida y para realizar la carga masiva.

**Recomendaciones generales para las operaciones masivas:**

- Siempre descarga la última versión de la plantilla.
- No modifiques el nombre de las cabeceras de las columnas.
- No modifiques el nombre de las pestañas
- No agregues pestañas, ni columnas adicionales.
- Revisa el glosario de cada plantilla para respetar las reglas y condiciones de cada campo.

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
