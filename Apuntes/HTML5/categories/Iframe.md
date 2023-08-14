## HTML 5
[![HTML5](https://img.shields.io/badge/HTML5-F64A1D?style=for-the-badge&logo=HTML5&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/index.md)

### Iframe
[![HTML5](https://img.shields.io/badge/Iframe-c08a44?style=for-the-badge&logo=HTML5&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/categories/Iframe.md)

#### Descripción de etiquetas
| Etiqueta  | Descripción  |
|:-:|---|
| **\<iframe\>\</iframe\>**  | Marco en línea para incrustar otro documento dentro del documento HTML actual  |

#### Descripción de atributos
| Etiqueta  |  Descripción  |  Opciones  |
|:-:|---|---|
| **allow**  | Políticas de características para el iframe  |   |
| **allowfullscreen**  | Activar el modo de pantalla completa  | true<br> false  |
| **allowpaymentrequest**  | Permitir que un <iframe> de origen cruzado invoque la API de solicitud de pago  | true<br>false  |
| **height**  | Altura  | pixels  |
| **loading**  | Modo del navegador para cargar un iframe  | eager<br> lazy  |
| **name**  | Nombre  | Texto  |
| **referrerpolicy**  | Información de referencia que debe enviarse al obtener el iframe  | no-referrer<br> no-referrer-when-downgrade<br> origin<br> origin-when-cross-origin<br> same-origin<br> strict-origin-when-cross-origin<br> unsafe-url  |
| **sandbox**  | Habilitar conjunto adicional de restricciones para el contenido  | allow-forms<br> allow-pointer-lock<br> allow-popups<br> allow-same-origin<br> allow-scripts<br> allow-top-navigation  |
| **src**  | Ubicación del documento a incrustar en el iframe  | Ubicación  |
| **srcdoc**  | Contenido HTML de la página que se mostrará en el iframe  | HTML_code  |
| **width**  | Anchura  | pixels  |

#### Ejemplo
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Iframe</title>
  </head>
  <body>
    <!-- Insertar página web  -->
    <iframe
      src="https://tabler-icons.io/"
      frameborder="0"
      width="400"
      height="600"
    ></iframe>
    <br />
    <hr />
    <br />
    <!-- Insertar video de vimeo  -->
    <iframe
      src="https://player.vimeo.com/video/163662857"
      frameborder="0"
      width="640"
      height="360"
      allowfullscreen
    ></iframe>
    <br />
    <hr />
    <br />
    <!-- Insertar video de youtube  -->
    <iframe
      width="560"
      height="315"
      src="https://www.youtube-nocookie.com/embed/dWR6A1qpi7g?start=163"
      title="Hala Madrid"
      frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
      allowfullscreen
    ></iframe>
    <br />
    <hr />
    <br />
    <!-- Insertar mapa de google maps  -->
    <iframe
      src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d12219.95664179679!2d-3.6017638004589534!3d40.03102144136401!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e0!3m2!1ses!2ses!4v1692014829162!5m2!1ses!2ses"
      width="600"
      height="450"
      style="border: 0"
      allowfullscreen
      loading="lazy"
      referrerpolicy="no-referrer-when-downgrade"
    ></iframe>
    
  </body>
</html>
```

[![HTML5](https://img.shields.io/badge/Iframe-c08a44?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/categories/Iframe.md)
