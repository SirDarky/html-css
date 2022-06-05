# Trabalhando com fontes

Tipografia transmmite mensagem
    
    - Negrito
    - Tamanho
    - Estilo

------------------------------------------------------

## Basic Font Properties

* font-family
* font-weight
* font-style
* font-size

------------------------------------------------------

## Font Family

* Tipo de fonte de um elemento
* Lista de fontes e ordem de prioridade
* Inclui *fallback* font

```css
p{
    font-family: "Times New Roman", Times, serif;
}
```
"Times" e "serif" é o fallback (o escape)

    - serif
    - sans

------------------------------------------------------

## Font Weight

* Peso da fonte

```css

p{
    font-weight:bold;
}
```

------------------------------------------------------

## Font Style

* O Estilo da fonte

```css
span {
    font-style: italic;
}
```

------------------------------------------------------

## Font Size

* O tamanho da fonte

```css
p{
    font-size: 18px;
}
```
------------------------------------------------------

## Web Fonts

- Fontes do sistema x fontes da web
- Como usar fontes para web?

    * @fonte-face
    * @import
    * link

### Referências

https://www.w3.org/TR/css-fonts-3/
https://css-tricks.com/snippets/css/using-font-face