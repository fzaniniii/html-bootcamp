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

<h1> Meu primeiro site</h1>
