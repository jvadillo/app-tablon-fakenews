# Fake News app
Aplicación web creada para el aprendizaje de Django.
Consiste en una aplicación para alertar a la ciudadanía de posibles fake news (noticias falsas). La aplicación mostrará a los usuarios el listado de noticias falsas y dónde se han publicado.

Los requerimientos se han dividido en dos niveles de dificultad.

## Requerimientos: Nivel 1

-   [ ] Una noticia falsa estará compuesta por un titular, una descripción, nombre del medio que la ha publicado, el enlace donde ha sido publicada, fecha de publicación y categoría.
-   [ ] Una categoría está formada por el nombre de categoría. Una noticia pertenece solo a una categoría (dentro de una categoría hay múltiples noticias).
-   [ ] Un usuario puede ver un listado de noticias falsas (su titular, fecha y categoría) en la página principal.
-   [ ] Un usuario puede ver el resto de detalles (descripción y enlace) de la noticia haciendo click en ella. Los detalles se mostrarán en una nueva página.

### Ejemplo de noticia publicada:

* Noticia falsa 1
  - BMW saca al mercado un nuevo vehículo eléctrico con autonomía para 20.000kms
  - 22/03/2020
  - Noticias de Álava
  - www.lorempisun.com
  - Tecnología
  - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam finibus, dui vitae sodales feugiat, nibh leo scelerisque mi, id dignissim magna est et urna. Curabitur pellentesque ut ex quis maximus. Aliquam scelerisque sem odio, a hendrerit tortor ultricies eget. Ut blandit, justo id sodales interdum, nibh urna dapibus odio, vitae suscipit turpis lacus sit amet eros. Nam ac erat sapien. Sed id enim varius, laoreet eros quis, sagittis diam. Pellentesque convallis consectetur felis, vitae iaculis libero gravida at. Maecenas semper at leo et dictum. 

* Noticia falsa 2
  - Vitoria-Gasteiz acogerá la próxima edición del Mobile World Congress
  - 10/02/2020
  - Deia
  - www.lorempisun.com
  - Actualidad
  - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam finibus, dui vitae sodales feugiat, nibh leo scelerisque mi, id dignissim magna est et urna. Curabitur pellentesque ut ex quis maximus. Aliquam scelerisque sem odio, a hendrerit tortor ultricies eget. Ut blandit, justo id sodales interdum, nibh urna dapibus odio, vitae suscipit turpis lacus sit amet eros. Nam ac erat sapien. Sed id enim varius, laoreet eros quis, sagittis diam. Pellentesque convallis consectetur felis, vitae iaculis libero gravida at. Maecenas semper at leo et dictum. 

**Nota:** los datos a visualizar pueden introducirse utilizando la shell de Django o la aplicación de administrador.

## Requerimientos: Nivel 2
-   [ ] Un usuario puede publicar (crear) una nueva noticia falsa.
-   [ ] Un usuario puede crear categorías.
-   [ ] Un usuario puede filtrar el listado de noticias falsas por categoría.
-   [ ] Un usuario puede borrar una noticia.

## Documentación de ayuda
-   [Curso Django paso a paso (videos)](https://www.youtube.com/playlist?list=PL8ZnVqiE4oiY6fh6_vvNKwkxfutf3CiMY)
-   [Curso Django paso a paso (repositorio)](https://developers.themoviedb.org/3)
-   [Documentación oficial de Django](https://docs.djangoproject.com/en/3.0/)

