<!-- Cabeceras 1-6 -->
# CABECERAS
# cabecera H1
## cabecera H2
### cabecera H3
#### cabecera H4
##### cabecera H5
###### cabecera H6


# UNDERLINES
<!-- underLines -->
Underline 1
----------
Underlne2
========
# Formatos de enfasis
<!-- Emphasis  Forma de resaltar Texto-->
- letra *italica* de la primera forma.
- letra  _italica_ de la segunda forma.

<!-- strong emphasis -->
- formato **bold o strong**
- formato __bold o strong__
<!-- formato tachado -->
- formato ~~hola~~
<!-- Listas -->
# LISTAS
<!-- Listas Ordenadas   ol-->
1. Esto es un item de lista ordenada.
2. Esto es un item de lista ordenada.
3. Esto es un item de lista ordenada.
<!-- Listas desordenadas  ul -->
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada

# LINKS
- [Esto es un Link en Markdown](http://www.google.com)
- [Esto es un Link al Index](index.html)

# IMAGENES
![Logo Github](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

# CODE SNIPPETS
Codigo en JSON
<!-- HIGHLIGTHT.JS RESALTAR CODIGO EN MARKDOWN -->
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```
Codigo JAVASCRIPT
```Javascript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}
export  $initHighlight;
```
# Tablas
| Nombre | Apellido | Documento | 
|--------| -------- | --------- |
| Cesar  | Zubilete | Sanchez   |
| Cesar  | calderon | Otamendi  |

# Citas
Esto es una texto referente a una cita que pondremos debajo:
>Esto es una cita 
asdasdasd

Esto es otro texto que no se relacionas con la cita anterior.
>Esto es otra cita.

# Divisores
Esto es un texto que sera dividido por - .

---
Esto es otro texto dividido por *.
***
Esto es otro texto dividido por _.

___
# Saltos de Linea
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.
Esto es nuestro tercer parrafo.
