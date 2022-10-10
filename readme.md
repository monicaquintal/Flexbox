### Flexbox (Flexible Box Layout)
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
  - com essa propriedade é possível mudar a ordem de exibição dos elementos, sem a necessidade de mudar suas disposições uma a uma no código. <br>

2. flex-wrap:<br>
  - define quebras de layout; <br>
  - opções: <strong>nowrap</strong> (é o padrão, define que não há quebra, os itens serão "apertados" para que caibam no container),  <strong>wrap</strong> (só ficam dentro do container os itens que cabem, permite a quebra) e <strong>wrap-reverse</strong> (exibe os itens em ordem inversa).<br>

3. justify-content:<br>
  - alinha os elementos na horizontal;<br>
  - possibilidades: <strong>flex-start</strong> (é o padrão, alinha no canto superior esquerdo), <strong>flex-end</strong> (cola os conteúdos no canto superior direito), <strong>center</strong> (centraliza os itens), <strong>space-between</strong> (distribui os itens adicionando espaçamento entre eles - últimos itens colados nas extremidades e espaço entre os centrais) e <strong>space-around</strong> (itens nas extremidades tambpem possuem espaçamento, igual os centrais do caso anterior).<br>

4. align-items:
  - faz o alinhamento vertical;<br>
  - opções: <strong>stretch</strong> (é a opção padrão, os itens preencherão a área até ocupar a altura do container), <strong>center</strong> (centraliza os itens, ainda respeitando o justify-content), <strong>flex-start</strong> (os itens ficam colados na parte superior), <strong>flex-end</strong> (itens colados na parte inferior) e <strong>baseline</strong> (utiliza a linha base do texto (superior) para fazer o alinhamento dos itens).<br>

