# Estudos_backend
Um registro de uma pequena trilha de estudos que estou seguindo estudando backend, com a intenção de aprimorar minhas habilidades em outras tecnologias.

# JavaScript Completo

## Gerais
// Comentários na mesma linha

// Console.log("Valor") Exibe Valor no terminal
//Node.Js - Apertar F-5 para rodar o Debug Console

# Operadores Matemáticos
## Somar
1 + 1 = 2, 10 + 10 = 20
Exemplo:
console.log(1 + 10) = 11
Ou, console.log("O valor da soma é: ", 20 + 20) = 40

Mais exemplos:
const numero1 = 10;
const numero2 = 40;

const soma = numero1 + numero2;

console.log("O Valor da soma é: ", soma);
Resultado: O Valor da soma é: 50

## Subtrair
const numero1 = 10;
const numero2 = 40;

const sub = numero1 - numero2;

console.log("O Valor da subtração é: ", sub);
Resultado: O Valor da subtração é: -30

## Dividir
const numero1 = 10;
const numero2 = 40;

const div = numero1 / numero2;

console.log("O Valor da divisão é: ", div);
Resultado: O Valor da divisão é: 0.25

## Multiplicação
const numero1 = 10;
const numero2 = 40;

const multi = numero1 * numero2;

console.log("O Valor da multiplicação é: ", multi);
Resultado: O Valor da multiplicação é: 400

---------------------------------------

# Strings e Concatenação

## Strings
Strings são: letras, números, caractéres diversos e textos
Identificadas por tipagem string, ou " "

Exemplos:
console.log("João Cosmala, Web Developer"); // = String em " "

// Diferenças
console.log("10"); // string
console.log(10); // número

console.log("10 + 10"); // Retorno: 10 + 10
console.log(10 + 10); // Retorno: 20

## Concatenação (mesclar)
Concatenação pode ser dita como: mesclar ou juntar
Se define em mesclar duas coisas diferentes em um aguardando um (1) resultado conjunto destes dois (2).

Exemplo:
console.log("Meu nome é João e tenho " + 23, "anos");
Você acabou de concatenar uma string e um número.

Outro meio de fazer isso é usando crases: ("` `") e $

Exemplo:
Meu nome é joão e minha idade é: ${23}

---------------------------------------

# Variáveis em JavaScript
Variáveis são maneiras de armazenarmos informações para que possamos usar novamente no futuro

## VAR, LET E CONST
Em JavaScript temos:
VAR
LET
CONST

## VAR
VAR -> Maneira antiga de escrever variáveis.
Perminte que adicionemos um valor nele, e posteriormente, podemos alterar este valor

## LET
LET -> Podemos adicionar um valor a ele, podendo também alterar este mesmo valor

## CONST
CONST -> Adicionamos um valor e ele é definido como único, sem poder alterar este valor depois.
Sendo está uma variável que só deve conter este determinado valor.

Exemplos:
var nome1 = "João";
let nome2 = "João";
const nome3 = "João";

---------------------------------------

# Números em JavaScript

Em JavaScript, diferente de outras linguagens, quando se tem um número, mesmo que seja impar, par, possua casa decimal e afins, ele não terá o que é conhecido como Float, Double, Integers e etc... Em JavaScript tudo isso é mais simplificado em um único tipo, tipo Number. Ou seja, qualquer coisa que seja um número, será dado como um número.

Exemplos:
console.log(21 + 10) = 31;
console.log(20 + 24.4444) = 44.4444;
console.log("10" + 10) = 1010 (??????) -> Isso ocorre porque número em aspas se torna uma string, deixando de ser um number.

Exemplos: 
console.log(10) -> numero
console.log("10") -> string

Outro fator importante são as casas decimais. Em JavaScript casas decimais são separadas por pontos ( . ), e não por vírgulas ( , ).
console.log(12, 3 + 13 + 3) -> 12, 16, 3

números também podem ser armazenados em variáveis:
const idade = 23
console.log(idade) -> 23

Resumindo, para trabalhar com números, devemos mante-los fora de strings, senão seram tratados como strings.

---------------------------------------

# Valores Booleanos

Valores booleanos são true ou false. 0 ou 1. Verdadeiro ou falso.

Exemplo:

const dormindo = false
const acordado = true

const comFome = "true" -> Não é booleano, é string, lembre-se das " " !!

---------------------------------------

# Operadores

Operadores são conhecidos como: "Operadores Lógicos", do qual são designados por símbolos que definem alguma função, algum ato, algum dever no seu código através da sua lógica.

## Operadores de: Atribuição, adição, subtração;
Alguns exemplos de operadores são:
• 1: = -> Operador de atribuição
• 2: += -> Operador de adição
• 3: -= -> Operador de subtração

Exemplos:
// Atribuilçao
let idade;
idade = 23;
console.log(idade); // Resultado = 23

let recebe = 2000;
recebe = recebe + 10;
console.log("Meu saldo é: ", recebe); // Resultado = 2010

recebe += 400;
console.log("Meu saldo é: ", recebe); // Resultado = 2410

recebe = recebe - 200;
console.log("Meu saldo é: ", recebe); // Resultado = 2210

recebe -= 200;
console.log("Meu saldo é: ", recebe); // Resultado = 2010

## Operadores de: Comparação;
Operadores de comparação sempre iram retornar true ou false no console.log;

Alguns exemplos de operadores de comparação são:
• 1: == -> Igual
• 2: != -> Diferente
• 3: === -> Estritamente igual
• 4: !== -> Estritamente diferente
• 5: > -> Maior que
• 6: < -> Menor que
• 7: >= Maior ou igual que
• 8: <= Menor ou igual que

Exemplos:

Operador de = (igual):
console.log("20 == 20: ", 20 == 20); // Resultado = true; 20 é igual a 20 então: true;
console.log("21 == 20: ", 20 == 20); // Resultado = false; 21 não é igual a 20 então: false;
console.log("21 == 21: ", 21 == 21); // Resultado = true; 21 é igual a 21 então: true;

Operador de != (Diferente):
console.log("20 != 20: ", 20 != 20); // Resultado = false; 20 não é diferente de 20 então: false;
console.log("21 != 20: ", 21 != 20); // Resultado = true; 21 é diferente de 20 então: true;
console.log("21 != 21: ", 21 != 21); // Resultado = false; 21 não é diferente de 21 então: false;

Operador de === (Estritamente igual):
console.log("20 === 20: ", 20 === 20); // Resultado = true; 20 é estritamente igual a 20 então: true;
console.log("21 === 21: ", "21" === 21); // Resultado = false; "21" não é estritamente igual a 21 então: false; Aqui vemos que === identificada "21" diferente de 20 pois 21 está em " " aspas, o deixando em string, logo, "21" não é estritamente igual a 21 porque "21" é uma string e 21 é um número.
console.log("21 === 21: ", 21 === 21); // Resultado = true; 21 é estritamente igual a 21 então: true;

Operador de !== (Estritamente Diferente):
console.log("20 !== 20: ", 20 !== 20); // Resultado = false; 20 não é estritamente diferente de 20 então: false;
console.log("21 !== 20: ", 21 !== 20); // Resultado = true; 21 é estritamente diferente de 20 então: true;
console.log("21 !== 21: ", 21 !== 21); // Resultado = false; 21 não é estritamente diferente de 21 então: false;

Operador de > (Maior que):
console.log("20 é maior que 20? ", 20 > 20); // Resultado = false; 20 não é maior que 20 então: false;
console.log("21 é maior que 20? ", 21 > 20); // Resultado = true; 21 é maior que 20 então: true;
console.log("21 é maior que 21? ", 21 > 21); // Resultado = false; 21 não é maior que 21 então: false;

Operador de < (Menor que):
console.log("20 é menor que 20? ", 20 < 20); // Resultado = false; 20 não é menor que 20 então: false;
console.log("21 é menor que 20? ", 21 < 20); // Resultado = false; 21 não é menor que 20 então: false;
console.log("21 é menor que 21? ", 21 < 21); // Resultado = false; 21 não é menor que 20 então: false;
console.log("12 é menor que 20? ", 12 < 20); // Resultado = true; 12 é menor que 20 então: true;

Operador de >= (Maior ou igual que):
console.log("20 é maior ou igual que 20? ", 20 >= 20); // Resultado = true; 20 é maior ou igual a 20 então: true;
console.log("21 é maior ou igual que 20? ", 21 >= 20); // Resultado = true; 21 é maior ou igual a 20 então: true;
console.log("12 é maior ou igual que 20? ", 12 >= 20); // Resultado = false; 12 não é maior ou igual a 20 então: false;

Operador de <= (Menor ou igual que):
console.log("20 é menor ou igual que 20? ", 20 <= 20); // Resultado = true; 20 é menor ou igual a 20 então: true;
console.log("21 é menor ou igual que 20? ", 21 <= 20); // Resultado = true; 21 não é menor ou igual a 20 então: false;
console.log("12 é menor ou igual que 20? ", 12 <= 20); // Resultado = false; 12 não é menor ou igual a 20 então: true;
