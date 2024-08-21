# Creando una Pagina Web con HTML5, CSS y JS

## Objetivo de la práctica:
Al finalizar la práctica, serás capaz de:
- Aprender a crear una página web
- Usar los elementos básicos de una página con HTML
- Aplicar estilos a la página creada
- Agregar código JavaScript 

## Objetivo Visual 
Crear un diagrama o imagen que resuma las actividades a realizar, un ejemplo es la siguiente imagen. 

imagen_1.


## Duración aproximada:
- xx minutos.

## Tabla de ayuda:
Agregar una tabla con la información que pueda requerir el participante durante el laboratorio, como versión de software, IPs de servers, usuarios y credenciales de acceso.
| Contraseña | Correo | Código |
| --- | --- | ---|
| Netec2024 | edgardo@netec.com | 123abc |

## Instrucciones 
<!-- Proporciona pasos detallados sobre cómo configurar y administrar sistemas, implementar soluciones de software, realizar pruebas de seguridad, o cualquier otro escenario práctico relevante para el campo de la tecnología de la información -->
### Tarea 1. Descripción de la tarea a realizar.

Paso 1. Abre Visual Studio Code y crea un nuevo archivo:

Abre tu editor de código y crea un nuevo archivo con la extensión .html, por ejemplo, index.html.

Paso 2. Estructura básica HTML:

Escribe el siguiente código en tu archivo index.html:

### HTML
```
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi primera página web</title>
    <link rel="stylesheet" href="styles.css">   

</head>
<body>
    <h1>¡Hola, mundo!</h1>
    <p>Este es mi primer párrafo.</p>
    <script src="script.js"></script>
</body>
</html>
```

```
Explicación:

<!DOCTYPE html>: Declara el tipo de documento.
<html>: Raíz de la página.
<head>: Contiene metadatos y enlaces a archivos externos.
<body>: Contiene el contenido visible de la página.
<title>: Define el título que aparece en la pestaña del navegador.
<link>: Enlaza el archivo CSS styles.css.
<script>: Enlaza el archivo JavaScript script.js.
```

Paso 3. Crea los archivos CSS y JavaScript:

Crea dos archivos nuevos en la misma carpeta que index.html:
styles.css para el estilo.
script.js para el código JavaScript.

Paso 4. Estiliza con CSS:

En el archivo styles.css, agrega reglas CSS para cambiar la apariencia de los elementos:

### CSS
```
body {
    font-family: Arial, sans-serif;
    text-align: center;
}

h1 {
    color: blue;
}
```

Paso 5. Agrega interactividad con JavaScript:

En el archivo script.js, escribe código JavaScript para agregar funcionalidad. Por ejemplo, puedes cambiar el color del texto al hacer clic en él:

### JavaScript

```
const h1 = document.querySelector('h1');

h1.addEventListener('click', () => {
    h1.style.color = 'red';
});
```

Paso 6. Abre el archivo en tu navegador:

Haz doble clic en index.html para abrirlo en tu navegador.


### Resultado esperado
En esta sección, se debe mostrar el resultado esperado de nuestro laboratorio
![imagen resultado](../images/img3.png)
