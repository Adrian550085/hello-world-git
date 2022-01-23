# Cabeceras
# Cabecera H1
## Cabecera #2
### Cabecera #3
#### Cabecera #4
##### Cabecera #5
###### Cabecera #6


# Underlines
Underline 1
-----------

Underline 2
===========


# Formatos de enfasis
- formato *italica* de la primer forma.
- formato _italica_ de la segunda forma.

- formato **hold o strong** de la primer forma.
- formato __hold o strong__ de la segunda forma.

- formato ~~tachado~~, formato normal.

- *formato italico* pero tambien **bold** y ~~tachado~~


# Listas
1. Esto es un item de lista ordenada
2. Esto es un item de lista ordenada
3. Esto es un item de lista ordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada

# Links
- <a href="http://google.com">Esto es un link HTML</a>
- [Esto es un link en markdown](http://google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo Nike](https://tentulogo.com/wp-content/uploads/2017/07/nIke-logo.jpg)

# Code Snippets
```JSON
Codigo en JSON
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
Codigo en Javascript
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