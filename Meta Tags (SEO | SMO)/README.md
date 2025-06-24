# Meta tags (SEO / SMO) ✨💻]

## 🛠️ Descrição do Projeto

Esta pasta é dedicada a explicação e apresentação dos modelos mais utilizados de tags voltada aos motores de busca como **Google**, **Yahoo** entre outros.

## 🚀 Como Usar

Para colocar essas tags, não é necessário intalar nenhuma dependência e sim estrutura-las dentro das tags ```<head>``` no começo do seu código. Algo mais ou menos assim:

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <!-- 🔥 Tags que vamos inserir aqui -->
</head>

<body>
    <!-- Conteúdo visível do site -->
</body>
</html>

```

## 🏷️ Tags Básicas

Essas são as tags mais comuns e são fundamentais para a formatação, estruturação, compatibilidade e responsividade do seu site.

```html
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
## 🏷️💻 Tags SEO (Search Engine Optimization)

"description"
```html
<meta name="description" content="">
```
- Esta tag serve para mostrar uma descrição breve e atraente da página para aparecer nos mecanismos de busca.
<br>
 
"robots"

```html
<meta name="robots" content="index, follow">
```
- Esta tag serve para mostrar ao robôs dos motores de busca se deve aparecer nos resultados de busca e se devem seguir os links de busca. Além deste, existe outro tipo como:

```html
<meta name="robots" content="noindex, nofollow">
```
- Esta tag serve para mostrar que os robôs não devem, nem mostrar esta página nas pesquisas e nem rastrear os links dela. 
<br>

"canonical"

```html
<link rel="canonical" href="https://www.seusite.com/pagina-atual">
```
- Esta tag serve para mostrar a URL oficial da página, ou seja, deve ser considerada como a URL principal da página.
<br>

## 🏷️📱 Open grafh SMO (Social Media Optimization) 

"og:type"

```html
<meta property="og:type" content="website">
```
- Define o tipo de conteúdo (geralmente "website", "article", "video", etc.) para as redes sociais.
<br>

"og:Title"

```html
<meta property="og:title" content="Título para Redes Sociais">
```
- Define o título que aparece quando a página é compartilhada nas redes sociais.
<br>

"og:description"

```html
<meta property="og:description" content="Descrição para redes sociais, atrativa e clara.">
```
- Mostra a descrição resumida no card de compartilhamento.
<br>

"og:image"

```html
<meta property="og:image" content="https://www.seusite.com/imagens/imagem-de-compartilhamento.jpg">
```
- Exibe uma imagem de capa ou destaque no card compartilhado.
<br>

"og:url"

```html
<meta property="og:url" content="https://www.seusite.com/pagina-atual">
```
- Indica a URL canônica que será exibida no card, associando o conteúdo.
<br>

"og:site_name"

```html
<meta property="og:site_name" content="Nome do Site">
```
- Mostra o nome do site ou da marca no card das redes sociais.


















