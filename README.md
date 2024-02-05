# API NBA 🏀

Este projeto de API Web ASP.NET Core, **API_NBA**, serve como uma plataforma para gerenciar informações sobre times e jogadores de basquete. Permite aos usuários realizar operações CRUD tanto em times quanto em jogadores.

## Sumário

- [Introdução](#introdução)
- [Funcionalidades](#funcionalidades)
- [Endpoints](#endpoints)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Instruções de Configuração](#instruções-de-configuração)
- [Uso](#uso)
- [Contribuições](#contribuições)
- [Licença](#licença)

## Introdução

A **API NBA** foi projetada para fornecer uma interface RESTful para interagir com times e jogadores de basquete. Ela aproveita o poder do framework ASP.NET Core juntamente com o Entity Framework Core para fornecer uma solução robusta e eficiente para o gerenciamento de dados relacionados a times e jogadores de basquete.

## Funcionalidades

- Operações CRUD para o gerenciamento de times de basquete.
- Operações CRUD para o gerenciamento de jogadores de basquete.
- Capacidade de recuperar times juntamente com seus jogadores.

## Endpoints

### Times

- **GET /api/Times**: Recupera todos os times.
- **GET /api/Times/jogadores**: Recupera um time juntamente com seus jogadores.
- **POST /api/Times**: Cria um novo time.
- **PUT /api/Times/{id}**: Atualiza um time por ID.
- **DELETE /api/Times/{id}**: Exclui um time por ID.

### Jogadores

- **GET /api/Jogadores**: Recupera todos os jogadores.
- **GET /api/Jogadores/{id}**: Recupera um jogador específico por ID.
- **POST /api/Jogadores**: Cria um novo jogador.
- **PUT /api/Jogadores/{id}**: Atualiza um jogador por ID.
- **DELETE /api/Jogadores/{id}**: Exclui um jogador por ID.

## Tecnologias Utilizadas

- ASP.NET Core 3.1
- Entity Framework Core
- MySQL
- Swagger (para documentação da API)

## Instruções de Configuração

1. Clone este repositório em sua máquina local.
2. Certifique-se de ter o [.NET Core SDK](https://dotnet.microsoft.com/download) instalado.
3. Configure um banco de dados MySQL e atualize a string de conexão no arquivo `appsettings.json`.
4. Navegue até o diretório do projeto e execute os seguintes comandos:
    ```bash
    dotnet build
    dotnet run
    ```
5. A API deverá estar sendo executada localmente em `https://localhost:5001`.

## Uso

- Utilize ferramentas como Postman ou curl para interagir com os endpoints da API.
- Consulte a seção [Endpoints](#endpoints) para detalhes sobre os endpoints disponíveis e seu uso.

## Contribuições

Contribuições são bem-vindas! Se encontrar algum problema ou tiver sugestões de melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Desenvolvido
- Lucas Benediht Caldeira

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).
