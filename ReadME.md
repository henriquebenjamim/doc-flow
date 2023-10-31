# Sistema de Gerenciamento de Documentos

## Descrição do Projeto

O Sistema de Gerenciamento de Documentos é um projeto Java com Spring que permite às organizações gerenciar documentos de forma eficiente. Os documentos podem ser categorizados, armazenados e acessados de maneira centralizada.

## Segmento

Este projeto pertence ao segmento de **Transformação Digital**, permitindo que as empresas otimizem seus processos, melhorem a colaboração e reduzam o uso de papel através de um sistema digital de gerenciamento de documentos.

## Tecnologias Utilizadas

- Java
- Spring Framework (Spring Boot)
- Banco de Dados (por exemplo, MySQL)
- RabbitMQ (Opcional, para mensageria)
- Swagger (Documentação da API)

## Entidades

O sistema lida com as seguintes entidades:

- **Documento:** Representa um documento com campos como título, descrição, data de criação, autor, conteúdo e categoria.
- **Categoria de Documento:** Categoriza os documentos e permite organizá-los em grupos específicos.

## Endpoints (Controllers)

### DocumentController

- **POST /api/document/upload:** Realiza o upload de um novo documento.
- **GET /api/document/{documentId}:** Obtém detalhes de um documento específico.
- **GET /api/document/{documentId}/download:** Baixa o arquivo do documento.

### CategoryController

- **POST /api/category/create:** Cria novas categorias de documentos.
- **GET /api/category/list:** Lista todas as categorias disponíveis.

## Configuração e Execução

1. Clone este repositório: `git clone https://github.com/`
2. Configure as informações do banco de dados no arquivo `application.properties`.
3. Execute a aplicação Spring Boot.

## Documentação da API

A documentação da API pode ser acessada em `/swagger-ui.html`. Use o Swagger para explorar e testar os endpoints da API.

## Licença

Este projeto é distribuído sob a licença [MIT](LICENSE).
