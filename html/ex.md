# HTML
## Parte 1
### Parte A
Crea una página HTML con los siguientes elementos:

1.- Agrega un div que contenga 2 elementos:
a.- H1 con el texto "Mi sitio web". 
b.- Párrafo con el texto: "Este es mi hermoso sitio web".  

2.- Agrega un div que contenga 5 elementos “a href”
a.- Inicio  b.- Acerca de  c.- Noticias  d.- Precios  e.- Inicio de sesión

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wladimir Moya</title>
</head>
<body>

    <div>
        <h1>"Mi sitio web"</h1>
        <p>Este es mi hermoso sitio web</p>
    </div>

    <div>
        <a href="#">Inicio</a>
        <a href="#">Acerca de</a>
        <a href="#">Noticias</a>
        <a href="#">Precios</a>
        <a href="#">Inicio de sesión</a>
    </div>
</body>
</html>
```

### Parte B

Agrega los siguientes elementos a index.html:
1.- Agrega un div que contenga 3 divs.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wladimir Moya</title>
</head>
<body>
    <div>
        <div></div>
        <div></div>
        <div></div>
    </div>
</body>
</html>
```
### Parte C

Agrega los siguientes elementos al primer div:
1.- Agrega un div (con el comentario número 1) que contenga: 
a.- H2 - Título h2.
b.- H5 - Descripción de título, 20 de noviembre de 2020.
c.- div - img src con altura y ancho igual al 100%.
d.- Párrafo - texto...
e.- Párrafo - agrega cualquier texto a este párrafo.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wladimit Moya</title>
</head>
<body>
    <div>
        <!-- Título h2 -->
        <h2></h2>
        <!-- Descripción de título, 20 de noviembre de 2020. -->
        <h5></h5>
        <div>
            <img src="" alt="" width="100%" height="100%">
        </div>
        <p>texto...</p>
        <p>El primer mensaje que se envió desde una computadora a otra conectadas a ese internet “primitivo” fue “Login” y lo que llegó a la otra computadora fue “Lo”. Aunque no llegó el mensaje completo para ese entonces ya fue un logro. Gracias a que solucionaron ese problema hoy puedes leer este post completo.</p>
    </div>
</body>
</html>
```

### Parte D

Duplica el div número 1 tres veces.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wladimit Moya</title>
</head>
<body>
    <div>
        <!-- Título h2 -->
        <h2></h2>
        <!-- Descripción de título, 20 de noviembre de 2020. -->
        <h5></h5>
        <div>
            <img src="" alt="" width="100%" height="100%">
        </div>
        <p>texto...</p>
        <p>El primer mensaje que se envió desde una computadora a otra conectadas a ese internet “primitivo” fue “Login” y lo que llegó a la otra computadora fue “Lo”. Aunque no llegó el mensaje completo para ese entonces ya fue un logro. Gracias a que solucionaron ese problema hoy puedes leer este post completo.</p>
    </div>
    <div>
        <!-- Título h2 -->
        <h2></h2>
        <!-- Descripción de título, 20 de noviembre de 2020. -->
        <h5></h5>
        <div>
            <img src="" alt="" width="100%" height="100%">
        </div>
        <p>texto...</p>
        <p>El primer mensaje que se envió desde una computadora a otra conectadas a ese internet “primitivo” fue “Login” y lo que llegó a la otra computadora fue “Lo”. Aunque no llegó el mensaje completo para ese entonces ya fue un logro. Gracias a que solucionaron ese problema hoy puedes leer este post completo.</p>
    </div>
    <div>
        <!-- Título h2 -->
        <h2></h2>
        <!-- Descripción de título, 20 de noviembre de 2020. -->
        <h5></h5>
        <div>
            <img src="" alt="" width="100%" height="100%">
        </div>
        <p>texto...</p>
        <p>El primer mensaje que se envió desde una computadora a otra conectadas a ese internet “primitivo” fue “Login” y lo que llegó a la otra computadora fue “Lo”. Aunque no llegó el mensaje completo para ese entonces ya fue un logro. Gracias a que solucionaron ese problema hoy puedes leer este post completo.</p>
    </div>
</body>
</html>
```

## Clase

### 1. Introducción
Abre un archivo HTML y edítalo para que aparezca tu nombre.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wladimit Moya</title>
</head>
<body>
    Wladimir Moya
</body>
</html>
```

### 2. Empezando con HTML5
Abre un archivo HTML y edítalo para que:
1.- El título del document será mis hobbies.
2.- Agrega un párrafo que hable de tus hobbies.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mis hobbies</title>
</head>
<body>
    <p>
        Mis hobbies son la escritura, lectura y me fascina hacer cosas raras con javascript en la web. Escribo documentacion personal de las tecnologías que estoy aprendiendo y escribo fragmentos de cuentos que espoer acabar algún día. Leo libros que explican herramientas tecnológicas como javascript. En la actualidad estoy leyendo Elocuent JavaScript. Lecturas que estan en modo espera por el momento son: El mundo y sus demonios, El Quijote de la mancha, Así habló Zaratustra.

    </p>
</body>
</html>
```

### 3. Lista
Crea un archivo de HTML con los siguientes atributos:
1.- Crea un título h1 “mis mejores amigos”.
2.- Crea una lista con tus mejores amigos.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wladimir Moya</title>
</head>
<body>
    <h1>Mis mejores amigos</h1>
    <ul>
        <li>Patricio</li>
        <li>Cecilia</li>
        <li>Carlos</li>
        <li>Ricardo</li>
        <li>Leonardo</li>
        <li>Fernando</li>
        <li>Hector</li>
    </ul>
</body>
</html>
```

### 4. Tablas
Crea un archivo de HTML con los siguientes atributos:
1. Crea un título h1 “mi familia”.
2. Crea una tabla con 3 columnas: nombre apellido y edad.
3. Agreda una tabla con los miembros de tu familia.

### 5. div y span
Crea un archivo de HTML con los siguientes atributos:
1. Crea un div con imagen y párrafo.
2. El tamaño de la imagen es height:50, width:50.
3. El alt de la imagen es “mikel”.

### 6. Formularios
Crea un formulario con 2 checkbox y un botón de submit:
1. El primer checkbox – me gustan los jeans
2. El segundo checkbox – me gustan las tshirts

### 7. iframe
Crea un archivo HTML con una conexión al website que tú quieras

### 8. video
Crea un archivo de HTML con los siguientes atributos:
1. Elemento H1 – mi video favorito.
2. Agrega un div con un elemento youtube y un párrafo con una descripción detrás.

### 9. audio
Crea un archivo de HTML con los siguientes atributos:
1. Elemento H1 – mi audio favorito.
2. Agrega un div con un elemento de audio y un párrafo con una descripción detrás.

## Tareas

### Tarea 1
Abre un archivo HTML y edítalo para que aparezca tu ciudad.

### Tarea 2
Abre un archive HTML y edítalo para que:
1. El título del document será tu jugador de basketball favorito.
2. Agrega un párrafo que hable acerca de tu jugador favorito.

### Tarea 3
Crea un archivo de HTML con los siguientes atributos:
1. Crea un título h1 con tus “Comidas favoritas”.
2. Crea una lista de tus comidas favoritas.

### Tarea 4
Crea un archivo de HTML con los siguientes atributos:
1. Crea título h1 “Mi tienda”.
2. Crea una tabla con 2 columnas: título, precio.
3. Agrégale a la tabla tus productos.

### Tarea 5
Crea un archivo de HTML con los siguientes atributos:
1. Crea un div con una imagen y un párrafo.
2. La medida de la imagen es height:100, width:100.
3. El alt de la imagen es “my actor favorito”.

### Tarea 6
Crea un formulario que contenga 3 text fields y un botón de submit:
Nombre, apellido, contraseña, botón con valor(text) enviar

### Tarea 7
Crea un iframe con tu sitio favorito
### Tarea 8
Crea un archivo de HTML con los siguientes atributos:
1. Elemento H1 element – my juego de basketball favorito.
2. Agrega un div con un elemento youtube que contenga un juego de basketball y un párrafo con una descripción detrás.