# Aula 02 – Introdução a Web Design e Controle de Versões

**Professor:** Me. Deivison S. Takatu (deivison.takatu@facens.br)

## 1. O que é Web Design e Termos Relacionados
* **Web Design:** Arte e ciência de criar websites funcionais, acessíveis e fáceis de usar, equilibrando estética, tecnologia, psicologia e usabilidade para atender ao cliente e ao usuário final.
* **Design Visual:** Cuida da estética do site — cores, tipografia, imagens, ícones e layout — criando uma interface coesa, alinhada à identidade visual e com hierarquia clara.
* **UX (User Experience / Usabilidade):** Foca na facilidade, eficiência e clareza da navegação e do fluxo de tarefas para reduzir frustrações e melhorar a experiência geral do usuário.
* **UI (User Interface / Interface do Usuário):** Trata dos elementos visuais e interativos (botões, menus, formulários, componentes) com os quais o usuário interage de forma intuitiva e responsiva.
* **Responsividade:** Capacidade do site de se adaptar e funcionar bem em diferentes tamanhos de tela e dispositivos (desktops, tablets e smartphones).
* **Acessibilidade:** Princípio de projetar e desenvolver sites e tecnologias digitais para que todas as pessoas — incluindo aquelas com deficiências visuais, auditivas, motoras ou cognitivas — consigam perceber, entender, navegar e interagir.
* **Boas práticas visuais:** Equilíbrio, contraste, proximidade, repetição e hierarquia visual para composições harmônicas e fáceis de ler.

---

## 2. HTML, CSS e JavaScript
* **HTML (HyperText Markup Language):** Linguagem de marcação que define a estrutura e o conteúdo exibido no navegador (títulos, parágrafos, imagens, links, botões, formulários) por meio de tags/elementos.
* **CSS (Cascading Style Sheets):** Linguagem de estilo que define a aparência visual (cores, fontes, tamanhos, espaçamentos, bordas, layouts e estados como `:hover`) usando seletores e propriedades.
* **JavaScript (JS):** Linguagem de programação usada nas páginas web para adicionar interatividade, manipular elementos HTML e CSS dinamicamente, responder a eventos (como cliques) e atualizar a interface.

---

## 3. Introdução ao Versionamento e Versionamento Semântico (SemVer)
* **O que é versionamento:** Processo de atribuir identificadores únicos a versões de um software ou documento (numéricos, como `v1.0`, `v1.1`, `v2.0`, ou por data), registrando o que mudou, quem alterou e quando.
* **Problemas sem versionamento:** Arquivos duplicados sem contexto (como `versao_final_agora_sim2.zip`), conflitos quando duas pessoas editam o mesmo arquivo, perda de código e ausência de histórico para auditoria ou reversão.
* **Benefícios do versionamento:** Controle de mudanças, histórico e auditabilidade, recuperação de versões anteriores, colaboração em equipe (inclusive com *branches*), gestão da qualidade antes da entrega, melhoria contínua e integração com outras ferramentas.
* **Versionamento Semântico (`MAJOR.MINOR.PATCH`):**
  * **MAJOR:** Mudanças incompatíveis com versões anteriores (ex.: `1.0.0` → `2.0.0`).
  * **MINOR:** Novas funcionalidades compatíveis com versões anteriores (ex.: `1.0.0` → `1.1.0`).
  * **PATCH:** Correções de bugs/erros sem quebrar compatibilidade (ex.: `1.1.0` → `1.1.1`).
* **Tipos comuns de alterações no código:** *Bug Fix*, *New Feature*, *Feature Enhancement*, *Refactoring*, *Performance*, *Security Patch*, *Dependency Update* e *Adding Tests*.

---

## 4. Introdução ao Git, VS Code, Tags e Deploy
* **Git:** Sistema de controle de versão distribuído (criado por Linus Torvalds), instalado localmente e operado via linha de comando ou interfaces integradas (como o VS Code), permitindo registrar versões, restaurar estados e sincronizar com repositórios remotos como o GitHub.
* **Configuração inicial e fluxo no VS Code:**
  * Verificar instalação com `git --version` no terminal/prompt.
  * Configurar identidade global caso solicitado:
    * `git config --global user.name "<Nome>"`
    * `git config --global user.email "<Email>"`
  * Criar a pasta do projeto (ex.: `WebDesign`), abrir no VS Code, criar `index.html`, `style.css` e `script.js`, inicializar o repositório na aba *Controle de Código-Fonte*, fazer *commit* e usar *Publicar Branch* para enviar ao GitHub.
* **Tags no Git:** Marcadores usados para identificar marcos ou versões estáveis no histórico (leves/*lightweight* ou anotadas/*annotated*). Comandos vistos: `git tag`, `git tag <nome da tag>` (ex.: `git tag 1.0.0`) e `git push origin <nome da tag>`.
* **Deploy e Vercel:** *Deploy* é colocar a aplicação em produção para acesso dos usuários finais (compilação, configuração de ambiente, testes e publicação). A **Vercel** facilita hospedagem e *deploy* contínuo integrado ao GitHub/GitLab/Bitbucket, com suporte a aplicações estáticas e frameworks modernos e *rollback* rápido.

---

## 5. Atividade Prática e Revisão
* **Revisão:** Atividade de revisão indicada na plataforma Wayground.
* **Atividade em grupo (Canvas):** Instalar o VS Code, criar e salvar na mesma pasta os arquivos `index.html`, `style.css` e `script.js`, configurar o Git e publicar em um repositório no GitHub, registrar novas alterações com *commits* e *tags* de versão, documentar o processo e enviar o arquivo na plataforma **Canvas**.

---
