## HTML 5
[![HTML5](https://img.shields.io/badge/HTML5-F64A1D?style=for-the-badge&logo=HTML5&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/index.md)

### Audio
[![HTML5](https://img.shields.io/badge/Audio-c044b8?style=for-the-badge&logo=HTML5&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/categories/Audio.md)

#### Descripción de etiquetas
| Etiqueta  | Descripción  |
|:-:|---|
| **\<audio\>\</audio\>**  | Define el audio  |
| **\<source\>**  | Define uno o varios recursos multimedia para elementos multimedia, como <video> y <audio>.  |

#### Descripción de atributos
| Atributo | Descripción  |
|:-:|---|
| **controls**  | Agrega controles de audio, como reproducción, volumen y pausa.  |
| **autoplay**  | Inicia un archivo de audio automáticamente  |
| **muted**  | Despues de autoplay, permite que el archivo de audio se reproduzca, pero silenciado  |
| **src**  | Ubicación del archivo  |
| **type**  | Tipo de medio  |

#### Tipos de medio
| Formato | Tipo de medio  |
|:-:|---|
| **MP3**  | audio/mpeg  |
| **OGG**  | audio/ogg (No soportado por navegador Safari)  |
| **WAV**  | audio/wav  |

#### Ejemplo
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Audio</title>
  </head>
  <body>
    <audio controls autoplay muted>
		  <source src="media/audio.mp3" type="audio/mpeg">
		  <source src="media/audio.ogg" type="audio/ogg">
	  </audio>
    
  </body>
</html>
```

[![HTML5](https://img.shields.io/badge/Audio-c044b8?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/HTML5_CSS3/blob/main/Apuntes/HTML5/categories/Audio.md)
