# Lista de pilotos de Fórmula 1 

O objetivo deste projeto é criar uma lista de pilotos de fórmula 1 registrados em 2019, a lista deve apresentar o nome e sobrenome do piloto, data de nascimento, nacionalidade e a um link para á página do piloto na wikipedia, ao clicar no link o aplicativo deve abrir a página correspondente. Também será necessário criar uma tela de sobre que deve ter seu acesso realizado através do menu -> sobre, a tela de sobre 
deve ter o nome do desenvolvedor do aplicativo, um breve texto explicando quais informações o aplicativo exibe. 

Todas as informações dos pilotos estão disponiveis na API https://ergast.com/mrd/methods/drivers/ 

Realize o fork do projeto e quando finalizar todas a implementações realize o Pull Request para o projeto principal. 

## Checklist 

* [ ] Consumir a API ergast utilizando a biblioteca retrofit
* [ ] Criar a listagem de pilotos utilizando RecyclerView
* [ ] Criar uma Activity para tela de sobre
* [ ] Criar recurso de menu com o item "Sobre" e carrega-lo na Activity principal
* [ ] Abrir a página da wikipedia através de uma Intent implicita 
* [ ] Abrir a activity sobre utilizando uma Intent explicita quando ocorrer um clique no menu sobre.
* [ ] Os layouts da tela devem ser baseados no canvas abaixo. 


<img width="60%" height="60%" src="https://github.com/brunoluizcs/android-drivers-f1/blob/master/canvas/canvas-formula1.png">

