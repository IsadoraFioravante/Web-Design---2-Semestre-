# Aula 03 – Fundamentos do HTML

**Professor:** Me. Deivison S. Takatu (deivison.takatu@facens.br)

## 1. Papel do HTML e Avanços do HTML5
* **HTML (HyperText Markup Language):** Linguagem de marcação usada para estruturar e definir o que será exibido no navegador (textos, títulos, parágrafos, links, imagens, botões, tabelas etc.) por meio de tags/elementos, trabalhando junto ao **CSS** (aparência/estilo) e ao **JavaScript** (interatividade e manipulação dinâmica).
* **Principais avanços do HTML5:** Melhor integração com CSS e JavaScript para páginas mais leves e funcionais, padrão universal para tags e funcionalidades e introdução de **tags semânticas** no lugar de estruturas baseadas apenas em `<div>` genéricas (como `div id="header"`, `div id="sidebar"`, `div class="post"`, `div id="footer"`).

---

## 2. Estrutura Básica, Anatomia de Tags e Atributos
* **Estrutura principal do documento:**
  * `<!DOCTYPE html>`: Declara o tipo de documento como HTML5 (geralmente acompanhado de `<html lang="pt-BR">`).
  * `<html>`: Define o início e o fim do documento HTML.
  * `<head>`: Contém informações/metadados sobre o documento e a aba do navegador (ex.: `<meta charset="UTF-8">`, `<title>`, `<link>` para CSS).
  * `<body>`: Contém o corpo visível da página no navegador e onde entram os elementos exibidos ao usuário.
* **Anatomia de uma tag e atributos:**
  * Elementos costumam ter **tag de abertura** (`<p>`), **conteúdo** e **tag de fechamento** (`</p>`), mas existem elementos **sem fechamento / sem conteúdo interno** (ex.: `<img>`, `<br>` / `<br/>`).
  * **Atributos** adicionam informações extras a um elemento HTML (ex.: `href` em `<a>`, `src` e `alt` em `<img>`, `id` e `class` para identificação e estilização).
  * **Comentários em HTML5:** Escritos entre `<!--` e `-->`, podendo ocupar uma ou várias linhas para documentar o código sem aparecer na renderização normal.

---

## 3. Tags Semânticas do HTML5
* `<header>`: Representa um cabeçalho (da página, de uma seção ou de um artigo), podendo reunir títulos, logotipo e navegação.
* `<nav>`: Agrupa links de navegação principais ou seções de navegação da página.
* `<section>`: Representa uma seção temática de um documento ou aplicação, reunindo conteúdo relacionado sob um mesmo tópico.
* `<article>`: Representa um conteúdo independente e autocontido (como um post de blog ou notícia), que faz sentido mesmo fora do contexto da página.
* `<aside>`: Representa conteúdo complementar, lateral ou separado do fluxo principal (como barras laterais, notas ou links relacionados).
* `<footer>`: Define o rodapé de um documento, seção ou bloco adjacente.

---

## 4. Títulos, Formatação de Texto e Parágrafos
* **Cabeçalhos (`<h1>` a `<h6>`):** Definem títulos e subtítulos em ordem decrescente de importância/hierarquia, sendo `<h1>` o título principal/mais importante da página.
* **Parágrafos e quebras de linha:** `<p>` delimita um bloco de parágrafo com espaçamento próprio, enquanto `<br>` (ou `<br/>`) quebra a linha sem iniciar um novo parágrafo.
* **Formatação de texto e boas práticas:**
  * O material apresenta tags como `<b>` (negrito), `<i>` (itálico), `<sub>` (subscrito) e `<sup>` (sobrescrito), além de destacar que tags/atributos antigos como `<font>`, `<center>`, `<u>`, `<s>`/`<strike>` e o atributo `align` foram descontinuados/substituídos por **CSS** (como `text-decoration: underline`, `text-decoration: line-through`, `text-align` e estilos inline/classes).

---

## 5. Atividade Prática (Aula 03)
* **Objetivo:** Construir uma página HTML5 estruturada e estilizada com CSS contemplando:
  * Estrutura inicial com `<!DOCTYPE html>`, `<html lang="pt-BR">`, `<head>` (`<meta charset="utf-8">`, `<title>`) e `<body>`.
  * `<header>` com títulos `<h1>` (centralizado), `<h2>` (à esquerda), `<h3>` (à direita) e `<h4>`, `<h5>`, `<h6>`.
  * `<nav>` com links (`<a>`) separados por `|` apontando para seções/âncoras (`#posts`, `#lateral`, `#rodape`).
  * `<section id="posts">` com `<article class="post">`, `<header>`/`<h2>`, parágrafos com `<strong>`, `<em>`, sublinhado (`text-decoration: underline`), riscado (`text-decoration: line-through`), `<sub>`, `<sup>`, estilo inline e quebra de linha `<br>` com texto justificado.
  * `<div class="center">` estilizado com a classe `.center` (`text-align: center;`), `<aside id="lateral">` e `<footer id="rodape">`.
* **Entrega:** Comentar o código e enviar a documentação (com código, repositório e prints) na plataforma **Canvas**.

---
