# Trabalho-final
Este projeto foi feitoe finalizado por Isabelly Fernandes, com o intuíto de fazer reservas através do console.
O sistema  permite que os usuários criem, visualizem, editem e cancelem
reservas de salas de reunião. Criar uma nova reserva especificando nome do solicitante, data, horário,
sala desejada e finalidade da reunião.
Visualizar a lista de todas as reservas com seus detalhes.
Editar os detalhes de uma reserva existente, como nome do solicitante,
data, horário, sala ou finalidade.
Cancelar uma reserva existente.

//Variáveis
1. salasDeReuniao
Um array de objetos que representa as salas de reunião disponíveis.
Cada objeto contém um id e um nome para identificar a sala.
2. reservas
Um array que armazena as reservas de salas de reunião criadas pelo usuário.
Cada reserva é um objeto com informações sobre a sala, data, horário, nome do solicitante e finalidade.
Funções
1. exibirMenu()
Esta função exibe o menu principal do programa com opções numeradas para o usuário.
O usuário pode escolher uma opção digitando o número correspondente.
2. criarReserva()
Esta função permite ao usuário criar uma nova reserva.
O usuário escolhe uma sala disponível pelo número.
Em seguida, fornece informações como data, horário, nome do solicitante e finalidade da reserva.
A reserva é armazenada no array reservas.
3. visualizarReserva()
Esta função exibe a lista de todas as reservas existentes.
Para cada reserva, mostra o nome do solicitante, data, horário, motivo da reserva e sala desejada.
4. editarReserva()
Esta função permite ao usuário editar uma reserva existente.
O usuário informa o nome e a data da reserva que deseja editar.
Em seguida, fornece a nova data e o novo nome para a reserva.
A reserva é atualizada com as novas informações.
5. deletarReserva()
Esta função permite ao usuário deletar uma reserva existente.
O usuário informa o nome da reserva que deseja deletar.
A função encontra a reserva pelo nome e a remove do array reservas.

//Uso do Programa
O programa começa com uma mensagem de saudação e pergunta se o usuário deseja fazer uma reserva.
O usuário pode digitar 'sim' ou 'não' (ou variações em minúsculas) para responder.
Se o usuário digitar 'sim', o menu principal é exibido e o usuário pode escolher uma das opções.
O usuário pode continuar fazendo reservas, visualizando, editando ou deletando reservas até escolher a opção "Sair" para encerrar o programa.
