# Escopo e objetivo

_Projeto usado na disciplina de Engenharia de Software_.

_Projeto com objetivo de desenvolver uma aplicação em forma de jogo que sirva para melhorar o reflexo do usuário_. O jogo consiste em clicar o mais rápido possível em círculos que aparecem na tela e gradativamente são diminuidos até desaparecerem.

O aplicativo será desenvolvido nas ferramentas React, Node.js, Typescript, Express.js e, para o banco de dados, MongoDB.

O usuário terá a opção de:

- Criar seu cadastro
- Acessar seus melhores resultados
- Diminuir ou aumentar a dificuldade
- Comparar seus melhores resultados com o de outros usuários

Entre outras funcionalidades

## Autores

[![image](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white) João Victor Taufner Pereira - Fullstack](https://github.com/jvtaufner)

[![image](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white) Stephanie Costa de Avelar - Fullstack](https://github.com/stephanie-cavelar)

## Instalação

Primeiro, clone o repositório

`git clone https://github.com/jvtaufner/reflex-improver.git`

Depois, instale o projeto. Para esse passo, é necessário ter o Node.js instalado.

```bash
  cd reflex-improver
  npm install
```

## Backlog do Produto

1 - Como um usuário, eu quero me cadastrar no aplicativo

2 - Como um usuário, gostaria de treinar meu reflexo.

3 - Como um usuário, quero poder diminuir ou aumentar a velocidade do jogo.

4 - Como um usuário, gostaria de ver meus resultados.

5 - Como um usuário, seria interessante poder ver como outros usuários performam.

6 - Como um usuário, gostaria de ser incentivado quando performo bem no jogo.

7 - Como um usuário, gostaria de ter fácil acesso aos meus melhores resultados.

8 - Como um usuário, gostaria de ver minha evolução ao longo do tempo.

9 - Como um usuário, quero poder mudar as cores do jogo.

10 - Como um usuário, gostaria de poder escolher o tempo de duração do jogo.

11 - Como um usuário, quero poder diminuir o tamanho dos objetos clicáveis para aumentar a dificuldade.

12 - Como um usuário, gostaria de dar feedback aos desenvolvedores, propondo melhorias.

## Backlog do Sprint

* __História 1:__ Como um usuário, eu quero me cadastrar no aplicativo
* __Tarefas e Responsáveis:__
    - Instalar Node, Express e MongoDB [João]
    - Criar modelo de usuário no banco de dados [João]
    - Criar rota para criar usuário na API do Back End [Stephanie]
    - Criar formulário de cadastro no Front End [Stephanie]

* __História 2:__ Como um usuário, quero poder diminuir ou aumentar a velocidade do jogo
* __Tarefas e Responsáveis:__
    - Criar um slider na interface do jogo [João]
    - Criar uma função para atualizar o estado do jogo [João]

* __História 3:__ Como um usuário, gostaria de ver meus resultados
* __Tarefas e Responsáveis:__
    - Ao fim de cada jogo, inserir o resultado no banco de dados[Stephanie]
    - Criar um modelo de resultados no banco de dados[Stephanie]
    - Criar uma rota para pegar os resultados dado o ID de um usuário[João]
    - Criar uma tela que mostre os resultados do usuário[João]

* __História 4:__ Como um usuário, gostaria de ser incentivado quando performo bem no jogo
* __Tarefas e Responsáveis:__
    - Definir um sistema de multiplicador de pontos para acertos consecutivos[João]
    - Mostrar na tela o multiplicador atual[João]

* __História 5:__ Como um usuário, gostaria de ver minha evolução ao longo do tempo.
* __Tarefas e Responsáveis:__
    - Fazer uma requisição na rota para pegar o resultado de todos os jogos de um usuário[Stephanie]
    - Criar uma tela que mostre estes resultados em forma de gráfico ao longo do tempo[Stephanie]






