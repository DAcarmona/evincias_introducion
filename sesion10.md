<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 10 


<!-- Su documentación aquí -->

## Actividad: Propiedades de posicionamiento de CSS
Objetivo:

Aplicar las propiedades de posicionamiento de CSS para crear diferentes efectos de visualización.

Instrucciones:

Crea un nuevo archivo HTML y CSS.
En el archivo HTML, crea una estructura básica de página web con dos elementos div.
En el archivo CSS, define las propiedades de visualización y posicionamiento de los elementos div.
Ejemplo:
```

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Ejemplo de posicionamiento de CSS</title>
  <style>
    .elemento-1 {
      position: absolute;
      top: 100px;
      left: 100px;
      background-color: red;
    }

    .elemento-2 {
      position: relative;
      top: 100px;
      left: 100px;
      background-color: green;
    }
  </style>
</head>
<body>
  <div class="elemento-1"></div>
  <div class="elemento-2"></div>
</body>
</html>
```

Este ejemplo muestra dos elementos div posicionados de forma absoluta y relativa, respectivamente. El elemento .elemento-1 se posiciona a 100 píxeles de la parte superior y izquierda de la ventana del navegador, mientras que el elemento .elemento-2 se posiciona a 100 píxeles de su posición original en el flujo normal del documento.

## Solución
```
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Ejemplo de posicionamiento de CSS</title>
  <link rel="stylesheet" href="styles.css">
  <style>
  
  </style>
</head>
<body>
  <div class="elemento-1">
<h2>Un poco de sobre el conflicto</h2>
<p>El conflicto entre palestinos e israelíes alcanzó una tensión
   sin precedentes en los últimos años.</p>

  </div>
  <div class="elemento-2">
    <h2>Un poco de historia</h2>
    <p>El conflicto actual entre israelíes y palestinos se remite a la declaración
       de independencia de Israel en 1948, un país que desde su fundación
        ha experimentado conflicto con sus vecinos, principalmente países árabes y musulmanes.
         Se trata de un conflicto que nació en el siglo pasado pero que ha estado latente
          durante décadas y parece no tener un fin a la vista.</p>
  </div>
</body>
</html>
```
```
.elemento-1 {
    position: absolute;
    top: 40px;
    left: 10px;
    background-color: rgba(146, 80, 94, 0.571);
  }

  .elemento-2 {
    position: absolute;
    top: 150px;
    left: 10px;
    background-color: rgb(21, 87, 21);
  }
```

Preguntas:

+ 1.¿Cuál es la diferencia entre los valores position: absolute y position: relative?
+ 2.¿Cómo se puede usar la propiedad z-index para controlar el orden de apilamiento de los elementos posicionados?
+ 3.¿Cómo se puede usar la propiedad display para controlar cómo se muestra un elemento en una página web?

## Respueta

1. `position absolute:`
Cuando se aplica position: absolute a un elemento, este se posiciona en relación con el elemento padre más cercano que tenga una posición distinta a static (por lo general, un elemento con position: relative

. `position: relative:`
Cuando se aplica position: relative a un elemento, este conserva su posición en el flujo normal del documento, es decir, ocupa espacio en la página como si no se hubiera modificado su posición.

2. La propiedad z-index se utiliza en CSS para controlar el orden de apilamiento (superposición) de elementos posicionados, como aquellos con position: relative, position: absolute, o position: fixed. Esta propiedad determina cuál de estos elementos se superpondrá a otros en la página. Un valor más alto de z-index sitúa el elemento por encima de los elementos con valores de z-index más bajos.

3. La propiedad display en CSS se utiliza para controlar cómo se muestra un elemento en una página web, es decir, cómo se renderiza en el navegador. Esta propiedad permite cambiar la forma en que se presenta un elemento, su flujo en el documento y su comportamiento.





