## CSS 3
[![CSS3](https://img.shields.io/badge/CSS3-196FB4?style=for-the-badge&logo=CSS3&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/CSS3/index.md)

### Pseudoclases y Pseudoelementos
[![CSS3](https://img.shields.io/badge/Pseudoclases_y_Pseudoelementos-c08a44?style=for-the-badge&logo=CSS3&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/CSS3/categories/Pseudoclases_y_Pseudoelementos.md)

#### Pseudoclases y Pseudoelementos
Son herramientas que permiten seleccionar y estilizar elementos de una manera más específica.

#### Tipos de Pseudoclases
| Tipo  | Descripción  |
|---|---|
| **:hover**  | Se aplica cuando el usuario pasa el cursor sobre un elemento  |
| **:active**  | Se aplica cuando el usuario hace clic en un elemento  |
| **:focus**  | Se aplica cuando un elemento obtiene el foco  |
| **:first-child**  | Se aplica al primer hijo de un elemento padre  |
| **:last-child**  | Se aplica al último hijo de un elemento padre  |
| **:nth-child(n)**  | Se aplica a un elemento que es el enésimo hijo de su padre  |
| **:nth-of-type(n)**  | Se aplica a un elemento que es el enésimo hijo de su tipo  |
| **:not(selector)**  | Se aplica a un elemento que no cumple con el selector especificado  |
| **:checked**  | Aplica un estilo a los elementos de formulario que están seleccionados  |

#### Tipos de Pseudoelementos
| Tipo  | Descripción  |
|---|---|
| **::before**  | Inserta contenido antes del contenido del elemento  |
| **::after**  | Inserta contenido después del contenido del elemento  |
| **::first-letter**  | Aplica un estilo a la primera letra de un elemento de bloque  |
| **::first-line**  | Aplica un estilo a la primera línea de un elemento de bloque  |
| **::selection**  | Aplica un estilo a las partes del documento que el usuario ha seleccionado  |

#### Ejemplo de Pseudoclases y Pseudoelementos
```css
/***** ***** ***** ***** ***** Pseudoclases */ 
a:hover {
  color: red;
}

input:focus {
  border: 2px solid blue;
}

li:first-child {
  font-weight: bold;
}

tr:nth-child(odd) {
  /*Representa las filas impares de una tabla HTML*/
}

tr:nth-child(even) {
  /*Representa las filas pares de una tabla HTML*/
}

p:nth-child(7) {
  /*Representa el séptimo elemento p*/
}

p:nth-child(5n) {
  /*Representa los elementos p 5, 10, 15, etc*/
}

p:nth-child(3n+4) {
  /*Representa los elementos p 4, 7, 10, 13, etc*/
}

p:nth-child(-n+3) {
  /*Representa los primeros tres elementos p entre un grupo de hermanos*/
}

p:nth-child(n){
  /*Representa cada elemento p*/
}



/***** ***** ***** ***** ***** Pseudoelementos */
p::before {
  content: "Antes del contenido: ";
  font-style: italic;
}

p::after {
  content: "Después del contenido.";
  font-weight: bold;
}

h1::first-letter {
  font-size: 2em;
}

p::first-line {
  color: green;
}

::selection {
  background-color: yellow;
  color: black;
}
```

[![CSS3](https://img.shields.io/badge/Pseudoclases_y_Pseudoelementos-c08a44?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/CSS3/categories/Pseudoclases_y_Pseudoelementos.md)
