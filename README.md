# PizzaStore API

A PizzaStore é uma API que implementa operações básicas de CRUD. Este código foi tirado do [Criar aplicativos Web e serviços com ASP.NET Core, API mínima e .NET](https://learn.microsoft.com/pt-br/training/paths/aspnet-core-minimal-api/).

## Descrição

Esta API foi desenvolvida para ensinar o básico da criação de API's mínimas aos desenvolvedores ASPNET.

## Endpoints

A seguir estão listados os endpoints disponíveis nesta API:

- `GET /pizza/{id}`: Retorna os detalhes de uma pizza específica com o ID fornecido.
- `GET /pizzas`: Retorna uma lista de todas as pizzas disponíveis na loja.
- `POST /pizza`: Cria uma nova pizza com os dados fornecidos no corpo da requisição.
- `PUT /pizza/{id}`: Atualiza os detalhes de uma pizza existente com o ID fornecido.
- `DELETE /pizza/{id}`: Exclui uma pizza existente com o ID fornecido.

## Documentação Swagger

Esta API inclui uma documentação Swagger que pode ser acessada em tempo de execução no ambiente de desenvolvimento. Para visualizá-la, siga as etapas abaixo:

1. Execute a aplicação em um ambiente de desenvolvimento.
2. Acesse a URL `http://localhost:<porta>/swagger/index.html`, onde `<porta>` é a porta em que a aplicação está sendo executada.

A documentação Swagger fornece uma interface interativa para explorar e testar os endpoints da API, bem como detalhes sobre os parâmetros de entrada e saída.

## Configuração do Banco de Dados

A API utiliza um banco de dados SQLite para armazenar informações sobre as pizzas. O arquivo do banco de dados (`Pizzas.db`) será criado automaticamente no diretório de execução da aplicação. Certifique-se de fornecer uma string de conexão válida no arquivo `appsettings.json` ou nas variáveis de ambiente para configurar o banco de dados.

## Execução da Aplicação

Para executar a aplicação, siga as etapas abaixo:

1. Certifique-se de ter o .NET SDK instalado na sua máquina.
2. Clone o repositório ou baixe os arquivos da aplicação.
3. Navegue até o diretório raiz da aplicação no terminal.
4. Execute o comando `dotnet run` para iniciar a aplicação.
5. Acesse os endpoints da API conforme documentado acima.

## Ambiente de Desenvolvimento

A aplicação está configurada para exibir a documentação Swagger e permitir testes interativos apenas quando executada em um ambiente de desenvolvimento. Certifique-se de configurar o ambiente corretamente para aproveitar esses recursos.
