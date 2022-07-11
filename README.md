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

# Sección de contenido

En HTML estructuramos el contenido en diferentes etiquetas que le ayuda al navegador a entender como esta estructurada una pagina.

## Header main y footer

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
		<!-- Etiquetas de sección de contenido   -->
		<header>
			<!-- menú de navegación, logo, redes sociales... -->
			Inicio Novedades Peliculas Contacto
		</header>
		<main>
			<!-- contenido principal de la pagina -->
			<h1>Esta es nuestra página de inicio</h1>
			<h2>Sección dentro del h1 </h2>
			<p>Este es un párrafo</p>
			<h3>Este seria una sección dentro de h2 </h3>
			<p>Este es un párrafo</p>
		</main>
		<footer>
			<!-- Pies de pagina -->
			<p>Este es el pie de la página</p>
		</footer>
	</body>

</html>
```

## Section vs article

- Section
Es un contenedor genérico que agrupa contenido que esta relacionado. Cuando creamos bloques cuyo contenido es parte de un bloque total usaremos section.

- Article
Es un contenedor que representa contenido independiente, es decir, podemos leer ese fragmento en cualquier otro sitio y tendría sentido por sí mismo.

- Aside
Se utiliza para representar contenido relacionado pero no forma parte del contenido principal.

- Anidamientos
Un `section` puede contener `articles`, por ejemplo, si tenemos varios artículos que hablan sobre etiquetas HTML, deben ir dentro de un section, ya que es contenido relacionado entre sí, y los `article` serían contenidos independiente por que podrían leer uno sin haber leído el resto, y seguirá teniendo sentido.
El `article` es diferente como un componente de la página de contenido independiente, esto implica que esta puede contener un `deader` y un `footer`.
También existe el caso de que `article` contenga un `secction`, el artículo independiente podría ser "navegadores" y este contener dentro secciones como "navegadores más utilizados en 2020"

> La forma correcta de saber si hemos puesto semantimacemnte bien nuestra estructura es con la herramienta en linea

``usando codigo``
Saldo de lineas

usando mas codigo ``este es codigo `dontro de otro codigo` aver que pasa `` saliendo del codigo.


