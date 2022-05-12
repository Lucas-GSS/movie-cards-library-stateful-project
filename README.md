# Boas vindas ao repositório do projeto de Movie Cards Library Stateful!

Projeto desenvolvido em React no módulo de Front-End

# Habilidades

Nesse projeto, você será capaz de:
  - Ler o estado de um componente e usá-lo para alterar o que exibimos no browser
  - Inicializar um componente, dando a ele um estado pré-definido
  - Atualizar o estado de um componente
  - Capturar eventos utilizando a sintaxe do React
  - Criar formulários utilizando sintaxe JSX com as tags : `input`, `textarea`, `select`, `form`
  - Transmitir informações de componentes filhos para componentes pais via callbacks

## O que deverá ser desenvolvido

Você deverá desenvolver uma aplicação que consiste em uma biblioteca de cartões de filmes dinâmica utilizando React. A biblioteca é composta por:

* Um cabeçalho;

* Uma barra de busca, utilizada pra filtrar quais cartões serão exibidos na lista de cartões;

* Uma lista de cartões, onde cada cartão representa um filme e possui uma imagem, título, subtítulo, sinopse e avaliação;

* Um formulário para adicionar um novo cartão na biblioteca.

Uma possível implementação dessa biblioteca consta abaixo.

![image](preview.gif)

Você precisará implementar componentes que em conjunto resultarão na biblioteca de cartões de filmes dinâmica.

## Desenvolvimento

Desenvolva uma aplicação **React** que seja composta por um `conjunto de componentes` React e
controlada por estados.

## Componentes

Esse projeto contém os seguintes `React Components`:

   - Header
   - MovieLibrary
   - SearchBar
   - MovieList
   - MovieCard
   - Rating
   - AddMovie

`<Header />`, `<MovieList />`, `<MovieCard />` e `<Rating />` **já estão implementados com os testes passando**. `<MovieLibrary />`, `<SearchBar />` e `<AddMovie />` já estão criados, mas precisam ser implementados de forma a passarem nos requisitos listados abaixo. 

# Requisitos do projeto

### 1 - Crie um componente chamado `<SearchBar />`

Esse componente renderizará uma barra com filtros acima da listagem de cartões. Quais cartões serão mostrados no componente `<MovieList />` dependerá dos filtros escolhidos. 

### 2 - Renderize um formulário dentro de `<SearchBar />`

Dentro desse formulário haverá campos usados na filtragem de cartões.

### 3 - Renderize um input do tipo texto dentro do formulário em `<SearchBar />`

### 4 - Renderize um input do tipo checkbox dentro do formulário em `<SearchBar />`

### 5 - Renderize um select dentro do formulário em `<SearchBar />`

### 6 - Crie um componente chamado `<AddMovie />`

Esse componente renderizará um formulário que permite adicionar na biblioteca um novo cartão de filme, dadas as seguintes informações do novo filme:

  - subtítulo
  - título
  - caminho da imagem
  - sinopse
  - avaliação
  - gênero

### 7 - Renderize um formulário dentro de `<AddMovie />`

Dentro desse formulário haverá campos usados para preencher informações do novo cartão a ser adicionado na biblioteca.

### 8 - Renderize um input do tipo texto dentro do formulário em `<AddMovie />` para obter o título do novo filme

### 9 - Renderize um input do tipo texto dentro do formulário em `<AddMovie />` para obter o subtítulo do novo filme

### 10 - Renderize um input do tipo texto dentro do formulário em `<AddMovie />` para obter o caminho da imagem do novo filme

### 11 - Renderize uma `textarea` dentro do formulário em `<AddMovie />` para obter a sinopse do novo filme

### 12 - Renderize um `input` do tipo `number` dentro do formulário em `<AddMovie />` para obter a avaliação do novo filme

### 13 - Renderize um `select` do formulário em `<AddMovie />` para selecionar o gênero do novo filme

### 14 - Renderize um botão do formulário em `<AddMovie />` para fazer uso dos dados do novo filme, contidos no estado de `<AddMovie />`

### 15 - Crie um componente chamado `<MovieLibrary />`

Esse componente renderizará a biblioteca de filmes que renderizará a `searchBar` e o `addMovies` para filtrar por filmes e adicionar um filme à biblioteca respectivamente.

### 16 - Configure o estado inicial do componente `MovieLibray`

### 17 - Renderize `<SearchBar />` dentro de `<MovieLibrary />`

### 18 - Renderize `<MovieList />` dentro de `<MovieLibrary />`

### 19 - Renderize `<AddMovie />` dentro de `<MovieLibrary />`

### 20 - Adicione proptypes a todos os componentes
