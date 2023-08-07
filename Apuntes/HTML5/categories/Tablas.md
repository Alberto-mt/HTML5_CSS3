## HTML 5
[![HTML5](https://img.shields.io/badge/HTML5-F64A1D?style=for-the-badge&logo=HTML5&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/index.md)

### Tablas
[![HTML5](https://img.shields.io/badge/Tablas-44c04c?style=for-the-badge&logo=HTML5&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/categories/Tablas.md)

#### Descripción de etiquetas de tabla
| Etiqueta  | Descripción  |
|:-:|---|
| **\<table\>\</table\>**  | Define la tabla  |
| **\<caption\>\</caption\>**  | Título de la tabla  |
| **\<thead\>\</thead\>**  | Contenedor de celdas de cabecera  |
| **\<tbody\>\</tbody\>**  | Contenedor de celdas principales  |
| **\<tfoot\>\</tfoot\>**  | Contenedor de celdas de pie de tabla  |
| **\<colgroup\>\</colgroup\>**  | Especifica grupo de celdas a formatear  |
| **\<col\>\</col\>**  | Especifica cada columna de un \<colgroup\>  |
| **\<th\>\</th\>**  | Celda de cabecera  |
| **\<tr\>\</tr\>**  | Fila de una tabla  |
| **\<td\>\</td\>**  | celda de una tabla  |

#### Atributos de tabla
| Atributo  | Descripción  |
|:-:|---|
| **border**  | Borde de tabla (para table) |
| **colspan**  | Agrupación de columnas (para td) |
| **rowspan**  | Agrupación de filas (para td) |
| **span**  | Agrupación de columnas (para col)  |

#### Ejemplo
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Tablas HTML5</title>
  </head>
  <body>
    <table border="1">
      <caption>
        Registro de clientes
      </caption>
      <thead>
        <th>id</th>
        <th>Nombre</th>
        <th>Apellido</th>
        <th>Teléfono</th>
        <th>email</th>
      </thead>
      <colgroup>
        <col span="1" style="background-color: rgb(204, 202, 202)" />
        <col span="2" style="background-color: rgb(130, 170, 215)" />
        <col span="1" style="background-color: rgb(131, 207, 143)" />
        <col span="1" style="background-color: rgb(211, 175, 137)" />
      </colgroup>
      <tbody>
        <tr>
          <td>1</td>
          <td colspan="2">Ana Lopez</td>
          <td>611111111</td>
          <td>ana.lopez@email.com</td>
        </tr>
        <tr>
          <td rowspan="2">2</td>
          <td rowspan="2" colspan="2">Luis Perez</td>
          <td>622222221</td>
          <td rowspan="2">luis.perez@email.com</td>
        </tr>
        <tr>
          <td>622222222</td>
        </tr>
        <tr>
          <td>3</td>
          <td colspan="2">Isabel Rodriguez</td>
          <td>633333333</td>
          <td>isabel.rodriguez@email.es</td>
        </tr>
      </tbody>
      <tfoot>
        <tr>
          <td colspan="5">Total de clientes: 3</td>
        </tr>
      </tfoot>
    </table>
  </body>
</html>
```
[![HTML5](https://img.shields.io/badge/Tablas-44c04c?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/categories/Tablas.md)
