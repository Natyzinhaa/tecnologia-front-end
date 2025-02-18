# Tecnologia Front-end #

### O que é HTML?
HTML (HyperText Markup Language) é a linguagem padrão para a criação de páginas web.
Definir os elementos que aparecem numa página, como títulos, parrágrafos, imagens, links, botões e tabelas.
Interagir páginas web através de links.

### Como é estruturado o HTML?
É composto por marcadores (tags) e atributos.
As tags são identificadas com um sinal de menor que (<), seguindo pelo nome da tag e um sinal de maior que(>).
A maioria das tags precisa ser fechada, o que representamos com uma barra(/) entre o sinal "<" e o nome da tag.

### Estruturas básica de um documento HTML
Aqui está um exemplo simples de um documento HTML:
``` HTML
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Para colocar titulo</title>
</head>
<body>
    
</body>
</html>
```

## Exemplos de tags
**`Button:`** Você pode criar um botão, a tag button de abertura <button>, e uma tag de fechamento </button>.

### Exemplo:
```HTML
<button>Curtir</button> 
```

## Textos e títulos:
**`p:`** Para codificar um parágrafo você precisa da tag de abertura e a tag de fechamento.

### Exemplo:
```HTML
<p>Olá Brasil</p>
```

**`h1 até o h6:`** Existem 6 tamanhos de títulos em HTML, de h1 a h6. A tag título enfatiza os textos tornando-os maiores e mais em negrito, h1 é o maior e mais em negrito e h6 é menor e menos em negrito.

### Exemplo:
```HTML
<h1>Olá</h1> 
```

## Quebras de linha, ênfase e importância:
**`br:`** Podemos separar linhas com a ajuda da tag de quebra de linha br, <br> é uma tag vazia. Tags vazias não tem fechamento e nem conteúdo.

### Exemplos:
```HTML
<h1>Ola mundo</h1> <br>
<h2>Que?</h2>
```

**`em:`** O elemento em torna texto itálico. 

### Exemplos:
```HTML
<em>Favorito</em>
```

**`strong:`** Para definir textos como importantes ou em negritos.

### Exemplos:
```HTML
<strong>Favorito</strong>
```

## Links e atributos:

**`a:`** 