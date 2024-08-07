Project title : Pokemon Backend
This repository(backend-pokemon) allows the managing the pokemon data. this Api allows user to add, edit, delete, and view pokemon info, as well as manage pokemon owners and their associated pokemon
features like add new pokemon, edit existing pokemon, delete pokemon, list all pokems
project Prerequesites
->java 11 or higher
->maven
->spring boot
Installation
1)clone the repository git clone https://github.com/uday-chowdary018/backend-pokemon.git
2)naviagte tp directory
project open in vs code or Ecliples, sts
Api Endpoints: (postman)
Add pokemon->
method:POST,
url:http://localhost:8080/api/pokemons
Get Pokemon By Id->
method:GET, 
url:http://localhost:8080/api/pokemons/{id}
update or edit pokemon 
-> method:PUT, 
url:http://localhost:8080/api/pokemons/{id}
Delete pokemon-> method:DeLETE,
url:http://localhost:8080/api/pokemons/{id}
List down all Pokemons->method:GET,
url:http://localhost:8080/api/pokemons
get pokemon owners -> method:GET, 
url:http://localhost:8080/api/pokemon-owners
To create tables in mysql database steps
create Database pokemons
use pokemos 
create table pokemons
craete table pokemons_owner
