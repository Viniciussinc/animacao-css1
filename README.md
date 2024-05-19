# animacao-css1
Este é um projeto sobre animações em css, com o intuito de praticarmos o que apreendemos na aula de desenvolvimento web 1. Seguindo isto dediquei este projeto sobre uma pagina de carregamento.
### Veja como ficou:
![Funcionamento do Projeto](https://github.com/Viniciussinc/animacao-css1/blob/main/Spin.gif)
### Codepen: https://codepen.io/Vinicius-Araujo-the-vuer/pen/yLWepZj
# Meu Projeto
Aqui está na integra o código HTML:
###  HTML:


```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <div id="spin"></div>
</body>
</html>
```
### Css:
```
#spin{
	width: 200px;
	height: 200px;
	background-color: #da8989;
	margin:100px auto;
	border-radius: 100%;
	border:25px solid  	#811616;
	border-top: 25px solid #db0b0b;
	animation: spin 10s  linear infinite;
}
@keyframes spin{
from{transform: rotate(0deg);}
to{transform: rotate(360deg);}
}
body{background-color: black;}
```
