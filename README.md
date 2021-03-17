# Datasets de Boletines Oficiales
<a href="https://datamarket.es">
  <img src="https://datamarket.es/static/core/img/banners/productos-de-supermercados-banner.png">
</a>

## Descripción

Todos los __tipos de Boletines Oficiales de España.__ Contiene 17 Boletines Oficiales de gobierno de cada comunidad autónoma, 17 Boletines Oficiales correspondientes a los parlamentos autonómicos, el Boletín Oficial del Estado (BOE) y los Boletines Oficiales de Congreso y Senado

Las características de este dataset son las siguientes:

* __Frecuencia de actualización__: actualizado cada 12h
* __Volumen estimado__: 
* __Histórico__: 

El dataset completo se puede adquirir en [DataMarket](https://datamarket.es/#boletines-oficiales-dataset), plataforma de referencia de datos externos en España. 

Este repositorio contiene los siguientes recursos:

* La documentación completa del dataset.
* Una muestra representativa del mismo disponible para su evaluación y uso gratuito.

## Muestra

La muestra se encuentra disponible para descarga en el siguiente [link](https://github.com/Data-Market/productos-de-supermercados/blob/main/boletines-oficiales-sample.csv).

## Documentación

A continuación se muestran las columnas de las que consta el dataset junto con su descripción.

| nombre | tipo | descripción | ejemplo |
|--------|------|-------------|---------|
| category | str | Categoría del producto. | marisco_y_pescado_pescado_congelado |
| description | str | Información adicional del producto (formato de empaquetado, etc.). | Pack-2 |
| insert_date | datetime | Fecha de extracción de la información. | 2020-09-23 14:15:00 |
| name | str | Nombre del producto. | Anguriñas de surimi Pescanova |
| price | float | Precio absoluto del producto. En caso de existir algún tipo de descuento aparecerá el menor precio disponible. | 1.99 |
| reference_price | float | Precio unitario (por unidad de medida del producto, €/Kg, €/L, etc.). | 7.96 |
| reference_unit  | str | Unidad de referencia del producto (Kg, L, etc.). | kg |
| supermarket | str | Supermercado al que pertenece el producto. | 433463D95980C252B92C204E3655BB81 |
