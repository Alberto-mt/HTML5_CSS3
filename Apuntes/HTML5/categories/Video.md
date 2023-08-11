## HTML 5
[![HTML5](https://img.shields.io/badge/HTML5-F64A1D?style=for-the-badge&logo=HTML5&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/index.md)

### Video
[![HTML5](https://img.shields.io/badge/Video-c08a44?style=for-the-badge&logo=HTML5&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/categories/Video.md)

#### Descripción de etiquetas
| Etiqueta  | Descripción  |
|:-:|---|
| **\<video\>\</video\>**  | Define el video  |
| **\<source\>**  | Define uno o varios recursos multimedia para elementos multimedia, como <video> y <audio>.  |

#### Descripción de atributos
| Atributo | Descripción  |
|:-:|---|
| **controls**  | Agrega controles de video, como reproducción, volumen y pausa.  |
| **autoplay**  | Inicia un archivo de video automáticamente  |
| **muted**  | Despues de autoplay, permite que el archivo de video se reproduzca, pero silenciado  |
| **src**  | Ubicación del archivo  |
| **type**  | Tipo de medio  |
| **width**  | Anchura del video  |
| **height**  | Altura del video  |

#### Tipos de medio
| Formato | Tipo de medio  |
|:-:|---|
| **MP4**  | video/mp4  |
| **Ogg**  | 	video/ogg (No soportado por navegador Safari)  |
| **WebM**  | video/webm  |

#### Ejemplo
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Video</title>
  </head>
  <body>
    <video width="350" height="250" controls autoplay muted>
	<source src="media/video.mp4" type="video/mp4">
	<source src="media/video.ogg" type="video/ogg">
    </video>
    
  </body>
</html>
```

[![HTML5](https://img.shields.io/badge/Video-c08a44?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/categories/Video.md)
