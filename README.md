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
| author | str | Entidad pública responsable de redactar la iniciativa perteneciente al Boletín Oficial. | Consejería de la Presidencia, Administración Pública e Interior |
| boe_ca | str | Comunidad autónoma del Boletín Oficial. | Andalucía |
| boe_id | str | Identificación del Boletín Oficial. | BOJA |
| boe_number | int | Número del Boletín Oficial. | 51 |
| date | datetime | Fecha de publicación del Boletín Oficial. | 2021-03-17 |
| initiative_header | str | Título descriptivo de la iniciativa perteneciente al Boletín Oficial. | Resolución de 12 de marzo de 2021, de la Dirección General de Recursos Humanos y Función Pública,... |
| initiative_text  | str | Texto completo de la iniciativa perteneciente al Boletín Oficial. | "De conformidad con lo establecido en la base séptima.2 de la Resolución de 10 de diciembre de 20... |
| initiative_type | str | Tipo de iniciativa del Boletín Oficial (orden, extracto, resolución...). | Resolución |
| section | str | Título de la sección del Boletín Oficial. | 2. Autoridades y personal |
| subsection | str | Título de la subsección del Boletín Oficial. | 2.2 Oposiciones, concursos y otras convocatorias |
| url | str | Url de la iniciativa perteneciente al Boletín Oficial. | https://www.juntadeandalucia.es/boja/2021/51/11 |
