# platzom-js

Clase de [Fundamentos de Javascript](https://platzi.com/clases/fundamentos-javascript/) en [Platzi](https://platzi.com/). Sobre como crear un modulo Npm

## Descripción del idioma

- Si la palabra termina con "ar", se le quitan esas dos letras.
- Si la palabta inicia con Z, se le añade "pe" al final.
- Si la palaba traducida tiene 10 o más letras, se debe partir en dos por la mitad y unir con un guión medio.
- Por último, si la palabra original es un [palíndromo](https://es.wikipedia.org/wiki/Pal%C3%ADndromo), ninguna regla anterior cuenta y se devuelve la misma palabra pero intercalando letras mayúsculas y minusculas.

## Instalación

```
npm install platzom
```

## Uso

```
import platzom from 'platzom'

platzom("Programar) // Program
platzom("Zorro) // Zorrope
platzom("Zarpar) // Zarppe
platzom("abecedario) // abece-dario
platzom("sometemos) // SoMeTeMoS

```

## Créditos

- [David Castillo](https://davecast.github.io)

## License

[MIT](https://opensource.org/licenses/MIT)