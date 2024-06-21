## JSON Server Project

Este projeto utiliza o `json-server` para fornecer uma API REST falsa com um conjunto de dados JSON fictícios. Ele é utilizado na aplicação `primeiraAjuda` para simular operações de API, facilitando o desenvolvimento e os testes.

### Pré-requisitos

- [x] Node.js instalado em sua máquina.

### Passo a passo para incluir informações na API: 
1. Baixar e instalar o Node.js.
2. Clonar o repositório.
3. Instalar o json-server.
4. Incluir na pasta "data", no arquivo db.json o recurso desejado. Obs: Siga o exemplo do recurso "postagens".
5. A atualização do projeto será automática após o seu commit.
6. O endpoint está informado na seção "about" deste repo.
7. Utilizar o endpoint/recursoDesejado.

### Endpoints
| Método | Endpoint       | Descrição                                |
| ------ | -------------- | ---------------------------------------- |
| GET    | /recurso      | Listagem               |
| GET    | /recurso/{id} | Retorna uma informação específica pelo `id`  |
| POST   | /recurso      | Adiciona uma nova informação                 |
| PUT    | /recurso/{id} | Atualiza uma informação específica pelo `id` |
| DELETE | /recurso/{id} | Remove uma informação específica pelo `id`   |
