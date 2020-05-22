Bem vindo a documentação da API do TRANSPORT! Aqui estão listadas as funcionalidades implementadas da API para consulta e desenvolvimento de software que interaja com a mesma.

O serviço TRANSPORT foca no gerenciamento de viagens entre pontos sendo da sua alçada:
* Controlar rotas
* Controlar viagens nessas rotas
* Controlar os pontos de parada das viagens
* Controlar os passageiros em cada viagem
* Controlar os passageiros entre pontos de parada, verificando quem embarca e quem desembarca em cada ponto

Coisas que o TRANSPORT **NÂO FAZ**:
* Venda de viagens
* Cadastro de passageiros
* Cadastro de motoristas
* Cadastro de empresas

O sistema tem algumas entidades:
* [Route](route.md) 
* [Trip](trip.md)
* [Stop Point](stop_point.md)
* [Driver](driver.md)
* [Company](company.md)
* [Passenger](passenger.md)