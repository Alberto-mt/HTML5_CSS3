## HTML 5
[![HTML5](https://img.shields.io/badge/HTML5-F64A1D?style=for-the-badge&logo=HTML5&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/index.md)

### Escritura rápida
[![HTML5](https://img.shields.io/badge/Escritura_rápida-447ac0?style=for-the-badge&logo=HTML5&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/categories/Escritura_rapida.md)

#### Descripción de símbolos
| Etiqueta  | Descripción  |
|:-:|---|
| **\>**  | Etiquetas hijas  |
| **\***  | Multiplicar etiquetas  |
| **\+**  | Etiquetas hermanas  |
| **\(\)**  | Agrupaciones de etiquetas  |
| **\^**  | Escalada de etiquetas  |
| **\#**  | Atributo id  |
| **\.**  | Atributo clase  |
| **\{\}**  | Texto de etiqueta  |
| **\$**  | Enumeración de atributos de elementos  |
| **\[\]**  | Atributos personalizados  |

#### Ejemplo
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Escritura rápida</title>
  </head>
  <body>
    <!-- Etiquetas hijas ">"
    nav>ul>li>a -->
    <nav>
      <ul>
        <li><a href=""></a></li>
      </ul>
    </nav>

    <!-- Multiplicar etiquetas "*"
    nav>ul>li*3>a -->
    <nav>
      <ul>
        <li><a href=""></a></li>
        <li><a href=""></a></li>
        <li><a href=""></a></li>
      </ul>
    </nav>

    <!-- Etiquetas hermanas "+"
    article>h3+figure>img+figcaption -->
    <article>
      <h3></h3>
      <figure>
        <img src="" alt="">
        <figcaption></figcaption>
      </figure>
    </article>

    <!-- Agrupaciones de etiquetas "()"
    (article>h3+figure>img+figcaption)*2 -->
    <article>
      <h3></h3>
      <figure>
        <img src="" alt="">
        <figcaption></figcaption>
      </figure>
    </article>
    <article>
      <h3></h3>
      <figure>
        <img src="" alt="">
        <figcaption></figcaption>
      </figure>
    </article>

    <!--Escalada de etiquetas "^"
    article>h3^figure>img+figcaption -->
    <article>
      <h3></h3>
    </article>
    <figure>
      <img src="" alt="">
      <figcaption></figcaption>
    </figure>

    <!-- Atributo id "#"
    div#identificador -->
    <div id="identificador"></div>

    <!-- Atributo clase "."
    div.clase -->
    <div class="clase"></div>

    <!-- Texto de etiqueta "{}"
    h1{Título} -->
    <h1>Título</h1>

    <!-- Enumeración de atributos de elementos "$" -->
    <!-- nav>ul>li*3#numero_$>a -->
    <nav>
      <ul>
        <li id="numero_1"><a href=""></a></li>
        <li id="numero_2"><a href=""></a></li>
        <li id="numero_3"><a href=""></a></li>
      </ul>
    </nav>
    <!-- nav>ul>li*3.$>a -->
    <nav>
      <ul>
        <li class="1"><a href=""></a></li>
        <li class="2"><a href=""></a></li>
        <li class="3"><a href=""></a></li>
      </ul>
    </nav>

    <!-- Atributos personalizados "[]"
    div[clase="container"] -->
    <div clase="container"></div>

  </body>
</html>
```

[![HTML5](https://img.shields.io/badge/Escritura_rápida-447ac0?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/categories/Escritura_rapida.md)
