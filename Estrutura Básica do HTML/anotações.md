FORMAÇÃO HTML

Módulo 1: Introdução ao HTML na prática

Ferramentas Utilizadas:

VScode: Visual Studio Code
Extensões:
Live Server
Google Chrome

INSPETOR DE ELEMENTOS

TAGS

<html> //define que é um documento html
	<head> //é pré carregado na página antes dela aparecer para o usuário
		<title>Meu site</title> //título da aba
	</head>
	<body> //tudo que o usuário irá ver na página
		Meu primeiro HTML!
</body>
</html>

Algumas tags possuem tag de fechamento, ex: <i></i>, porém, existem algumas que não possuem, como por exemplo: 

<input type=”text” /> onde é aberto um campo para digitar na página
<img />

Algumas tags, como no exemplo acima, possuem atributos (type=”text”)...

Tags genéricas

id=”titulo”: identificador deste elemento que pode ser usado no JavaScript
style=”titulo”: geralmente utilizado no CSS para formatar o elemento (trocar cor, fonte etc…)
class=”titulo-principal”: tudo que tiver como 

Tags específicas

input type=”text”
input type=”number”
input type=”color”

img src=”endereço da imagem (Seja do pc ou do navegador)”
img width=”150”: altera o tamanho da imagem

Isso são atributos.

TEXTOS - TIPOGRAFIA

Hierarquia de títulos de h1 a h6

Citações: blockquote

LISTAS

ORDENADAS:

O navegador interpreta de forma padrão mas isso pode ser personalizado através de CSS

<ol> //lista ordenada (1. 2. 3…)
	<li>Item 1</li>//os itens da lista
</ol>

NÃO ORDENADAS
<ul> //lista não ordenada, com pontos (marcadores)

LINKS

tag: a: âncora

Ex:

<html>
	<head>
		<title>Título do Site</title>
	</head>
	<body>
		<h1>Meu primeiro site</h1>
		<ul>
			<li>
				<a href="https://fabiozanini.com">fabiozanini.com</a> //isso faz o link abrir na mesma página
			</li>
			<li>
				<a href="https://fabiozanini.com" target="_blank">fabiozanini.com</a> //o target blank faz faz o link abrir em uma nova aba
			</li>
			<li>
				<a href="https://fabiozanini.com" title="Passar o mouse" target="_blank">fabiozanini.com</a> //Este Atributo 'title', permite abrir um balão com o nome ao passar o mouse por cima
			</li>
		</ul>
	</body>
</html>

Tag hr: serve pra traçar uma linha divisória

Resumo de tags aprendidas:

a: para criar links
hr: traçar linha divisória

Link com ancoragem (Pra mesma página. Ex: índice)

Para isso, podemos usar o id assim:

<a href="#surgimento"></a>

<h1>O Surgimento da pilha alcalinha</h1>
<h2>Você pode se surpreender em como isso ocorreu</h2>
<p>a pilha alcalina surgiu após a necessidade de os ratos de laboratório demonstrarem aptidão a jogar jogos eletrônicos, então, para não ter que utilizar energia elétrica, pesquisadores criaram as pilhas para que eles possam jogar e se movimentar ao mesmo tempo.</p>

**Deixando tudo mais organizado:**

**Tags aprendidas**

**ESTRUTURA E HIERARQUIA**

<h1> até <h6>: Estas são tags utilizadas para determinar o tamanho do texto e seguir uma hirarquia, sendo o h1 o maior e o h6 o menor. É importante seguir uma ordem lógica sem pular níveis.

<p>: Este é utilizado para determinar os parágrafos. É um bloco de construção básico para textos corridos.

<hr>: O Hr é utilizado para criar uma linha divisória quebrando um tema ou separando um assunto

**FORMATAÇÃO E ÊNFASE**

<strong>: É a tag utilizada para destacar uma letra, palavra ou parte do texto (Negrito). Serve para dar ênfase.

<i> Itálico, servindo para temas técnicos, pensamentos, termos etc.

<u> Sublinhado, deixando uma linha logo abaixo da letra, palavra ou frase.

<mark> É utilzado para destacar/marcar partes do texto que são relevantes.

<small> Serve para comentários laterais ou letras miúdas (Avisos legais, direitos autorais), diminuindo o tamanho da fonte.

<sub> Define um texto um pouco mais abaixo da linha, exemplo: H<sub>2</sub>O (H20)

<sup> Define um texto um pouco mais acima da linha, exemplo: x<sub>2</sub> (x2 x ao quadrado)

**LISTAS E CITAÇÕES**

<ol>: Lista ordenada. Utilizada quando a sequência dos itens importa (ex: tutoriais passo a passo).

<ul>: Lista não ordenada. Utilizada para itens sem hierarquia de sequência (ex: lista de compras).

<li>: Item de lista. É a tag obrigatória dentro de <ol> ou <ul> para conter cada elemento.

<blockquote>: Indica uma seção citada de outra fonte. Geralmente causa um recuo visual no texto.

**NAVEGAÇÃO**

<a>: Define um hiperlink. Utiliza o atributo **href** para conectar o usuário a outra página, arquivo ou seção

<font>: Era utilizada para definir a aparência do texto através de atributos como color, size e face.

Uso no desafio: Embora hoje o CSS faça esse papel, você a usará para alterar o visual diretamente na tag (ex: <font color="red">Texto</font>).

<del> (Deleted): Indica que um trecho de texto foi removido. O navegador exibe o texto com uma linha atravessada. É ideal para mostrar o que mudou em uma aula ou uma atualização de preço.

<p> (Paragraph): A tag fundamental para organizar blocos de texto. Ela separa os pensamentos e garante o espaçamento vertical correto na página.

<abbr> (Abbreviation): Representa uma abreviação ou sigla.

Dica de Prática: Sempre use com o atributo title para que, ao passar o mouse, o navegador mostre o texto completo. Ex: <abbr title="Digital Innovation One">DIO</abbr>