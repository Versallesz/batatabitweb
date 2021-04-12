# Batatabit, una página mobile first.

[Esta página](https://versallesz.github.io/mobileFirstweb/ "Esta página") es el resultado de un curso de maquetación mobile first, que como su nombre lo indica, los estilos fueron diseñados pensando en dispositivos móviles, siendo luego adaptados para pantallas más grandes.

###### Estilos
Los estilos se encuentran en la carpeta css donde existen 2 archivos:
styles.css → Donde están los estilos ajustados a mobile.
tablet.css → Se encuentran los estilos para pantallas desde 930px

###### Segmentación de los estilos
Es buena práctica separar los estilos de la página por dispositivo adaptado, dejando las media queries en un archivo a parte.
En este caso, para que se alternaran los estilos dependiendo de la resolución de pantalla, se agregó una querie a la etiqueta link del archivo css en el html, quedando de la siguiente forma:

     <link rel="stylesheet" href="./css/styles.css">
     <link rel="stylesheet" href="./css/tablet.css" media="(min-width: 930px)">
