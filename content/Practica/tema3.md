---
title: "Tema3"
date: 2021-11-20T21:24:25+01:00
draft: false
weight: 3

---

## TAREA 3

### Hierramientas para desarrollo web

## **1. Babel/ WebPack/ Prototype/ Polyfill**

### ***Babel***

Babel es un compilador de JavaScript que puede traducir lenguajes de programación o de marcado a JavaScript.

{{< tabs >}}
{{% tab name="JCódigo introducido" %}}
```
[1, 2, 3].map(n => n + 1);

```
{{% /tab %}}
{{% tab name="Salida Babel" %}}
```
[1, 2, 3].map(function(n) {
  return n + 1;

```
{{% /tab %}}
{{< /tabs >}}

> Página oficial: [Babel](https://babeljs.io/)


### ***WebPack***

Webpack es una herramienta de compilación que coloca todos los *assets*, incluso Javascript, imágenes, fuentes y CSS, en un gráfico de dependencia. Webpack usa la funcción require () para apuntar a archivos locales, como imágenes, y decidir cómo se procesan en el paquete Javascript final.

![WebPack schema](https://miro.medium.com/max/1838/1*BMzCIp_YZxE1u-L8ozqrZg.png)


>Página oficial: [WebPack](https://webpack.js.org/)


### ***Prototype***

Prototype proporciona varias funciones para desarrollar aplicaciones JavaScript, por ejemplo funciones de biblioteca para admitir clases y objetos basados ​​en clases. 

***Video tutorial sobre Prototype***

{{<youtube 4jb4AYEyhRc>}}

> Página oficial: [Prototype](http://prototypejs.org/)


### ***Polyfill***

Es un servicio que acepta una solicitud de un conjunto de funciones del navegador y devuelve solo los *olyfills* que necesita el navegador solicitante.

{{% notice note %}}
 **Polyfill** es un código que implementa una función en los navegadores web que no son compatibles con la función.
{{% /notice %}}

> Página oficial [Polyfill](https://polyfill.io/v3/)



## 2. PHP/ Frameworks de php

### ***PHP***

PHP es un lenguaje de programación del lado del servidor. que se utiliza para desarrollar sitios web estáticos o sitios web dinámicos o aplicaciones web. Los scripts PHP solo se pueden interpretar en un servidor que tenga PHP instalado.

{{< tabs >}}
{{% tab name="PHP código" %}}
```
<?php
$var = 'Bob';
$Var = 'Joe';
echo "$var, $Var"; 
?>

```
{{% /tab %}}
{{% tab name="Salida" %}}
```
Bob, Joe
```
{{% /tab %}}
{{< /tabs >}}

> Página oficial: [PHP](https://www.php.net/)


### ***Frameworks de php***
* Laravel
* Symfony
* CodeIgniter
* Zend Framework / Laminas Project
* Yii (Framework)
* CakePHP


## 3. DJango/  JSP/  Css/ Bootstrap

### ***DJango***

Django es un marco web Python de alto nivel que permite el desarrollo rápido de sitios web seguros y fáciles de mantener. Es gratuito y de código abierto, tiene una comunidad activa y próspera, excelente documentación y muchas opciones de soporte gratuito y de pago..

{{% notice info %}}
Para crear tu primer projecto con Django, desde Coomand line escribe el comando:

```
$ django-admin startproject mysite
```
{{% /notice %}}

Página oficial [DJango](https://www.djangoproject.com/)



### ***JSP***

JSP (Java Server Pages) es una tecnología que ayuda a los desarrolladores de software a crear páginas web dinámicas basadas en HTML y XML, entre otros tipos de documentos. JSP es similar a PHP, pero usa el lenguaje de programación Java.
Java Server Pages (JSP) es una tecnología que nos permite mezclar HTML estático con HTML generado dinámicamente.

![JSP schema](https://sites.google.com/site/javawebec/_/rsrc/1322799602850/home/jsp/jsp.png.1322799602749.png?height=233&width=320)


> Saber más sobre [JSP](https://www.tutorialspoint.com/jsp/index.htm)


### ***CSS***

CSS es el lenguaje que usamos para diseñar un documento HTML. CSS describe cómo se deben mostrar los elementos HTML.


***Sintaxis CSS***
```
p {
  margin-top: 100px;
  margin-bottom: 100px;
  margin-right: 150px;
  margin-left: 80px;
}
```

Saber más sobre [CSS](https://www.w3schools.com/css/)



### ***Bootstrap***

Bootstrap permite cerar rápidamente sitios receptivos que se adapta a las medidas de la pantalla del despositivo.

![Bootstrap schema](https://mobomo.s3.amazonaws.com/uploads/2017/09/BlogArticle-BootstrapGrid.png)

Página oficial [Bootstrap](https://getbootstrap.com/)


## 4. Vue/ React/ Angular/ JavaScript/ TypeScript/  JQuery

### ***Vue***

Vue.js es un framework de JavaScript, que se utiliza para crear UI (interfaces de usuario) y SPA (aplicaciones de una sola página). Es una biblioteca tan fácil de aprender y con el conocimiento de HTML, CSS y JavaScript, podemos comenzar a construir aplicaciones web en Vue.js.

***Video tutorial sobre Vue***

{{<youtube YrxBCBibVo0>}}


Página oficial: [Vue](https://vuejs.org/)



### ***React***

React js es una biblioteca de JavaScript de código abierto que se utiliza para crear interfaces de usuario (UI). React permite a los desarrolladores crear grandes aplicaciones web que pueden cambiar datos, sin recargar la página. El objetivo principal de React es ser rápido, escalable y simple.

***Sintaxis React***

```
class ShoppingList extends React.Component {
  render() {
    return (
      <div className="shopping-list">
        <h1>Lista de compras para {this.props.name}</h1>
        <ul>
          <li>Instagram</li>
          <li>WhatsApp</li>
          <li>Oculus</li>
        </ul>
      </div>
    );
  }
}

// Uso de ejemplo: <ShoppingList name="Mark" />
```

Página oficial: [React](https://reactjs.org/)



### ***Angular***

Angular es un framework de JavaScript de código abierto escrito en TypeScript. Permite a los usuarios crear aplicaciones de gran tamaño de forma sostenible.

{{% notice tip %}}
**Que es framework?**
Framework es una estructura previa que se puede aprovechar para desarrollar un proyecto.
El Framework es una especie de plantilla, un esquema conceptual, que simplifica la elaboración de una tarea, ya que solo es necesario complementarlo de acuerdo a lo que se quiere realizar.
{{% /notice %}}

Página oficial [Angular](https://angular.io/features)


### ***Javascript***



```

```

Página oficial [JavaScript](https://www.javascript.com/)






