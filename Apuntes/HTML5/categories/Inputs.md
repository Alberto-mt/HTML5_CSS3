## HTML 5
[![HTML5](https://img.shields.io/badge/HTML5-F64A1D?style=for-the-badge&logo=HTML5&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/index.md)

### Inputs
[![HTML5](https://img.shields.io/badge/Inputs-c044b8?style=for-the-badge&logo=HTML5&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/categories/Inputs.md)

#### Descripción de etiquetas de inputs
| Etiqueta  | Descripción  |
|:-:|---|
| **\<input type="button"\>**  | Botón simple para aplicarle funcionalidad |
| **\<input type="checkbox"\>**  | Casilla de verificación  |
| **\<input type="color"\>**  | Selector de color  |
| **\<input type="date"\>**  | Fecha  |
| **\<input type="datetime-local"\>**  | Fecha y hora sin zona horaria  |
| **\<input type="email"\>**  | email  |
| **\<input type="file"\>**  | Selector de archivos  |
| **\<input type="hidden"\>**  | Campo oculto al usuario  |
| **\<input type="image"\>**  | Imagen como botón  |
| **\<input type="month"\>**  | Mes y año  |
| **\<input type="number"\>**  | Numérico  |
| **\<input type="password"\>**  | Contraseña  |
| **\<input type="radio"\>**  | Botones de selección de opción  |
| **\<input type="range"\>**  | Número dentro de un rango  |
| **\<input type="reset"\>**  | Botón de reset de datos de formulario  |
| **\<input type="search"\>**  | Campos de busqueda  |
| **\<input type="submit"\>**  | Botón de envío de datos de formulario  |
| **\<input type="tel"\>**  | Teléfono  |
| **\<input type="text"\>**  | Texto de una línea  |
| **\<input type="time"\>**  | Selector de hora sín zona horaria  |
| **\<input type="url"\>**  | Url  |
| **\<input type="week"\>**  | Semana y año  |

#### Atributos de inputs
| Etiqueta  | Descripción  |
|:-:|---|
| **checked**  | Campo de entrada preseleccionado (para type="checkbox" o type="radio") |
| **disabled**  | campo de entrada debe deshabilitado |
| **max**  | Máximo valor permitido de un campo de entrada |
| **maxlength**  | Número máximo de caracteres |
| **min**  | Mínimo valor permitido de un campo de entrada |
| **pattern**  | Expresión regular que valida el input |
| **placeholder**  | Sugerencia de valor a introducir |
| **readonly**  | Campo de entrada de solo lectura |
| **required**  | Campo de entrada requerido |
| **size**  | Ancho de campo de entrada |
| **step**  | Intervalos de cantidades  |
| **value**  | Valor por defecto |


#### Ejemplo
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Inputs HTML5</title>
  </head>
  <body>
    <form action="">
      <input type="button" />
      <br><br>
      <input type="checkbox" checked/>
      <br><br>
      <input type="color" />
      <br><br>
      <input type="date" max="2025-06-01"/>
      <br><br>
      <input type="datetime-local" />
      <br><br>
      <input type="email" placeholder="correo@correo.com"/>
      <br><br>
      <input type="file" />
      <br><br>
      <input type="hidden" />
      <br><br>
      <input type="image" />
      <br><br>
      <input type="month" />
      <br><br>
      <input type="number" min="1" max="10"/>
      <br><br>
      <input type="password" />
      <br><br>
      <input type="radio" checked/>
      <br><br>
      <input type="range" min="0" max="100" step="10"/>
      <br><br>
      <input type="reset" />
      <br><br>
      <input type="search" />
      <br><br>
      <input type="submit" disabled/>
      <br><br>
      <input type="tel" placeholder="611111111" required/>
      <br><br>
      <input type="text" maxlength="50" pattern="[A-Za-z0-9]+"/>
      <br><br>
      <input type="time" />
      <br><br>
      <input type="url" placeholder="https://www.google.es/" readonly/>
      <br><br>
      <input type="week" />
    </form>
  </body>
</html>
```

[![HTML5](https://img.shields.io/badge/Inputs-c044b8?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/categories/Inputs.md)
