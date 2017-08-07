# Platzom

Platzom es un idioma inventado para el [Curso de Fundamentos de JS](https://platzi.com/js).

## Descripcion del idioma

- Si la palabra termina en 'ar', se le quitan esos dos caracteres.
- Si la palabra inicia con z, se le anade 'pe' al final.
- Si la palabra traducida tiene 10 o mas letras, se debe partir a la mitad y unir con un guion del medio.
- Si la palabra original es un palindromo, ninguna regla anterior cuenta y se devuelve la misma palabra intercalando mayusculas y minusculas

## Instalacion

```
npm install platzom
```

## Uso

```
import platzom from 'platzom'

platzom('Programar') //Program
platzom('Zorro') //Zorrope
platzom('Zarpar') //Zarppe
platzom('Abecedario') //Abece-dario
platzom('sometemos') //SoMeTeMoS
```

## Licencia

[MIT](https://opensource.org/licenses/MIT)
