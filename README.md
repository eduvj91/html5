                  ██╗  ██╗████████╗███╗   ███╗██╗     ███████╗
                  ██║  ██║╚══██╔══╝████╗ ████║██║     ██╔════╝
                  ███████║   ██║   ██╔████╔██║██║     ███████╗
                  ██╔══██║   ██║   ██║╚██╔╝██║██║     ╚════██║
                  ██║  ██║   ██║   ██║ ╚═╝ ██║███████╗███████║
                  ╚═╝  ╚═╝   ╚═╝   ╚═╝     ╚═╝╚══════╝╚══════╝


# Primeros pasos

## Vocabulario web

- IP: Es el identificador numérico de una página web, es único y representa la dirección donde está el ordenador que contiene esa página web.
- Dominio web/ URL: Uniform Resource Locator. Es el nombre asociado a la IP que utilizamos para solicitar recursos, en nuestro caso un sitio web.
- DNS: Domain Name System: Es un servidor cuya principal función es traducir el nombre de dominio a su identificador único.
- Sitio web: Es un conjunto de uno o varios recursos web alojados en el mismo dominio.
- Servidor web: Es un ordenador cuyo objetivo es servir recursos web.
- Hosting: Es el almacenamiento del servidor web. Es disco duro donde el servidor guarda los recursos.
- Petición: Es la acción de pedir recursos a un servidor.

## ¿Qué es HTML?
- Es un lenguaje de marcado de hipertextos (Hyper Text Markup Lenguaje).
- HTML no es un lenguaje de programación, es un lenguaje de estructura.
- Es la base con la que están creadas TODAS las página web del mundo.
- Cada etiqueta le dice al navegador y a los motores de búsqueda cuál es la estructura de los documentos, elementos, organización, etc.

## Estructura básica de HTML
```html
<!DOCTYPE html>  <!-- Estándar del documento HTML-5 -->
<html lang="en"> <!-- Atributo que la pagina está en español -->
	<! --- head
	Colección de meta datos, son los datos que le pasamos a nuestro sitio web
	Esto no tiene una representación visual pero el navegador lo entiende
	-->
	<head>
		<meta charset="UTF-8"> <!-- El tipo carácter -->
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
		<title>Document</title>
	</head>

	<!-- Representa todo el contenido de nuestra página web -->
	<body> 
		<h1>Esta es nuestra página de inicio</h1>
	</body>

</html>
```
