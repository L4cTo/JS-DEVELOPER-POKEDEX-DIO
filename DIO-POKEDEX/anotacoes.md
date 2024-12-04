# Anotações

## Areas de dados
* URL;
* Request Method;

* Request Headers:
Configuração da API;
- accept-lengauges
pt-BR
pt;q=0.9
en;q=0.8
en-GB;q=0.7
en-US;q=0.6

* authorization: Baerer

* Response Headers:
Configuração da API;

### primeira area de transferencia de dados
Após o path temos o (id) que é dinamico ou seja vai mudando de acordo com o que se deseja.

### segunda area de transferencia de dados
#### |Carry string|

quando usamos o get queremos buscar alguma coisa, podemos tambem utilizar alguns parametros para filtrar.
Ex: quero um pokemom com o tipo (glass)

#### Como funciona?

ela aparece após o (?) e funciona com passagem de chave e valor.
Ex: https://pokeapi.co/ep1/v2/pokemon?type=grass.

caso eu queira adicionar mais algum elemento no "filtro" podemos utilizar o (&).
Ex: https://pokeapi.co/ep1/v2/pokemon?type=grass&name=i

ou seja carry string: 
type=grass
name=i

## Respostas

### Headers
são uma configuração da requisição.

### bodyes
São geralmente utilizados em Post. é um conjunto de dados robustos, e envia o que foi pedido no request header.

* Ex:

request headers: content-type: json

body {
    "name":"Teste"
}

### Resposta de servidores
* Status code: significa oq ocorreu com a requisição. (se foi processada/se não foi processada)

* 200 - 299: Sucesso;
* 300 - 399: livred act;
* 400 - 499: erro por parte do cliente;
* 500 - 599: erro por parte do servidor;

### Response headers
Resposta ao cabeçalho
### Response body
Resposta ao corpo
* Relembrando 
(se foi pedido um GET não faz sentido ter um body, mas pode ter. 
agora se é um POST faz sentido ter um body.)