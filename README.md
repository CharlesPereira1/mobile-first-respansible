# Respansividade

## CSS Unit

Unidades de medidas do CSS

```js
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
```

Layout Fixo

`px` - pixel

Layout Fluido
`%` - Porcentagem
`auto` - Automática
`vh` - Viewport Height
`vh` - Viewport Height

Textos fixos
`1px` = 0.75pt
`16px` = 12pt

Textos fluidos / line height
`em` - Multiplicado pelo pai e pode se elevar ao quadrado se já existir ref.
`rem` - Multiplicado pelo root

## CSS Media Queries

```css
@media (max-width: 320px) {
  #form h3 {
    font-size: 2rem;
  }
}
```

## HTML Media Attrib. print

```js
<link rel="stylesheet" href="print.css" media="print" />
```

##Image

```js
<picture class="image" alt="Imagem">
              <source
                media="(min-width: 768px)"
                srcset="https://image.com/vi/#$%@#$%@#$%/default.jpg"
              />
```
