<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 4


<!-- Su documentación aquí -->

# Tablas en HTML5
Las tablas HTML se utilizan para mostrar datos en formato tabular. Se componen de filas `(<tr>)` y columnas `(<td> o <th>)`.

+ `<table>`:
 Esta etiqueta representa la tabla en su conjunto. Dentro de ella deben incluirse las etiquetas `<tr>` y `<td> o <th>`.
+ `<tr>`: Esta etiqueta representa una fila de la tabla. Dentro de ella deben incluirse las etiquetas `<td> o <th>`.
+ `<td>`: Esta etiqueta representa una celda de la tabla que contiene datos.
+ `<th>`: Esta etiqueta representa una celda de la tabla que contiene encabezados.
## `<table>`
En HTML5, la etiqueta <table> se utiliza para representar una tabla. Las tablas se utilizan para mostrar datos de forma organizada en filas y columnas.

La etiqueta `<table>` tiene una serie de atributos que se pueden utilizar para personalizar su apariencia y comportamiento. Estos atributos incluyen:

+ border: Este atributo especifica el ancho del borde de la tabla.
+ cellpadding: Este atributo especifica el espacio entre el contenido de una celda y su borde.
+ cellspacing: Este atributo especifica el espacio entre las celdas de una tabla.
+ align: Este atributo especifica la alineación del contenido de la tabla.
+ valign: Este atributo especifica la alineación vertical del contenido de la tabla.
Además de los atributos mencionados anteriormente, la etiqueta <table> tiene un atributo obsoleto llamado bgcolor. Este atributo se utilizaba para especificar el color de fondo de la tabla. En HTML5, el color de fondo de la tabla se puede especificar utilizando CSS.

## `<thead> y <tbody>`
Las etiquetas `<thead> y <tbody>` se utilizan para organizar el contenido de la tabla en secciones.

+ `<thead>`: Esta etiqueta representa la cabecera de la tabla.
+ `<tbody>`: Esta etiqueta representa el cuerpo de la tabla.
## `<tr>, <td> y <th>`
Las tablas HTML se componen de filas y columnas. Las filas se definen mediante la etiqueta `<tr>` y las columnas se definen mediante la etiqueta `<td> o <th>`.

La etiqueta <td> se utiliza para representar una celda de datos. La etiqueta <th> se utiliza para representar una celda de encabezado.

Las celdas de una tabla se pueden combinar utilizando los atributos colspan y rowspan. El atributo colspan especifica la cantidad de columnas que una celda ocupará. El atributo rowspan especifica la cantidad de filas que una celda ocupará.

A continuación se muestra un ejemplo de una tabla HTML:
```
<table border="1" cellpadding="5" cellspacing="10">
  <thead>
    <tr>
      <th>Nombre</th>
      <th>Apellido</th>
      <th>Edad</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Juan</td>
      <td>Pérez</td>
      <td>20</td>
    </tr>
    <tr>
      <td>María</td>
      <td>González</td>
      <td>25</td>
    </tr>
  </tbody>
</table>
```
# Atributos colspan y rowspan

Los atributos colspan y rowspan se utilizan en HTML para combinar celdas de una tabla. El atributo colspan especifica la cantidad de columnas que una celda ocupará, mientras que el atributo rowspan especifica la cantidad de filas que una celda ocupará.

Ejemplo
```
<table border="1">
    <thead>
      <tr>
        <th rowspan="2">Cabecera</th>
        <th colspan="2">Columna 1</th>
      </tr>
      <tr>
        <th>Subcolumna 1</th>
        <th>Subcolumna 2</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td rowspan="2">Celda fusionada</td>
        <td>Contenido 1</td>
        <td rowspan="2">Celda fusionada</td>
      </tr>
      <tr>
        <td>Contenido 2</td>
      </tr>
      <tr>
        <td colspan="2">Totales</td>
        <td>Subtotal</td>
        <td>Impuestos</td>
      </tr>
    </tbody>
  </table>
  ```
  # Actividad: ## Crear una tabla HTML con información sobre productos.
Escribir una tabla HTML con 10 filas que muestre información sobre productos reales. La tabla debe tener las siguientes columnas:

+ Código
+ Nombre
+ Descripción
+ Precio
+ Stock
+ Fecha de creación

Además, combinar celdas en la tabla con los atributos rowspan y colspan, como se muestra en la siguiente imagen.


# Actividad

```
<table border="1">
    <thead>
      <tr>
        <th>Codigo</th>
        <th>Nombre</th>
        <th>Descripción</th>
        <th>Precio</th>
        <th>Stock</th>
        <th>Fecha de creación</th>
      </tr>
  
      
    </thead>
    <tbody>
      <tr>
        <td>0001</td>
        <td>iphone 14 Pro max</td>
        <td>El iphone 14 Pro max es el smartphone mas potente del mercado.cuenta con
          una pantalla OLED de 6,7 pulgadas, un procesador A 16 Bionic y un sistema cámaras de
           48 megapixeles
        </td>
        <td>4.899.000 COP</td>
        <td>10</td>
        <td>2022-09-21</td>
        
      </tr>
      
      <tr>
        <td>0002</td>
        <td>MackBook Pro M2Pro</td>
        <td>El iphone 14 Pro Max esta disponible en cuatro colores: grafito, plata. oro y 
          sierra </td>
        <td>100</td>
        
        
      </tr>
      <tr>
        <td>010</td>
        <td>Nintendo Switch OLED</td>
        <td>El MackBook pro. Es el nuevo portatil profesional de apple cuenta con
          el procesador M2 pro, una pantalla liquid retina XDR y un sistema de
         cámaras TrueDepth con cámara Face time HD.
        </td>
        <td>10.499.000 COP</td>
        <td>10</td>
        <td>2023-06-06</td>
        </tr>
        <tr>
          <td>004</td>
          <td></td>
          
        <td>MackBook Pro M2Pro esta disponible en dos colores: Gris especial y plata.</td>
        <td>75</td>
        </tr>

        <tr>
          <td>005</td>
          <td></td>
          
          <td>La nintendo switch OLED es la versión mejorada de la consola Nintendo
            Switch cuenta con una pantalla OLED de 7 pulgadas, mas almacenamiento y
             un soporte  ajustable.
             <td>1.099.000 COP</td>
             <td>10</td>
             <td>2021-10-08</td>
          </td>
        </tr>

        <tr>
          <td>006</td>
          <td></td>
          
          <td>La Nintendo Switch OLED esta disponible en dos colores: Blanco y Negro</td>
          <td>75</td>
        </tr>

        
      </tr>
    </tbody>
  </table>
  ```
  ```
<table border="1" cellpadding="3" cellspacing="5">
  <thead>
    <tr>
      <th>Codigo</th>
      <th>Nombre</th>
      <th>Descripcion</th>
      <th>Precio</th>
      <th>Stock</th>
      <th>Fecha de creacion</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>001</td>
      <td>Aguacate</td>
      <td>hass</td>
      <td>3000</td>
      <td>100</td>
      <td>26/08/2023</td>
    </tr>
    <tr>
      <td>002</td>
      <td>Café</td>
      <td>Molido</td>
      <td>12000</td>
      <td>500</td>
      <td>26/08/2023</td>
    </tr>
    <tr>
      <td>003</td>
      <td>Granadilla</td>
      <td>Amarilla</td>
      <td>1500</td>
      <td>30</td>
      <td>26/08/2023</td>
    </tr>
    <tr>
      <td>004</td>
      <td>Manzana</td>
      <td>Verde</td>
      <td>2000</td>
      <td>50</td>
      <td>26/08/2023</td>
    </tr>
    <tr>
      <td>005</td>
      <td>Lulo</td>
      <td>Injerto</td>
      <td>4000</td>
      <td>500</td>
      <td>26/08/2023</td>
    </tr>
    <tr>
      <td>006</td>
      <td>Durazno</td>
      <td>Criollo</td>
      <td>1500</td>
      <td>100</td>
      <td>26/08/2023</td>
    </tr>
    <tr>
      <td>007</td>
      <td>Papa</td>
      <td>Capira</td>
      <td>3600</td>
      <td>500</td>
      <td>26/08/2023</td>
    </tr>
    <tr>
      <td>008</td>
      <td>Uva</td>
      <td>Chilena</td>
      <td>10000</td>
      <td>500</td>
      <td>26/08/2023</td>
    </tr>
    <tr>
      <td>009</td>
      <td>Maracuyá</td>
      <td>Tradicional</td>
      <td>7000</td>
      <td>800</td>
      <td>26/08/2023</td>
    </tr>
    <tr>
      <td>0010</td>
      <td>Mango</td>
      <td>Tomy</td>
      <td>5000</td>
      <td>400</td>
      <td>26/08/2023</td>
    </tr>
  </tbody>
</table>
```





