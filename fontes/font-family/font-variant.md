## Font-variant

* Variações na apresentação fonte

```css
p{
    font-variant: small-caps;
}
```

------------------------------------------------------

## Font-stretch

* alargamento ou encolhimento da fonte
* aceita palavras-chaves como: expanded, condensed, normal
* aceita porcentagens de 50% a 200%

```css
p{
    font-stretch: expanded;
}
```

------------------------------------------------------

## Letter-spacing

* Espaços entre caracteres

```css
p{
    letter-spacing: 4px;
}
```
------------------------------------------------------

## Word-spacing

* Espaços entre caracteres
```css
p{
    word-spacing: 4px;
}
```

------------------------------------------------------

## Line-height

* Espaços entre linhas
* Pode ser com unidades ou sem unidades de medida
* Comuns: 1.5 ou 2

```css
p{
    line-height: 1.6 ;
}
```

------------------------------------------------------

## Text-transform

* Transformação do texto

```css
p{
    text-transform: uppercase; /* capitalize / lowercase / none */
}
``` 

------------------------------------------------------

## Text-decoration

* Aparencia decorativa de um texto
* Line: underline / overline / line-throght
    * podemos aplicar mais de 1 valor
* Style: wavy / dotted / double / dashed / solid
* Color: `<color>` values

```css
p{
    text-decoration: underline; /* shorthand */
}
```
------------------------------------------------------

## Text-align

* Alinhamento de um texto

```css
p{
    text-align: center; /* left / right / center / justify */
}
```
------------------------------------------------------

## text-shadow

* Sombra aplicada a um texto
* Perminte múltiplos valores

```css
p{
    text-shadow: 1px 1px 1px red,
                2px 2px 1px green; /* offset-x / offset-y / blur-radius / color */
}
```
------------------------------------------------------

## Short hand

* Font-style, font-variant, font-weight, font-stretch, font-size, line-height e font-family.

```css
p{
    /* -style, -variant, -weight, - stretch, -size, line-height, e -family*/
    font: italic normal bold normal 3em/1.5 Helvetica, Arial, sans-serif;
}
```
------------------------------------------------------