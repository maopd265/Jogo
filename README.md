# Jogo General


 //Objetivos:
/*Desenvolver um modelo orientado a objetos simples (modelagem do problema com objetos!).
Empregar conceitos que facilitam a manutenção e o reuso de software (encapsulamento)
Uso de exceções.
Implementação de listas encadeadas
Manter classes com responsabilidades bem definidas (p.ex.: interface com usuário acontece somente na(s) classe(s) que implementam a interface, e não nas outras!)
Estabelecer relações entre objetos usando referências (Composição: em uma classe pode-se declarar uma variável de instância cujo tipo é o de outra classe do projeto...)


Descrição do Projeto:

O projeto envolve o desenvolvimento de um modelo de classes para o jogo "General" e implementação delas na linguagem de programação Java. 

O Problema:

No jogo "General" o objetivo do Jogador é obter o maior número possível de pontos com um conjunto de combinações de números. Os números dessas combinações são resultantes do lançamento de 5 dados.

A cada rodada um Jogador poderá lançar os Dados até 3 vezes (o jogador decide quando quer parar). 
No segundo e terceiro lançamentos o jogador pode escolher quais dados permanecem "na mesa" e quais serão lançados novamente.
Quando o jogador terminar sua série de lançamentos deve indicar que combinação deve ser considerada para efeito de pontuação.

Os pontos obtidos com a combinação de números são computados da seguinte forma:

Sequência
Possíveis sequências: 1-2-3-4-5 / 2-3-4-5-6 / 3-4-5-6-1
Número de pontos: 20

Full-Hand
O número x em 3 dados e o número y nos dois restantes (para x diferente de y)
Número de pontos: ( 3 * x + 2 * y ) + 30

Quadra
O número x em quatro dados diferentes
Número de pontos: ( 4 * x ) + 40

General
O número x nos cinco dados
Número de pontos: ( 5 * x ) + 50

Combinações Simples
Para cada número de 1 a 6 o jogador pode marcar pontos como no exemplo:
Ex: Se o jogador obtiver a seguinte sequência de números:   2   3   2   2   5

Pode escolher marcar 6 pontos relativos aos 3 dados com o número 2.

Uma vez que o jogador já informou como pretende pontuar (indicando uma das possibilidades acima), o jogo deve verificar se os números nos dados realmente correspondem à combinação indicada.

Jogadores

Os jogadores devem ser cadastrados (somente jogadores cadastrados podem jogar).
Para manter uma lista de jogadores, deve-se utilizar uma implementação de lista encadeada.

Para cada jogador, além de dados de identificação, deve-se manter também informações sobre o número de jogos em que participou, o número de vitórias e de empates obtidos.

O jogo deve oferecer a opção de apresentar os jogadores nas 3 primeiras posições em número de vitórias (os números de jogos e de empates devem ser usados como critério de desempate quando os jogadores têm o mesmo número de vitórias)

Jogabilidade

O jogo deve possibilitar o enfrentamento entre 2 jogadores em uma única rodada (com três lançamentos para cada jogador)
Vence quem obtiver o maior número de pontos.



