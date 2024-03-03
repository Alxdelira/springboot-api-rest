<h1 align="center">:file_cabinet: README.md</h1>

## :memo: Descrição
Projeto voltado para aprendizado e prática.

## :books: Funcionalidades
- **Em Construção** ...

## :wrench: Tecnologias utilizadas
- SpringBoot

## Controllers do Spring Boot para Gerenciamento de Produtos

Este pacote contém os controladores responsáveis por gerenciar operações relacionadas aos produtos em uma aplicação Spring Boot.

## Classes:

### ProductController

Esta classe é responsável por lidar com as requisições HTTP relacionadas aos produtos. Ela fornece endpoints para criar, recuperar, atualizar e excluir produtos.

#### Endpoints:

- **POST /products**: Cria um novo produto com base nos dados fornecidos.
- **GET /products**: Recupera todos os produtos disponíveis.
- **GET /products/{id}**: Recupera um produto específico com base no ID fornecido.
- **PUT /products/{id}**: Atualiza um produto existente com base no ID fornecido.
- **DELETE /products/{id}**: Exclui um produto existente com base no ID fornecido.

#### Métodos Principais:

- **saveProduct**: Método para criar um novo produto.
- **getAllProducts**: Método para recuperar todos os produtos.
- **getOneProducts**: Método para recuperar um único produto com base no ID.
- **updateProduct**: Método para atualizar um produto existente com base no ID.
- **deleteProducts**: Método para excluir um produto existente com base no ID.

## Dependências:

- **ProductRecordDto**: Um DTO (Data Transfer Object) que contém os dados necessários para criar ou atualizar um produto.
- **ProductModel**: Um modelo que representa um produto.
- **ProductRepository**: Uma interface que lida com as operações de banco de dados relacionadas aos produtos.

## Utilização:

Os métodos nesta classe podem ser acessados por meio de requisições HTTP a partir de clientes, como aplicativos front-end ou outras APIs.

## Configuração Adicional:

Certifique-se de configurar corretamente as dependências e o mapeamento das URLs para garantir o funcionamento adequado dos endpoints.

## :handshake: Colaboradores
<table>
  <tr>
    <td align="center">
      <a href="http://github.com/Alxdelira">
        <img src="https://avataaars.io/?avatarStyle=Circle&topType=ShortHairTheCaesarSidePart&accessoriesType=Prescription02&hairColor=Black&facialHairType=BeardLight&facialHairColor=Black&clotheType=Hoodie&clotheColor=Black&eyeType=Happy&eyebrowType=UpDown&mouthType=Smile&skinColor=Brown" width="100px;" alt="Foto de Alexandre Lira no GitHub"/><br>
        <sub>
          <b>Alxdelira</b>
        </sub>
      </a>
    </td>
  </tr>
</table>
