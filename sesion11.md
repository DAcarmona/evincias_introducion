<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 11 


<!-- Su documentación aquí -->

## link  https://dacarmona.github.io/sesi-n11/

# Actividad: Propiedades CSS, SeudoClases, SeudoElementos y Reglas @css
Crear un documento HTML y probar cada uno de los ejemplos de la sesión 11

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alma del campo café</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    

    <div class=contenedor1>
        <h1 class="titulo">Granja saludable</h1>
        
        <p>Alma del campo es una marca de cafes especiales, con unas notas unicas
           y variedades de aromas frutales </p>
           <img src="https://www.fundacionmaude.com/wp-content/uploads/2017/08/cafe_soluble.jpg" alt="Aguacate" class="imagen">

    </div>

    <div class="contenedor2">
    <h3>Aguacate hass</h3>
    <p> Es conocido también por el nombre de fruta del corazón
         ya que se parece al órgano vital y los beneficios
         del aceite que tienen sirven para reducir el colesterol</p>
         <img src="https://www.eje21.com.co/site/wp-content/uploads/2017/07/Aguacate-Hass.jpg" alt="Aguacate" class="imagen">
    </div>
</body>
</html>
```
```
.contenedor1{
    
    float: left;
    width: 50%;
    height: 50px;
    margin: 10px;
    padding: 10px;
    color: #4d1fce;
    
    font-family: 'Times New Roman', serif;
    font-size: 40px;
    font-weight: bold;
    
}

.imagen{


        width: 80%;
        height: 60vh;
        margin: 30px;
        padding: 20px;
         border-radius:30px ;
      
}

.contenedor2 {
    float: left;
    width: 50%;
    height: 100px;
    margin: 650px;
    padding: 10px;
    color: #235a0f;
    
    font-family: 'Times New Roman', serif;
    font-size: 40px;
    font-weight: bold;
    

}

.titulo {
    font-family: 'arial', sans-serif; 
    font-size: 48px; /* Ajusta el tamaño de fuente según tus preferencias */
    font-weight: bold;
    color: #472c3e; /* Cambia el color a tu preferencia, este es un color de ejemplo */
}

```




