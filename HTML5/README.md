# HTML5

## Estrutura Básica

    <!DOCTYPE html>
    <html>
      <head>
      <meta>
      <title></title>
      <link:css>
      </head>
      <body>
      </body>
    </html>

## Semâtinca Parte - 1

    - <section> - Seção Generica.
    - <aside> - Representa um conteúdo relacionado da página.
    - <header> - Cabeçalho da Página ou Section.
    - <footer> - Rodapé da página ou parte da página e rodapé da section.
    - <article> - Conteúdo relevante como o artigo de um blog.
    - <h1>-<h6> - Representa a importância do titulo.

## Textos e links - p, a

- p - Representa um parágrafo, mas aceita todo tipo de conteúdo dentro dele.

- a - Link(âncora) interliga varios conteúdos na Web,
  exemplo: \*<a href="https://www.linkedin.com/in/bruno-barbosa-neves-1b15621ab/">LinkedIn</a> \*<a href="mailto:brunobningles@gmail.com">E-mail</a> \*<a target="_blank">Link</a>

## Imagens - img

- img - Imagem - img tem apenas dois atributos próprios o source(obrigatório) e o alt(recomendável para melhorar a acessibilidade).

## Listas ul, ol, li

- ul - Reresenta uma lista que não é importante

- ol - São importantes e são representandos com números, letras ou algorismo romano.

- li - Item da lista ul ou ol

# CSS3

## Introdução CSS3

  <ol>
    <li>
      O que são seletores.
    </li>
    <li>
      Conceitos básicos.
    </li>
    <li>
      Os principais seletores.
    </li>
  </ol>

## ID e Classes

- ID: é representado pelo símbolo # (hash) seguido de um nome para o ID.

- Class: é representada de forma parecida com o ID, mas é precedida por um . (ponto) em vez de # (hash).

## Conceitos Básicos

### Box model - Existe 4 áreas, margin, border, padding, content.

- Margin - É o espaçamento entre elementos.

- Border - Circunda o padding e o content. Com a border podemos ainda alterar a largura e a cor.

- Padding - E o espaçamento entre a border e o content. <br>

- Content - É o que o seu bloco representa. <br>

### Estilizando elementos

<h3>Padding e Margin</h3>

- Explicação:<br>
  - 1ª Forma: <br>
    - Colocamos um valor superior e inferior, depois colocamos para os lados esquerdo e direito.<br><br>
  - 2ª Forma: <br>
    - Começamos pelo topo 15px, lado direito 10px, inferior 5px, lado esquerdo 0, sempre dessa forma.<br><br>
  - 3ª Forma: <br>
    - É com as propriedades específicas para cada lado. Exemplo: padding-left: 10px; <br><br>

<h3>Background</h3>
  - Explicação: <br>
    - A propriedade <i>background</i> tem tem um atalho para várias propriedades, e uma boa opção de leitura é a Documentação do MDN. <br>
    <br>
    - E como podemos utilizar a background? <br>
      - Podemos utilizar a background da seguinte forma para alterar as cores.
        - 1ª Forma: <br>
          - Pelo nome da cor. <br>
          background: gray;
        - 2ª Forma: <br>
          - Pelo código Hexadecimal. <br>
           background: #ccc
        - 3ª Forma: <br>
          - É usando o atalho background<br><br>
<h3>Border</h3>
  - Explicação: <br>
   - Vimos que a propriedade border pode ter 3 valores: a largura, a cor e o estilo, mas existem algumas particularidades nisso. <br>
      - A largura pode ser usada com várias unidades, como px, em e mm. <br>
      - A cor pode ser atribuída pelo nome ou por um código hexadecimal.
      
        - solid: mostra uma borda simples e reta;

        - dotted: são bolinhas com um pequeno espaçamento entre elas;

        - dashed: forma uma linha tracejada.

    - Existem ainda outras propriedades para border que são:

      - border-width
      - border-color
      - border-style
      - border-radius

<h3>Estilizando textos</h3>

- font-family <br>

  - Com o font-family podemos alterar a fonte dos nossos textos, como uma fonte da internet ou uma que esteja instalada no nosso computador. <br>

- font-size <br>

  - O font-size nos ajuda a mudar o tamanho do texto.<br>

- font-style <br>

  - Usamos o font-style para tornar um texto itálico, na maioria das vezes você usará apenas o valor italic para ele, mas se precisar tirar o itálico de um texto você pode usar o valor normal.
