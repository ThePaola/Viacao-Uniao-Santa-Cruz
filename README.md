# Viacao-Uniao-Santa-Cruz
Exercício Técnico IT Academy - 17 Edição.

Esta atividade consiste na simulação de um sistema de
reserva de passagens da Viação União Santa Cruz. A figura
ao lado mostra o mapa de assentos, existem 46 assentos. O
ônibus da linha 160 (Porto Alegre -> Florianópolis) tem duas
saídas diárias às 6h e às 16h. Esta linha tem parada apenas
na cidade de Criciúma.
Porto Alegre -> Florianópolis 6h R$19,45
Porto Alegre -> Florianópolis 16h R$23,50
Porto Alegre -> Criciúma 6h R$12,90
Porto Alegre -> Criciúma 16h R$15,90
Criciúma -> Florianópolis 10h R$7,30
Criciúma -> Florianópolis 20h R$10,30
O sistema deverá iniciar mostrando o mapa de assentos na
tela (em modo texto*), com cerca de 30% dos assentos já
ocupados sendo metade deles passagens de Porto Alegre ->
Florianópolis e a outra metade de Porto Alegre -> Criciúma
(você pode fazer isso de forma manual/fixa ou então fazer
com que o computador reserve aleatoriamente alguns
assentos de forma automática).
Você deve implementar as seguintes funcionalidades:
1. [Visualizar o mapa de assentos] O programa deverá representar em modo
texto o estado de cada assento (ocupado/disponível).
a. Para o horário das 6h
b. Para o horário das 10h
c. Para o horário das 16h
d. Para o horário das 20h
2. [Reservar passagem] O programa deverá permitir que o usuário escolha um
assento livre para o horário que deseja, 6h, 10h, 16h ou 20h. O programa
deverá solicitar o identificador do assento. Se estiver disponível, o programa
deverá marcar o assento como ocupado. Caso contrário, deverá exibir uma
mensagem ao usuário e retornar ao menu.
a. Uma passagem para a rota Porto Alegre -> Florianópolis
b. Uma passagem para a rota Porto Alegre -> Criciúma
c. Uma passagem para a rota Criciúma -> Florianópolis
3. [Liberar uma reserva] O programa deverá solicitar o identificador do assento
e liberá-lo.
4. [Encontrar assentos livres] O programa deverá solicitar ao usuário quantos
assentos ele gostaria de reservar em determinado horário, nessa etapa é
necessário que seja mais de um (exemplo: 2, 3, etc.) e localizar a primeira
sequência de assentos que estiver disponível (ex.: “41, 42”, “41, 42, 43”) e
marcá-lo como ocupado. Caso não tenha uma sequência disponível de
bancos livres deverá informar ao usuário.
5. [Dados estatísticos] Exibir o mapa de assento da rota e apresentar as
seguintes informações: número de assentos total, número de assentos
disponíveis, número de assentos reservados e total acumulado em reservas.
a. Uma passagem para a rota Porto Alegre -> Florianópolis
b. Uma passagem para a rota Porto Alegre -> Criciúma
c. Uma passagem para a rota Criciúma -> Florianópolis
6. [Terminar o programa] Permitir que o usuário saia do programa.
* Você pode exibir o mapa de assentos em modo texto da forma que achar mais
conveniente e útil, utilizando caracteres, símbolos, números, espaços e etc. Use a
criatividade!
Observações:
a) Sugere-se o desenvolvimento de um programa na linguagem de sua
preferência, com uma interface também de sua preferência podendo ser gráfica
ou textual/console, com um menu com as opções enumeradas nos requisitos;
b) Você deve escrever o código que realiza as funções requeridas e armazena os
dados lidos em memória (do jeito que você quiser).
c) Não é necessário gravar dados em nenhum formato, nem usar sistemas de
banco de dados.
d) O programa deverá lidar com dados de entrada inválidos e informar uma
mensagem adequada caso ocorram.
e) Para facilitar, não é necessário lidar com a acentuação de palavras.
