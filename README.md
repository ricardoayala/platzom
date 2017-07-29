# Platzom

Platzon es un idioma inentado para el curso de [fundamentos de JavaScript](https://platzi.com/js), de [Platzi](https://platzi.com), el mejor lugar de educación online
##
- Si la palabra termina con "ar" se le quitan esas dos letras
- Si la palabra inicia con Z, se le añade "pe" al final
- Si la palabra traducida tiene 10 o más letras, se debe partir en dos por la mitad y unir con un guion medio
- Por último, si la palabra original es un palíndromo, ninguna regla anterior cuenta y se devuelve la misma palabra pero intercalando letras mayúsculas y minúsculas

##Instalación

```
npm install platzom
```

## Uso

```
import platzom from 'platzom'
platzom("Programar") //Program
platzom("Zorro") // Zorrope
platzom("Zarpar") // Zarppe
Platzom("abecedario") //abece-dario
platzom("sometemos") //SoMeTeMoS
```

##Créditos
- [Ricardo Ayala Montes](https://twitter.com/RicardoAyalaM)

## Licencia

[MIT](https://opensource.org/licenses/MIT)
