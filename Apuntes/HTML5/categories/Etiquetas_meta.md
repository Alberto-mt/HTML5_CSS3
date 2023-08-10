## HTML 5
[![HTML5](https://img.shields.io/badge/HTML5-F64A1D?style=for-the-badge&logo=HTML5&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/index.md)

### Etiquetas meta
[![HTML5](https://img.shields.io/badge/Etiquetas_meta-44c04c?style=for-the-badge&logo=HTML5&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/categories/Etiquetas_meta.md)

#### Descripción de etiquetas meta
| Etiqueta  | Descripción  |
|:-:|---|
| **\<meta\>\<\/meta\>**  | Define metadatos sobre un documento HTML  |

#### Descripción de atributos meta
| Etiqueta  | Descripción  |
|:-:|---|
| **charset**  | Tipo de codificación de caracteres para el documento HTML  |
| **content**  | Valor asociado al atributo http-equiv o name  |
| **http-equiv**  | Cabecera HTTP para la información/valor del atributo content  |
| **name**  | Nombre del metadato |

#### Ejemplo
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Tipo de codificación de caracteres para el documento HTML  -->
    <meta charset="UTF-8" />

    <!-- Palabras clave para motores de búsqueda -->
    <meta name="keywords" content="desarrollo web, html5, etiquetas meta">

    <!-- Descripción de la página web  -->
    <meta name="description" content="Etiquetas meta de html5">

    <!-- Autor de la página web  -->
    <meta name="author" content="Alberto Montealegre">

    <!-- Especifica uno de los paquetes de software utilizados para generar el documento (no se utiliza en páginas creadas a mano) -->
    <meta name="generator" content="FrontPage main">

    <!-- Política de contenidos para el documento  -->
    <meta http-equiv="content-security-policy" content="default-src 'self'">
    <!-- Especifica la codificación de caracteres del documento  -->
    <meta http-equiv="content-type" content="text/html; charset=UTF-8">
    <!-- Intervalo de tiempo para que el documento se actualice
      Refresca la página cada 5 segundos (3600 es una hora)  -->
    <meta http-equiv="refresh" content="5">
    <!-- Define cual es la hoja de estilos por defecto  -->
    <meta http-equiv="default-style" content="Hoja de estilos por defecto">

    <!-- Configuración de la ventana gráfica
      Importante para sitios web adaptables a dispositivos moviles -->
    <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <!-- width=device-width: Establece que el ancho de la pagina sea igual al del dispositivo -->
    <!-- user-scalable=no: Establece que el usuario no puede escalar el sitio web -->
    <!-- initial-scale=1.0: Establece que la pagina tendra un tamaño inicial de 1  -->
    <!-- maximum-scale=1.0: Establece que la pagina tendra un tamaño maximo de 1  -->
    <!-- minimum-scale=1.0: Establece que la pagina tendra un tamaño minimo de 1  -->
    <title>Etiquetas meta</title>
  </head>
  <body>
    
  </body>
</html>
```

[![HTML5](https://img.shields.io/badge/Etiquetas_meta-44c04c?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/categories/Etiquetas_meta.md)
