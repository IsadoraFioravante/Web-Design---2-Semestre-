# Aula 05 – SEO com HTML

**Professor:** Me. Deivison S. Takatu (deivison.takatu@facens.br)

## 1. O que é SEO e Busca Orgânica vs. Links Patrocinados
* **SEO (Search Engine Optimization):** Conjunto de técnicas e estratégias aplicadas para melhorar o posicionamento orgânico de um site nos mecanismos de busca (como o Google), aumentando a visibilidade e o alcance sem depender exclusivamente de anúncios pagos.
* **Caminhos para a otimização:** Analisar o comportamento e os termos buscados pelos usuários, planejar conteúdos relevantes e claros e otimizar a performance, a organização e a segmentação do site.
* **SEO vs. Links Patrocinados:** Links patrocinados trazem destaque rápido, mas têm custo mais elevado e funcionam apenas durante o período da campanha ativa; o SEO constrói resultados orgânicos e sustentáveis a longo prazo.

---

## 2. Arquitetura do Site, Crawling, Indexação e PageRank
* **Crawling (Rastreamento):** Processo pelo qual robôs dos buscadores percorrem a web para descobrir novas páginas ou atualizações. Pode ser apoiado por um *sitemap*, priorizando a página inicial bem conectada às demais e evitando a indexação de páginas internas de busca.
* **Indexação:** Etapa após o rastreamento em que o buscador analisa e cataloga textos, imagens, vídeos, palavras-chave, títulos e tags para classificar as páginas por tema.
* **Fatores que influenciam o posicionamento:** Arquitetura do site, autoridade da página e do domínio, certificados SSL e HTTPS, conteúdo único e de qualidade, palavras-chave no título, responsividade, TrustRank, URLs amigáveis e velocidade de carregamento.
* **PageRank:** Métrica em escala de 0 a 10 baseada na quantidade e qualidade dos links que apontam para uma página; embora tenha dado lugar a métricas como autoridade de domínio e de página, links de qualidade continuam relevantes para o ranqueamento.

---

## 3. Práticas de SEO em HTML e Acessibilidade
* **Cabeçalho (`<head>`):**
  * Usar `<meta charset="utf-8">` e `<meta name="viewport" content="width=device-width, initial-scale=1">` para correta codificação e adaptação mobile.
  * Definir `<title>` único (cerca de até 60 caracteres) e `<meta name="description" content="...">` clara (até cerca de 155 caracteres).
  * Usar `<link rel="canonical" href="...">` para evitar problemas de conteúdo duplicado, além de *favicon*, *manifest* e `hreflang` quando houver versões por idioma/região.
  * Controlar indexação quando necessário com `<meta name="robots" content="noindex, nofollow">`.
* **Idioma, semântica e headings:**
  * Definir o idioma do documento com `<html lang="pt-BR">`.
  * Estruturar com tags semânticas (`<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<aside>`, `<footer>`).
  * Usar uma hierarquia lógica de cabeçalhos (`<h1>` a `<h6>`), mantendo geralmente apenas um `<h1>` por página e ajustando a aparência visual com CSS em vez de pular níveis apenas por estética.
* **Links, navegação e breadcrumbs:**
  * Escrever textos de link descritivos (evitando termos genéricos como "clique aqui"), fortalecer conexões com links internos e utilizar *breadcrumbs* (`<nav aria-label="Breadcrumb">` com `<ol>`) para indicar a hierarquia.
* **Imagens e mídia:**
  * Preencher `alt` descritivo (sem exagero de palavras-chave) e informar `width` e `height` para evitar saltos de layout durante o carregamento, além de recursos como carregamento diferido (*lazy loading*) quando aplicável.
* **Dados estruturados (JSON-LD):**
  * Incluir marcações em `<script type="application/ld+json">` (ex.: Schema.org para `Article`, `FAQ`, `Product`) para fornecer contexto aos buscadores e favorecer *rich results* e maior CTR.
* **Acessibilidade e SEO:**
  * Rótulos claros (`<label>`, `aria-label`), bom contraste de cores e foco visível para navegação por teclado (`:focus`) beneficiam usuários e mecanismos de busca.

---

## 4. Atividade Prática (Aula 05)
* **Página HTML:** Criar uma página web em HTML com no mínimo 200 linhas de código, tema livre (podendo partir de atividades anteriores), incorporando melhorias de interface, design, mídias e recursos vistos anteriormente.
* **Verificação e documentação:** Avaliar a página otimizada em uma ferramenta de PageRank, comentar todo o código explicando o funcionamento e as técnicas de SEO aplicadas, documentar em arquivo e enviar na plataforma **Canvas**.

---
