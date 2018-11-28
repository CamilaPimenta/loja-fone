# HTML 5

É uma linguagem de marcação que tem as seguintes responsabilidades:

- Conteúdo;
- Semântico - utilizar as TAG's de forma correta;
- Estrutura;

## TAG

- `<!DOCTYPE html>` - Informa para o navegador usar a versão mais atual.

- `<h1>` - Heading (valores de 1 - 6)

  > Usamos ele quando queremos definir títulos

- `<html>` - tags "head" e "body" são tags html

- `<meta charset="utf-8" />` - tag e comando para ter caracteres especiais

- `<head>` - Configuração. Tag que envolve as tag de configuração

- `<body>` - Tag envolve as tag's de texto que aparece para o usuário

- `<a>` - Links (a - anchor)
  > Usamos para definir a navegação do usuário. Se você tem um texto que você quer que o o usuário clique e ele vá para outro lugar você pode usar essa tag junto com o atributo `href`. Exemplo de um `a` que o usuário é direcionado para um site:

```
<a href="http://www.google.com.br"> Google </a>
```

- `<nav>` - Envolve as tags e informa as tag's para navegação. Tag 'pai'

```
<nav>
        <a href="http://collabcode.training">Produtos</a>
        <a href="http://collabcode.training">Serviços</a>
        <a href="http://collabcode.training">Carrinho (10)</a>
      </nav>
```

- `<header>` - Envolve as tags do cabeçalho do site

- `<title>` - browser que defini onde vai o título. Geralmente no texto da aba da página.

---

# CSS

É uma linguagem de estilo.
Tem as seguintes responsabilidades.

- Visual;

- `font-size` - define o tamanho da fonte;
- `background-color` - define a cor de fundo;
- `color` - define a cor da fonte;
- `font-family` - define a família da fonte [prestar atenção na família da fonte];
- `text-decoration` - deixa o texto simples;
- `overflow: hidden` - propriedade para esconder um elemento;
- `opacity` - deixa o elemento opaco;
- `float` - elemento flutuante;
- `margin-left/right` - fornece a margem externa para o elemento. (respiro/responsivo).

  Forma resumida para codificar o margin left, right, top, bottom, quantidade de valor entre parênteses:

```
margin: top/bottom right/left; (2 valores);
```

> `margin` - Espaçamento entre elementos. Se houver dois elementos e empurrar/distanciar um elemento do outro é chamado de respiro externo _margin_.

- `padding-left/right` - fornece a margem interna para o elemento. (respiro/responsivo);
- `padding-top` - fornece margem do topo para o próximo elemento;
- `padding-bottom` - fornece margem entre dois elementos;

Forma resumida para codificar o padding left, right, top, bottom, quantidade de valor entre parênteses:

```
padding: top right, bottom, left; (todos valores);
padding: top/bottom right/left; (2 valores);
padding: top right/left bottom; (3 valores);
padding: top/rigth/left/bottom;(1 valor);
```

> `padding` - Espaçamento dentro do próprio elemento. Se desejamos que o conteúdo se afaste/empurre a extremidade, então é um respiro interno _padding_.
