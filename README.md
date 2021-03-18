# Datasets de Noticias Económicas

<a href="https://datamarket.es">
  <img src="https://datamarket.es/media/banners/noticias-economicas-banner.png">
</a>

## Descripción

Noticias económicas de los __principales medios especializados de España__. 

Las características de este dataset son las siguientes:

* __Frecuencia de actualización__: diariamente
* __Volumen estimado__: 300 noticias cada día
* __Histórico__: disponible desde octubre de 2020

El dataset completo se puede adquirir en [DataMarket](https://datamarket.es/#noticias-economicas-dataset), plataforma de referencia de datos externos en España. 

Este repositorio contiene los siguientes recursos:

* La documentación completa del dataset.
* Una muestra representativa del mismo disponible para su evaluación y uso gratuito.

## Muestra

La muestra se encuentra disponible para descarga en el siguiente [link](https://github.com/Data-Market/noticias-economicas/blob/main/noticias-economicas-sample.csv).

## Documentación

A continuación se muestran las columnas de las que consta el dataset junto con su descripción.

| nombre | tipo | descripción | ejemplo |
|--------|------|-------------|---------|
| authors | str | Autores separados por comas. | Miguel Ángel Criado, Adriano Machado |
| base_url | str | Sitio web donde se publicó el artículo. | https://www.expansion.com/mercados/cronica-bolsa.html |
| insert_date | datetime | Fecha de inserción en la base de datos. | 2020-10-08 02:00:00 |
| keywords | str | Etiquetas del artículo separadas por comas. | sembró, confusión, presidente, siembra, unidos, eeuu, trump, sobresalta, tras, estímulos |
| publish_date | datetime | Fecha de publicación del artículo. | 2020-10-08 02:00:00 |
| summary | str | Resumen del artículo. | El presidente de Estados Unidos, Donald Trump. EFEEl presidente sobresalta a los mercados al parecer contradecirse sobre |
| text | str | Contenido del artículo. | El presidente de Estados Unidos, Donald Trump. EFE El presidente sobresalta a los mercados al parecer contradecirse sobre el |
| title | str | Título del artículo. | Trump siembra la confusión sobre los estímulos en EEUU |
| top_image_url | str | Url de la imagen de portada. | https://phantom-expansion.unidadeditorial.es/219e767ee56c4fde9ff6f898d81373ad/f/webp/assets/multimedia/imagenes/2020/10/07/16020 |
| url | str | Url del artículo. | https://www.expansion.com/economia/2020/10/08/5f7e2a0d468aeb81038b4635.html |
