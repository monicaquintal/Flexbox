## Flexbox (Flexible Box Layout)
Curso Desenvolvimento Web Completo 2022. 
<hr>

### Aula 01: Flexbox - container.
Flexbox:
- é um recurso do CSS 3, um novo módulo de layout; <br>
- permite que se disponha elementos em container de maneira muito mais simples e poderosa;<br>
- permite que deixemos os layout mais flexíveis.<br>
<br>

Observações:<br>
- definir "display: flex" no container.<br><br>

1. flex-direction:<br>
  - define as direções que quer alinhar os elementos (flex items);<br>
  - parâmetros: <strong>row</strong> | <strong>row-reverse</strong> | <strong>column</strong> | <strong>column-reverse</strong>;<br>
  - com essa propriedade é possível mudar a ordem de exibição dos elementos, sem a necessidade de mudar suas disposições uma a uma no código. <br><br>

2. flex-wrap:<br>
  - define quebras de layout; <br>
  - opções: <strong>nowrap</strong> (é o padrão, define que não há quebra, os itens serão "apertados" para que caibam no container),  <strong>wrap</strong> (só ficam dentro do container os itens que cabem, permite a quebra) e <strong>wrap-reverse</strong> (exibe os itens em ordem inversa).<br><br>

3. justify-content:<br>
  - alinha os elementos na horizontal;<br>
  - possibilidades: <strong>flex-start</strong> (é o padrão, alinha no canto superior esquerdo), <strong>flex-end</strong> (cola os conteúdos no canto superior direito), <strong>center</strong> (centraliza os itens), <strong>space-between</strong> (distribui os itens adicionando espaçamento entre eles - últimos itens colados nas extremidades e espaço entre os centrais) e <strong>space-around</strong> (itens nas extremidades tambpem possuem espaçamento, igual os centrais do caso anterior).<br><br>

4. align-items:
  - faz o alinhamento vertical;<br>
  - opções: <strong>stretch</strong> (é a opção padrão, os itens preencherão a área até ocupar a altura do container), <strong>center</strong> (centraliza os itens, ainda respeitando o justify-content), <strong>flex-start</strong> (os itens ficam colados na parte superior), <strong>flex-end</strong> (itens colados na parte inferior) e <strong>baseline</strong> (utiliza a linha base do texto (superior) para fazer o alinhamento dos itens).<br><br>

### Aula 02: Flexbox - itens - parte 1.

1. propriedade order:
  - é possível criar classes novas e utilizar o atributo "order" para alterar a ordem de exibição dos itens (dentro de um flex item);<br>
  - numerar esse atributo com números inteiros (podendo ser negativo; o valor inicial padrão é 0) para definir a ordem.<br><br>

2. propriedade flex-growth:
  - define a proporção de espaço ocupado por um item; <br>
  - o padrão é zero; quando é atrubuido valor 1, o item ocupará todo o espaço disponível até o máximo do container. Ao aumentar o número do flex-growth, o item ocupará um espaço maior. <br>
  - ou seja, quando maior o número, maior o espaço que ele ocupa.<br><br>

### Aula 03: Flexbox - itens - parte 2.

 1. flex-shrink:
  - define a proporção com que um item deve encolher caso seja necessário;<br>
  - aceita apenas valores positivos, e seu valor padrão é 1;<br>
  - quanto maior o valor, menor o espaço que ocupará.<br><br>

2. flex-basis:
  - indica o tamanho inicial do flex item antes da distribuição do espaço restante;<br>
  - pode ser usado inclusive com shrink e growth.<br>
  <hr>

### Observações:

1. O Flexbox <a href="https://caniuse.com/?search=flexbox">não é suportado</a> em todas as versões dos navegadores. Para que o Flexbox funcione adequadamente em navegadores antigos, utilizar <a href="https://github.com/jonathantneal/flexibility">este link</a> disponibilizado na aula.<br>
(To start using Flexbox in Internet Explorer 8 & 9 or any older browser, download the flexibility.js script and include it anywhere on your page.)<br><br>

2. Uso dos <a href="https://autoprefixer.github.io/">Prefixos</a> também é recomendado para o Flexbox. <br><br>
