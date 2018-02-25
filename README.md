# Frontend Desing con Foundation y PostCSS
## Ejercicio

La idea de este ejercicio es que aprendamos a trabajar con uno de los frameworks (entorno de trabajo o marco de trabajo) para el diseño frontend (interfaz) más utilizados en la industria actualmente, como lo es Foundation.

### Herramientas utilizadas
* HTML5
* CSS3
* JS
* Foundation
* **Gulp** (Automatización de tareas)
	- css-mqpacker: para unificar las media-queries de nuestro proyecto, lo cual es muy útil para no tener código repetido en nuestro fichero css final. 

* Postcss (gulp-postcss para procesamiento de CSS)
	- postcss-mixins: para reutilizar estilos de CSS.
	- postcss-import: para importar archivos CSS dentro de otros archivos CSS. Debemos tener cuidado de no hacer “require” usando la palabra reservada “import” (la cual es usada por JS), para este caso usamos: atImport.
	- postcss-nested: extienden la sintaxis de CSS; similar a SASS y Stylus, cómo por ejemplo, la posibilidad de anidar clases.

### Equipo
* [Enrique Valerio (Cursante)](https://github.com/Caballero73 "Enrique Valerio - Cursante")