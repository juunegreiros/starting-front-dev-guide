# Um guia pra começar no mundo do Front End

Fiz esse guia baseado no processo que uso com o pessoal que dou mentoria e que contratei pelo Projeto Trampolim e para ser utilizado inicialmente em uma palestra no [Hack the FEG](https://www.even3.com.br/htf2021/). 

## Indice

- [Lista de Conteúdos](#lista-de-conteudos)
- [Lista de Conhecimentos Fundamentais](#lista-de-conhecimentos-fundamentais)
- [Cronograma base](#cronograma-base)

## Lista de Conteúdos

Inicialmente, tivemos uma lista de conteúdos e fomos marcando todos os que já tinham pelo menos noção do que era. Não tem problema não saber nenhum item da lista, inclusive. O mais importante aqui é se familiarizar com nomes e ter um tracking do que você está aprendendo com o passar do tempo.

Separei esses conteúdos iniciais em quatro categorias: gerais, lógica de programação, HTML e CSS. Ignorei um pouco o JavaScript no comecinho, mas vou deixar aqui a lista de JS que usamos quando começamos com ele também. 

Lembrando que essa lista é apenas um tracker, então está em ordem alfabética e não de prioridade. A ordem de prioridade que seguimos está nas próximas seções.

<details>
    <summary>Gerais</summary>

- [ ] Diferenças entre Back End e Front End
- [ ] Editor de texto
- [ ] Eslint
- [ ] Git
- [ ] Inspecionador de Elementos
- [ ] Live Server
- [ ] Npm
- [ ] Scrum
- [ ] Servidor
- [ ] Terminal

</details>

<details>
    <summary>Lógica de Programação</summary>

- [ ] Arrays
- [ ] Estrutura condicional (if/else)
- [ ] Estrutura de repetição (for, while, etc)
- [ ] Objetos
- [ ] Operação de negação
- [ ] Operações aritméticas (soma, multiplicação, etc)
- [ ] Operações condicionais (maior que, igual que, etc)
- [ ] Tipos de dados (number, string, boolean, etc)
- [ ] Variáveis

</details>

<details>
    <summary>HTML</summary>

- [ ] Acessibilidade
- [ ] Formulário
- [ ] Semântica
- [ ] SVG

</details>

<details>
    <summary>CSS</summary>

- [ ] After e Before
- [ ] Animações
- [ ] BEM - Block Element Modifier
- [ ] Box Model
- [ ] CSS Variables
- [ ] Display
- [ ] Estilização de texto
- [ ] Flexbox
- [ ] Formulário
- [ ] Grid
- [ ] Imagens
- [ ] Position
- [ ] Seletores

</details>

<details>
    <summary>JavaScript</summary>

- [ ] Array methods (map, filter, reduce)
- [ ] Async JS (promises/async/await)
- [ ] Data Attributes
- [ ] DOM
- [ ] Estruturas de dados
- [ ] Fetch API & HTTP
- [ ] Funções
- [ ] Loops
- [ ] Tipos de dados

</details>


## Lista de Conhecimentos Fundamentais

- [ ] HTML básico - semântica e tags
- [ ] Fundamentos CSS
- [ ] Posicionamentos e alinhamentos
- [ ] Design Responsivo
- [ ] SASS
- [ ] Princípios de UI
    - [ ] Cor e contraste
    - [ ] Whitespace 
    - [ ] Scale
    - [ ] Hierarquia Visual
    - [ ] Tipografia

## Cronograma base

Vou dividir esse cronograma em fases, pra ficar um pouco mais simplificado. As atividades das fases aconteciam em paralelo e, no nosso caso, como elas fazem 4 horas por dia, cada fase representa de 7 a 15 dias.

Para todos os projetos desenvolvidos:
- Tudo no github (criando uma branch separada para trabalhar e abrindo Pull Request para revisão)
- Quebrando os projetos em pequenas tarefas antes de começar e criando um card no Trello para cada tarefa. 

### Fase 1 - lógica e básico de html e css

- **Lógica de programação**: Fases do [Human Resource Machine](https://store.steampowered.com/app/375820/Human_Resource_Machine/) todos os dias.
- **HTML + CSS + noções de design**: site pessoal.
    - Layout no figma: a ideia aqui é ser algo que você goste, não precisa ficar perfeito, mas é importante ter seu nome, imagem (não necessariamente sua), um textinho e links de contato.
    - Criação do repositório com o nome da conta + github.io
    - Desenvolvimento em HTML + CSS e rodando no github pages.
    - Exemplo da [Larissa](https://github.com/lahgomes/lahgomes.github.io) e da [Karina](https://github.com/karinaramos0401/karinaramos0401.github.io)
- **Pesquisa e estudo**: estudar um conteúdo específico para explicar pra um grupo. A ideia aqui é pegar familiaridade com organização de conteúdo e pesquisa. Aqui podem entrar quaisquer outros temas, mas os temas que usamos foram:
    - Unidades de medida
    - Formulários
        - Input
        - Checkbox e radio button
        - Select
    - Image
    - Background-image
    - Seletores
    - Pseudo-seletores
    - Pseudo-elementos

### Fase 2 - básico de js, semântica, básico de css, css variables, BEM

- **Javascript**: continuar os algoritmos no Human Resource Machine e migrar os exercícios do Human Resource Machine que já tinham resolvido para JavaScript.
    - Exemplo da [Larissa](https://github.com/lahgomes/algoritmos) e da [Karina](https://github.com/karinaramos0401/algoritmo)
- **Javascript**: [30 days of code do Hacker Rank](https://www.hackerrank.com/domains/tutorials/30-days-of-code) até o dia 7 - Arrays.
- **HTML + CSS**: reprodução de layout de todo-list. Aqui poderia ser outros projetos que possuem layout e funcionalidade separados como uma calculadora.
    - Procuramos o layout no codepen ou em outros sites com modelos bonitos. Tem alguns links de referência nesse [outro repositório](https://github.com/juunegreiros/utilities).
    - Por enquanto, apenas HTML e CSS, inclusive pra marcar os itens da lista como concluídos.


### Fase 3 - mais algoritmos em js, data-attributes, manipulação de DOM
- **Javascript**: término dos exercícios do Human Resource Machine e continuação da migração dos exercícios resolvidos do Human Resource Machine para JavaScript.
- Funcionalidade do todo-list.
    - A ideia aqui é aprender mais sobre manipulação do DOM de forma geral. 
    - Exemplo da [Larissa](https://github.com/lahgomes/todo-list-JS) e da [Karina](https://github.com/karinaramos0401/todolist)

### Fase 4 - sass, manipulação de data, mais manipulação de DOM, formulários
- **Javascript**: terminar a migração dos exercícios resolvidos do Human Resource Machine para JavaScript.
- Desenvolvimento da landing page do Projeto Trampolim (que ainda não está no ar).
    - HTML + CSS
    - Countdown de data
    - Formulário de envio de e-mail

### Fase 5 - introdução ao react
Como o Trampolim usa React, priorizei o contato inicial com a ferramenta. Você pode inverter a fase 5 com a 6, já que a 5 não depende de ferramenta.

- Migrar a todo-list para React
    - Exemplo [Larissa](https://github.com/lahgomes/todo-list-react) e [Karina](https://github.com/karinaramos0401/to-do-list-react)

### Fase 6 - json-server, fetch API, manipulação de arrays
- Criação de API usando [json-server](https://github.com/typicode/json-server)
- Consumir a API na todo-list. Aqui consumimos no React, mas poderia ser no VanillaJS (js puro) também.

### Fase 7 - confiança com react + API
- Procurar uma [API pública](https://github.com/public-apis/public-apis) com um tema que goste
- Fazer um aplicativo em React (ou com outra ferramenta que quiser) baseado nessa API 
- Exemplo da [Larissa](https://github.com/lahgomes/spotify-minimalist) e da [Karina](https://github.com/karinaramos0401/catalog-anime)

### Fase 8 - leitura de código e refatoração
- Ler um código antigo (nesse caso foi esse [aqui](https://codepen.io/juunegreiros/pen/goGgKQ?editors=0010)) e refatorar
- Exemplo [Larissa](https://github.com/lahgomes/refactor_form-login-and-signup) e [Karina](https://github.com/karinaramos0401/sign-up-)

### Fase 9 - Plataforma
Desenvolvimento em projeto real.

