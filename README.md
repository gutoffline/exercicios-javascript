# Exercícios
## Variáveis
1 - Uma empresa separou os seus ganhos dos meses nas seguintes variáveis:
- let janeiro =  100
- let fevereiro = 300
- let março = 90

Ela precisa da sua ajuda para saber o total do lucro adquirido. 
Sua missão é usar os operadores junto com as variáveis para fazer esse cálculo e use o console.log para imprimir o resultado!

```javascript
let janeiro =  100
let fevereiro = 300
let marco = 90

let valorTotal = janeiro + fevereiro + marco;
console.log(valorTotal);

```

<br>

2 - Em uma escola, um professor quer calcular a média de notas dos seus alunos. Ele tem separado em variáveis cada nota dos trabalhos realizados por cada aluno:
- let trabalhoDeHistoria = 8.0
- let trabalhoDeMatematica = 7.0
- let trabalhoDeCiencia = 10
- let trabalhoDeGeografia = 9.5

O professor já sabe que a média é calculada com a soma de todas as notas e dividindo pelo total. 

Mas ele se perdeu um pouco no código, e precisa da sua ajuda para terminar essa tarefa! 
Sua missão é ajudar o professor com o seu conhecimento dos operadores aritméticos para calcular a média dos alunos. Atribua na variável media o cálculo matemático para chegar no valor requisitado.

<br>

3 - Precisamos criar um código que gera cartão de visita com nome, sobrenome e profissão. 
Crie uma variável para guardar cada informação, depois faça a concatenação das informações numa variável chamada cartaoDeVisita.

<br>

4 - Declare e atribua duas variáveis: numeroA e numeroB, em que ambas precisam conter um valor numérico. Em seguida, faça as variáveis de soma, subtração, multiplicação e divisão utilizando essas duas variáveis.

<br>

## Estrutura de decisão
5 - Precisamos verificar se uma pessoa pode se aposentar com base na idade. 
Utilize a condicional if else para verificar se a variável idade é maior que 65 e imprima uma mensagem para cada caso:
- Condição verdadeira : “Você já pode se aposentar”
- Condição falsa: “Você ainda não pode se aposentar”

```javascript
let idade = 40

if (idade > 65){
    console.log("Você já pode se aposentar")
}else{
    console.log("Você ainda não pode se aposentar")
}

```

<br>

6 - Precisamos de um código que verifique a idade do usuário para ver se já tem idade mínima para adquirir carta de habilitação. Para isso, teremos uma variável nome que guarda um valor do tipo string, e uma variável idade que guarda um valor do tipo numérico.
O sistema deve cumprimentar o usuário independente da idade, o resultado seria assim:
Caso o usuário tenha idade mínima para dirigir imprima: 
- “Olá, NOME_DO_USUARIO_AQUI”
- ”Você passou no nosso teste e já pode dirigir!”.

Caso o usuário não tenha a idade mínima para dirigir imprima somente o cumprimento:
- “Olá, NOME_DO_USUARIO_AQUI”*/

```javascript
let nome = "João"
let idade = 17

console.log("Olá, "+nome)
if(idade>=18){
    console.log("Você passou no nosso teste e já pode dirigir!")
}
```

<br>

7 - Vamos otimizar nosso sistema de autoescola! Caso o usuário tenha 18 anos ou mais, ele pode dirigir, 
se a afirmação for negativa precisamos imprimir a mensagem “Ops, você ainda não tem a idade mínima para dirigir!”.


<br>

8 - Precisamos criar um código que ajude os usuários a saber se pode ir ao banco. 
Sabemos que o banco está aberto em todos os os dias da semana, exceto em  finais de semana. 
Caso o usuário possa ir ao banco você deve exibir com console.log a seguinte mensagem: “Você pode ir ao banco”, 
caso contrário, ‘O banco está fechado, tente outro dia’
Para esse exercício leve em consideração as seguintes informações:
-  Dias da semana pro sistema: segunda, terca, quarta, quinta, sexta, sabado e domingo.
- Você terá a seguinte variável no código: diaSemana
- Para esse exercício você deve usar na condição do if o operador && para juntar as condições lógicas junto ao operador diferente de(!=).

```javascript
let diaSemana = 'sabado'

if(diaSemana != 'sabado' && diaSemana != 'domingo'){
    console.log("Você pode ir ao banco")
}
else {
    console.log("O banco está fechado, tente outro dia")
}
```

<br>

9 - Queremos um código que oriente o usuário de acordo com o saldo da conta bancária. 
Para isso precisamos de uma variável saldo que guarda um número decimal(float), e imprime uma mensagem de acordo com a situação financeira. 
- Se o saldo for maior que 0 (zero) imprima “Seu saldo está positivo! Gostaria de fazer um investimento?”.
- se o saldo for menor que zero(0) imprima “Seu saldo está negativo! Gostaria de fazer um empréstimo?”.

<br>

10 - Utilize a condicional if/else para verificar a variável estrangeiro que guarda um valor booleano. Caso o valor seja verdadeiro solicite o Registro Nacional de Estrangeiros(RNE). Se o valor for falso solicite o Cadastro de Pessoa Física (CPF).
- Mensagem para estrangeiro: “Você poderia apresentar seu RNE, por favor?”
- Mensagem para brasileiro: “Você poderia apresentar seu CPF, por favor?”

```javascript
let estrangeiro = true

if(estrangeiro){
  console.log("Você poderia apresentar seu RNE, por favor?")
}else{
  console.log("Você poderia apresentar seu CPF, por favor?")
}

```

<br>

11 - Precisamos de ajuda para escrever um código que de acordo com a quantidade de lados iguais de um triângulo, exiba com console.log se ele é Equilátero, Isósceles ou Escaleno, sem a necessidade de repetir no código a palavra “triângulo”. 

- Triângulo Equilátero: possui os 3 lados iguais.	
- Triângulo Isósceles: possui 2 lados iguais.	
- Triângulo Escaleno: possui 3 lados diferentes*/



```javascript
let ladosIguais = 0

if(ladosIguais == 3){
    console.log("Equilátero")

}
else if (ladosIguais == 2){
    console.log("Isósceles")
}
else{
    console.log("Escaleno")
}
```

<br>

12 - Posso comprar esse produto?
Queremos criar um código que ajude o usuário a saber se ele pode comprar um produto ou não. Para acontecer a venda, a quantidade do produto no estoque tem que ser maior que zero e o produto está ativo.

Para escrever este código, teremos duas variáveis já definidas: produtoQtd, produtoAtivo. 

Faça uma condição que supra a necessidade acima, se o usuário puder comprar o produto exiba a seguinte mensagem “Você pode finalizar essa compra”. Caso contrário exiba “Produto não está disponível para compra”

<br>


13 - Dentro do código estará criada uma variável numeroDaSorte  contendo um número. 
Sua missão é verificar se o valor da variável é par ou ímpar utilizando o operador relacional módulo (%). Imprima “Par” ou “Ímpar” de acordo com o resultado.

```javascript
let numeroDaSorte = 18
if (numeroDaSorte % 2 == 0){
    console.log("Par")
}else{
    console.log("Ímpar")
}
```

14 - Precisamos criar um código que ajude um petshop a dizer se o pet está com o peso ideal. 
E para isso eles deixaram para você as informações que ele usam para fazer essa classificação:
 - Abaixo de 4kg = Abaixo do Peso
 - Maior que 10kg = Acima do Peso
 - Se tiver entre esses dois valores =  Peso normal.

Utilizando o ELSE IF e crie o código para suprir essa necessidade e imprimindo as mensagens de acordo com a lista acima!

<br>

15 - Um parque de diversão te contratou para criar um código para ajudar os usuários a saber se eles podem ir em uns dos brinquedos.
 As regras são:
- Ser maior que 1,50m ou ter 21 anos ou mais.

Diante disso, crie condições que supra essa necessidade, exiba a seguinte mensagem caso o usuário possa usar o brinquedo: “Você pode subir”.  Caso ele não possa: “Desculpe, você não atende os requisitos para usar o brinquedo”. Vale dizer que para esse exercício você terá duas variáveis: usuarioAltura e usuarioIdade

```javascript
let usuarioAltura = 170
let usuarioIdade = 21

//seu código aqui
if(usuarioAltura > 150 || usuarioIdade >= 21){
    console.log("Você pode subir")
}
else{
    console.log("Desculpe, você não atende os requisitos para usar o brinquedo")
}
```

<br>

16 -  No sistema político atual, temos algumas regras para participar das eleições. 
A principal delas, é que o voto é obrigatório a partir dos 18 anos, e opcional a partir dos 16! 

Diante desse cenário, escreva um código que de acordo com a variável idade informe ao usuário usando console.log(),
 “Você é obrigado a votar” caso ele cumpra o requisito ou “Seu voto é opcional”.


<br>

## Estrutura de repetição

17 - Uma empresa mandou uma lista contendo os números mensais de tudo o que ela faturou, 
e nosso trabalho é ajudá-los a criar um relatório que exiba em quantos meses eles tiveram o saldo negativo.
- let listaDeGanhos = [10, 30, -10, -5, -1, 40]


Com base no array acima, que está disponível no código, faça um loop que verifique quantos meses tiveram valores negativos e armazene a contagem uma variável chamada totalNegativos que também está disponível no código.

```javascript
let listaDeGanhos = [10, 30, -10, -5, -1, 40]
let totalNegativos = 0

//seu loop aqui:
for(let i = 0; i< listaDeGanhos.length; i++){
    if(listaDeGanhos[i] < 0){
        totalNegativos++;
    }
}
```

<br>

18 - Precisamos imprimir somente os números pares de 0 à 20. 
Mas temos alguns requisitos, você precisa utilizar, o loop for, 
o comando continue e o numero deve ser o contador do loop! 
Vamos lá?


```javascript
for(let i = 0; i <= 20; i++){
    if(i%2!=0){
        continue
    }else{
        console.log(i)
    }
}
```

<br>

19 - Uma empresa separou em uma lista, os valores dos lucros mensais. 
Com isso você terá no código um array com o seguinte nome: listaDeLucro 
contendo em cada posição o valor de recebido de cada mês!
- let listaDeLucro = [100, 30, 300, -10, 600, 10] 

Seu trabalho será criar um loop que calcule o valor total baseado nessa lista, 
e coloque o valor em uma variável já existente no código chamada: lucroTotal*/

```javascript
let listaDeLucro = [100, 30, 300, -10, 600, 10]
let lucroTotal = 0;

//seu loop aqui
for(let i = 0; i < listaDeLucro.length; i++){
    lucroTotal += listaDeLucro[i]
}
```

<br>

20 - Temos um array em uma variável chamada baralho e precisamos de um script que procure a carta “Rei” entre as cartas do baralho. Assim que encontrar o “Rei” pare o loop utilizando break  e exiba um console.log a seguinte frase: Encontrei o Rei!

```javascript
let baralho = ["Ás", "Dama", "Rei", "Valete"]

for(let i = 0; i< baralho.length; i++){
  if(baralho[i] == "Rei"){
    console.log("Encontrei o Rei!")
    break
  }
}

``` 

<br>

21 -  Vamos criar um bingo, onde os números da cartela serão representados por um array chamado cartela, 
e o número sorteado deve ficar em uma variável chamada numeroSorteado. 
Seu trabalho será  verificar se existe o número sorteado na cartela, 
quando encontrar deve imprimir “Encontrei o número!” e parar o loop!


```javascript
let cartela = [8, 13, 18, 22, 42, 49]
 let numeroSorteado = 42

  for(let i = 0; i < cartela.length; i++){
    if(cartela[i] == numeroSorteado){
      console.log("Encontrei o número!")
      break
    }
  }
```

<br>

22 - Temos uma lista com nomes de todos os integrantes da família mas esqueceram de colocar o sobrenome! 
Seu desafio será imprimir nome junto com o sobrenome “Macedo” para cada integrante da família. 
Mas temos uma exceção, temos um integrante com sobrenome diferente, se tiver algum “Pedro”, coloque o sobrenome “Sousa”.

Dica: Utilize for  e continue para criar a solução.
Acrescente um espaço antes do sobrenome, por exemplo: “ Sousa”.

```javascript
let familia = ["Joana", "Felipe", "Gabriela", "Carlos", "Pedro", "Bruno"]

for(let i = 0; i < familia.length; i++){
    if(familia[i] == "Pedro"){
        console.log(familia[i] + " Sousa")
        continue
    }else{
        console.log(familia[i] + " Macedo")
    }
}
```

<br>

23 - Vamos criar um robô que manda “Bom dia, grupo!” para cada dia da semana, ou seja,  7 vezes. Utilize o laço de repetição for para fazer com mais praticidade!

<br>

24 -  Precisamos de um código que calcule a tabuada de multiplicação do 7 e imprima a expressão seguido do resultado. 
Exemplo:<br>

7 x 1 = 7<br>
7 x 2 = 14<br>
7 x 3 = 21<br>

Lembre-se de fazer a multiplicação do 7x1 até 7x10! 
Há, uma última dica, você pode usar a variável i que é nosso contador para concatenar na hora de montar a mensagem “7 x 1” 
Afinal os valores depois do X (1,2,3,4…) são os valores que mudam de acordo com cada loop.

<br>

25 - Uma agência de carros quer exibir seu catálogo para os clientes.
Eles exportaram os nomes dos carros no formato de array que se chama listaDeCarros:
- let listaDeCarros = [ "Fox", "Uno", "Gol", "Astra", "Fiesta"]

Seu trabalho é percorrer essa array exibindo os nomes dos carros:

“Nome do Carro: Fox”<br>
“Nome do Carro: Uno”<br>

Crie um loop que atenda o problema acima utilizando uma variável chamada i como contador, 
e que use o console.log para exibir o nome dos carro de acordo com o exemplo acima.

<br>

26 -  Um sacolão montou uma lista com as frutas que eles vendem, 
e de acordo com a fruta que o usuário busca eles querem informar se existe a fruta na lista ou não! 
- let listaDeFrutas = [ "Uva", "Banana",  "Manga", "Cajá", "Pinha"]

Você deverá criar um loop que verifique se a fruta contida na variável busca existe na lista de frutas do sacolão. Se existe basta exibir uma mensagem, “Sim, temos a fruta banana disponível”. 
Use a variável busca para exibir o nome da fruta nessa mensagem de forma dinâmica.

<br>

27 - Os engenheiros de uma montadora estão projetando o computador de bordo de um carro. Eles precisam de uma função que possa calcular a autonomia atual do automóvel, em outras palavras, quantos quilômetros ele consegue andar com a quantidade de combustível atual. 

A autonomia pode ser obtida multiplicando a quantidade de combustível pelo rendimento. Será que você consegue ajudá-los?

Escreva uma função chamada autonomia:
```javascript
function autonomia(quantidadeDeCombustivel, rendimento){

	...

}
```

Essa função deve receber dois parâmetros:

- O primeiro, que represente a quantidade de combustível que está no tanque
- O segundo, que represente o rendimento do automóvel

A função deve retornar a autonomia do automóvel.

Lembre-se: a autonomia do automóvel pode ser obtido multiplicando o rendimento pela quantidade de combustível presente no tanque.

A tela deve ficar parecido com o **CÁLCULO DE AUTONOMIA** disponível nesse link: https://www.figma.com/file/uRMnOizK4wQEsn6CGcPVGm/Untitled?node-id=1%3A2

<br>

28 - A lavanderia DigitalLaundry lava roupa por quilo. Ela cobra dos seus clientes R$ 5,00 por cada quilo de roupa suja. Atualmente, eles usam um caderninho e uma calculadora para descobrir o valor que cada cliente tem a pagar. Precisamos automatizar essa empresa!

Escreva uma função calculaValorDevido
```javascript
function calculaValorDevido(pesoDaRoupaSuja) {

	…

}
```

A função recebe como parâmetro o peso de roupa suja (em quilos) e deve retornar o valor a ser cobrado do cliente.

A tela deve ficar parecido com o **LAVANDERIA** disponível nesse link: https://www.figma.com/file/uRMnOizK4wQEsn6CGcPVGm/Untitled?node-id=1%3A2

<br>

29 - Depois de nossa consultoria, a lavanderia DigitalLaundry percebeu que poderia deixar a sua cobrança mais sofisticada e justa. Ela decidiu cobrar R$10,00 fixo, a título de taxa de serviço (independente da quantidade de roupa), mais R$ 3,00 por quilo de roupa suja. 

Reescreva a função calculaValorDevido

```javascript
function calculaValorDevido(pesoDeRoupaSuja){

	...

}
```
Essa função recebe como único parâmetro a quantidade de roupa suja. 

Ela deve retornar o valor a ser cobrado do cliente usando a nova política de preços.


<br>

30 - Crie uma função chamada cartaoDeVisitas, ela deverá imprimir o seu nome em conjunto com sobrenome, o seu telefone, profissão e e-mail!

A tela deve ficar parecido com o **CARTÃO DE VISITA** disponível nesse link: https://www.figma.com/file/uRMnOizK4wQEsn6CGcPVGm/Untitled?node-id=1%3A2

31 - Um mercado tem uma lista de produtos, que eles querem exibir para todo novo cliente que chegar! 

Como o processo é um pouco trabalhoso e repetitivo eles precisam do seu conhecimento em funções para ajudá-los.

Eles já tem um código, porém toda vez eles precisam reescrever o código para exibir ao cliente:

```javascript

var lista = [ 'Leite', 'tomate', 'Biscoito', 'Tapioca']

for(var i = 0; i < lista.length; i++){

	console.log(lista[i])

}
```
Seu trabalho é melhorar esse código, para ficar mais simples utilizá-lo e acrescente imagens a lista de produtos. 
Precisamos que você transforme o código acima em uma função chamada listarProdutos.

A tela deve ficar parecido com o **LISTA DE PRODUTOS** disponível nesse link: https://www.figma.com/file/uRMnOizK4wQEsn6CGcPVGm/Untitled?node-id=1%3A2
