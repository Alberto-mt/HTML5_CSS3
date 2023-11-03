## CSS 3
[![CSS3](https://img.shields.io/badge/CSS3-196FB4?style=for-the-badge&logo=CSS3&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/CSS3/index.md)

### Metodologías de escritura
[![CSS3](https://img.shields.io/badge/Metodologias_de_escritura-447ac0?style=for-the-badge&logo=CSS3&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/CSS3/categories/Metodologias_de_escritura.md)

#### Tipos de metodologías de escritura
En CSS, existen diferentes metodologías y enfoques para escribir y organizar el código. Algunos de los tipos de escritura más populares son:
- **BEM (Block Element Modifier)**: BEM es una metodología de nomenclatura que se centra en la estructura y organización del código CSS. Se basa en la idea de dividir los componentes en bloques, elementos y modificadores. Esto ayuda a crear un código CSS más modular y reutilizable.
```css
.block {
  /* Estilos para el bloque */
}

.block__element {
  /* Estilos para el elemento dentro del bloque */
}

.block__element--modifier {
  /* Estilos modificados para el elemento dentro del bloque */
}
```
- **Utility-First CSS**: Utility-First CSS es una metodología que se centra en la creación de clases CSS atómicas y reutilizables que se pueden combinar para construir componentes y diseños. En lugar de escribir estilos específicos para cada elemento, se utilizan clases utilitarias predefinidas para aplicar estilos rápidamente. Ejemplos de frameworks que utilizan este enfoque son Tailwind CSS y UnoCSS.
```html
<!-- Clases de Tailwind CSS  -->
<button class="bg-black p-2 rounded">Click me</button>
```
- **Módulos CSS**: Los módulos CSS son una forma de organizar el código CSS en módulos independientes y reutilizables. Cada módulo tiene su propio archivo CSS y se puede importar según sea necesario. Esto ayuda a mantener el código más modular y facilita la colaboración en proyectos grandes.
```css
/* Estilos para el módulo 1 */
.module1 {
  /* Estilos para el módulo 1 */
}

/* Estilos para el módulo 2 */
.module2 {
  /* Estilos para el módulo 2 */
}
```

#### Ejemplo de metodologías de escritura
```css
/***** ***** Metodologías de escritura ***** *****/

/***** BEM (Block Element Modifier) *****/

.card{}

.card__titulo{}

.card__imagen{}

.card__botom{}

.card__botom--activo{}

/***** Utility-First CSS *****/

.text-center{}

.color-red-100{}

.bg-blue-200{}

.p-2{}

.m-2{}

/***** Módulos CSS *****/

.card{}

.card h2 {}

.card img {}

.card a {}
```

[![CSS3](https://img.shields.io/badge/Metodologias_de_escritura-447ac0?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/CSS3/categories/Metodologias_de_escritura.md)
