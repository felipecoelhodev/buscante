# Buscante 

Desenvolvido com React, o Buscante vai além de uma interface de busca: é um estudo aprofundado sobre padrões de otimização para aplicações web de alto desempenho. O projeto destaca-se pela aplicação de estratégias modernas de paralelismo, controle de fluxo e normalização de dados, garantindo uma experiência fluida mesmo ao lidar com múltiplas fontes de dados(endpoints) e estados assíncronos complexos. A plataforma permite buscar livros de forma abrangente, visualizar detalhes técnicos e gerenciar uma lista personalizada de favoritos.

## Funcionalidades

- **Busca Global**: Pesquisa de livros por título, autor ou assunto através da integração com a Google Books API.
- **Gestão de Favoritos**: Sistema para adicionar ou remover livros de uma lista de desejos persistente.
- **Detalhes Completos**: Visualização de informações como autor, editora, data de publicação, número de páginas e categorias.
- **Interface Responsiva**: Design otimizado para desktop, tablets e dispositivos móveis utilizando Tailwind CSS.
- **Pré-visualização**: Links diretos para visualizar amostras dos livros quando disponíveis.

## Tecnologias Utilizadas

- **Frontend**: [React](https://reactjs.org/) com [TypeScript](https://www.typescriptlang.org/).
- **Estilização**: [Tailwind CSS](https://tailwindcss.com/) para um design moderno e utilitário.
- **Gerenciamento de Estado**: Context API e `useReducer` para busca e favoritos.
- **Roteamento**: [React Router DOM](https://reactrouter.com/).
- **Ícones**: SVG personalizados e paleta de cores curada.

## Como Executar o Projeto

1. Clone o Projeto e Instale as dependências:
```bash
npm install
```

2. Inicie o servidor de desenvolvimento(abra um terminal para o server e o outro para rodar o projeto e use os seguintes comandos um para cada terminal):
```bash
npm run start
```
```bash
npm run dev
```
