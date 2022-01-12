# 🟢 POKEDEX 🟢
---
### Definição
O projeto em questão faz o consumo da API https://pokeapi.co/api/v2/pokemon/, que retorna os dados dos mais diversos Pokemons.

Há uma única página com a listagem de vários Pokemons, a qual além de visualizar o nome dos pokemons, é possível ver tambéms seus tipos e uma foto do mesmo
 --- 

# Desenvolvimento
Para a criação da aplicação servidora, utilizou-se o micro framework Javascript Express. O consumo da API rest se deu através do package Axios. Para obtenção dos dados detalhados de cada um dos Pokemons, eu criei um loop que vai de 0 a 800, executando um get na API pra obteção dos dados de cada um dos 801 Pokemons por Id. É exibido o nome da espécie do Pokemon, seus tipos, e uma imagem ao estilo dos jogos clássicos da Nintendo. Com o retorno dos dados da API, utilizei do método reduce, para iterear sobre o resultado de cada requisição para obteção de dados do Pokemon. A cada iteração é retornado uma String com elementos HTML com os dados do Pokemon e as classes CSS já definidas no arquivo ./public/style.css . Ao final temos uma String com elementos para exibição de cada um dos Pokemons ao qual é adicionado na String de retorno com a estrutura de HTML base.

## Acesso
Link da aplicação no heroku: https://analia-beatriz.herokuapp.com/

## Desenvolvido por 
 👩‍💻 Anália Beatriz