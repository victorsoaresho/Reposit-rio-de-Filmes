# Gerenciador de Filmes

Este projeto é uma aplicação Java desenvolvida com o objetivo de estudar a arquitetura **MVC (Model-View-Controller)**. Ele gerencia filmes, atores e diretores, permitindo a adição, listagem e manipulação de dados relacionados aos filmes.

## Estrutura do Projeto

- **App.java**: Arquivo principal onde a aplicação é iniciada.
- **Controllers**: Contém as classes controladoras responsáveis por lidar com a lógica de negócios, como `FilmeController`.
- **Entities**: Modelos de dados que representam entidades do sistema como `Ator`, `Diretor` e `Filme`.
- **Repositories**: Classes responsáveis por acessar e gerenciar dados (similar a um DAO - Data Access Object).
- **Services**: Contém a lógica de negócios para manipular as entidades, como a classe `FilmeService`.
- **UI**: Interface de usuário do sistema, lidando com a interação com o usuário.
- **Utils**: Funções auxiliares, como `Leitura` para manipulação de entradas.

## Requisitos

- Java 8 ou superior
- IDE para desenvolvimento em Java (IntelliJ IDEA, Eclipse, etc.)
- Gradle ou Maven (opcional, se usar dependências externas)

## Como Executar

1. Clone o repositório ou faça o download do projeto.
2. Abra o projeto em sua IDE Java.
3. Compile o código.
4. Execute a classe `App.java` para iniciar a aplicação.

## Funcionalidades

- **Adicionar filme**: Permite cadastrar filmes com título, ano de lançamento, e detalhes de atores e diretores.
- **Listar filmes**: Mostra uma lista de todos os filmes cadastrados.
- **Manipulação de atores e diretores**: Gerencia os dados de atores e diretores associados aos filmes.

## Arquitetura MVC

Este projeto foi construído com base na arquitetura MVC:
- **Model (Entidades)**: Representa os dados e as regras de negócios (classes `Ator`, `Diretor`, `Filme`).
- **View (UI)**: Apresenta os dados para o usuário e recebe suas interações.
- **Controller**: Lida com a lógica e as interações, comunicando a View com o Model (`FilmeController`).

## Estrutura do Código

- **src/**: Contém todo o código-fonte Java.
  - **entities/**: Definição das entidades do sistema.
  - **repositories/**: Repositórios para acesso a dados.
  - **services/**: Lógica de negócios.
  - **controllers/**: Controladores responsáveis por orquestrar o fluxo da aplicação.
  - **ui/**: Interface do usuário.
  - **utils/**: Utilitários de suporte.

## Contribuindo

1. Faça um fork do projeto.
2. Crie uma nova branch para suas alterações: `git checkout -b minha-nova-feature`.
3. Faça commit das suas alterações: `git commit -m 'Adiciona nova feature'`.
4. Faça push para a branch: `git push origin minha-nova-feature`.
5. Abra um Pull Request.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
