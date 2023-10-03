<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 


<!-- Su documentación aquí -->

# Actividad: Aplicando estilos con selectores CSS
El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.

Pasos:

Crea el esqueleto de una página web simple con la siguiente estructura:

+ Encabezado `<header>`
+ Tres párrafos `<p>`
+ Una imagen `<img>`
+ Un pie de página `<footer>`
Aplica los siguientes estilos usando selectores de etiqueta:

+ Color rojo a los encabezados `<h1>`
+ Color azul a los párrafos `<p>`
+ Borde grueso negro a la imagen `<img>`
Aplica los siguientes estilos usando seleccionadores de clase:

+ Color verde a los elementos con la clase ".destacado"
+ Tamaño de fuente grande a los elementos con la clase ".grande"
Aplica los siguientes estilos usando seleccionadores de ID:

+ Color amarillo al elemento con ID "#principal"
Sombra al elemento con ID "#sombras"
Aplica los siguientes estilos usando seleccionadores descendientes:

+ Color gris a los párrafos dentro de un 
`<div>`
+ Centrar el contenido de la sección `<section>`
# Actividad

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alma del campo café</title>
    <link rel="stylesheet" href="Styles.css">
</head>
<body>
<header>
<h1>Café especial</h1>
<h2>Despierta tus sentidos</h2>
<p>Lo que distingue al café colombiano de otros cafés es su perfil de sabor único,
     que puede atribuirse a varios factores.</p> 

    <p>En primer lugar, Colombia tiene un clima perfecto para cultivar café de alta calidad,
     gracias a su abundante sol y precipitaciones regulares a lo largo del año. 
    </p>
        
    <p>Además, los granos colombianos suelen recolectarse a mano y procesarse
     cuidadosamente para garantizar su máxima frescura y sabor.
    </p>
    <img src="https://federaciondecafeteros.org/static/images/Collage%20granos.jpg"width="400">
<div>
<p>Es una bebida que se caracteriza por su facultad estimulante y sus propiedades organolépticas,
     es decir, que se puede percibir a través de todos los sentidos para comprobar
      su calidad y ‘frescura’, además de ser una de las más consumidas en el mundo.</p>

</div>

</header>
    
</body>
</html>
```
```
h1 {
color:red;
}

p{

color:blue
}

img {
    border: 800px;
}

div p{
    color:grey
}

body {
    background-color: #FAACA8;
    background-image: linear-gradient(19deg, #FAACA8 0%, #DDD6F3 100%);
    

}
```


