# Formulario de Login - Documentación

¡Hola! Soy Ronald Duarte, estoy practicando para ser desarrollador y he creado este proyecto de un formulario de login de usuario. El proyecto consiste en dos archivos: `index.html` y `style.css`. A continuación, proporciono una descripción detallada de cada uno de ellos:

## Archivo `index.html`

El archivo `index.html` es una página HTML que contiene la estructura y el contenido del formulario de login. A continuación, se describen las principales partes del código:

### Etiqueta `<!DOCTYPE html>`

Esta es la declaración del tipo de documento y se coloca al comienzo del archivo para indicar que se está utilizando HTML5.

### Etiqueta `<html>`

La etiqueta `<html>` es la envoltura principal de todo el contenido de la página y define el comienzo y el final del documento HTML.

### Etiqueta `<head>`

Dentro de la etiqueta `<head>`, se encuentran elementos meta y enlaces a recursos externos utilizados por la página. En este caso, se definen el juego de caracteres (`UTF-8`), la compatibilidad con Internet Explorer, la escala del contenido y el título de la página.

### Etiqueta `<body>`

Dentro de la etiqueta `<body>`, se encuentra todo el contenido visible de la página web. Aquí se coloca el formulario de login con los campos para el usuario y la contraseña.

### Div con clase "contenedor"

Este div con la clase "contenedor" engloba todo el contenido del formulario y tiene un estilo CSS aplicado para centrarlo en la página y darle un aspecto visual agradable.

### Encabezado `<h2>`

Dentro del div "contenedor", encontramos un encabezado `<h2>` que muestra el título "Login".

### Formulario `<form>`

El formulario `<form>` es donde los usuarios pueden ingresar sus credenciales de inicio de sesión. Se define un atributo `action` vacío, lo que significa que aún no se ha configurado la acción de envío, y se utiliza el método `post` para enviar los datos del formulario.

### Campos de entrada

Dentro del formulario, encontramos dos campos de entrada `<input>`. Uno para el nombre de usuario con el atributo `type="text"` y otro para la contraseña con el atributo `type="password"`. Ambos campos son requeridos, lo que significa que el usuario debe completarlos antes de enviar el formulario.

### Botón de envío

Después de los campos de entrada, hay un botón de envío `<input>` con el atributo `type="submit"`. Al hacer clic en este botón, el formulario se enviará para su procesamiento.

## Archivo `style.css`

El archivo `style.css` contiene la hoja de estilos CSS que da estilo y apariencia al formulario de login. A continuación, se describen los estilos aplicados:

### Estilos globales

Se definen estilos generales para el `html` y `body`, estableciendo una altura del 100% para la página y un fondo degradado que crea un efecto visual atractivo.

### Estilos del contenedor

Se definen los estilos para el div con la clase "contenedor". Se aplica un margen, un ancho fijo, un relleno y un fondo semitransparente que da una apariencia de caja al formulario. También se establece un radio de borde para suavizar las esquinas.

### Estilos del encabezado

Se definen los estilos para el encabezado `<h2>` dentro del contenedor. Se aplica un margen inferior, un tamaño de fuente grande y un color azul claro para resaltar el título "Login".

### Estilos de las etiquetas y campos de entrada

Se definen los estilos para las etiquetas y los campos de entrada `<input>` dentro del contenedor. Se cambia el color del texto a blanco, se elimina el fondo y se agrega un borde inferior blanco para resaltar los campos de entrada.

### Estilos del botón de envío

Se definen los estilos para el botón de envío `<input>` dentro del contenedor. Se aplica un color de fondo rosa, se elimina el borde y se ajusta el espaciado y el texto en mayúsculas para resaltar el botón de envío.

---

Este proyecto es un simple formulario de login de usuario con una apariencia agradable y fácil de usar. Puedes utilizarlo como punto de partida para construir funcionalidades de autenticación más avanzadas en tus proyectos web. ¡Espero que te sea útil! Si tienes alguna pregunta o sugerencia, no dudes en contactarme.

¡Gracias por revisar la documentación! 😊
