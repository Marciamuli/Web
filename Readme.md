# Web

Aqui irei disponiblizar todos os códigos que utilizo em sala de aula com as Turmas do Técnico em Informática no Senac SP - Unidade Vila Prudente. 

## O que é HTML?

Existem 3 linguagens básicas que utilizamos para criar websites: HTML, CSS e JavaScript. 

O HTML é a linguagem que irá exibir a informação. O CSS é a linguagem que vai deixar essa informação bonitona. O JavaScript é a linguagem que vai fazer essa informação receber alguns comportamentos. 

O HTML sem dúvida é a mais importante de todas, por que como dissemos no começo, é ela que exibe a informação. Além de exibir a informação, ela dá significado. Isso é importante por que alguns sistemas como o Google, que irão ler sua página, precisam entender o que é cada elemento nela e o que cada um desses elementos significam.

O acrônico HTML significa em inglês: HyperText Markup Language. Para gente aqui fica: Linguagem de Marcação de Hipertexto. Bonito, né?

Por trás das palavras Hipertexto e Marcação tem muita história e guardam a real essência da função do HTML. Você vai saber mais na próxima página, onde falamos sobre Semântica, que nada mais é do que a organização da informação usando HTML.

Se você tiver que guardar alguma coisa sobre o que é HTML, guarde isso: HTML serve para dar significado e organizar a informação dos websites.

Tendo isso em mente, você já saberá muito mais do que a maioria dos profissionais por aí.

## Estrutura básica de um documento HTML
```html
<html>
<head>
	<title>Aqui vai o título do site ou da página</title>
</head>
<body>
	Aqui vai todo o conteúdo do site que será apresentado para o usuário.

</body>
</html>
```

## O que é CSS?

CSS, sigla em inglês para Cascading Style Sheet, que em português quer dizer Folha de Estilo em Cascata, é uma linguagem que cuida da apresentação visual de páginas web através de regras de estilos. Podemos resumir que é uma linguagem de estilização ou apresentação.

A história da Folha de Estilo começou a surgir quando seu criador Håkon Wium Lie constatou que não havia como estilizar documentos em uma plataforma para publicação eletrônica. Em novembro de 1994 em Chicago, Håkon apresentou a proposta inicial do CSS em uma Web conferência.

Esta linguagem consiste em dar forma aos elementos HTML presentes na página web. HTML e CSS são parceiros. O CSS só existe em função do HTML.

Ela pega uma página praticamente sem estilos e enriquece com cores, formas, tamanhos e até animações. E esta linguagem que define qual a cor de um texto, onde determinado bloco será posicionado, entre outros estilos.

E o que é muito bacana é que o CSS também é um recurso acessível para estilizar o que você projetou em seu editor gráfico através de suas propriedades.

Um dos maiores atrativos do CSS é separar a apresentação em um arquivo externo. Com isso o HTML, que antes estava com a função de marcar e apresentar visualmente o conteúdo, ficou responsável por somente estruturar o conteúdo através da marcação.

### O que é possível fazer com CSS?

- Estruturar o layout do site;
- Posicionar elementos na página web;
- Mudar a ordem de apresentação dos elementos HTML;
- Colocar espaçamentos entre elementos;
- Preencher com espaço vazio entre a borda de um bloco e seu conteúdo;
- Colocar diferentes tipos de bordas de diferentes cores nos blocos;
- Inserir bordas arredondadas aos blocos;
- Colocar cor de fundo, gradiente ou imagem de fundo aos blocos;
- Trabalhar com diversas propriedades para tipografia. Inserir sombras em textos e blocos;
- Fazer pequenas animações, transições;
- Ocultar elementos, entre tantas coisas.

### Benefícios de adotar o CSS

- A separação da folha de estilo da marcação;
- Facilidade de manutenção visual do site através de um arquivo externo;
- Disponibilidade de diretiva para construção de layouts que atendam diferentes tipos de dispositivos.
- Aumento na velocidade de carregamento de páginas.

### A Estrutura

__Seletor__: Ele é responsável por selecionar o elemento, ou elementos HTML que receberão determinado estilo.

__Propriedade__: Se refere às características visuais que um elemento pode possuir. Tomamos como comparação qualquer objeto que podemos medir suas dimensões. Altura e largura seriam propriedades deste objeto quando pensamos em tamanho. Os elementos HTML também possuem propriedades de altura e largura.

__Valor__: Corresponde ao produto da propriedade. Ou seja, ele define como o elemento será apresentado. Se um elemento tem uma altura, o valor corresponde ao seu tamanho seguida pela sua unidade de medida. Um bloco com 2 cm de altura possui a propriedade altura cujo valor é 2 cm.

![regra-css](https://user-images.githubusercontent.com/6373438/64572493-efbb3500-d33d-11e9-8332-157970f0371d.jpg)

### Tipos de Seletores

- __Seletor__ – também conhecido como a tag na qual queremos aplicar a formatação;
- __ID__ – quando você coloca um nome identificador para o elemento;
- __Classe__ – que trabalha de forma semelhante ao ID, mudando apenas a forma como é feita a declaração no arquivo HTML e a chamada dele no arquivo CSS.
