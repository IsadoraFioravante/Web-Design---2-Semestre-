# Aula 04 – Mídias em HTML

**Professor:** Me. Deivison S. Takatu (deivison.takatu@facens.br)

## 1. Base HTML5 e Separação de Responsabilidades
* **HTML, CSS e JavaScript:** O **HTML** fornece a estrutura e o conteúdo da página, o **CSS** define a aparência visual (cores, fontes, tamanhos e layouts) e o **JavaScript** adiciona interatividade e manipulação dinâmica.
* **Avanços do HTML5:** Melhor integração com CSS e JavaScript, padrão universal para tags e funcionalidades e uso de tags semânticas (como `<header>`, `<main>` e `<footer>`) em vez de estruturar tudo apenas com `<div>`.

---

## 2. Imagens, Vídeo e Áudio
* **Imagens (`<img>`):**
  * Elemento sem conteúdo interno/fechamento próprio (`<img src="..." alt="..."/>`), onde `src` e `alt` são obrigatórios.
  * `src` indica o caminho/arquivo da imagem (incluindo extensão) e `alt` fornece o texto alternativo descritivo.
  * `width` (largura) e `height` (altura) em pixels ajustam as dimensões: sem definir nenhum dos dois, mantém o tamanho original; definindo apenas um, o outro ajusta-se proporcionalmente.
* **Vídeo (`<video>`):**
  * Permite incorporar vídeos diretamente na página sem *plugins* externos nos navegadores modernos.
  * Atributos abordados: `src` (caminho do ficheiro, ex.: `video.mp4`), `controls` (exibe controlos de reprodução como *play*, *pause*, volume e barra de progresso), `width` e `poster` (imagem de capa antes da reprodução).
* **Áudio (`<audio>`):**
  * Permite reproduzir áudio diretamente no navegador sem *plugins* externos.
  * Pode usar `src` diretamente ou múltiplas tags `<source>` (ex.: `.mp3` e `.ogg`) dentro de `<audio controls>`, além de um texto de fallback caso o navegador não suporte áudio.

---

## 3. Formulários, Links, Listas e Tabelas
* **Formulários (`<form>`):**
  * Coletam dados do utilizador (como nome, e-mail, mensagens ou preferências) para envio ao servidor ou processamento com JavaScript.
  * Elementos vistos: `action`, `method`, `<label for="...">`, `<input type="text">`, `<input type="email">`, `<textarea>` e `<input type="submit">`.
* **Links (`<a>`):**
  * Criam ligações para outras páginas, ficheiros, e-mails ou secções da própria página por meio do atributo `href`.
  * Podem envolver texto, imagens (`<img>`), títulos ou abrir numa nova aba com `target="_blank"`.
* **Listas (`<ol>`, `<ul>`, `<li>`):**
  * Organizam conjuntos de itens: `<ol>` cria listas ordenadas (sequenciais) e `<ul>` cria listas não ordenadas, ambas contendo elementos `<li>`.
* **Tabelas (`<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`):**
  * Estruturam dados em linhas (`<tr>`) e colunas dentro de `<table>` (com `<thead>` para cabeçalhos com `<th>` e `<tbody>` para dados com `<td>`, além do atributo `border` quando usado).

---

## 4. Identificadores (`id`), Classes (`class`) e Contêiner `<div>`
* **Atributo `id`:** Identifica um elemento de forma única na página (deve aparecer apenas uma vez por documento).
* **Atributo `class`:** Agrupa vários elementos que compartilham a mesma classificação ou estilo (ex.: `.destaque` no CSS).
* **Contêiner genérico (`<div>`):** Agrupa outros elementos HTML sem significado semântico próprio, útil para organização estrutural e aplicação de estilos com classes/CSS.

---

## 5. Atividade Prática (Aula 04)
* **Objetivo:** Criar um `index.html` com estrutura HTML5 (`<head>`, `<body>`, `<header>`, `<main>`, `<footer>`) e incluir:
  * Três imagens com `<img>` (`src`, `alt`, `width`, `height` e teste sem dimensões fixas).
  * Um vídeo com `<video>` (`controls`, `width`, `poster` e teste sem `controls`).
  * Um áudio com `<audio controls>`, duas fontes (`.mp3` e `.ogg`) e mensagem alternativa.
  * Um formulário com nome obrigatório, e-mail obrigatório, `<textarea>` e botão de envio.
  * Três tipos de links (`<a>`): link simples, imagem clicável e abertura em nova aba (`target="_blank"`).
  * Lista ordenada (`<ol>`) com 3 passos e lista não ordenada (`<ul>`) com 3 itens.
  * Tabela com 3 colunas e 3 linhas usando `<thead>`/`<th>` e `<tbody>`/`<td>`.
  * Elementos com `id="introducao"`, `class="destaque"` (estilizados no CSS com fundo amarelo claro) e uma `<div>` agrupando `<h3>` e dois `<p>` com classe/estilo próprio.
* **Entrega:** Comentar o código, documentar tudo (código, repositório e capturas de ecrã) e enviar na plataforma **Canvas**.

---
