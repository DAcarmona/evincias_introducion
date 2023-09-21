<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 5 


<!-- Su documentación aquí -->
# Formulario HTML
Los formularios HTML son elementos de una página web que permiten a los usuarios introducir datos. Estos datos pueden ser enviados a un servidor web para su procesamiento, o pueden utilizarse para realizar acciones en el lado del cliente.

Los formularios HTML están formados por uno o más controles de formulario. Los controles de formulario son elementos que permiten a los usuarios introducir datos de diferentes tipos, como texto, números, fechas, etc.

# Diseñó de un formulario
Al diseñar un formulario HTML, hay una serie de factores a tener en cuenta:

+  La finalidad del formulario: ¿Qué datos desea recopilar del usuario? ¿Cómo se utilizarán estos datos?
+ El público objetivo: ¿Quién utilizará el formulario? ¿Qué nivel de alfabetización tecnológica tienen?
+ La usabilidad: El formulario debe ser fácil de usar y comprender.
# Ejemplo de formulario
```
<form action="example.php" method="post">
  <label for="nombre">Nombre:</label>
  <input type="text" name="nombre" id="nombre" placeholder="Nombre">
  <label for="email">Correo electrónico:</label>
  <input type="email" name="email" id="email" placeholder="Correo electrónico">
  <label for="edad">Edad:</label>
  <input type="number" name="edad" id="edad" placeholder="Edad">
  <input type="submit" value="Enviar">
</form>
```

# Etiqueta de formularios
## La etiqueta `<form>`
La etiqueta `<form>` en HTML5 define un formulario web. Un formulario web es un elemento de una página web que permite a los usuarios introducir datos. Estos datos pueden ser enviados a un servidor web para su procesamiento, o pueden utilizarse para realizar acciones en el lado del cliente.

La etiqueta `<form>` tiene los siguientes atributos obligatorios:

+ action: Especifica la URL del archivo en el servidor web al que se enviarán los datos del formulario.
+ method: Especifica el método HTTP que se utilizará para enviar los datos del formulario. Los métodos HTTP más comunes son post y get.
La etiqueta `<form>` también tiene los siguientes atributos opcionales:

+ enctype: Especifica el tipo de codificación de datos que se utilizará para enviar los datos del formulario.
+ name: Especifica el nombre del formulario. Este nombre se utiliza para identificar el formulario en el código del servidor.
+ autocomplete: Especifica si el navegador debe rellenar automáticamente los campos del formulario.
# La etiqueta `<label>`
La etiqueta `<label>` de HTML se utiliza para asociar una etiqueta con un elemento de formulario. La etiqueta `<label>` se utiliza para proporcionar una etiqueta para un control de entrada, lo que ayuda a los usuarios a comprender la función del control de entrada.

La etiqueta `<label>` tiene los siguientes atributos obligatorios:

for: Especifica el id del elemento de formulario al que se asocia la etiqueta. La etiqueta <label> también tiene los siguientes atributos opcionales:

+ accesskey: Especifica una tecla de acceso para la etiqueta.
+ tabindex: Especifica el índice de tabulación de la etiqueta.

Para asociar una etiqueta con un control de entrada, colocamos la etiqueta `<label>` junto al control de entrada y especificamos el id del control de entrada en el atributo for de la etiqueta `<label>`.

Por ejemplo, el siguiente código crea un checkbox con el nombre "intereses" y el valor "deporte" y lo asocia con una etiqueta con el texto "Deportes":
```
<input type="checkbox" name="intereses" value="deporte" id="deportes">
<label for="deportes">Deportes</label>
```
La etiqueta "Deportes" se muestra junto al checkbox. Cuando el usuario hace clic en el checkbox, la etiqueta "Deportes" también se activa.

El atributo for de la etiqueta `<label>` es obligatorio para que la etiqueta `<label>` funcione correctamente. Si no especificamos el atributo for, la etiqueta `<label>` no se asociará con ningún elemento de formulario.

La etiqueta `<label>` es una herramienta importante para mejorar la accesibilidad de los formularios web. Al asociar una etiqueta con un control de entrada, podemos proporcionar una etiqueta para el control de entrada, lo que ayuda a los usuarios a comprender la función del control de entrada.

# La etiqueta `<input>`
La etiqueta `<input>` de HTML se utiliza para crear controles interactivos para formularios web. Los controles de entrada pueden ser campos de texto, botones de radio, casillas de verificación, listas desplegables, etc.

La etiqueta `<input>` tiene los siguientes atributos obligatorios:

type: Especifica el tipo de control de entrada. Los tipos de control de entrada más comunes son text, password, radio, checkbox, submit, reset y file. name: Especifica el nombre del control de entrada. Este nombre se utiliza para identificar el control de entrada en el código del servidor. La etiqueta `<input>` también tiene los siguientes atributos opcionales:

+ value: Especifica el valor inicial del control de entrada.
+ checked: Especifica si el control de entrada está marcado o no.
+ disabled: Especifica si el control de entrada está deshabilitado o no.
+ readonly: Especifica si el control de entrada es de solo lectura o no.
+ size: Especifica el tamaño del control de entrada.
+ maxlength: Especifica la longitud máxima del valor del control de entrada.
+ placeholder: Especifica un texto que se muestra en el control de entrada cuando está vacío.
+ autocomplete: Especifica si el navegador debe rellenar automáticamente el control de entrada.
+ autofocus: Especifica el control de entrada que debe tener el foco cuando la página se carga.

Además de estos atributos, la etiqueta `<input>` también admite una serie de atributos aria para mejorar la accesibilidad de los controles de entrada para las personas con discapacidades.

### Ejemplos de la etiqueta input:
### Texto
`<input type="text" name="nombre" placeholder="Nombre">
<label for="nombre">Nombre</label>`

### Contraseña
`<input type="password" name="contraseña" placeholder="Contraseña">
<label for="contraseña">Contraseña</label>`

### Radio
`<input type="radio" name="sexo" value="hombre"> Hombre
<label for="hombre">Hombre</label>
<input type="radio" name="sexo" value="mujer"> Mujer
<label for="mujer">Mujer</label>`

### Casilla de verificación
`<input type="checkbox" name="intereses" value="deporte"> Deportes
<label for="intereses">Deportes</label>
<input type="checkbox" name="intereses" value="cine"> Cine
<label for="cine">Cine</label>`

### Botón de envío
`<input type="submit" value="Enviar">
<label for="enviar">Enviar</label>`

### Botón de reinicio
`<input type="reset" value="Restablecer">
<label for="restablecer">Restablecer</label>`

### Archivo
`<input type="file" name="archivo">
<label for="archivo">Archivo</label>`

### Color
`<input type="color" name="color">
<label for="color">Color</label>`

### Fecha
`<input type="date" name="fecha">
<label for="fecha">Fecha</label>`

### Hora
`<input type="time" name="hora">
<label for="hora">Hora</label>`

### Fecha y hora
`<input type="datetime-local" name="fecha_hora">
<label for="fecha_hora">Fecha y hora</label>`

### Semana
`<input type="week" name="semana">
<label for="semana">Semana</label>`

### Teléfono
`<input type="tel" name="teléfono">
<label for="teléfono">Teléfono</label>`

### Url
`<input type="url" name="sitio_web">
<label for="sitio_web">Sitio web</label>`

### Email
`<input type="email" name="correo_electrónico">
<label for="correo_electrónico">Correo electrónico</label>`

### Número
`<input type="number" name="edad">
<label for="edad">Edad</label>`

### Ejemplos de tipos de etiqueta input
```
<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <title>Ejemplos de la etiqueta input HTML5</title>
</head>

<body>
    <h1>Ejemplos de la etiqueta input HTML5</h1>

    <!-- Ejemplo de campo de texto con placeholder -->
    <div>
        <label for="nombre">Nombre</label>
        <input type="text" name="nombre" placeholder="Nombre" id="nombre">
    </div>

    <!-- Ejemplo de campo de contraseña con placeholder -->
    <div>
        <label for="contraseña">Contraseña</label>
        <input type="password" name="contraseña" placeholder="Contraseña" id="contraseña">

    </div>

    <!-- Ejemplo de botones de radio -->
    <div>
        <input type="radio" name="sexo" value="hombre" id="hombre">
        <label for="hombre">Hombre</label>
        <input type="radio" name="sexo" value="mujer" id="mujer">
        <label for="mujer">Mujer</label>
    </div>

    <!-- Ejemplo de casillas de verificación -->
    <div>
        <input type="checkbox" name="intereses" value="deporte" id="deporte">
        <label for="deporte">Deportes</label>
        <input type="checkbox" name="intereses" value="cine" id="cine">
        <label for="cine">Cine</label>
    </div>

    <!-- Ejemplo de botón de envío -->
    <div>
        <input type="submit" value="Enviar" id="enviar">
    </div>

    <!-- Ejemplo de control de entrada de archivo con placeholder -->
    <div>
        <input type="file" name="archivo" placeholder="Archivo" id="archivo">
    </div>

    <!-- Ejemplo de control de entrada de color -->
    <div>
        <input type="color" name="color" id="color">
        <label for="color">Color</label>
    </div>

    <!-- Ejemplo de control de entrada de fecha -->
    <div>
        <input type="date" name="fecha" id="fecha">
        <label for="fecha">Fecha</label>
    </div>

    <!-- Ejemplo de control de entrada de hora -->
    <div>
        <input type="time" name="hora" id="hora">
        <label for="hora">Hora</label>
    </div>

    <!-- Ejemplo de control de entrada de fecha y hora -->
    <div>
        <input type="datetime-local" name="fecha_hora" id="fecha_hora">
        <label for="fecha_hora">Fecha y hora</label>
    </div>

    <!-- Ejemplo de control de entrada de semana -->
    <div>
        <input type="week" name="semana" id="semana">
    </div>

    <!-- Ejemplo de control de entrada de teléfono con placeholder -->
    <div>
        <input type="tel" name="teléfono" placeholder="Teléfono" id="teléfono">
        <label for="teléfono">Teléfono</label>
    </div>

    <!-- Ejemplo de control de entrada de URL con placeholder -->
    <div>
        <input type="url" name="sitio_web" placeholder="Sitio web" id="sitio_web">
        <label for="sitio_web">Sitio web</label>
    </div>

    <!-- Ejemplo de control de entrada de número con placeholder -->
    <div>
        <input type="number" name="edad" placeholder="Edad" id="edad">
        <label for="edad">Edad</label>
    </div>

</body>

</html>
```


# La etiqueta `<textarea>`
La etiqueta `<textarea>` HTML5 se utiliza para crear un control de entrada de texto de varias líneas. Los textarea input se utilizan a menudo para recopilar comentarios, reseñas, o otro tipo de texto largo.

La etiqueta textarea tiene los siguientes atributos:

+ name: Especifica el nombre del control de entrada. El nombre del control de entrada se utiliza para identificar el control de entrada en el formulario.
+ id: Especifica el ID del control de entrada. El ID del control de entrada se utiliza para identificar el control de entrada en el código JavaScript.
+ placeholder: Especifica un texto predeterminado que se muestra en el control de entrada cuando está vacío.
+ rows: Especifica el número de filas del textarea input.
+ cols: Especifica el número de columnas del textarea input.
+ maxlength: Especifica la longitud máxima del texto que se puede ingresar en el textarea input.
+ minlength: Especifica la longitud mínima del texto que se puede ingresar en el textarea input.
+ required: Especifica si el textarea input es obligatorio.
+ disabled: Especifica si el textarea input está deshabilitado.
+readonly: Especifica si el textarea input está bloqueado para escritura.

El siguiente código muestra un ejemplo de textarea input HTML5:

`<textarea name="comentarios" id="comentarios" placeholder="Ingrese sus comentarios aquí" rows="10" cols="50"></textarea>`


Este código creará un textarea input con 10 filas y 50 columnas. El usuario podrá ingresar hasta 500 caracteres en el textarea input.

Los textarea input HTML5 son una herramienta útil para recopilar texto largo de los usuarios.

# `La etiqueta <select>`
La etiqueta `<select>` HTML5 se utiliza para crear un menú desplegable. Los menús desplegables se utilizan a menudo para recopilar una selección de opciones de los usuarios.

La etiqueta `<select>` tiene los siguientes atributos:

+ name: Especifica el nombre del control de entrada. El nombre del control de entrada se utiliza para identificar el control de entrada en el formulario.
+ id: Especifica el ID del control de entrada. El ID del control de entrada se utiliza para identificar el control de entrada en el código JavaScript.
+ multiple: Especifica si el usuario puede seleccionar más de una opción del menú desplegable.
+ size: Especifica el número de opciones que se muestran en el menú desplegable de forma predeterminada.
+ required: Especifica si el menú desplegable es obligatorio.
+ disabled: Especifica si el menú desplegable está deshabilitado.
+ readonly: Especifica si el menú desplegable está bloqueado para escritura.
El siguiente código muestra un ejemplo de select input HTML5:
```
<select name="color" id="color">
  <option value="rojo">Rojo</option>
  <option value="verde">Verde</option>
  <option value="azul">Azul</option>
</select>
```
Este código creará un menú desplegable con tres opciones: rojo, verde y azul. El usuario puede seleccionar una opción del menú desplegable.

También puede utilizar el atributo multiple para permitir que el usuario seleccione más de una opción del menú desplegable. Por ejemplo, el siguiente código creará un menú desplegable con tres opciones, y el usuario podrá seleccionar todas las opciones que desee:
```
<select name="colores" id="colores" multiple>
  <option value="rojo">Rojo</option>
  <option value="verde">Verde</option>
  <option value="azul">Azul</option>
</select>
```

Los menús desplegables HTML5 son una herramienta útil para recopilar una selección de opciones de los usuarios.

# La etiqueta `<option>`
La etiqueta `<option>` HTML5 se utiliza para crear una opción en un menú desplegable. Las opciones se utilizan para recopilar una selección de opciones de los usuarios.

La etiqueta <option> tiene los siguientes atributos:

+ value: Especifica el valor de la opción. El valor de la opción se envía al servidor cuando el usuario selecciona la opción.
+ label: Especifica el texto que se muestra en la opción.
+ selected: Especifica si la opción está seleccionada de forma predeterminada.
+ disabled: Especifica si la opción está deshabilitada.
+ readonly: Especifica si la opción está bloqueada para escritura.
El siguiente código muestra un ejemplo de etiqueta option HTML5:
```
<option value="rojo">Rojo</option>
<option value="verde">Verde</option>
<option value="azul">Azul</option>
```

Este código creará tres opciones de menú desplegable: rojo, verde y azul. El atributo value especifica el valor de cada opción. El atributo label especifica el texto que se muestra en cada opción.

También puede utilizar el atributo selected para seleccionar una opción de forma predeterminada. Por ejemplo, el siguiente código seleccionará la opción rojo de forma predeterminada:
```
<option value="rojo" selected>Rojo</option>
<option value="verde">Verde</option>
<option value="azul">Azul</option>
```
Las etiquetas option HTML5 son una herramienta útil para recopilar una selección de opciones de los usuarios.

# La etiqueta `<button>`
La etiqueta `<button>` HTML5 se utiliza para crear un botón. Los botones se utilizan para realizar acciones, como enviar un formulario, abrir una nueva pestaña o ventana, o iniciar un proceso.

La etiqueta `<button>` tiene los siguientes atributos:

+ type: Especifica el tipo de botón. Los tipos de botón comunes incluyen submit, reset, y button.
+ name: Especifica el nombre del botón. El nombre del botón se utiliza para identificar el botón en el formulario.
+ id: Especifica el ID del botón. El ID del botón se utiliza para identificar el botón en el código JavaScript.
+ value: Especifica el valor del botón. El valor del botón se envía al servidor cuando el usuario hace clic en el botón.
+ disabled: Especifica si el botón está deshabilitado.

El siguiente código muestra un ejemplo de etiqueta `<button>` HTML5:

`<button type="submit" value="Enviar">Enviar</button>`

Este código creará un botón que dice "Enviar". El botón es del tipo submit, lo que significa que enviará el formulario al servidor cuando el usuario haga clic en él. El valor del botón es "Enviar", que se enviará al servidor cuando el usuario haga clic en el botón.

También puede utilizar el atributo type para especificar el tipo de botón. Los tipos de botón comunes incluyen:

+ submit: Este tipo de botón envía el formulario al servidor cuando el usuario hace clic en él.
+ reset: Este tipo de botón restablece el formulario a su estado inicial cuando el usuario hace clic en él.
+ button: Este tipo de botón no tiene una función predefinida.
 El botón se puede utilizar para realizar cualquier acción deseada.

Los botones HTML5 son una herramienta útil para realizar acciones en una página web.

Resumen etiquetas HTML

# Actividad: Diseñar un formulario de pedido de un producto
Objetivo:

Aplicar los conocimientos sobre los tipos de etiquetas HTML para diseñar un formulario de pedido de un producto.

Instrucciones:

1. Crear un nuevo documento HTML.

2. Crear un formulario con los siguientes campos:

+ Nombre del producto
+ Cantidad
+ Precio unitario
+ Precio total
+ Dirección de envío
+ Información de contacto (nombre, correo electrónico, número de teléfono)
Agregar los siguientes campos relacionados al formulario:
+ Método de pago
+ Fecha de entrega
+ Comentarios

Utilizar las etiquetas HTML apropiados para cada campo.
Previous

# Actividad
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
    <h1>FORMULARIO</h1>
    <form action="example.php" method="post">
        <div>
            <label for="nombre del producto">Nombre del producto:</label>
            <input type="text" name="nombre" id="nombre">
        </div><br>

        <div>
            <label for="cantidad">Cantidad</label>
            <input type="text" name="nombre" id="nombre">
        </div><br>

        <div>
            <label for="precio unitario">Prcio unitario</label>
            <input type="text" name="precio unitario" id="precio unitario">
        </div><br>

        <div>
            <label for="precio total">Precio total</label>
            <input type="text" name="precio total" id="precio total">
        </div><br>

        <div>
            <label for="dirección de envío">Dirección de envío</label>
            <input type="text" name="dirección de envío" id="dirección de envío">
        </div><br>
        <h2>Información de contacto</h2><br>

        <div>
            <label for="nombre">Nombre</label>
            <input type="text" name="nombre" id="nombre">
        </div><br>

        <div>

            <label for="correo_electrónico">Correo electrónico</label>
            <input type="email" name="correo_electrónico">
        </div><br>

        <div>
            <label for="numero de contácto">Numero de contácto</label>
            <input type="text" name="nomero de contácto" id="numero de contácto">
        </div><br>
        <div>
            <select>
                <option value="metodos de pago">Metodos de pago</option>
                <option value="efectivo">Efectivo</option>
                <option value="tarjeta">Tarjeta</option>
                <option value="creédito">Creédito</option>
            </select>
        </div><br>
        <div>
            <label for="fecha">Fecha</label>
            <input type="date" name="fecha">
        </div><br>

        <div>
            <textarea name="comentarios" id="comentarios" placeholder="Ingrese sus comentarios aquí" rows="10"
                cols="50"></textarea>

        </div><br>


        <div>
            <input type="submit" value="Enviar">
        </div>
    </form>
</body>

</html>
```






