# • JavaScript Completo, ou quase...

---------------------------------------

# • Operadores Matemáticos
### Somar
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

### Subtrair
const numero1 = 10;
const numero2 = 40;

const sub = numero1 - numero2;

console.log("O Valor da subtração é: ", sub);
Resultado: O Valor da subtração é: -30

### Dividir
const numero1 = 10;
const numero2 = 40;

const div = numero1 / numero2;

console.log("O Valor da divisão é: ", div);
Resultado: O Valor da divisão é: 0.25

### Multiplicação
const numero1 = 10;
const numero2 = 40;

const multi = numero1 * numero2;

console.log("O Valor da multiplicação é: ", multi);
Resultado: O Valor da multiplicação é: 400

---------------------------------------

# • Strings e Concatenação

### Strings
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

# • Variáveis em JavaScript
Variáveis são maneiras de armazenarmos informações para que possamos usar novamente no futuro

### VAR, LET E CONST
Em JavaScript temos:
VAR
LET
CONST

### VAR
VAR -> Maneira antiga de escrever variáveis.
Perminte que adicionemos um valor nele, e posteriormente, podemos alterar este valor

### LET
LET -> Podemos adicionar um valor a ele, podendo também alterar este mesmo valor

### CONST
CONST -> Adicionamos um valor e ele é definido como único, sem poder alterar este valor depois.
Sendo está uma variável que só deve conter este determinado valor.

Exemplos:
var nome1 = "João";
let nome2 = "João";
const nome3 = "João";

---------------------------------------

# • Números em JavaScript

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

# • Valores Booleanos

Valores booleanos são true ou false. 0 ou 1. Verdadeiro ou falso.

Exemplo:

const dormindo = false
const acordado = true

const comFome = "true" -> Não é booleano, é string, lembre-se das " " !!

---------------------------------------

# • Operadores

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

## Operador de = (igual):
console.log("20 == 20: ", 20 == 20);
// Resultado = true; 20 é igual a 20 então: true;

console.log("21 == 20: ", 20 == 20);
// Resultado = false; 21 não é igual a 20 então: false;

console.log("21 == 21: ", 21 == 21);
// Resultado = true; 21 é igual a 21 então: true;

## Operador de != (Diferente):
console.log("20 != 20: ", 20 != 20); 
// Resultado = false; 20 não é diferente de 20 então: false;

console.log("21 != 20: ", 21 != 20);
// Resultado = true; 21 é diferente de 20 então: true;

console.log("21 != 21: ", 21 != 21);
// Resultado = false; 21 não é diferente de 21 então: false;

## Operador de === (Estritamente igual):
console.log("20 === 20: ", 20 === 20);
// Resultado = true; 20 é estritamente igual a 20 então: true;

console.log("21 === 21: ", "21" === 21);
// Resultado = false; "21" não é estritamente igual a 21 então: false;
Aqui vemos que === identificada "21" diferente de 20 pois 21 está em " " aspas, o deixando em string, logo, "21" não é estritamente igual a 21 porque "21" é uma string e 21 é um número.

console.log("21 === 21: ", 21 === 21);
// Resultado = true; 21 é estritamente igual a 21 então: true;

## Operador de !== (Estritamente Diferente):
console.log("20 !== 20: ", 20 !== 20);
// Resultado = false; 20 não é estritamente diferente de 20 então: false;

console.log("21 !== 20: ", 21 !== 20);
// Resultado = true; 21 é estritamente diferente de 20 então: true;

console.log("21 !== 21: ", 21 !== 21);
// Resultado = false; 21 não é estritamente diferente de 21 então: false;

## Operador de > (Maior que):
console.log("20 é maior que 20? ", 20 > 20);
// Resultado = false; 20 não é maior que 20 então: false;

console.log("21 é maior que 20? ", 21 > 20);
// Resultado = true; 21 é maior que 20 então: true;

console.log("21 é maior que 21? ", 21 > 21);
// Resultado = false; 21 não é maior que 21 então: false;

## Operador de < (Menor que):
console.log("20 é menor que 20? ", 20 < 20);
// Resultado = false; 20 não é menor que 20 então: false;

console.log("21 é menor que 20? ", 21 < 20);
// Resultado = false; 21 não é menor que 20 então: false;

console.log("21 é menor que 21? ", 21 < 21);
// Resultado = false; 21 não é menor que 20 então: false;

console.log("12 é menor que 20? ", 12 < 20);
// Resultado = true; 12 é menor que 20 então: true;

## Operador de >= (Maior ou igual que):
console.log("20 é maior ou igual que 20? ", 20 >= 20);
// Resultado = true; 20 é maior ou igual a 20 então: true;

console.log("21 é maior ou igual que 20? ", 21 >= 20);
// Resultado = true; 21 é maior ou igual a 20 então: true;

console.log("12 é maior ou igual que 20? ", 12 >= 20);
// Resultado = false; 12 não é maior ou igual a 20 então: false;

## Operador de <= (Menor ou igual que):
console.log("20 é menor ou igual que 20? ", 20 <= 20);
// Resultado = true; 20 é menor ou igual a 20 então: true;

console.log("21 é menor ou igual que 20? ", 21 <= 20);
// Resultado = true; 21 não é menor ou igual a 20 então: false;

console.log("12 é menor ou igual que 20? ", 12 <= 20);
// Resultado = false; 12 não é menor ou igual a 20 então: true;

---------------------------------------

# • Operadores Lógicos;
Operadores lógicos são operadores que assim como os anteriores, também determinam uma função. Assim como em Lógica Aplicada, opedadores lógicos são usados para determinar: E, OU, OUOU, NEGAÇÃO e etc...

Aqui temos como principais:
• -> && -> E -> and lógico
• -> || -> OU -> or lógico
• -> ! -> NEGAÇÃO -> negação lógica

## &&
• Para que retorne um verdadeiro (true), as duas condições precisam ser verdadeiras
Exemplo:
• true && true = true;
• false && false = true;
• true && false = false;
• false && true = false;

TRUE
const nome = "joao";
const idade = 23;
console.log(nome === "joao" && idade === 23);
// Resultado: true; nome é === estritamente igual a "joao" && (E) idade também é estritamente igual a 23;

FALSE
const nome = "joao";
const idade = 23;
console.log(nome === "joao" && idade === 20);
// Resultado: false; nome é === estritamente igual a "joao" && (E) idade não é estritamente igual a 23;

TRUE
console.log("23 >= 23 && 70 >= 70: ", 23 >= 23 && 70 >= 70);
// Resultado: true; Porque 23 é maior ou igual a 23 e 70 é maior ou igual a 70

---------------------------------------

## || e |
• || -> Para que retorne um verdadeiro (true), uma das condições deve ser verdadeira
Exemplo para ||:
• true || true = true;
• false || false = false;
• true || false = true;
• false || true = true;

const joao = true;
const manu = false;

console.log(joao || manu); // Resultado: true;
console.log(manu || joao); // Resultado: true;
console.log(joao || joao); // Resultado: true;
console.log(manu || manu); // Resultado: false;

Mais exemplos:
(Aqui resolvi dar um exemplo mais avançado pois ele se adequa melhor a questão de como costuma ser mais utilizado esse contexto das Pipes)
Observação:
Levando em consideração o mercado de trabalho, muitas vezez precisamos determinar e comparar valores para as nossas funções através de 0 e 1


• Situação 1: Resultado true

//Aqui temos um objeto com o nome de sexualidade que nos trás dois valores BOOLEANOS, verdadeiro para masculino e falso para feminino
const sexualidade = {
    masculino: true,
    feminino: false,
};

//Denominei duas variáveis, uma com o nome de joao, e outra com o nome de manu.
//joao é masculino, logo, é verdadeiro
//manu é feminino, logo, é falso
const joao = sexualidade.masculino; // true
const manu = sexualidade.feminino; // false

// E para nos mostrar o resultado no terminal temos mais um console.log com o Operador Lógico de || para identificar valores 0 e 1 / verdadeiro e falso.
console.log(joao || manu); // Resultado: true; Porque João é verdadeiro;

• Situação 2: Resultado true

const joao = sexualidade.feminino; // false
const manu = sexualidade.masculino; // true

console.log(joao || manu); // Resultado: true; Porque Manu é verdadeiro;

• Situação 3: Resultado false

const joao = sexualidade.feminino; // false
const manu = sexualidade.feminino; // false

console.log(joao || manu); // Resultado: false; Porque João e Manu são falsos;

• Situação 4: Resultado true

const joao = sexualidade.feminino; // true
const manu = sexualidade.masculino; // true

console.log(joao || manu); // Resultado: true; Porque Joao e Manu são verdadeiros;

---------------------------------------

## • | (BitWise)
Agora iremos mudar um pouco sobre oq aprendemos de true ou false em || e considerar manipular bits com | (bitwise)
O operador | é usado como um manipulador de bits. Se tratarmos variáveis booleanas (true or false) com |, ele irá nos retornar 1 ou 0;
Porém, também pode ser usado para realizar operações lógicas. No entanto, ao contrário do ||, o | opera nos bits individuais dos números.
Normalmente é usado em situações onde a manipulação de bits é necessária.

Exemplo:
let x = 5; // Em binário: 0101;
let y = 3; // Em binário: 0011;
let result = x | y; // Resultado: 7 (binário: 0111);

OU

Se tivermos valores booleanos novamente, receberemos 0 ou 1 como resposta ao invés de true ou false.

const joao = true;
const manu = false;

console.log(joao | manu); // Resultado: 1 = true;
console.log(manu | joao); // Resultado: 1 = true;
console.log(joao | joao); // Resultado: 1 = true;
console.log(manu | manu); // Resultado: 0 = false;

// Observação, fora as condicionais de bit, em booleano, | também irá retornar o mesmo que ||, sendo necessário pelo menos um dos valores ser verdadeiro.

---------------------------------------

## • ! e !!
O operador de negação, na minha opinião, é mais simples de ser usado.
Ele irá transformar o que é true, em false, e o que é false, em true.
Também podendo com: !! (dupla negação) transformar algo que é true, em true, ou algo que é false, em false

Exemplos:
const joao = true
const manu = false

console.log(joao) // Resultado: true;
console.log(!joao) // Resultado: false;
console.log(!!joao) // Resultado: true;
console.log(manu) // Resultado: false;
console.log(!manu) // Resultado: true;
console.log(!!manu) // Resultado: false;

---------------------------------------

# • Convenções e Padrões
(Padrões de nomenclatura, convenções e o que são variáveis)

#### Variáveis (O que são ?)
Variáveis são como contêineres ou espaços de armazenamento na programação, usados para guardar e manipular dados. Elas são como "caixas" nomeadas onde você pode guardar diferentes tipos de informações, como números, texto, listas, objetos, entre outros. Imagine uma caixa onde você coloca algo dentro e pode alterar ou trocar seu conteúdo sempre que necessário. As variáveis funcionam de maneira similar na programação. Ao usar variáveis, você dá um nome a um pedaço de memória do computador para referenciar e manipular esses dados. Por exemplo, você pode ter uma variável chamada idade para armazenar a idade de uma pessoa.

Exemplo:

const nome = joao 
const idade = 23

(Assim como já estávamos fazendo anteriormente);
