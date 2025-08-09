# starting_html

![HTML5](<html5.png>)

Explicando cada trecho da estrutura base do HTML:

```html
<!DOCTYPE html>
```
- **`<!DOCTYPE html>`**: Esta declaração informa ao navegador que o documento é um arquivo HTML5. É importante para garantir que o navegador renderize a página corretamente de acordo com as especificações do HTML.

```html
<html lang="pt-BR">
```
- **`<html lang="pt-BR">`**: Esta tag abre o elemento raiz do documento HTML. O atributo `lang="pt-BR"` especifica que o conteúdo da página está em português do Brasil, o que ajuda os navegadores e ferramentas de acessibilidade a interpretar e apresentar o conteúdo corretamente.

```html
  <head>
    <meta charset="UTF-8" />
    <title>Document</title>
  </head>
```
- **`<head>`**: Esta seção contém metadados sobre o documento, que não são exibidos diretamente na página.
  - **`<meta charset="UTF-8" />`**: Esta meta tag define a codificação de caracteres do documento como UTF-8, que é uma codificação padrão que suporta a maioria dos caracteres de todas as línguas, incluindo acentos e caracteres especiais.
  - **`<title>Document</title>`**: Esta tag define o título da página, que aparece na aba do navegador. Neste caso, o título é "Document".

```html
  <body>
    <h1>Hello, World!</h1>

    <script src="main.js"></script>
  </body>
```
- **`<body>`**: Esta seção contém o conteúdo visível da página, ou seja, tudo que será exibido para o usuário.

  - **`<h1>Hello, World!</h1>`**: Esta tag representa um cabeçalho de nível 1, que é o mais importante em termos de hierarquia de títulos. O texto "Hello, World!" será exibido em um tamanho maior e em negrito, indicando que é um título principal da página.

  - **`<script src="main.js"></script>`**: Esta tag inclui um arquivo JavaScript externo chamado `main.js`. O código contido nesse arquivo será executado quando a página for carregada. Isso permite que você adicione interatividade e funcionalidades dinâmicas à sua página.

```html
</html>
```
- **`</html>`**: Esta tag fecha o elemento raiz do documento HTML, indicando que o conteúdo do HTML terminou.

### Resumo
Este código HTML básico define uma página com a codificação de caracteres UTF-8, um título e um cabeçalho que exibe "Hello, World!". Além disso, inclui um arquivo JavaScript externo para adicionar funcionalidades à página.
