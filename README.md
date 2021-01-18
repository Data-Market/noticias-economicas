# Noticias Económicas

Noticias económicas de los principales medios especializados de España. Este dataset se puede adquirir en [Data Market](https://datamarket.es/#noticias-economicas-dataset), plataforma de referencia de datos externos en España. Puede consultar nuestro catálogo de datos en la siguiente url: [datamarket.es](https://datamarket.es/)

A continuación se muestran las columnas de las que consta el dataset en el formato __nombre_columna__: __ejemplo_columna__, donde ejemplo_columna representa posibles valores que se pueden encontrar en dicha columna.

| nombre        | tipo     | descripción                                 | ejemplo                                                                                                                          |
|---------------|----------|---------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------|
| url           | str      | Url del artículo.                           | https://www.expansion.com/economia/2020/10/08/5f7e2a0d468aeb81038b4635.html                                                      |
| base_url      | str      | Sitio web donde se publicó el artículo.     | https://www.expansion.com/mercados/cronica-bolsa.html                                                                            |
| authors       | str      | Autores separados por comas.                | Miguel Ángel Criado, Adriano Machado                                                                                             |
| title         | str      | Título del artículo.                        | Trump siembra la confusión sobre los estímulos en EEUU                                                                           |
| summary       | str      | Resumen del artículo.                       | El presidente de Estados Unidos, Donald Trump. EFEEl presidente sobresalta a los mercados al parecer contradecirse sobre         |
| text          | str      | Contenido del artículo.                     | El presidente de Estados Unidos, Donald Trump. EFE El presidente sobresalta a los mercados al parecer contradecirse sobre el     |
| publish_date  | datetime | Fecha de publicación del artículo.          | 2020-10-08 02:00:00                                                                                                              |
| top_image_url | str      | Url de la imagen de portada.                | https://phantom-expansion.unidadeditorial.es/219e767ee56c4fde9ff6f898d81373ad/f/webp/assets/multimedia/imagenes/2020/10/07/16020 |
| keywords      | str      | Etiquetas del artículo separadas por comas. | sembró, confusión, presidente, siembra, unidos, eeuu, trump, sobresalta, tras, estímulos                                         |
| insert_date   | datetime | Fecha de inserción en la base de datos.     | 2020-10-08 02:00:00                                                                                                              |
