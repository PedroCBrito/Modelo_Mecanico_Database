# Modelo_Mecanico_Database

Modelagem feita no MySQL workbench para Bootcamp DataBase Experience na DIO, nele fiz um modelo para uma Oficina mecanica do zero, como meu primeiro projeto desse feito sozinho nesse bootcamp.
Deixo o PNG e o arquivo para edicao, se tiver dicas fico aberto para aprender, obrigado.

Nesse modelo tento refinar o maximo, adcionei o estoque que não foi pedido pois achei que seria um ponto necessario a ser considerado.
Optei tambem para nao ter que repitir os mesmos atributos para clientes e os funcionarios (mecanicos) por criar uma entidade pessoa que referenciaria duas outras entidades que é cliente e mecanico, desta forma fazendo uma especificação assim como fiz na forma como guardar se o veiculo foi para revisão períodica ou para concerto, assim guardando na entidade "Motivo de ir ao mecanico" para depois passar direto para o Veiculo.
