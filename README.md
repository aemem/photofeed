
Es un feed the fotos mostrando posts individuales para cada imagen, uno debajo de otro. 

Tiene arriba un header con un h1 con el títilo de la página. Tiene un text-align center para centrar el texto, margin 0  y padding 5px.

Después hay una serie de posts. Cada post es un div con clase post y consta de un header, una imagen y un footer. Tiene margin auto para centrarlo horizontalmente y un margin-top para separarlo del elemento de encima. No tiene padding para que la foto ocupe todo el ancho. El header y el footer sí tienen padding.

El header del post tiene un h2 con el título de la foto y otro con la fecha. Utilicé float para que cada uno quedara a un lado.

La imagen ocupa todo el ancho del post y tiene su texto alternativo. 

El footer tiene un p con la descrición de la foto y un hashtag en negrita hecho con b.



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
