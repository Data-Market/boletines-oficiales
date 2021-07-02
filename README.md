# Datasets de Boletines Oficiales
<a href="https://datamarket.es">
  <img src="https://datamarket.es/media/banners/boletines-oficiales-banner.png">
</a>

## Descripción

Todos los __tipos de Boletines Oficiales de España.__ Contiene 17 Boletines Oficiales de gobierno de cada comunidad autónoma, 17 Boletines Oficiales correspondientes a los parlamentos autonómicos, el Boletín Oficial del Estado (BOE) y los Boletines Oficiales de Congreso y Senado

Las características de este dataset son las siguientes:

* __Frecuencia de actualización__: actualizado cada 24h
* __Volumen estimado__: 3.000 registros cada día
* __Histórico__: disponible desde enero de 2010 en adelante

El dataset completo se puede adquirir en [DataMarket](https://datamarket.es/#boletines-oficiales-dataset), plataforma de referencia de datos externos en España. 

Este repositorio contiene los siguientes recursos:

* La documentación completa del dataset.
* Una muestra representativa del mismo disponible para su evaluación y uso gratuito.

## Muestra

La muestra se encuentra disponible para descarga en el siguiente [link](https://github.com/Data-Market/boletines_oficiales/blob/main/boletines-oficiales-sample.csv).

## Documentación

A continuación se muestran las columnas de las que consta el dataset junto con su descripción.

| nombre | tipo | descripción | ejemplo |
|--------|------|-------------|---------|
| author | str | Entidad pública responsable de redactar la iniciativa perteneciente al Boletín Oficial. | Consejería de Economía y Hacienda |
| boe_ca | str | Comunidad autónoma del Boletín Oficial. | Castilla y León |
| boe_extra | bool | Define si la iniciativa pertenece a un Boletín Oficial extraordinario. | False |
| boe_id | str | Identificación del Boletín Oficial al que pertenece la iniciativa. | BOCYL |
| boe_number | int | Número del Boletín Oficial al que pertenece la iniciativa. | 124 |
| boe_type | Define si la iniciativa pertenece a un Boletín Oficial de gobierno o parlamento autonómico. | gobierno |
| date | datetime |  Fecha de publicación del Boletín Oficial al cual pertenece la iniciativa. | 2021-06-29 |
| initiative_code | str | Código identificativo de la iniciativa. | IE/AT/3-2019 |
| initiative_header | str | Título descriptivo de la iniciativa perteneciente al Boletín Oficial. | Información publica relativa a la solicitud de autorización administrativa, aprobación del... |
| initiative_status | str | Define el estado administrativo en el cual se encuentra la iniciativa. | resuelto |
| initiative_text | str | Texto completo de la iniciativa perteneciente al Boletín Oficial. | En fecha 17 de enero de 2019 se recibe en este servicio territorial la solicitud por parte de... |
| initiative_type | str | Tipo de iniciativa del Boletín Oficial (orden, extracto, resolución...). | información |
| section | str | Título de la sección del Boletín Oficial a la que pertenece la iniciativa. | V. Anuncios |
| subsection | str | Título de la subsección del Boletín Oficial a la que pertenece la iniciativa. | E. ANUNCIOS |
| url | str | Url de la iniciativa perteneciente al Boletín Oficial. | https://bocyl.jcyl.es//html/2021/06/29/html/BOC... |
