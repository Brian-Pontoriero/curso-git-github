# Versión del curso
Versión Actual: v1.2.2

# Cabeceras
# Cabecera 1
## Cabecera 2
### Cabecera 3
#### Cabecera 4
##### Cabecera 5
###### Cabecera 6

# Underlines
underline 1
-----------
underline 2
===========

# Formatos de énfasis
- Formato *italica* de la primer forma.
- Formato _italica_ de la segunda forma.
- Formato **bold o strong** de la primer forma.
- Formato __bold o strong__ de la segunda forma.
- Formato ~~tachado~~, Formato normal.
- Aquí podemos usar Formato *italica*, pero también **bold** y ~~tachado~~.

# Listas
1. Esto es un ítem de lista ordenada.
2. Esto es un ítem de lista ordenada.
3. Esto es un ítem de lista ordenada.

- Esto es un ítem de lista desordenada.
- Esto es un ítem de lista desordenada.
- Esto es un ítem de lista desordenada.

# Links
- <a href="https://www.google.com.ar">Esto es un link HTML</a>
- [Esto es un link en Markdown](https://www.google.com.ar)
- [Esto es un link al index](index.html)

# Imágenes
![Logo Github](https://cdn-icons-png.flaticon.com/256/25/25231.png)


# Code Snippets
Código en JSON
```JSON
{
    "glosario": {
        "title": "glosario de ejemplo",
        "Divbrillo": {
            "título": "S",
            "Lista de brillo": {
                "Entrada de brillo": {
                    "ID": "SGML",
                    "Ordenar como": "SGML",
                    "GlossTerm": "Lenguaje de marcado generalizado estándar",
                    "Acrónimo": "SGML",
                    "Abreviatura": "ISO 8879:1986",
                    "Definición de brillo": {
                        "para": "Un lenguaje de meta-marcado, utilizado para crear lenguajes de marcado como DocBook.",
                        "GlossSeeAlso": ["GML", "XML"]
                    },
                    "GlossSee": "marcado"
                }
            }
        }
    }
}
```

Código en Javascript
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
```
# Tablas
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Brian  | Pontoriero | 37609735 |
| Tomás  | Tompson | 33987609 |

# Citas
Esto es un texto referente a una cita que pondremos debajo.
> Esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior.
>Esto es otra cita.

# Líneas Divisorias
Esto es un texto dividido por guiones medios.

---
Esto es un texto dividido por asteriscos.

***

Esto es un texto dividido por guiones bajos.

___

# Saltos de línea
Esto es nuestro primer párrafo.

Esto es nuestro segundo párrafo.

Esto es nuestro tercer párrafo.
- Lista

