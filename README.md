# Traductor

test es un idioma inventado por [Daniel Avellaneda](https://www.totumo.net)

## Descripción del idioma

- Si la palabra termina en "ar" se le quitan esos dos caracteres
- Si la palabra inicia con Z, se le añade "pe" al final
- Si la palabra traducida tiene 10 o mas letras se debe partir a la mitad y unir con un guión del medio
- Si la palabra original es un palíndromo, ninguna regla anterior cuenta y se devuelve la misma palabra intercalando mayúsculas y minúsculas

## Instalación

```
npm install platzom
```

## Uso

```
import platzom from 'platzom'

platzom("Programar") // Programar
platzom("Zorro") // Zorrope
platzom("Zarpar") // Zarppe
platzom("abecedario") // abece-dario
platzom("sometemos") // SoMeTeMoS
```

## Créditos
- [Daniel Avellaneda](https://www.totumo.net)

## Licencia

[MIT](https://opensource.org/licenses/MI)
