# Ecommerce-React
Ecommerce React

Trabalho / Projeto de uma aplicação de tela inicial de um comércio eletrônico (E-commerce), desenvolvido em React. A aplicação consome dados da API pública **Fake Store API** para renderizar, listar e filtrar dinamicamente os produtos de uma loja virtual.

Principais Recursos

* ** React:** Escolhido pela facilidade na criação de componentes e gerenciamento de estado (`useState`, `useEffect`).
* ** JavaScript:** Lógica de requisições assíncronas (`fetch`).
* ** Integração com API Externa:** Consumo dinâmico de dados (títulos, preços, imagens e categorias) através de requisições HTTP (`fetch`).

Componentização e Estrutura do Projeto

***ListaProdutos.jsx:** Componente de passagem/iteração. Ele recebe o vetor de produtos via *props* e utiliza a função `.map()` para criar a grade de exibição estruturada.

**CardProduto.jsx:** Componente especialista responsável por renderizar individualmente a estrutura visual de cada item (imagem, preço e as informações devidamente traduzidas pelas tabelas de consulta interna).

O projeto adota os conceitos de modularidade e reutilização do React. A interface foi estilizada utilizando CSS moderno focado em responsividade e experiência do usuário.


Como Rodar a Aplicação

Certifique-se de ter o [Node.js](https://nodejs.org/) instalado em seu sistema operacional antes de prosseguir.

1. Abra / navegue até o diretório correto do projeto. No seu terminal, acesse a pasta que contém o arquivo: 

cd ecommerce-react

2. Instale as dependências necessárias. Baixe os pacotes descritos no gerenciador de dependências rodando o comando:

npm install

3. Inicie o servidor de desenvolvimento. Execute o script para rodar o compilador (geralmente gerenciado pelo Vite):

npm run dev

Abra o navegador e acesse o endereço local gerado no terminal (ex: `http://localhost:5173`) para interagir com a aplicação.


# IFPE Campus Jaboatão
Curso: Análise e Desenvolvimento de Sistemas
Disciplina: Programação Web 2
Prof: Josino Rodrigues
Aluno: Amaro Souza Jr.
