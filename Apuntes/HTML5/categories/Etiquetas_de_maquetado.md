## HTML 5
[![HTML5](https://img.shields.io/badge/HTML5-F64A1D?style=for-the-badge&logo=HTML5&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/index.md)

### Etiquetas de maquetado
[![HTML5](https://img.shields.io/badge/Etiquetas_de_maquetado-447ac0?style=for-the-badge&logo=HTML5&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/categories/Etiquetas_de_maquetado.md)

#### Descripción de etiquetas
| Etiqueta  | Descripción  |
|:-:|---|
| **\<article\>\</article\>**  | Contenidos independientes y autónomos  |
| **\<aside\>\</aside\>**  | Contenido indirectamente relacionado con el contenido de la página  |
| **\<details\>\</details\>**  | Detalles adicionales que el usuario puede ver u ocultar  |
| **\<div\>\</div\>**  | Sirve de contenedor para cualquier elemento, NO tiene sentido semantico  |
| **\<figcaption\>\</figcaption\>**  | Título para un \<figure\>  |
| **\<figure\>\</figure\>**  | Ilustraciones, diagramas, fotos...  |
| **\<footer\>\</footer\>**  | Pie de página de un documento o sección  |
| **\<header\>\</header\>**  | Cabecera de un documento o sección  |
| **\<main\>\</main\>**  | Contenido principal de un documento  |
| **\<mark\>\</mark\>**  | Texto marcado/resaltado  |
| **\<nav\>\</nav\>**  | Conjunto de enlaces de navegación  |
| **\<section\>\</section\>**  | Sección en un documento  |
| **\<summary\>\</summary\>**  | Encabezado visible para un elemento \<details\>  |
| **\<time\>\</time\>**  | Fecha/hora  |

#### Ejemplo
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Etiquetas de maquetado</title>
</head>
<body>
    <header>
        <h1>Header</h1>
        <nav>
            <h4>nav</h4>
            <ul>
                <li><a href="#">Inicio</a></li>
                <li><a href="#">Categorías</a></li>
                <li><a href="#">Sobre nosotros</a></li>
                <li><a href="#">Contacto</a></li>
            </ul>
        </nav>
    </header>
    <aside>
        <h3>Aside</h3>
        <nav>
            <h4>nav</h4>
            <ul>
                <li><a href="#">Inicia sesión</a></li>
                <li><a href="#">Registrate</a></li>
            </ul>
        </nav>
    </aside>
    <main>
        <h2>main</h2>
        <section>
            <h3>Section</h3>
            <article>
                <h4>Article</h4>
                <figure>
                    <img src="https://placehold.co/600x450" alt="imagen">
                    <figcaption>Nueva tienda!!</figcaption>
                </figure>
            </article>
        </section>
        <section>
            <h3>Section</h3>
            <div>
                <figure>
                    <img src="https://placehold.co/150x100" alt="imagen">
                    <figcaption>Camisetas</figcaption>
                </figure>
            </div>
            <div>
                <figure>
                    <img src="https://placehold.co/150x100" alt="imagen">
                    <figcaption>Pantalones</figcaption>
                </figure>
            </div>
            <div>
                <figure>
                    <img src="https://placehold.co/150x100" alt="imagen">
                    <figcaption>Bañadores</figcaption>
                </figure>
            </div>
        </section>
    </main>
    <footer>
        <h3>Footer</h3>
        <details>
            <h4>Details</h4>
            <summary>Horario de verano</summary>
            <p>De <time>10:30</time> a <time>20:00</time></p>
        </details>
    </footer>

</body>
</html>
```

[![HTML5](https://img.shields.io/badge/Etiquetas_de_maquetado-447ac0?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/categories/Etiquetas_de_maquetado.md)
