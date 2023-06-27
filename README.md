# Tech Challenge - Primeira fase
[Repositório do projeto do desafio da primeira fase.](www.github.com)

## Documentação das APIs
Documentação das APIs desenvolvidas, com exemplos de entrada e saída e descrição dos endpoints.

### Cadastro de endereços
A API de gestão de endereços tem como objetivo permitir o gerenciamento de informações sobre os endereços cadastrados em nosso sistema.
#### Endpoint: POST /api/endereco
~~~javascript
{
  "rua": "Rua Maria Helena",
  "numero": 512,
  "bairro": "Novo Tempo",
  "cidade": "Belém",
  "estado": "Rio Grande do Sul"
}
~~~

### Gestão de pessoas
A API de gestão de pessoas tem como objetivo permitir o cadastro e gerenciamento de informações sobre as pessoas relacionadas aos usuários cadastrados em nosso sistema.
#### Endpoint: POST /api/pessoa
~~~javascript
{
  "nome": "João Paulo da Siva",
  "data-de-nascimento": "11-10-1990",
  "sexo": "Masculino",
  "parentesco": "Tio"
}
~~~

### Gestão de eletrodomésticos
API de gestão de eletrodomésticos tem como objetivo permitir o cadastro e gerenciamento de informações sobre os aparelhos eletrônicos dos usuários cadastrados em nosso sistema.
#### Endpoint: POST /api/eletrodomestico
~~~javascript
{
  "nome": "Batedeira",
  "modelo": "Bat-2110",
  "potencia": "1500W",
  "tensao": "127V",
  "quantidade": 1
}
~~~

[Swagger da API](https://app.swaggerhub.com/apis/JoneyPereira/Tech-Challenge-Primeira-fase/1.0.0)

