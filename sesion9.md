<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 9 


<!-- Su documentación aquí -->

# Actividad: Propiedades de espaciado y unidades de medida
Objetivo:

Practicar el uso de las propiedades de espaciado margin, padding, border y border-radius, con diferentes unidades de medida.

Crea un nuevo archivo HTML y CSS.
En el archivo HTML, agrega el siguiente código:
```
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Propiedades de espaciado</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="contenedor">
    <div class="elemento"></div>
  </div>
</body>
</html>
```
3. En el archivo CSS, agrega el siguiente código:
```
.contenedor {
  width: 200px;
  height: 200px;
}

.elemento {
  width: 100px;
  height: 100px;
}
```
4. Abre el archivo HTML en tu navegador. Verás un cuadrado de 100x100 píxeles.

5. Practicar el uso de las propiedades de espaciado.

+ Margin: Agrega un margen de 10 píxeles a todos los lados del elemento.
```
.elemento {
  margin: 10px;
  width: 100px;
  height: 100px;
}
```
+ Padding: Agrega un relleno de 20 píxeles a todos los lados del elemento.
```
.elemento {
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}
```
+ Border: Agrega un borde de 5 píxeles de color rojo.
```
.elemento {
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}
```
+ Border-radius: Agrega un radio de esquina de 10 píxeles.
```
.elemento {
  border-radius: 10px;
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}
```
+ #### Unidades de medida: Prueba diferentes unidades de medida para las propiedades de espaciado. Por ejemplo, puedes usar unidades porcentuales (%) para establecer un margen o relleno del 50%.
```
.elemento {
  border-radius: 10px;
  border: 5px solid red;
  margin: 50%;
  padding: 50%;
  width: 100px;
  height: 100px;
}
```
## Preguntas:
1.¿Qué es la propiedad margin?

2.¿Qué es la propiedad padding?

3.¿Qué es la propiedad border?

4.¿Qué es la propiedad border-radius?

5.¿Qué unidades de medida se pueden utilizar para las propiedades de espaciado?

#Ejercicio
```
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Propiedades de espaciado</title>
  <link rel="stylesheet" href="estilos.css">
</head>
<body>
    <h1>café</h1>
<div class="contenedor">
<div class="elemento"></div>
    
  </div>
</body>
</html>
```
```
.contenedor {
    width: 800px;
    height: 700px;
  }
  
  .elemento {
    border-radius: 10px;
    border: 10px solid red ;
    padding: 200px;
    margin: 100px;
    width: 100px;
    height: 100px;
   
  }
```
 ###  1.¿Qué es la propiedad margin?

 La propiedad "margin" es una propiedad CSS (Cascading Style Sheets) que se utiliza para establecer el espacio en blanco alrededor de un elemento HTML. Esta propiedad controla el espacio exterior de un elemento, es decir, el espacio que lo separa de otros elementos circundantes en la página web.

### 2.¿Qué es la propiedad padding?
La propiedad "padding" es una propiedad CSS (Cascading Style Sheets) que se utiliza para establecer el espacio en blanco entre el contenido de un elemento HTML y su borde. En otras palabras, el "padding" controla el espacio interior de un elemento, la distancia entre el contenido y el borde del elemento.

### 3.¿Qué es la propiedad border?
La propiedad "border" es una propiedad CSS (Cascading Style Sheets) que se utiliza para establecer las características del borde alrededor de un elemento HTML, como un div, un botón, una imagen u otros elementos. El borde es una parte importante del diseño de la interfaz de usuario en una página web, ya que puede ayudar a resaltar o separar elementos, proporcionar estructura visual y mejorar la estética general de la página.

### 4.¿Qué es la propiedad border-radius?
La propiedad "border-radius" es una propiedad CSS que se utiliza para redondear las esquinas de un elemento con bordes, como un div, un botón, una imagen u otros elementos. Permite darle una apariencia más suave y estilizada a los bordes de un elemento, creando esquinas redondeadas en lugar de esquinas afiladas. Esta propiedad es especialmente útil para crear diseños modernos y atractivos en sitios web y aplicaciones.

### 5.¿Qué unidades de medida se pueden utilizar para las propiedades de espaciado?
En CSS, se pueden utilizar varias unidades de medida para establecer propiedades de espaciado como "margin", "padding", "border-width" y otras. Estas unidades de medida permiten definir dimensiones y espacios en una página web de manera precisa. Algunas de las unidades de medida más comunes incluyen:

Píxeles (px): Esta es la unidad de medida más común y se utiliza ampliamente. Un píxel es la unidad más pequeña de una pantalla y se adapta bien para establecer tamaños y espacios precisos. Por ejemplo, margin: 10px; establece un margen de 10 píxeles.

Porcentaje (%): Las unidades de porcentaje son relativas al tamaño del contenedor padre. Por ejemplo, width: 50%; hará que un elemento ocupe el 50% del ancho de su contenedor padre.

Em (em): El "em" es una unidad relativa basada en el tamaño de fuente del elemento. Un valor de 1em es igual al tamaño de fuente actual, por lo que margin: 1em; establecerá un margen igual al tamaño de fuente actual.

Rem (rem): Similar a "em", pero se basa en el tamaño de fuente del elemento raíz (generalmente el tamaño de fuente del elemento <html>). Es útil para mantener una consistencia en el diseño en toda la página.

Viewport Width (vw) y Viewport Height (vh): Estas unidades son relativas al tamaño de la ventana gráfica del navegador. width: 50vw; hará que un elemento ocupe el 50% del ancho de la ventana gráfica.

Viewport Minimum (vmin) y Viewport Maximum (vmax): Estas unidades se basan en el tamaño mínimo y máximo de la ventana gráfica. Por ejemplo, width: 50vmin; hará que un elemento ocupe el 50% del tamaño más pequeño entre el ancho y la altura de la ventana gráfica.

Centímetros (cm), milímetros (mm), pulgadas (in), puntos (pt) y picas (pc): Estas son unidades de medida absolutas y se utilizan principalmente para propósitos de impresión y diseño gráfico. Sin embargo, su uso en diseño web es menos común debido a la variabilidad en el tamaño de pantalla de los dispositivos.

Fracciones de la unidad de espacio disponible (fr): Se utilizan en contextos de diseño de diseño flexible y grid layout para dividir el espacio disponible en fracciones. Por ejemplo, grid-template-columns: 1fr 2fr; divide las columnas en una proporción de 1:2.

La elección de la unidad de medida depende del contexto y de los objetivos de diseño de tu página web. Debes considerar factores como la accesibilidad, la respuesta en diferentes dispositivos y la estética general de tu diseño al seleccionar la unidad de medida adecuada.





