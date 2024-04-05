
# Desafios de Código Intermediário C# - Coding The Future Avanade III- .NET Developer - DIO

## Desafio 1 - Desafios de Código Coding The Future Avanade lll - Item Mágico!
> Em jogos de RPG, os jogadores frequentemente adquirem itens mágicos que possuem poderes e habilidades especiais. Neste desafio, você deve criar uma classe "ItemMagico" que represente um item mágico e seja capaz de armazenar o nome, descrição e poder do item.

> Crie a classe "ItemMagico" que possua os seguintes atributos: "nome", "descricao" e "poder". Além disso, a classe deve ter um método chamado "criar", que recebe como argumento os valores do nome, descrição e poder do item, respectivamente.

- Entrada: A entrada será dada pela chamada do método "criar" da classe "ItemMagico", utilizando o io.read() para obter os valores dos atributos de cada item:

- nome: nome do item
- descricao: descrição do item
- poder: poder do item
- Importante: a entrada deverá ocorrer de acordo com a ordem das informações fornecidas acima.

- Saída: A saída deverá ser a impressão das informações do item criado, no formato:

- Nome: [nome do item]
- Descrição: [descrição do item]
- Poder: [poder]

- Entrada:	Espada Flamejante   /   Uma espada de fogo!   /   50
- Saída: Nome: Espada Flamejante   /   Descrição: Uma espada de fogo!   /   Poder: 50

## Desafio 2 - Desafios de Código Coding The Future Avanade lll - Construindo um Exército de Robôs
> Você é um inventor de robôs excêntrico e engraçado, que decidiu criar seu próprio exército de robôs para ajudá-lo em suas tarefas diárias. Para isso, você precisa desenvolver uma classe Robô que permita que cada um dos seus robôs tenha características únicas. Crie seu próprio robô personalizado, escolhendo seu nome, modelo e ano de fabricação, e veja seu exército de robôs engraçados tomar forma diante dos seus olhos!

> Você precisa criar uma classe Robo que possua um construtor que inicialize a classe com as características do robô (nome, modelo e ano de fabricação). Além disso, você precisa implementar métodos para exibir as características do robô.

- Escreva uma classe Robo, que possua os seguintes atributos e métodos:

> Três atributos: nome, modelo e ano de fabricação;
Construtor: deverá inicializar a classe com o nome, modelo e ano de fabricação;
Método chamado exibirInformações: que não receba parâmetros e exiba na tela as características do robô.
Seu programa deve solicitar ao usuário o nome, modelo e ano de fabricação do robô e criar um objeto Robo com essas informações. Em seguida, deve chamar o método exibirInformacoes para exibir as características do robô.

- Entrada: A entrada deverá receber os atributos do robô, conforme exemplo abaixo:

> nome: referente ao nome do robô (string).
modelo: referente ao modelo do robô (string).
ano: referente ao ano da criação do robô (int).
IMPORTANTE: A entrada deverá seguir a ordem informada acima.

- Saída: O código deverá retornar uma mensagem (string) informando o nome, modelo e ano do robô criado, de acordo com o que foi recebido como entrada. 

- Entrada:	Robozão   /   RBZ1000   /   2022
- Saída: O robô Robozão, modelo RBZ1000, foi fabricado em 2022.

## Desafio 3 - Desafios de Código Coding The Future Avanade lll - Descubra a Carta

> Nesse desafio, você deverá criar um programa que permita ao usuário escolher o valor e o naipe de uma carta de baralho, e exibir a carta escolhida.

> Para isso, será necessário criar uma classe chamada Carta, que possua dois atributos: naipe e valor. Os valores de naipe e valor devem ser definidos como enumerações, para facilitar a escolha do usuário.

> Como observação, os valores do enum Valor são:
Ás = 1; Valete = 2; Dama = 3; Rei = 4.

> Já os valores do enum Naipe são :
Paus = 0; Ouros = 1; Copas = 2; Espadas = 3.

> O programa deve permitir que o usuário escolha o valor e o naipe da carta, e em seguida criar uma instância da classe Carta com os valores escolhidos. Por fim, o programa deve exibir a carta escolhida, mostrando tanto o valor quanto o naipe da carta.

- Requisitos:
- Utilizar a classe "Carta" que possui dois atributos: "naipe" e "valor", ambos são enums.
- Utilizar switch case para tratar exceções ao escolher o naipe e o valor da carta.
- O programa deve permitir que o usuário escolha o naipe e o valor da carta.
- O programa deve exibir a carta escolhida pelo usuário.

- Entrada: A entrada deve receber duas informações, referentes ao valor e naípe, conforme exemplo abaixo:
valor: Enum  - representando o valor da carta;
naipe: Enum  - representando o náipe da carta.

- Saída: O código deverá retornar uma mensagem (string) informando qual o valor da carta e seu náipe, após receber como entrada os Enums valor e naipe. 

- Entrada:	1   /   0
- Saída: Carta escolhida: Ás de Paus
