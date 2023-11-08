## CSS 3
[![CSS3](https://img.shields.io/badge/CSS3-196FB4?style=for-the-badge&logo=CSS3&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/CSS3/index.md)

### Fondo (Background)
[![CSS3](https://img.shields.io/badge/Fondo-447ac0?style=for-the-badge&logo=CSS3&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/CSS3/categories/Fondo.md)

#### Color de fondo
**background-color**

Se pueden utilizar diferentes tipos de valores de color, como palabras clave, valores hexadecimales o funciones rgb().

```css
.mi-elemento {
  background-color: white;
  /* background-color: #FFFFFF; */
  /* background-color: rgb(255, 255, 255); */
  /* background-color: rgba(255, 255, 255, 1) */
  /* background-color: var(--blanco); */
}
```

#### Imagen de fondo
**background-image**

Se puede especificar la URL de la imagen que se utilizará como fondo.

```css
.mi-elemento {
  background-image: url("imagen.jpg");
  /* background-image: none; */
  /* background-image: var(--imagen); */
}
```

#### Repetición de fondo
**background-repeat**

| Valor  | Descripción  |
|---|---|
| **repeat**  | Repetir en ambas direcciones  |
| **no-repeat**  | No repetir  |
| **repeat-x**  | Repetir solo horizontalmente  |
| **repeat-y**  | Repetir solo verticalmente  |

```css
.mi-elemento {
  background-repeat: repeat;
  /* background-repeat: no-repeat; */
  /* background-repeat: repeat-x; */
  /* background-repeat: repeat-y; */
}
```

#### Tamaño de fondo
**background-size**

| Valor  | Descripción  |
|---|---|
| **auto**  | Valor por defecto, el ancho y alto de la imagen  |
| **100px 100px**  | Ancho y alto que nosotros le especifiquemos, si solo ponemos el primer valor, el segundo sera automatico  |
| **100% 100%**  | Porcentaje del ancho y alto que tendra el fondo tomando en cuenta el contenedor padre  |
| **cover**  | Ajusta el ancho de la imagen para que avarque el ancho del contenedor padre  |
| **contain**  | Ajusta la imagen para que avarque el ancho y alto del contenedor padre  |

```css
.mi-elemento {
  background-size: auto;
  /* background-size: 100px 100px; */
  /* background-size: 100% 100%; */
  /* background-size: cover; */
  /* background-size: contain; */
}
```

#### Fondo adjunto
**background-attachment**

Determina si la posición de una imagen de fondo será fija dentro de la pantalla o si se desplazará junto con su bloque contenedor.

| Valor  | Descripción  |
|---|---|
| **scroll**  | La imagen de fondo se moverá dentro de la pantalla junto con el bloque que la contiene  |
| **fixed**  | La imagen de fondo estará fija en la pantalla y no se moverá con el bloque contenedor  |
| **local**  | La imagen de fondo se mantendrá fija si el elemento tiene barras de desplazamiento y el usuario se mueve dentro del elemento  |

```css
.mi-elemento {
  background-attachment: scroll;
  /* background-attachment: fixed; */
  /* background-attachment: local; */
}
```

#### Posición de fondo
**background-position**

Define la posición inicial de la imagen de fondo especificada y su valor inicial es 0% 0%.

Se utiliza para definir la posición inicial de una imagen de fondo en un elemento específico. Esta propiedad acepta diferentes valores, como palabras clave, porcentajes, longitudes y combinaciones de estos valores.

Es importante tener en cuenta que cuando se utilizan palabras clave junto con otros valores, las palabras clave "left" y "right" solo se utilizarán como primer valor, y las palabras clave "top" y "bottom" solo se utilizarán como segundo valor.

| Valor  | Descripción  |
|---|---|
| **top center;**  | Posicionará la imagen de fondo en la parte superior y centrada horizontalmente  |
| **25% 75%;**  | Posicionará la imagen de fondo en un 25% desde el borde izquierdo y un 75% desde el borde superior  |
| **5px bottom;**  | Posicionará la imagen de fondo a 5 pixels desde el borde izquierdo y en la parte inferior  |
| **center 10%;**  | Posicionará la imagen de fondo centrada verticalmente y a un 10% desde el borde superior  |

```css
.mi-elemento {
  background-position: top center;
  /* background-position: 25% 75%; */
  /* background-position: 5px bottom; */
  /* background-position: center 10%; */
}
```

[![CSS3](https://img.shields.io/badge/Fondo-447ac0?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/CSS3/categories/Fondo.md)
