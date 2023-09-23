# Clase 01 - Parte I: Introducción al Desarrollo Web

## ¿Qué es el Diseño Web?

### Definición

Según Marie Quilly (2014):

> "Es la planificación y el diseño de páginas de internet con la interacción de medios como textos, imágenes, vídeos, sonido y enlaces a otras páginas web".

### Objetivos y Metodología

El diseño web se realiza para cumplir con un objetivo específico, como dar a conocer un producto o servicio. La información se presenta de una manera interactiva, amena y accesible.

### Estructura del Diseño Web

Quilly destaca tres conceptos clave en el diseño web:

1. **Navegabilidad**: Dirección y métodos para moverse de una página a otra.
2. **Interactividad**: Transición entre medios y aplicaciones.
3. **Arquitectura de la Información**: Organización de la información.

### Adaptabilidad

El diseño debe ser adaptable para que funcione en cualquier dispositivo.

```html
<!-- Ejemplo de código HTML adaptable -->
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

## Herramientas Básicas para el Diseño y Desarrollo Web

### Lenguajes para el Desarrollo Web

Se utilizan varios lenguajes, pero en este curso se cubrirán principalmente HTML y CSS.

#### ¿Qué es el HTML?

HTML es un lenguaje de marcado que se utiliza para estructurar contenido en la web. Se encarga solo de la estructura, no del diseño, que es tarea de CSS.

- **Etiqueta**: Palabra que etiqueta algo como un bloque de texto o imagen.
- **Atributo**: Característica especial que se asigna a una etiqueta.
- **Estructura**: Organización del lenguaje HTML.

```html
<!-- Ejemplo de código HTML -->
<!DOCTYPE html>
<html>
<head>
  <title>Mi Página</title>
</head>
<body>
  <h1>Hola Mundo</h1>
</body>
</html>
```

#### ¿Qué es el CSS?

CSS es el lenguaje de diseño gráfico para la web.

- **Estilo**: Atributos asignados al HTML.
- **Reglas**: Características que deben cumplir las sentencias.
- **Medidas**: Valores asignados a cada atributo.
- **Fuente**: Tipos de letras.

```css
/* Ejemplo de código CSS */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}
```

### ¿Qué es un lenguaje de programación?

Un lenguaje de programación es un sistema estructurado que permite procesar datos en información, basados en algoritmos. Ejemplos son PHP, JavaScript y Python.

## Conceptos Básicos sobre Internet

### Internet

Es una red global de computadoras interconectadas para compartir información.

### Navegador Web

Software que permite a los usuarios navegar en la web. Ejemplos incluyen Google Chrome, Firefox y Safari.

### Buscadores Web

Son programas que permiten buscar información en la web mediante palabras clave.

### ¿Qué es un Sitio Web?

Un sitio web es un conjunto de archivos y directorios almacenados en un servidor web.

#### Diferencia entre una página web y un sitio web

- **Página web**: Un único documento que se puede mostrar en un navegador.
- **Sitio web**: Colección de páginas web interconectadas.

### El modelo cliente-servidor

Explica cómo se resuelve una petición de una página web en el servidor.

## Herramientas a Utilizar

### Navegadores

Para probar la web se necesita más de un navegador. Los más comunes son Google Chrome, Mozilla Firefox y Opera.

### Editor de Texto

Programas como Sublime Text, VS Code o Atom permiten escribir código fuente de proyectos.

### Terminal o Consola

Utilidad para interactuar con el computador a través de comandos.

---
---

# Clase 01 - Parte II: Prototipado y conceptos básicos del HTML

Para iniciar cualquier proyecto WEB es necesario tener un bosquejo de lo que queremos hacer. De esta manera evitamos grandes cambios en las siguientes etapas del proyecto. También nos permite definir de una manera rápida y sencilla los bloques o secciones que va a tener cada una de las páginas de un sitio web, de modo que podamos jerarquizar la información y definir los bloques de contenido.

## Proceso de Prototipado

Para iniciar este proceso tenemos varios pasos a seguir:

- Sketch
- Wireframe
- MockUp
- Prototipo interactiva
- Diseño final

### Sketch

Un sketch es un dibujo rápido o bosquejo de guía general que no tiene por qué tener muchos detalles y que reproduce un concepto, idea o generalidad de un proyecto de una manera muy sencilla. Por generalidad se realiza a mano con lápiz y borrador por su facilidad en el momento de plasmar una base o punto de partida.

### Wireframe

Es una representación estática en baja calidad de un diseño. En esta representación se definen, para una fácil comprensión:

- **¿qué?** Los principales grupos de contenido
- **¿dónde?** La estructura de la información
- **¿cómo?** La descripción y visualización básica del usuario – interacción de la interfaz

### Mockup

Representación estática de un diseño en calidad media o alta. Representa la estructura de la información, visualiza el contenido y demuestra las funcionalidades básicas de una manera estática. Permite revisar la parte visual real del proyecto.

**Entregable**: Una imagen.

### Prototipo

Representación navegable del producto final. Simula la interacción interfaz-usuario y debe permitir que el usuario:

- Experimente interactuando con la interfaz y contenido del proyecto.
- Pruebe las principales interacciones de una manera similar al producto final.


---


## HTML

HTML es un "lenguaje" de marcado (de etiquetas) para crear documentos para web. Permite indicar dónde queremos cada elemento (párrafos, negritas, itálicas, imágenes, etc.).

```html
<!DOCTYPE html>
<html>
<head>
    <title>My Web Page</title>
</head>
<body>
    <p>Hello, world!</p>
</body>
</html>
```

### Evolución del HTML

- HTML 1 y 2 (1991): Elementos de texto e imágenes.
- HTML 3 (1995): Basado en Tablas. No había un estándar.
- HTML 4 (1998): Aparece CSS, primer estándar oficial.
- XHTML 1.0 (2000): Es de la W3C, basado en XML.
- HTML5 (2004): Primer borrador creado por la WHATWG.

### Otros lenguajes para hacer sitios web

- **CSS**: Aplica el formato visual y estructural de una página.

```css
body {
    font-family: Arial, sans-serif;
}
```

- **Javascript**: Permite crear efectos-web.

```javascript
alert("Hello, world!");
```

- **PHP**: Para crear sitios dinámicos.

```php
<?php
echo "Hello, world!";
?>
```

### Herramientas de desarrollo

- Cualquier programa que escriba texto plano (Notepad, Notepad++, Sublime Text, etc).
- Un navegador Web (o más de uno).

### Convenio de archivos

Los archivos de tu sitio web llevan nombres aleatorios, pero deben cumplir con tres reglas por convención:

1. No debe tener espacios, acentos, eñes, ni símbolos o si son varias palabras usar guiones “ - “ o “ _ “ ej: “mi-pagina-web”
2. Deben estar escritos en minúsculas
3. Deben tener la extensión “.html” (esa es la forma que el servidor web sabe que es un documento web)

### Documento predeterminado

Es el archivo que se muestra cuando se pide una URL en un browser pero no se especifica un archivo.

### Etiquetas HTML

Las etiquetas HTML están delimitadas por un inicio y un final de cada elemento.

```html
<p>This is a paragraph.</p>
```

### Atributos de las etiquetas

Todas las etiquetas aceptan atributos.

```html
<a href="https://www.example.com">Visit Example.com</a>
```

### Sintaxis del código

Al HTML no le importa si las etiquetas las escribís una al lado de la otra o una debajo de la otra.

### Comentarios HTML

Es parte del código que el navegador no mostrará.

```html
<!-- This is a comment -->
```

### Estructura básica

El HTML tiene una estructura de elementos que debe insertarse siempre en cada documento. Hay dos elementos principales: `<head>` y `<body>`.

#### Doctype

Cuando escribimos nuestro documento HTML, lo primero que tenemos que escribir es el DOCTYPE.

```html
<!DOCTYPE html>
```

### Tipos de etiqueta Grupo General

Todas las etiquetas que van dentro del `<body></body>` se dividen en dos grupos:

- Elementos de bloque
- Elementos de línea

### Etiquetas de usos múltiples

Existen dos etiquetas las cuales son utilizadas principalmente para dar formato CSS y orden.

### HTML5

HTML5 incorpora etiquetas semánticas que no sólo generan estructura, sino que también definen su contenido.

```html
<header>This is the header</header>
<main>This is the main content</main>
<footer>This is the footer</footer>
```



## Referencias

- [MDN Web Docs](https://developer.mozilla.org/es/docs/Web/HTML)
- [W3Schools](https://www.w3schools.com/)
- [Apuntes tomados de mis clases en Coderhouse](https://www.coderhouse.com/)
