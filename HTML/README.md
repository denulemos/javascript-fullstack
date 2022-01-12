# HTML 5
**(Ejemplo 1)** 

Es un lenguaje de hipertexto, un lenguaje de notacion. Los navegadores al leer estos archivos HTML pueden reconocer los elementos mediante sus etiquetas o tags.

Habran distintos ejemplos de archivos HTML para abrir en el navegador y ver como estan hechos. En orden va de menos complejo a mas complejo. 

* Ejemplo encabezado: `<h1>Texto</h1>`, la etiqueta en este caso es el `h1`, la h hace referencia a **header**, mientras mayor el numero, menor su importancia como titulo. 

* Ejemplo parrafo: `<p>Parrafo</p>`

* Ejemplo Lista: El elemento `ul` se refiere a "Unorganized List", `ol` a "Organized List" (ya que estan numerados los elementos), y el tag `li` hace referencia a "List Item"
    ```
    <ul>
    <li>Primer elemento</li>
    <li>Segundo Elemento</li>
    </ul>
    ````

HTML no cambió mucho en el tiempo, hubieron versiones de acuerdo al crecimiento de la complejidad de la web en si misma. Para eso se creo la W3C (World Wide Web Consortium) que mantiene la especificacion que garantiza que una web pueda mostrarse en un navegador de forma correcta, que el estandar de HTML sea el mismo en todos lados, al igual que CSS. 

Actualmente esta la version 5 (2022). Es la version de la especificacion, no un nuevo HTML en si mismo. 

## Estructura principal de una pagina
**(Ejemplo 2)**

Para indicarle al navegador que el contenido de nuestro documento es HTML debemos iniciar su estructura con las siguientes cosas:

* Un DOCTYPE `<!DOCTYPE html>`, no es una etiqueta en si, es una instruccion para el navegador. Para versiones anteriores a HTML5, la instruccion es distinta.
* La etiqueta `<html>` que va a englobar a todo el documento HTML, con el `<head>` y el `<body>`, es el elemento padre. 
* `<head>` posee metadata, son datos acerca de los datos, cómo va a estar estructurada la pagina en terminos generales. No es visual y debe ir antes del `<body>`.

## Contenido de la pagina
**(Ejemplo 3)**

Es importante darle a la pagina una estructura de jerarquias correcta en lo que respecta a los headers, para que los motores de busqueda puedan indexar nuestra pagina de manera correcta, y muestre el contenido resumido de una forma correcta. 

`<h1>` es mas importante que `<h2>` y asi sucesivamente, misma logica para el indexado, para los lectores de pantalla, etc.. 

## Estructura HTML5
**(Ejemplo 4)**

Las etiquetas `main, footer, section, etc` fueron agregadas en HTML. 

* La etiqueta `main` marca la informacion mas relevante de la pagina, todo esto para que pueda ser indexada correctamente, que tome lo principal de la pagina, no cambia nada visualmente.
* La etiqueta `header` agrega elementos de encabezado, como logos, iconos, informacion del autor, agrupa algunos contenidos jerarquicamente de importante. Es menos "importante" que lo que hay dentro de `main`.