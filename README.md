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

