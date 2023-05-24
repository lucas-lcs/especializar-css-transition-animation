# CSS transition e animation

Quando temos alguma propriedade css que muda de valor em um hover, focus ou outro tipo de interação, podemos usar o transition para suavizar a mudança do ponto A ate o ponto B

**Transition property e duration**

transistion-property - é a propriedade css que queremos aplicar a transição

transition-duration - é o tempo de duração da transição

*Somente valores quantificáveis podem ser animados. Isso quer dizer que não é possível fazer uma animação de display indo de none para block, mas sim de opacity de 0 para 1;*

**Transition timing functions**

- ease - Início lento, rápido e final lento (este é o padrão)
- linear - Mesma velocidade do início ao fim
- easy-in - Início lento
- easy-out - Final lento
- easy-in-out - Início e fim lentos
- cubic-bezier(n,n,n,n) - Permite definir seus próprios valores em uma função cubic-bezier

**Transition delay**

transition-delay é uma propriedade CSS que permite atrasar o inicio de uma transição em uma escala de segundos

**Transition property all**

transition-property: all, é usado para aplicar transição em todos os elementos quantificáveis disponíveis e que estejam sofrendo alteração


## Resultados do transition e Transition Timming Function 

- *Transition*

![Peek 24-05-2023 05-54](https://github.com/lucas-lcs/especializar-css-transition-animation/assets/121250838/88a71462-c8f0-4b81-9c35-d8a5d13e5bf4)

- *Transition Timming Function*

![Peek 24-05-2023 05-55](https://github.com/lucas-lcs/especializar-css-transition-animation/assets/121250838/d4d4692d-13e0-4b57-81b2-df29e8e345bb)