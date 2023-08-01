## HTML 5
[![HTML5](https://img.shields.io/badge/HTML5-F64A1D?style=for-the-badge&logo=HTML5&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/index.md)

### Enlaces
[![HTML5](https://img.shields.io/badge/Enlaces-447ac0?style=for-the-badge&logo=HTML5&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/categories/Enlaces.md)

#### Estructura de enlace
```html
<a href="https://www.google.es/" target="_blank">Google</a>
```
| Atributo  | Descripción  |
|:-:|---|
| href  | Dirección url  |
| target  | Especifica donde abrir el vinculo  |

#### Tipos de atributo target
| Tipo  | Descripción  |
|:-:|---|
| _self  | En la misma ventana/pestaña en la que se hizo clic (por defecto)  |
| _blank  | En una nueva ventana o pestaña  |
| _parent  | En el marco principal  |
| _top  | En el cuerpo completo de la ventana  |

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
    <div>
        <p><a href="https://www.google.es/" target="_self">Google</a></p>
    </div>

    <div>
        <p><a href="https://www.google.es/" target="_blank">Google</a></p>
    </div>

    <div>
        <p><a href="https://www.google.es/" target="_parent">Google</a></p>
    </div>

    <div>
        <p><a href="https://www.google.es/" target="_top">Google</a></p>
    </div>

    <div>
        <p>
            <a href="https://www.google.es/" target="_blank">
                <img src="https://placehold.co/600x400" alt="Imagen">
            </a>
        </p>
    </div>

</body>
</html>
```

[![HTML5](https://img.shields.io/badge/Enlaces-447ac0?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/categories/Enlaces.md)
