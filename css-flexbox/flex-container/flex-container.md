# Propriedades do Flex Container

* Direção dos itens
* Multi linhas
* Alinhamento
    * Principal
    * Cruzado
* espaços entre os itens

## Direção dos itens

- Flex é uma dimensão (horizontal ou vertical)
- podemos mudar a direção com `flex-direction`
- Valores: (row | row-reverse | column | column-reverse)

## Flex-wrap

- Podemos usar multi linhas.
- Cada nova linha, um novo flex container 
- Valores: (wrap | wrap-reverse)

## Flex-flow

- Shorthand
- flex-direction || flex-wrap

ex: 
```css
flex-flow: column wrap;
```