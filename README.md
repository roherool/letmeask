# NLW - LETMEASK

Projeto desenvolvido com **React.JS**

## Aula 01 - Liftoff

- [x] **0:00:00** - Início
- [x] **0:52:52** - Criando o projeto **`yarn create react-app letmeask --template typescript`**
- [x] **1:11:00** - Entendendo o **ReactDOM** e como a renderização funciona
- [x] **1:15:00** - **Component** no react, para entender melhor, tudo é componente dentro do react.
- [x] **1:17:32** - **Propriedade**, são informações passadas para o componente
- [x] **1:27:00** - **Estado** Entendendo o conceito no react de **state**, é como uma informação é mantida dentro de um componente, sempre que o valor de uma informação é alterado, o estado do componente é alterado. Esse conceito de **estado** dentro do react é o conceito mais importante que deve ser aprendido. Esse conceito vem do paradigma da programação funcional, conhecido como **imutabilidade**, o valor de um componente é imutável, nunca se altera o valor do componente em si, e sim cria-se um novo componente, setando um novo valor, a partir do valor do componente anterior.
- [x] **1:37:10** Integrando o projeto ao **Firebase** **`https://console.firebase.google.com/`**
- Instalando o package do Firebase **`yarn add firebase`**
- [x] Código da aula: **`#together`**

## Aula 02 - Maximum Speed

- [x] **0:00:00** - Início
- [x] **0:11:00** - Criando a pasta **_pages_**
- [x] **0:11:30** - Criando a página da Home e a sua estrutura HTML
- [x] **0:20:07** - Criando o estilo da Home e instalando o **SASS** **`yarn add sass`**
- [x] **0:42:50** - Criando a tela de criação de salas
- [x] **0:46:00** - Criando o recurso de navegação, através de roteamento **`yarn add react-router-dom`** e **`yarn add @types/react-router-dom -D`**
- [x] **0:51:50** - Criando a autenticação com o Firebase
- [x] **0:57:00** - Criando e entendendo o conceito de **Context API**, que são formas de compartilhar informações entre dois ou mais componentes dentro da nossa aplicação.
- [x] **1:18:20** - Recuperar o estado de autenticação utilizando o hook: **useEffect**
- [x] **1:24:00** - Refaturando o hook: **useEffect**, separando o Context
- [x] Código da aula: **`#unidade`**

## Aula 03 - In Orbit

- [x] **0:00:00** - Início
- [x] **0:09:00** - Criando a persistência de dados com o **Realtime Database** do Firebase
- [x] **0:12:00** - Criando o recurso de salas no aplicativo
- [x] **0:29:13** - Criando o fluxo de entrar na sala
- [x] **0:33:00** - Criando as regras de autenticação e autorização do Firebase
- [x] **0:44:00** - Criando a página da sala
- [x] **1:01:00** - Criando o recurso de novas perguntas
- [x] **1:09:00** - Melhorando o fluxo das perguntas
- [x] **1:14:00** - Criando o estado do component room
- [x] **1:30:00** - Ouvindo novas perguntas da sala
- [x] Código da aula: **`#embuscadeevolução`**

## Aula 04 - Landing

- [x] **0:00:00** - Início
- [x] **0:08:25** - Criando a estrutura das perguntas em HTML
- [x] **0:22:00** - Criando a funcionalidade das perguntas e o hook useRoom
- [x] **0:27:20** - Criando a página AdminRoom, do administrador da sala
- [x] **0:35:00** - Criando a funcionalidade de likes na sala
