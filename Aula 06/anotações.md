# Aula 06 – CSS: Seletores, Cores, Tipografia e Layouts Básicos

**Professor:** Me. Deivison S. Takatu (deivison.takatu@facens.br)

## 1. Regras de Negócio do Projeto, Benchmarking e Prototipação
* **Regras de negócio do projeto:**
  * Ter pelo menos 5 páginas diferentes interligadas por links e incluir um menu interativo.
  * Utilizar pelo menos 20 mídias (imagens, vídeos, áudios, etc.) e implementar pelo menos 10 funcionalidades.
  * Ter pelo menos 30 estilizações diferentes e garantir responsividade em desktop, tablet e celular.
  * Manter pelo menos 30 commits no GitHub, incluir um `README.md` explicando o projeto e realizar o *deploy*.
* **Benchmarking da aplicação:** Análise de aplicações e soluções existentes para conhecer referências do mercado, identificar padrões de interface e UX, comparar recursos, encontrar boas práticas e evitar problemas já conhecidos.
* **Prototipação e ferramentas:** Criação de interfaces visuais antes da codificação para visualizar a solução, validar com usuários/clientes, antecipar falhas de usabilidade, iterar rapidamente e facilitar a conversão para código. Entre as abordagens e ferramentas citadas estão prototipação a partir de imagens ou *prompts*, plugins no Figma (como `html.to.design` e `Musho.ai`), Uizard e ferramentas com IA como o Stitch.

---

## 2. Cascading Style Sheets (CSS) e Formas de Aplicação
* **Estrutura de uma regra CSS:** Segue o formato `seletor { propriedade: valor; }`, em que o seletor indica o alvo HTML, a propriedade define o aspecto a alterar e o valor estabelece a configuração desejada (substituindo atributos antigos equivalentes do HTML, como `bgcolor`, por soluções mais flexíveis e padronizadas).
* **CSS In-line:** Aplicado diretamente no elemento HTML via atributo `style="..."`; indicado apenas para testes ou ajustes pontuais.
* **CSS Interno:** Definido dentro da tag `<style>` no cabeçalho do documento HTML; útil quando o estilo se aplica apenas a uma página específica ou para testes rápidos.
* **CSS Externo:** Escrito em arquivo separado `.css` e vinculado ao HTML com `<link rel="stylesheet" href="...">`; abordagem mais recomendada para manter, reutilizar e padronizar estilos em várias páginas.

---

## 3. Propriedades CSS, Classes (`class`) e Identificadores (`id`)
* **Cores e tipografia:**
  * `color`: define a cor do texto (nomes de cores, hexadecimal como `#ff0000`, etc.).
  * `background-color`: define a cor de fundo do elemento.
  * `font-family`: define a família tipográfica (ex.: `Arial, sans-serif` ou `'Courier New', monospace`).
  * `font-size`: controla o tamanho da fonte em unidades como `px`, `em`, `rem` ou `%`.
* **Espaçamento, dimensões e layout básico:**
  * `margin`: margem externa ao redor da borda do elemento (valor único, vertical/horizontal ou `top right bottom left`).
  * `padding`: preenchimento interno entre a borda do elemento e o seu conteúdo.
  * `border`: define espessura, estilo e cor da borda (ex.: `2px solid black`).
  * `width` e `height`: controlam largura e altura do elemento.
  * `display`: define o comportamento de exibição (ex.: `block`, `inline`, `flex`).
  * `position` com `top`, `right`, `bottom` e `left`: controla o posicionamento (ex.: `relative`, `absolute`, `fixed`) e o deslocamento associado.
  * `text-align`: controla o alinhamento horizontal do texto (ex.: `center`, `justify`).
* **Seletores de classe e ID:**
  * **Classes (`.classe`):** Reutilizáveis em vários elementos para compartilhar o mesmo estilo e facilitar a manutenção.
  * **IDs (`#id`):** Destinados a elementos únicos da página, úteis para estilização específica, navegação por âncora e manipulação via JavaScript.

---

## 4. Atividade Prática e Revisão (Aula 06)
* **Revisão:** Atividade na plataforma Wayground e material de apoio disponível no repositório de exemplo da aula.
* **Atividade prática:**
  * Criar um projeto com `index.html` e `style.css` vinculado externamente via `<link>`.
  * Aplicar as propriedades CSS vistas em aula de forma clara no layout e adicionar pelo menos 10 propriedades CSS extras para melhorar design, interatividade e responsividade.
  * Versionar e publicar no GitHub via Git no VS Code, expandindo o projeto para que `index.html` tenha mais de 300 linhas e `style.css` tenha mais de 200 linhas.
  * Comentar todo o código explicando cada parte, documentar tudo (código, repositório e capturas de ecrã) e enviar na plataforma **Canvas**.

---
