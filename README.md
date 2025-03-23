# 🍳 Site de Receitas

Este projeto é um **site de receitas**, onde o usuário pode digitar um ingrediente e obter uma lista de receitas que utilizam esse ingrediente. A aplicação utiliza a **API de receitas** para buscar dados em tempo real e exibir as receitas de forma clara e organizada.

## 🚀 Tecnologias Usadas

- **HTML**
- **CSS**
- **JavaScript**
- **API de Receitas:** TheMealDB

![HTML Badge](https://img.shields.io/badge/HTML-5-orange)
![CSS Badge](https://img.shields.io/badge/CSS-3-blue)
![JavaScript Badge](https://img.shields.io/badge/JavaScript-ES6-yellowgreen)

## 💡 Objetivo

O objetivo deste projeto foi criar uma aplicação simples e funcional para:

- Praticar manipulação de dados usando **JavaScript**.
- Consumir uma **API externa** TheMealDB, para buscar receitas com base em ingredientes.
- Desenvolver um layout limpo e responsivo para exibir as receitas de forma clara e organizada.

## 🛠 Funcionalidades

- **Busca por ingrediente**: O usuário pode digitar um ingrediente para obter uma lista de receitas que utilizam esse ingrediente.
- **Exibe receitas**: Nome da receita, imagem e uma breve descrição.
- **Detalhes da receita**: Ao clicar em uma receita, o usuário pode ver os ingredientes, instruções de preparo e outras informações detalhadas.
- **Design responsivo**: A interface se adapta a diferentes tamanhos de tela (desktop e mobile).

## 📜 Lógica do JavaScript

A lógica do JavaScript foi desenvolvida seguindo os seguintes passos:

1. **Pegar a informação do Input, quando o botão for clicado**:
   - Capturar o valor digitado pelo usuário no campo de busca.
   - Disparar a busca quando o botão de pesquisa for clicado.

2. **Ir até a API, e trazer as receitas**:
   - Fazer uma requisição à API TheMealDB para buscar receitas que contenham o ingrediente digitado.

3. **Colocar as receitas na Tela**:
   - Exibir as receitas retornadas pela API em cards, com nome, imagem e uma breve descrição.

4. **Saber quando o usuário clicou na receita**:
   - Adicionar um evento de clique em cada card de receita para capturar qual receita foi selecionada.

5. **Buscar informações da receita individual na API**:
   - Fazer uma nova requisição à API para buscar os detalhes da receita selecionada.

6. **Colocar a receita individual na tela**:
   - Exibir os detalhes da receita, como ingredientes, instruções de preparo e uma imagem maior.

## 📜 Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.

## 🎥 Créditos

Este projeto foi desenvolvido por Laura Trigo com base no vídeo [Aplicativo De Receitas Com VSCODE, HTML, CSS e Javascript](https://www.youtube.com/watch?v=r6L0UW1YZ2w).
