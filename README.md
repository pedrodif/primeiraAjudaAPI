## JSON Server Project

Este projeto utiliza o `json-server` para fornecer uma API REST falsa com um conjunto de dados JSON fictícios. Ele é utilizado na aplicação `primeiraAjuda` para simular operações de API, facilitando o desenvolvimento e os testes.

### Pré-requisitos

- [x] Node.js instalado em sua máquina.

Passo a passo para incluir informações na API: 
1. Baixar e instalar o Node.js.
2. Clonar o repositório.
3. Instalar o json-server.
4. Incluir na pasta "data", no arquivo db.json o recurso desejado. Obs: Siga o exemplo do recurso "postagens".
5. O endpoint está informado na seção "about" deste repo.
6. Utilizar o endpoint/recursoDesejado.

# Endpoints
| Método | Endpoint       | Descrição                                |
| ------ | -------------- | ---------------------------------------- |
| GET    | /produtos      | Retorna todos os produtos                |
| GET    | /produtos/{id} | Retorna um produto específico pelo `id`  |
| POST   | /produtos      | Adiciona um novo produto                 |
| PUT    | /produtos/{id} | Atualiza um produto específico pelo `id` |
| DELETE | /produtos/{id} | Remove um produto específico pelo `id`   |
