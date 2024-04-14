Objetivos
Criar projeto Spring Boot Java:
Iniciar um novo projeto Spring Boot usando o Spring Initializr ou seu IDE favorito.
Configurar as dependências necessárias para o desenvolvimento do projeto, incluindo Spring Data JPA, H2 e Lombok.
Implementar modelo de domínio:
Criar classes Java que representem as entidades do seu domínio, como por exemplo, Produto, Categoria ou Cliente.
Anotar as classes com as anotações JPA adequadas para mapear os objetos do domínio para as tabelas do banco de dados.
Estruturar camadas lógicas:
Criar pacotes separados para cada camada lógica do seu aplicativo: resource, service e repository.
Implementar interfaces e classes em cada camada seguindo os princípios do SOLID.
Configurar banco de dados de teste (H2):
Configurar o banco de dados H2 em seu projeto, utilizando a biblioteca Spring Boot Data JPA e o arquivo application.properties.
Definir a URL de conexão, nome de usuário e senha para o banco de dados H2.
Povoar o banco de dados:
Criar scripts SQL para criar as tabelas do banco de dados e inserir dados iniciais.
Executar os scripts SQL durante o processo de inicialização do aplicativo Spring Boot.
CRUD - Create, Retrieve, Update, Delete:
Implementar métodos nas classes de serviço para realizar as operações CRUD (Criar, Ler, Atualizar e Excluir) nas entidades do domínio.
Utilizar as interfaces de repositório do Spring Data JPA para persistir os dados no banco de dados.
Tratamento de exceções:
Implementar mecanismos para capturar e tratar exceções durante a execução do aplicativo.
Utilizar classes de exceção personalizadas para identificar e gerenciar diferentes tipos de erros.
