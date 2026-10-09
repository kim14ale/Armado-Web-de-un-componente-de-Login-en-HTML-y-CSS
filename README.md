# Login responsive - AdminExpress

Página de inicio de sesión basada en la imagen de referencia de la actividad. El objetivo es practicar la estructura con HTML, la distribución con CSS Grid y el uso de media queries para distintos tamaños de pantalla.

## Herramientas utilizadas

- HTML5 para organizar el contenido y los campos del formulario.
- CSS3 para definir colores, fuentes, márgenes y bordes.
- CSS Grid para distribuir las secciones y alinear los iconos con los campos.
- Media queries para adaptar la página a tabletas y celulares.

## Contenido del proyecto

| Archivo | Función |
| --- | --- |
| `index.html` | Estructura del login, campos de correo y contraseña, botón y enlaces. |
| `estilos.css` | Apariencia de la página y ajustes responsive. |
| `README.md` | Descripción del proyecto e instrucciones de uso. |

## Abrir el proyecto

1. Descarga los archivos del repositorio.
2. Guarda `index.html` y `estilos.css` en la misma carpeta.
3. Abre `index.html` en el navegador.

Opcionalmente, puedes utilizar Live Server en Visual Studio Code. No requiere dependencias, JavaScript ni un proceso de compilación.

## Adaptación a pantallas

| Ancho | Comportamiento |
| --- | --- |
| Más de 900 px | Panel azul al 51% y sección del formulario al 49%. |
| De 601 a 900 px | Las columnas cambian a 43% y 57%; se reduce el título y el espacio interior. |
| Hasta 600 px | Se oculta el panel azul y queda una sola columna. El botón ocupa todo el ancho del formulario y aparece el enlace Sign Up. |

En celulares también se ocultan las etiquetas visibles de los campos. Los campos conservan sus nombres accesibles mediante `aria-label`.

Para observar la adaptación, cambia el ancho de la ventana o utiliza el modo de dispositivos del navegador.

## Alcance

Este proyecto presenta el diseño visual de un login. Los campos permiten escribir un correo y una contraseña, pero el botón Sign In no ejecuta ninguna acción porque utiliza `type="button"`. No existe conexión a un servidor ni autenticación de usuarios.

Los enlaces Forgot password? y Sign Up tienen `#` como destino provisional.
