# Aula 07 – CSS: Box Model e Flexbox

**Professor:** Me. Deivison S. Takatu (deivison.takatu@facens.br)

## 1. Gestão de Projetos Web, Backlog e Scrum
* **Problemas sem planejamento:** Tarefas esquecidas, requisitos confusos, retrabalho, conflitos no Git, atrasos, problemas de integração e dificuldade para acompanhar o progresso.
* **Benefícios com gestão:** Responsabilidades claras, prioridades definidas, entregas incrementais, acompanhamento do progresso e redução de retrabalho.
* **Gestão do backlog:** Reúne funcionalidades, melhorias, correções e atividades necessárias para evoluir o produto, organizando prioridades para focar primeiro no que é mais importante.
* **Scrum:** Framework ágil para desenvolver produtos complexos de forma incremental, com inspeção frequente, adaptação e entregas contínuas; ajuda a organizar requisitos, priorizar funcionalidades, planejar *Sprints* e acompanhar a equipe.

---

## 2. CSS Box Model (Modelo das Caixas)
* **O que é:** Descreve as caixas geradas pelos elementos HTML e detalha o ajuste de margens, bordas, preenchimento interno e conteúdo para cada elemento.
* **Camadas do Box Model:**
  * **Content:** Área onde o conteúdo (texto, imagens, etc.) é exibido (controlada com propriedades como `width` e `height`).
  * **Padding:** Espaçamento interno entre o conteúdo e a borda.
  * **Border:** Linha que envolve o *padding* e o conteúdo.
  * **Margin:** Espaçamento externo que separa o elemento de outros elementos ao redor.
* **Por que aplicar:** Controlar dimensões, criar espaçamento e organização visual, evitar sobreposição e problemas de dimensionamento, construir layouts mais previsíveis e facilitar a adaptação a diferentes telas.

---

## 3. Flexbox (Flexible Box Layout) e Layouts Responsivos
* **O que é:** Módulo de layout unidimensional focado em organizar itens em linhas ou colunas, distribuir espaço automaticamente, alinhar horizontal e verticalmente, adaptar ao tamanho da tela e reduzir posicionamentos manuais.
* **Principais propriedades do Flexbox:**
  * `flex-direction`: Define o eixo principal do contêiner (`row`, `column`, `row-reverse`, `column-reverse`).
  * `justify-content`: Alinha os itens ao longo do eixo principal (`flex-start`, `center`, `flex-end`, `space-between`, `space-around`, `space-evenly`).
  * `align-items`: Alinha os itens ao longo do eixo transversal (`flex-start`, `center`, `flex-end`, `stretch`, `baseline`).
  * `align-content`: Alinha as linhas do contêiner quando há múltiplas linhas (`flex-start`, `center`, `flex-end`, `stretch`, `space-between`, `space-around`).
  * `flex-wrap`: Controla se os itens quebram para nova linha (`nowrap`, `wrap`, `wrap-reverse`).
  * `gap`: Define o espaçamento entre os itens.
* **Layouts responsivos:** Técnica de adaptar o conteúdo a celulares, tablets e desktops para melhorar usabilidade e experiência do usuário, utilizando `<meta name="viewport" content="width=device-width, initial-scale=1.0">`.

---

## 4. Atividades Práticas (Aula 07)
* **Atividade 01:** Preencher o formulário com as informações do grupo e anexar o comprovante/print na atividade.
* **Atividade 02:**
  * Criar um projeto com `index.html` e `style.css` vinculado externamente via `<link>`.
  * Adicionar 20 elementos configurando valores de conteúdo (*content*), *padding*, *border* e *margin*.
  * Aplicar 20 propriedades de Flexbox para organizar os elementos de forma responsiva.
  * Integrar e publicar no GitHub via Git no VS Code, expandir o projeto para que `index.html` tenha mais de 400 linhas e `style.css` tenha mais de 300 linhas, comentar todo o código, documentar tudo (código, repositório e prints) e enviar na plataforma **Canvas**.

---
