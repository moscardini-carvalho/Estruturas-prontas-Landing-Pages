# Meta Tags (SEO / SMO) ✨💻

## 🛠️ Descrição do Projeto

Esta pasta é dedicada à explicação e apresentação dos modelos mais utilizados de tags voltadas aos motores de busca como **Google**, **Yahoo**, entre outros.

## 🚀 Como Usar

Para colocar essas tags, não é necessário instalar nenhuma dependência, apenas estruturá-las dentro da tag `<head>` no início do seu código. Algo mais ou menos assim:

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

---

## 🏷️ Tags Básicas

Essas são as tags mais comuns e fundamentais para a formatação, estruturação, compatibilidade e responsividade do seu site.

```html
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

---

## 🏷️💻 Tags SEO (Search Engine Optimization)

### "description"

```html
<meta name="description" content="">
```
- Esta tag serve para mostrar uma descrição breve e atraente da página nos mecanismos de busca.
<br>

### "robots"

```html
<meta name="robots" content="index, follow">
```
- Permite que os robôs dos motores de busca indexem a página e sigam os links.

```html
<meta name="robots" content="noindex, nofollow">
```
- Instrui os robôs a **não indexar** a página e **não seguir** os links.
<br>

### "canonical"

```html
<link rel="canonical" href="https://www.seusite.com/pagina-atual">
```
- Indica qual é a **URL oficial e principal** da página, evitando problemas de conteúdo duplicado.
<br>

---

## 🏷️📱 Open Graph (SMO - Social Media Optimization)

### "og:type"

```html
<meta property="og:type" content="website">
```
- Define o tipo de conteúdo (ex.: "website", "article", "video") para redes sociais.
<br>

### "og:title"

```html
<meta property="og:title" content="Título para Redes Sociais">
```
- Define o título que aparece quando a página é compartilhada.
<br>

### "og:description"

```html
<meta property="og:description" content="Descrição para redes sociais, atrativa e clara.">
```
- Exibe uma descrição resumida no card de compartilhamento.
<br>

### "og:image"

```html
<meta property="og:image" content="https://www.seusite.com/imagens/imagem-de-compartilhamento.jpg">
```
- Mostra a imagem de destaque no card das redes sociais.
<br>

### "og:url"

```html
<meta property="og:url" content="https://www.seusite.com/pagina-atual">
```
- Informa a URL da página que será associada ao compartilhamento.
<br>

### "og:site_name"

```html
<meta property="og:site_name" content="Nome do Site">
```
- Define o nome do site ou da marca exibido no card social.
<br>

---

## 🏷️🐦 Twitter Card (SMO)

### "twitter:card"

```html
<meta name="twitter:card" content="summary_large_image">
```
- Define o tipo de card no Twitter (neste caso, imagem grande).
<br>

### "twitter:title"

```html
<meta name="twitter:title" content="Título para Twitter">
```
- Define o título que será exibido quando a página for compartilhada no Twitter.
<br>

### "twitter:description"

```html
<meta name="twitter:description" content="Descrição curta para Twitter.">
```
- Descrição curta e atrativa que aparecerá no card do Twitter.
<br>

### "twitter:image"

```html
<meta name="twitter:image" content="https://www.seusite.com/imagens/imagem.jpg">
```
- Define a imagem de capa exibida no card do Twitter.
<br>

### "twitter:site"

```html
<meta name="twitter:site" content="@perfil_do_site">
```
- Informa o perfil oficial do site no Twitter.
<br>

### "twitter:creator"

```html
<meta name="twitter:creator" content="@perfil_do_criador">
```
- Informa o criador ou autor do conteúdo no Twitter.
<br>

---

## 💻 PWA (Progressive Web App)

### "manifest"

```html
<link rel="manifest" href="/manifest.json">
```
- Conecta o site ao arquivo `manifest.json`, permitindo que ele funcione como um app instalável (PWA).

### "theme-color"

```html
<meta name="theme-color" content="#0057FF">
```
- Define a cor da barra de navegação no navegador mobile e na interface do PWA.

### "apple-mobile-web-app-capable"

```html
<meta name="apple-mobile-web-app-capable" content="yes">
```
- Faz o site abrir em tela cheia como um aplicativo no iPhone ou iPad, sem barra de navegador.

---

## ✨ Performance

### "preconnect"

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
```
- Cria uma conexão antecipada com servidores como o Google Fonts, acelerando o carregamento de recursos externos.

### "dns-prefetch"

```html
<link rel="dns-prefetch" href="//www.google-analytics.com">
```
- Resolve antecipadamente o DNS de um servidor externo, reduzindo o tempo de carregamento.

### "preload"

```html
<link rel="preload" href="/fonts/Font-Name.woff2" as="font" type="font/woff2" crossorigin>
```
- Faz o pré-carregamento de uma fonte essencial, otimizando a performance.

---

## 🔐 Segurança

### "Content-Security-Policy"

```html
<meta http-equiv="Content-Security-Policy" content="default-src 'self'; img-src *; script-src 'self' 'unsafe-inline' https://www.googletagmanager.com; style-src 'self' 'unsafe-inline';">
```
- Define regras de segurança que controlam quais recursos podem ser carregados, protegendo contra ataques como XSS.

---

## 🔥 Favicon

```html
<link rel="icon" href="/favicon.ico" type="image/x-icon">
```
- Define o ícone que aparece na aba do navegador e nos favoritos.

---

## 🎨 Estilo (CSS)

```html
<link rel="stylesheet" href="/css/estilos.css">
```
- Conecta o arquivo CSS externo que define toda a aparência e estilos visuais da página.

---

## 🧰 Ferramentas para Testar Meta Tags

- 🔗 [Facebook Sharing Debugger](https://developers.facebook.com/tools/debug/)
- 🔗 [Twitter Card Validator](https://cards-dev.twitter.com/validator)
- 🔗 [MetaTags.io - Gerador e Visualizador](https://metatags.io/)
- 🔗 [Google Rich Results Test](https://search.google.com/test/rich-results)

---

## 📚 Referências

- 🔗 [Open Graph Protocol](https://ogp.me/)
- 🔗 [Twitter Developer - Cards](https://developer.twitter.com/en/docs/twitter-for-websites/cards/overview/abouts-cards)
- 🔗 [Google SEO Starter Guide](https://developers.google.com/search/docs/fundamentals/seo-starter-guide)
- 🔗 [MDN Web Docs - Meta Tags](https://developer.mozilla.org/pt-BR/)

---


