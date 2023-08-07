## HTML 5
[![HTML5](https://img.shields.io/badge/HTML5-F64A1D?style=for-the-badge&logo=HTML5&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/index.md)

### Formularios
[![HTML5](https://img.shields.io/badge/Formularios-447ac0?style=for-the-badge&logo=HTML5&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/categories/Formularios.md)

#### Descripción de etiquetas de formulario
| Etiqueta  | Descripción  |
|:-:|---|
| **\<form\>\</form\>**  | Define formulario  |
| **\<fieldset\>\</fieldset\>**  | Agrupación de datos relacionados en un formulario  |
| **\<legend\>\</legend\>**  | Leyenda para el elemento <fieldset>  |
| **\<datalist\>\</datalist\>**  | Especifica una lista de opciones predefinidas para un elemento \<input\>  |
| **\<input\>**  | Elemento de entrada de datos (de varios tipos)  |
| **\<label\>\</label\>**  | Elemento visual que define elementos de entrada de datos del formulario   |
| **\<select\>\</select\>**  | Define lista desplegable  |
| **\<optgroup\>\</optgroup\>**  | Grupo de opciones relacionadas en una lista desplegable  |
| **\<option\>\</option\>**  | Define opción a ser seleccionada  |
| **\<textarea\>\</textarea\>**  | Elemento de entrada de datos multilínea  |
| **\<button\>\</button\>**  | Botón al que se le puede hacer click  |
| **\<output\>\</output\>**  | Resultado de un cálculo (como el realizado por un script)  |

#### Atributos de formulario
| Etiqueta  | Descripción  |
|:-:|---|
| **accept-charset**  | Codificación de caracteres de formulario para su envío |
| **action**  | Dónde enviar los datos del formulario |
| **autocomplete**  | Autocompletado activo o desactivado |
| **enctype**  | Cómo se deben codificar los datos del formulario al enviarlos (solo para metodo post)  |
| **method**  | Método HTTP de envío |
| **name**  | Nombre de formulario |
| **novalidate**  | No validar formulario al enviarlo |
| **rel**  | Relación entre un recurso vinculado y el documento actual |
| **target**  | Dónde mostrar la respuesta que se recibe después de enviar el formulario |

#### Ejemplo
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Formularios HTML5</title>
  </head>
  <body>
    <form
      name="formCoche"
      accept-charset="UTF-8"
      action=""
      method="post"
      enctype="multipart/form-data"
      target="_blank"
      autocomplete="off"
      novalidate
    >
      <fieldset>
        <legend>Datos de coche</legend>
        <label for="txtMarca">Marca: </label><br />
        <input type="text" id="txtMarca" name="txtMarca" /><br /><br />

        <label for="txtModelo">Modelo: </label><br />
        <input type="text" id="txtModelo" name="txtModelo" /><br /><br />

        <label for="selColorExterior">Color exterior: </label>
        <select id="selColorExterior" name="selColorExterior">
          <option value="amarillo">Amarillo</option>
          <option value="azul">Azul</option>
          <option value="Blanco" selected>Blanco</option>
          <option value="Negro">Negro</option>
        </select><br /><br />

        <label for="txaFichaTecnica">Ficha técnica: </label><br />
        <textarea
          id="txaFichaTecnica"
          name="txaFichaTecnica"
          rows="10"
          cols="30"
        >
        </textarea><br /><br />

        <label for="txdPackConfort">Pack confort: </label><br />
        <input list="txdPackConfort" name="txdPackConfort" />
        <datalist id="txdPackConfort">
          <option value="Básico"></option>
          <option value="Todo incluido"></option>
          <option value="Sport"></option>
        </datalist><br /><br />

        <button type="btnEnviar" onclick="alert('Enviado con exito')">
          Enviar
        </button>
      </fieldset>
    </form>

  </body>
</html>
```

[![HTML5](https://img.shields.io/badge/Formularios-447ac0?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/categories/Formularios.md)
