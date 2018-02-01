# PLATZOM

Platzom es un codificador de palabras desarrollado para el curso de [Fundamentos de JavaScript](https://platzi.com/js) de [Platzi](https://platzi.com/).

## Descripcion del Idioma

- Si la palabra termina en "ar", se elimina esa terminación.
- Si la palabra inicia con Z, se le añade "pe" al final de la palabra.
- Si la palabra traducida tiene 10 o más letras, se debe partir en dos por la mitad, y unirlas con un guion "-".
- Finalmente si la palabra es un palindromo, ninguna regla anterior cuenta, y se devuelve la misma palabra pero con MAYUSCULAS y minusculas intercaladas.

## Instalación

```
npm install platzom
```

## USO

```
import platzom from 'platzom'

platzom("Programar") //Program
platzom("Zorro") //Zorrope
platzom("Zarpar") //Zarpe
platzom("abecedario") //abece-dario
platzom("sometemos") //SoMeTeMoS

```

## Créditos
- [Sacha Lifszyc](https://twitter.com/@slifszc)
- [Diego Polanco](https://twitter.com/@diego_polanco)

<!-- ## Licencia -->

[MIT](https://opensource.org/licenses/MIT)
