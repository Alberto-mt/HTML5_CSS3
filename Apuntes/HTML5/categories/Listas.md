## HTML 5
[![HTML5](https://img.shields.io/badge/HTML5-F64A1D?style=for-the-badge&logo=HTML5&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/index.md)

### Listas
[![HTML5](https://img.shields.io/badge/Listas-c044b8?style=for-the-badge&logo=HTML5&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/categories/Listas.md)

#### Descripción de etiquetas de listas
| Etiqueta  | Descripción  |
|:-:|---|
| \<ol\>\</ol\>  | Lista ordenada  |
| \<ul\>\</ul\>  | Lista desordenada  |
| \<li\>\</li\>  | Elemento de la lista  |
| \<dl\>\</dl\>  | Lista de descripciones  |
| \<dt\>\</dt\>  | Término en una lista de descripciones  |
| \<dd\>\</dd\>  | Describe el término  |

#### Atributos de listas ol
| Atributo  | Descripción  |
|:-:|---|
| reversed  | Invertir orden de lista  |
| start  | Empezar lista por un elemento en concreto  |
| type  | Tipo de marcador de elementos de la lista ("1","A", "a", "I", "i")  |

#### Ejemplo
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Etiquetas de texto en línea HTML5</title>
</head>
<body>
    <!-- TIPOS DE LISTAS -->
    <!-- Lista ordenada -->
    <ol>
        <l1>rojo</l1>
        <l1>azul</l1>
        <l1>verde</l1>
    </ol>

    <!-- Lista desordenada -->
    <ul>
        <li>Jose</li>
        <li>Luis</li>
        <li>Pepe</li>
    </ul>

    <!-- Lista de descripciones -->
    <dl>
        <dt>Html5</dt>
        <dd>Estructura página web</dd>
        <dt>CSS3</dt>
        <dd>Estilos de página web</dd>
    </dl>

    <!-- ATRIBUTOS DE: ol-->
    <!-- reversed -->
    <ol reversed>
        <li>Jose</li>
        <li>Luis</li>
        <li>Pepe</li>
    </ol>

     <!-- start -->
    <ol start="2">
        <li>Jose</li>
        <li>Luis</li>
        <li>Pepe</li>
    </ol>

    <!-- type -->
    <ol type="1">
        <li>Jose</li>
        <li>Luis</li>
        <li>Pepe</li>
    </ol>

    <ol type="A">
        <li>Jose</li>
        <li>Luis</li>
        <li>Pepe</li>
    </ol>

    <ol type="a">
        <li>Jose</li>
        <li>Luis</li>
        <li>Pepe</li>
    </ol>

    <ol type="I">
        <li>Jose</li>
        <li>Luis</li>
        <li>Pepe</li>
    </ol>

    <ol type="i">
        <li>Jose</li>
        <li>Luis</li>
        <li>Pepe</li>
    </ol>

</body>
</html>
```

[![HTML5](https://img.shields.io/badge/Listas-c044b8?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/categories/Listas.md)
