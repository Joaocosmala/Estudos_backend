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

### Variáveis (O que são ?)
Variáveis são como contêineres ou espaços de armazenamento na programação, usados para guardar e manipular dados. Elas são como "caixas" nomeadas onde você pode guardar diferentes tipos de informações, como números, texto, listas, objetos, entre outros. Imagine uma caixa onde você coloca algo dentro e pode alterar ou trocar seu conteúdo sempre que necessário. As variáveis funcionam de maneira similar na programação. Ao usar variáveis, você dá um nome a um pedaço de memória do computador para referenciar e manipular esses dados. Por exemplo, você pode ter uma variável chamada idade para armazenar a idade de uma pessoa.

Exemplo:

const nome = joao 
const idade = 23

(Assim como já estávamos fazendo anteriormente);

---------------------------------------

### Convenções de nomes de variáveis

NOME_VARIAVEL = valores que servem de referência
Este tipo de nomenclatura de variável serve para armazenarmos valores que teremos como padrões em nossa aplicação.

Exemplo:
Você tem uma aplicação de contas a pagar aonde este retona para você cálculos de tudo que entrou naquele mês a pagar e em todos os cálulos é adicionado 2% de imposto.
Estes 2% de imposto seria uma variável global, aonde o tipo de nomenclatura é seguido por: NOME_VARIAVEL

Fora este tópico, como padrão para todas as outras variáveis temos apenas que seguir as regras de nunca dar espaço, até porque o JavaScript não irá permitir uma variável de nome (Joao Guilherme), por exemplo, e também não colocar números, caractéres especiais ou começar com a minha letra maiúscula. (A primeira letra de qualquer variável deve ser sempre minúscula)

Exemplo:
nomeDaMinhaVariavel = Padrão para qualquer nome de variável.

---------------------------------------

### Palavras reservadas que não podem ser utilizadas em nome de variáveis
Palavras reservadas em JavaScript são termos que têm significados específicos dentro da linguagem e são utilizados para várias finalidades, como declaração de variáveis, definição de estruturas de controle (como loops e condicionais), definição de funções, entre outros. Essas palavras têm funções pré-definidas na linguagem e não podem ser usadas para outros propósitos, como nomear variáveis, funções ou classes. Por exemplo, palavras reservadas como if, else, for, while, function, var, let, const, entre outras, são usadas para definir a estrutura do código, e tentar utilizá-las como nomes de variáveis resultaria em erros no código JavaScript.

Mais exemplos de palavras reservadas:
break, case, catch, class, const, continue, debugger, default, delete, do, else, enum, export, extends, false, finally, for, function, if, implements, import, in, instanceof, interface, let, new, null, package, private, protected, public, return, static, super, switch, this, throw, true, try, typeof, var, void, while, with, yield

---------------------------------------

### Diferenças entre Undefined e Null

##### • undefined:
É um valor primitivo que indica que uma variável foi declarada, mas ainda não foi atribuída com um valor.
Quando você declara uma variável e não a inicializa, seu valor padrão é undefined. Ou seja, quando é esperado um valor, porém, ele não existe.
Também é o valor retornado por uma função que não tem uma declaração return explícita ou por acessar propriedades inexistentes em um objeto.

##### • null:
Já o null é um valor especial que representa a ausência intencional de um valor ou a falta de um valor válido.
Quando uma variável é declarada, mas nenhum valor é atribuído a ela, seu valor padrão é undefined. No entanto, quando você define explicitamente uma variável como null, está indicando que essa variável não possui nenhum valor ou referência a um objeto.

Exemplos:
let exemploUndefined;
console.log(exemploUndefined); // Resultado: undefined

let exemploNull = null;
console.log(exemploNull); // Resultado: null

---------------------------------------

### O que é um NaN? (not-a-number)
O NaN é uma abreviação de "Not-a-Number", que em português significa "Não é um número".
Em JavaScript, NaN é um valor especial que representa um resultado de operação matemática inválida ou indefinida. Da qual por alguma questão lógica não pôde ser executada como deveria.

Esse valor é retornado quando ocorrem operações aritméticas que não conseguem gerar um número válido.
Por exemplo, dividir zero por zero ou realizar operações matemáticas com valores que não são números resultará em NaN.

Exemplo:
O NaN é uma abreviação de "Not-a-Number", que em português significa "Não é um número".
Em JavaScript, NaN é um valor especial que representa um resultado de operação matemática inválida ou indefinida. Da qual por alguma questão lógica não pôde ser executada como deveria.

Esse valor é retornado quando ocorrem operações aritméticas que não conseguem gerar um número válido.
Por exemplo, dividir zero por zero ou realizar operações matemáticas com valores que não são números resultará em NaN.

console.log("joao" * 5); // Resultado: NaN
Isso ocorre porque "joao" é uma string somente, aonde não tem um valor atribuido, ou seja, "joao" não é um number

porém caso atribuirmos um valor a joao dentro de uma variável, isso fica possível
Exemplo funcional:

const joao = 10;
console.log(joao * 5); // Resultado: 50

PARTICULARIDADE DO JAVASCRIPT
JavaScript permite para nós termos um número entre aspas, ou seja, strings, e ainda assim conseguir identificar este como número para concluirmos a operação.
Exemplo de particulatidade:

console.log("10" / 2); // Resultado: 5
console.log("20" / 2); // Resultado: 10

Porém, caso coloquemos uma letra dentro das aspas, mesmo que ainda haja um número, não irá funcionar e retornará: NaN
Exemplo:
console.log("20w" * 5);

Outro ponto importante: Caso utilizarmos um número em strings " " e um número para fazer alguma operação, se fizermos uma soma utilizando + o JavaScript não irá consider
a soma, e sim apenas adicionar o número em strings em frente ao número real
Exemplo:

console.log("20" + 5); // Resultado: 205

---------------------------------------

# • Estruturas Condicionais

### Blocos de código
Para entendermos as estruturas condicionais, primeiro precisamos entender o que são os blocos de código.
Blocos de códigos são definidos por todo ou qualquer código que esteja dentro de chaves { }
Exemplo:
{
// isso é um bloco de código
// tudo que estiver dentro de abertura e fechamento de chaves
// é bem simples
}

---------------------------------------

### IF, ELSE, ELSE IF
Literal para o português: (se, senão, senão se)
Estruturas de controle são definidas por condições, a partir de medidas ou caminhos que precisamos tomar enquanto estamos codificando.
Exemplo:
Preciso que meu código faça x coisa, porém, caso aconteça y coisa, quero que ocorra z coisa. Se não, quero que retorne x coisa. Endenteu? São condições que precisamos atribuir com ações.
Essas condições também são baseadas como true ou false, por exemplo, quando determinada ação for true, faça x, quando for false, faça y.
O caminho para isso seria algo semelhante a isso aqui: Start -> Condição (true ou false) if true -> ação1 -> end, (if false) -> ação2 -> end.
![image](https://github.com/Joaocosmala/Estudos_backend/assets/78692465/ae8562ef-a625-4b53-bf82-eeab3e0091e6)

Exemplo:
let resultado;
const numero = 10;

if (numero >= 0 && numero < 9) {
resultado = "Número maior ou igual a 0 e menor que 9";
} else if (numero >= 10 && numero < 33) {
resultado = "Número maior ou igual a 10 e menor do que 33";
} else {
resultado = "Número maior do que 32";
};

console.log(resultado);

---------------------------------------

### Variáveis -> ESCOPOS
Este aqui é o que já aprendemos sobre variáveis anteriormente
-> Variáveis
Variáveis são maneiras de armazenarmos informações para que possamos usar novamente no futuro

var nome1 = "João";
let nome2 = "Manu";
const nome3 = "Shake"

// Porém, devemos entender agora o que é um escopo global, local ou em bloco/block.

// Vamos pegar de referência os seguintes códigos:
// Código 1:
const media = 10;
if (media > 9) {
    var resultado = "TESTE OK";
}
console.log(resultado); // Resultado: TESTE OK. (está correto!) -> var;

console.log("========================");

/*
// Porém, se:
// Código 2:
const mediaDois = 10;
if (mediaDois > 9) {
    let resultadoUm = "TESTE OK";
}
console.log(resultadoUm); // Resultado: Retornará erro, resultadoUm is not defined -> let;
// Isso acontece porque resultadoUm está dentro do bloco de código. A variável existe, mas seu valor nunca foi utilizado.

console.log("========================");

// E isso também acontece quando usamos const
// Código 3:
const mediaTres = 10;
if (mediaTres > 9) {
    const resultadoDois = "TESTE OK";
}
console.log(resultadoDois); // Resultado: Retornará erro, resultadoDois is not defined -> const;
// Isso acontece porque resultadoUm está dentro do bloco de código. A variável existe, mas seu valor nunca foi utilizado.

Então para conseguirmos ter o resultado que buscamos mostrado na tela, precisamos colocar nosso console.log(); dentro do nosso bloco aonde está a variável que buscamos. */

const mediaQuatro = 10;
if (mediaQuatro > 9) {
    const resultadoTres = "TESTE OK";
    console.log(resultadoTres); // Agora está tudo dentro do mesmo bloco!!
};

![image](https://github.com/Joaocosmala/Estudos_backend/assets/78692465/5df7886d-1696-4c5a-ad42-90af6aad2041)

Analisando está imagem podemos ver que:
Em programação, o escopo se refere à visibilidade e acessibilidade de variáveis em diferentes partes do código.
Em JavaScript, existem três tipos principais de escopo: global, local e de bloco.
Cada tipo determina onde as variáveis podem ser acessadas e utilizadas.

1: No escopo global, as variáveis são declaradas fora de qualquer função.
Isso significa que elas podem ser acessadas de qualquer lugar do código, seja dentro ou fora de funções.
Variáveis globais são acessíveis em todo o programa.

2: No escopo local, as variáveis são declaradas dentro de uma função.
Elas só podem ser acessadas dentro dessa função específica.
Variáveis locais existem apenas dentro do contexto em que são definidas, e não podem ser acessadas fora desse contexto.

3: O escopo de bloco foi introduzido com a introdução do let e const.
Variáveis declaradas com let e const têm escopo de bloco, o que significa que elas são visíveis apenas dentro do bloco de código em que são definidas.

---------------------------------------

### Truthy e Falsy
Em JavaScript, os conceitos de "truthy" e "falsy" se referem à forma como os valores são avaliados em contextos booleanos, como em estruturas condicionais (if, while, &&, ||, entre outros).

JavaScript reconhece todos os valores como verdadeiros em uma estrutura de condição, menos:
• False
• 0
• -0
• 0m
• "" ou " ou ``
• null
• undefined
• NaN

Truthy: São valores que são considerados como verdadeiros quando avaliados em um contexto booleano.
Isso não significa que sejam estritamente iguais a true, mas são interpretados como verdadeiros.
Alguns exemplos de valores truthy são: true, números diferentes de zero (1, 2.5, -1), strings não vazias ("hello"), arrays e objetos não vazios, e até mesmo certos objetos vazios que são considerados truthy.

#### • Exemplos de valores truthy:
if ("hello") {
    // Este bloco será executado, pois a string "hello" é truthy
}

Falsy: São estes valores que são considerados como falsos em um contexto booleano.
Assim como com "truthy", isso não significa que sejam estritamente iguais a false, mas são interpretados como falsos.
Alguns exemplos de valores falsy são: false, 0, null, undefined, NaN, strings vazias (""), null e undefined.

#### • Exemplos de valores Falsy:
if (0) {
    // Este bloco NÃO será executado, pois o valor 0 é falsy
}

É importantíssimo entender estes conceitos quando trabalhar com condicionais em JavaScript, pois às vezes valores inesperados podem ser avaliados como verdadeiros ou falsos.
O que pode afetar a lógica do programa. O conhecimento sobre valores truthy e falsy é útil para escrever código mais conciso e compreensível.


Outros exemplos:

if (true) {
    console.log("true é truthy");
}; // Resultado: true é truthy


if ("testando qualquer coisa") {
    console.log("testando qualquer coisa é truthy");
}; // Resultado: testando qualquer coisa é truthy


if ("") {
    console.log("Aspas duplas vazias é truthy");

} else {
    console.log("Aspas duplas vazias é falsy");
    
} // Resultado: Aspas duplas vazias é falsy


if (0) {
    console.log("0 é truthy");
    
} else {
    console.log("0 é falsy");
    
} // Resultado: 0 é falsy


if (-0) {
    console.log("0 é truthy");

} else {
    console.log("0 é falsy");
    
} // Resultado: -0 é falsy

// ----------------------------------------------------------------------------------------------------------------------------------------

let alistamento;
if (alistamento) {

    console.log("Este rapaz se alistou no exército");
    
} else {

    console.log("Este rapaz ainda não se alistou no exército");
    
} // Resultado: Falsy, porque let alistamento é undefined;
