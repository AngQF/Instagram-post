# ![4Geeks Logo](http://assets.breatheco.de/apis/img/images.php?blob&random&cat=icon&tags=4geeks,16) HTML Hello

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io#https://github.com/4GeeksAcademy/html-hello.git)

The most basic boilerplate for any 4Geeks Academy student using the [gitpod.io](gitpod.io) coding editor.

[![How to open html/css preview of my project in gitpod](https://github.com/4GeeksAcademy/Templates-Boilerplates/blob/master/assets/hello-html-intro.png?raw=true)](https://youtu.be/dfbDCMu_p-0)

## What to do next?

Create an `index.html` file with the [basic HTML structure](http://content.breatheco.de/lesson/what-is-html-learn-html#page-structure) and see it live by running a web-server using the following command:

```sh
$ pip3 install flask && python3 server.py
```

- You can create as many HTML files as you want
- You can also create CSS files and import them into your website using a `<link>` tag placed between the `<head></head>` tags, like this:

```html
<head>
  ...
  <link rel="stylesheet" type="text/css" href="styles.css">
  ...
</head>
```

EXPLICACIÓN :

En head puse el link de google fonts y el de los iconos de font awesome.

Puse un div general que contuviera todo el contenido del post y luego lo separé por partes (header, img, body).

-header: aquí puse todo lo que iba antes de la imagen. Y lo volví a separar en distintos divs,uno para el icono del logo de html5, otro para el texto que acompaña al logo y en el último el icono de los tres puntos. Y en css con los márgenes y medidas de ancho y alto, lo ajusté para que se viera como en el ejemplo.

-img: en este div puse la imagen con el mismo ancho que el div general para que se extendiera de lado a lado.

-body: como en header, lo dividí en varios divs:
uno para la línea donde solo hay iconos, que a su vez lo dividí en un div por cada icono; para en css poderlos editar más fácil. Y lo último, los dos <p>.

