# Aula 08 – JS: Sintaxe, Variáveis e Estruturas

**Professor:** Me. Deivison S. Takatu (deivison.takatu@facens.br)

## 1. Aviso sobre a AC2 e Introdução ao JavaScript
* **Apresentações da AC2:** Organizadas em mais de um dia a partir dos grupos formados na disciplina, com limite máximo de quatro apresentações por dia e aviso com a maior antecedência possível caso seja necessária alteração após o sorteio das datas.
* **O que é JavaScript:** Linguagem de programação executada principalmente no lado do cliente (*client side*), diretamente no navegador, permitindo validação de formulários, alteração de estilos, inserção dinâmica de conteúdo, comunicação com servidores, manipulação do DOM e interatividade.
* **Formas de incluir JavaScript no HTML:**
  * Diretamente no corpo/documento com a tag `<script>`.
  * Em arquivo externo vinculado com `<script src="script.js"></script>` (recomendado para organização e manutenção em projetos maiores).
  * Em atributos de eventos no HTML, como `onclick` e `onblur`.

---

## 2. Variáveis, Tipos de Dados e Operadores
* **Variáveis e sensibilidade a maiúsculas:** Não exigem declaração apenas no início do script e são *case sensitive* (`nome`, `Nome` e `NOME` são identificadores diferentes).
  * `var`: Escopo de função (ou global fora de funções).
  * `let`: Escopo de bloco `{ }`, mais restrito e previsível.
  * `const`: Define constantes.
* **Tipos de dados e `typeof`:** O JavaScript identifica automaticamente os tipos de valores, incluindo *String*, *Number*, *Boolean*, *Undefined*, *Null*, *Object*, *Array*, *Symbol* e *BigInt*, podendo ser inspecionados com `typeof`.
* **Operadores:**
  * **Aritméticos:** `+`, `-`, `*`, `/`, `%` (resto), `**` (exponenciação), `++` (incremento) e `--` (decremento).
  * **Comparação:** `==` (igualdade com conversão de tipo), `===` (igualdade estrita: valor e tipo), `!=`, `!==`, `>`, `<`, `>=` e `<=`.
  * **Atribuição:** `=`, `+=`, `-=`, `*=`, `/=` e `%=`.
  * **Lógicos:** `&&` (E), `||` (OU) e `!` (NÃO).

---

## 3. Estruturas de Controle, Repetição, Funções, Arrays e Objetos
* **Condicionais:** Avaliam expressões booleanas para desviar o fluxo com `if`, `else if` e `else` (além de operador ternário `condicao ? valorSeVerdadeiro : valorSeFalso`).
* **Estruturas de repetição:** Executam blocos repetidamente com `for`, `while` e `do...while`, podendo interromper o laço com `break` ou avançar para a próxima iteração com `continue`.
* **Funções:** Blocos reutilizáveis que recebem parâmetros e podem retornar valores com `return`, declarados de forma tradicional (`function nome() {}`) ou como *arrow functions* (`const nome = () => {}`). Funções e métodos frequentes incluem `console.log()`, `alert()`, `prompt()`, `confirm()`, seletores/eventos do DOM e `.innerHTML` / `.textContent`.
* **Arrays:** Estruturas sequenciais indexadas que armazenam múltiplos valores em uma variável (com propriedades e métodos como `.length`, `.forEach()` e `.filter()`).
* **Objetos:** Estruturas que agrupam dados em propriedades e comportamentos em métodos, usando `this` dentro de métodos para referenciar o próprio objeto.

---

## 4. DOM e Exemplos Práticos
* **DOM (Document Object Model):** Representação em árvore da estrutura da página que o JavaScript manipula dinamicamente; o material também menciona o *Virtual DOM* (usado no React), que atualiza uma cópia, compara com o DOM real e aplica apenas as diferenças.
* **Seleção e alteração do DOM:**
  * Seleção: `getElementById()`, `querySelector()` e `querySelectorAll()`.
  * Manipulação: `.textContent`, `.value`, `.classList`, `createElement()`, `appendChild()` e `.addEventListener()`.
* **Exemplos vistos:** Alternância de *dark mode* (`.classList.toggle('dark')`), botão voltar ao topo com rolagem suave, efeito de digitação (*typewriter*) com `setTimeout` e abertura/fechamento de *modal* (*pop-up*).

---

## 5. Atividade Prática e Revisão (Aula 08)
* **Revisão:** Atividade na plataforma Wayground e material de apoio no repositório de exemplo da aula.
* **Atividade prática:**
  * Criar um projeto com `index.html`, `style.css` e `script.js` (vinculado via `<script src>`), implementando pelo menos 5 funcionalidades em JavaScript a partir dos exemplos da aula.
  * Criar um arquivo `Readme.md` no projeto com pelo menos 100 linhas descrevendo as funcionalidades implementadas.
  * Integrar e publicar no GitHub via Git no VS Code, expandindo o projeto para que `index.html` tenha mais de 500 linhas, `style.css` tenha mais de 400 linhas e `script.js` tenha mais de 300 linhas.
  * Comentar todo o código explicando o que cada parte faz, documentar tudo (código, repositório e capturas de ecrã) e enviar na plataforma **Canvas**.

---
