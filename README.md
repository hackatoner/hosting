github_hosting
==============

Proyecto de demostración para mostrar cómo usar github para alojar aplicaciones estáticas.

Acerca del proyecto
===================

El proyecto es simplemente una aplicación que accede a una lista de contactos geocodificada a través de un web service expuesto en [CartoDB](http://cartodb.com/) y lo muestra en un mapa utilizando la libería [LeafLet](http://leafletjs.com/).

El web service está disponible en http://devel.cartodb.com/api/v2/, y pueden probarlo mediante la siguiente consulta: [http://devel.cartodb.com/api/v2/sql?q=select * from my_contacts](http://devel.cartodb.com/api/v2/)

La aplicación consiste en arhivos html, css y js, ya que no requiere ningún procesamiento del lado del servidor.

Debido a esto es que podemos usar [GitHub Pages](http://pages.github.com/) para alojarla.

Si te interesa la aplicación aquí hay una [serie de artículos](http://opensas.wordpress.com/2013/06/27/journey-to-the-open-data-jungle-with-openrefine-cartodb-leaflet-and-javascript/) en la que explico paso a paso como desarrollarla:

[Trabajando con OpenRefine](http://opensas.wordpress.com/2013/06/27/journey-to-the-open-data-jungle-with-openrefine-cartodb-leaflet-and-javascript/)

[Georreferenciando información con OpenRefine y OpenStreetMap](http://opensas.wordpress.com/2013/06/30/using-openrefine-to-geocode-your-data-using-google-and-openstreetmap-api/)

[Publicando tu información en un web service con CartoDB](http://opensas.wordpress.com/2013/07/06/publish-your-own-geocoded-web-services-with-cartodb/)
