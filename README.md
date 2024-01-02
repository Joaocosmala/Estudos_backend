# • JavaScript Completo, ou quase... 😎🤯

---------------------------------------

# • Operadores Matemáticos
### Somar
1 + 1 = 2 <br>
10 + 10 = 20 <br>

Exemplo: <br>
`console.log(1 + 10) = 11` <br>
Ou <br>
`console.log("O valor da soma é: ", 20 + 20) = 40` <br>

Mais exemplos: <br>

`const numero1 = 10;` <br>
`const numero2 = 40;` <br>
`const soma = numero1 + numero2;` <br>
`console.log("O Valor da soma é: ", soma);` <br>
`Resultado: O Valor da soma é: 50` <br>

### Subtrair
`const numero1 = 10;` <br>
`const numero2 = 40;` <br>
`const sub = numero1 - numero2;` <br>
`console.log("O Valor da subtração é: ", sub);` <br>
`Resultado: O Valor da subtração é: -30` <br>

### Dividir
`const numero1 = 10;` <br>
`const numero2 = 40;` <br>
`const div = numero1 / numero2;` <br>
`console.log("O Valor da divisão é: ", div);` <br>
`Resultado: O Valor da divisão é: 0.25` <br>

### Multiplicação
`const numero1 = 10;` <br>
`const numero2 = 40;` <br>
`const multi = numero1 * numero2;` <br>
`console.log("O Valor da multiplicação é: ", multi);` <br>
`Resultado: O Valor da multiplicação é: 400` <br>

---------------------------------------

# • Strings e Concatenação

### Strings
Strings são: letras, números, caractéres diversos e textos <br>
Identificadas por tipagem string, ou " " <br>

Exemplos: <br>
`console.log("João Cosmala, Web Developer");` = String em " " <br>

Diferenças <br>
`console.log("10");` = string <br>
`console.log(10);` = número <br>

`console.log("10 + 10");` Retorno: 10 + 10 <br>
`console.log(10 + 10);` Retorno: 20 <br>

## Concatenação (mesclar)
Concatenação pode ser dita como: mesclar ou juntar <br>
Se define em mesclar duas coisas diferentes em um aguardando um (1) resultado conjunto destes dois (2). <br>

Exemplo: <br>
`console.log("Meu nome é João e tenho " + 23, "anos");` <br>
Você acabou de concatenar uma string e um número. <br>

Outro meio de fazer isso é usando crases: ("` `") e $ <br>

Exemplo: <br>
Meu nome é joão e minha idade é: ${23} <br>

---------------------------------------

# • Variáveis em JavaScript
Variáveis são maneiras de armazenarmos informações para que possamos usar novamente no futuro <br>
Em JavaScript temos: VAR, LET, CONST <br>

---------------------------------------

#### VAR
Maneira antiga de escrever variáveis. <br>
Perminte que adicionemos um valor nele, e posteriormente, podemos alterar este valor <br>

---------------------------------------

#### LET
Podemos adicionar um valor a ele, podendo também alterar este mesmo valor

---------------------------------------

#### CONST 
Adicionamos um valor e ele é definido como único, sem poder alterar este valor depois. <br>
Sendo está uma variável que só deve conter este determinado valor. <br>

---------------------------------------

Exemplos: <br>
`var nome1 = "João";` <br>
`let nome2 = "João";` <br>
`const nome3 = "João";` <br>

---------------------------------------

# • Números em JavaScript

Em JavaScript, diferente de outras linguagens, quando se tem um número, mesmo que seja impar, par, possua casa decimal e afins, ele não terá o que é conhecido como Float, Double, Integers e etc... Em JavaScript tudo isso é mais simplificado em um único tipo, tipo Number. Ou seja, qualquer coisa que seja um número, será dado como um número. <br>

Exemplos: <br>
`console.log(21 + 10) = 31;` <br>
`console.log(20 + 24.4444) = 44.4444;` <br>
`console.log("10" + 10) = 1010` (??????) -> Isso ocorre porque número em aspas se torna uma string, deixando de ser um number. <br>

Exemplos:  <br>
`console.log(10)` -> numero <br>
`console.log("10")` -> string <br>

Outro fator importante são as casas decimais. Em JavaScript casas decimais são separadas por pontos ( . ), e não por vírgulas ( , ). <br>
console.log(12, 3 + 13 + 3) -> 12, 16, 3 <br>

números também podem ser armazenados em variáveis: <br>
`const idade = 23;` <br>
`console.log(idade);` -> 23 <br>

Resumindo, para trabalhar com números, devemos mante-los fora de strings, senão seram tratados como strings. <br>

---------------------------------------

# • Valores Booleanos

Valores booleanos são true ou false. 0 ou 1. Verdadeiro ou falso. <br>

Exemplo: <br>
`const dormindo = false` <br>
`const acordado = true` <br>

`const comFome = "true"` -> Não é booleano, é string, lembre-se das " " !! <br>

---------------------------------------

# • Operadores
Operadores são conhecidos como: "Operadores Lógicos", do qual são designados por símbolos que definem alguma função, algum ato, algum dever no seu código através da sua lógica. <br>

## Operadores de: Atribuição, adição, subtração;
Alguns exemplos de operadores são: <br>
• 1: = -> Operador de atribuição <br>
• 2: += -> Operador de adição <br>
• 3: -= -> Operador de subtração <br>

Exemplos: <br>
#### Atribuilçao <br>

`let idade;` <br>
`idade = 23;` <br>
`console.log(idade);` Resultado = 23 <br>

`let recebe = 2000;` <br>
`recebe = recebe + 10;` <br>
`console.log("Meu saldo é: ", recebe);` Resultado = 2010 <br>

`recebe += 400;` <br>
`console.log("Meu saldo é: ", recebe);` Resultado = 2410 <br>

`recebe = recebe - 200;` <br>
`console.log("Meu saldo é: ", recebe);` Resultado = 2210 <br>

`recebe -= 200;` <br>
`console.log("Meu saldo é: ", recebe);` Resultado = 2010 <br>

## Operadores de: Comparação;
Operadores de comparação sempre iram retornar true ou false no console.log; <br>

Alguns exemplos de operadores de comparação são: <br>
• 1: == -> Igual <br>
• 2: != -> Diferente <br>
• 3: === -> Estritamente igual <br>
• 4: !== -> Estritamente diferente <br>
• 5: > -> Maior que <br>
• 6: < -> Menor que <br>
• 7: >= Maior ou igual que <br>
• 8: <= Menor ou igual que <br>

Exemplos: <br>

## Operador de = (igual):
`console.log("20 == 20: ", 20 == 20);`
= Resultado = true; 20 é igual a 20 então: true;
`console.log("21 == 20: ", 20 == 20);`
= Resultado = false; 21 não é igual a 20 então: false;
<br>
`console.log("21 == 21: ", 21 == 21);` <br>
= Resultado = true; 21 é igual a 21 então: true;
<br>

---------------------------------------

## Operador de != (Diferente):
`console.log("20 != 20: ", 20 != 20);` 
= Resultado = false; 20 não é diferente de 20 então: false;
<br>
`console.log("21 != 20: ", 21 != 20);`
= Resultado = true; 21 é diferente de 20 então: true;
<br>
`console.log("21 != 21: ", 21 != 21);`
= Resultado = false; 21 não é diferente de 21 então: false;
<br>

---------------------------------------

## Operador de === (Estritamente igual):
`console.log("20 === 20: ", 20 === 20);`
= Resultado = true; 20 é estritamente igual a 20 então: true;
<br>
`console.log("21 === 21: ", "21" === 21);`
= Resultado = false; "21" não é estritamente igual a 21 então: false; <br>
Aqui vemos que === identificada "21" diferente de 20 pois 21 está em " " aspas, o deixando em string, logo, "21" não é estritamente igual a 21 porque "21" é uma string e 21 é um número. <br>
<br>
`console.log("21 === 21: ", 21 === 21);`
= Resultado = true; 21 é estritamente igual a 21 então: true;
<br>

---------------------------------------

## Operador de !== (Estritamente Diferente):
`console.log("20 !== 20: ", 20 !== 20);`
= Resultado = false; 20 não é estritamente diferente de 20 então: false;
<br>
`console.log("21 !== 20: ", 21 !== 20);`
= Resultado = true; 21 é estritamente diferente de 20 então: true;
<br>
`console.log("21 !== 21: ", 21 !== 21);`
= Resultado = false; 21 não é estritamente diferente de 21 então: false;
<br>

---------------------------------------

## Operador de > (Maior que):
`console.log("20 é maior que 20? ", 20 > 20);`
= Resultado = false; 20 não é maior que 20 então: false;
<br>
`console.log("21 é maior que 20? ", 21 > 20);`
= Resultado = true; 21 é maior que 20 então: true;
<br>
`console.log("21 é maior que 21? ", 21 > 21);`
= Resultado = false; 21 não é maior que 21 então: false;
<br>

---------------------------------------

## Operador de < (Menor que):
`console.log("20 é menor que 20? ", 20 < 20);`
= Resultado = false; 20 não é menor que 20 então: false;
<br>
`console.log("21 é menor que 20? ", 21 < 20);`
= Resultado = false; 21 não é menor que 20 então: false;
<br>
`console.log("21 é menor que 21? ", 21 < 21);`
= Resultado = false; 21 não é menor que 20 então: false;
<br>
`console.log("12 é menor que 20? ", 12 < 20);`
= Resultado = true; 12 é menor que 20 então: true;
<br>

---------------------------------------

## Operador de >= (Maior ou igual que):
`console.log("20 é maior ou igual que 20? ", 20 >= 20);`
= Resultado = true; 20 é maior ou igual a 20 então: true;
<br>
`console.log("21 é maior ou igual que 20? ", 21 >= 20);`
= Resultado = true; 21 é maior ou igual a 20 então: true;
<br>
`console.log("12 é maior ou igual que 20? ", 12 >= 20);`
= Resultado = false; 12 não é maior ou igual a 20 então: false;
<br>

---------------------------------------

## Operador de <= (Menor ou igual que):
`console.log("20 é menor ou igual que 20? ", 20 <= 20);`
= Resultado = true; 20 é menor ou igual a 20 então: true;
<br>
`console.log("21 é menor ou igual que 20? ", 21 <= 20);`
= Resultado = true; 21 não é menor ou igual a 20 então: false;
<br>
`console.log("12 é menor ou igual que 20? ", 12 <= 20);`
= Resultado = false; 12 não é menor ou igual a 20 então: true;
<br>

---------------------------------------

# • Operadores Lógicos;
Operadores lógicos são operadores que assim como os anteriores, também determinam uma função. Assim como em Lógica Aplicada, opedadores lógicos são usados para determinar: E, OU, OUOU, NEGAÇÃO e etc... <br>

Aqui temos como principais: <br>
• -> && -> E -> and lógico <br>
• -> || -> OU -> or lógico <br>
• -> ! -> NEGAÇÃO -> negação lógica <br>

## &&
• Para que retorne um verdadeiro (true), as duas condições precisam ser verdadeiras <br>
Exemplo: <br>
• true && true = true; <br>
• false && false = true; <br>
• true && false = false; <br>
• false && true = false; <br>

TRUE <br>
`const nome = "joao";` <br>
`const idade = 23;` <br>
`console.log(nome === "joao" && idade === 23);` <br>
`Resultado: true; nome é === estritamente igual a "joao" && (E) idade também é estritamente igual a 23;` <br>

FALSE <br>
`const nome = "joao";` <br>
`const idade = 23;` <br>
`console.log(nome === "joao" && idade === 20);` <br>
`Resultado: false; nome é === estritamente igual a "joao" && (E) idade não é estritamente igual a 23;` <br>

TRUE <br>
`console.log("23 >= 23 && 70 >= 70: ", 23 >= 23 && 70 >= 70);` <br>
`Resultado: true; Porque 23 é maior ou igual a 23 e 70 é maior ou igual a 70;` <br>

---------------------------------------

## || e |
• || -> Para que retorne um verdadeiro (true), uma das condições deve ser verdadeira <br>

Exemplo ||: <br>
• true || true = true; <br>
• false || false = false; <br>
• true || false = true; <br>
• false || true = true; <br>

`const joao = true;` <br>
`const manu = false;` <br>

`console.log(joao || manu);` Resultado: `true` <br>
`console.log(manu || joao);` Resultado: `true` <br>
`console.log(joao || joao);` Resultado: `true` <br>
`console.log(manu || manu);` Resultado: `false` <br>

Mais exemplos: <br>
(Aqui resolvi dar um exemplo mais avançado pois ele se adequa melhor a questão de como costuma ser mais utilizado esse contexto das Pipes) <br>

Observação:
Levando em consideração o mercado de trabalho, muitas vezez precisamos determinar e comparar valores para as nossas funções através de 0 e 1 <br>

---------------------------------------

• Situação 1: Resultado true <br>

Aqui temos um objeto com o nome de sexualidade que nos trás dois valores BOOLEANOS, verdadeiro para masculino e falso para feminino <br>
`const sexualidade = {` <br>
    `masculino: true,` <br>
    `feminino: false,` <br>
`};` <br>

Denominei duas variáveis, uma com o nome de joao, e outra com o nome de manu. <br>
joao é masculino, logo, é verdadeiro <br>
manu é feminino, logo, é falso <br>
`const joao = sexualidade.masculino;` = `true` <br>
`const manu = sexualidade.feminino;` = `false` <br>

E para nos mostrar o resultado no terminal temos mais um console.log com o Operador Lógico de || para identificar valores 0 e 1 / verdadeiro e falso. <br>
`console.log(joao || manu);` Resultado: true; Porque João é verdadeiro; <br>

---------------------------------------

• Situação 2: Resultado true <br>

`const joao = sexualidade.feminino;` = `false` <br>
`const manu = sexualidade.masculino;` = `true` <br>

`console.log(joao || manu);` Resultado: true; Porque Manu é verdadeiro; <br>

---------------------------------------

• Situação 3: Resultado false <br>

`const joao = sexualidade.feminino;` = `false` <br>
`const manu = sexualidade.feminino;` = `false` <br>

`console.log(joao || manu);` Resultado: false; Porque João e Manu são falsos; <br>

---------------------------------------

• Situação 4: Resultado true <br>

`const joao = sexualidade.feminino;` = `true` <br>
`const manu = sexualidade.masculino;` = `true` <br>

`console.log(joao || manu);` Resultado: true; Porque Joao e Manu são verdadeiros; <br>

---------------------------------------

## • | (BitWise)
Agora iremos mudar um pouco sobre oq aprendemos de true ou false em || e considerar manipular bits com | (bitwise) <br>
O operador | é usado como um manipulador de bits. Se tratarmos variáveis booleanas (true or false) com |, ele irá nos retornar 1 ou 0; <br>
Porém, também pode ser usado para realizar operações lógicas. No entanto, ao contrário do ||, o | opera nos bits individuais dos números. <br>
Normalmente é usado em situações onde a manipulação de bits é necessária. <br>

Exemplo: <br>
`let x = 5;` Em binário: 0101; <br>
`let y = 3;` Em binário: 0011; <br>
`let result = x | y;` Resultado: 7 (binário: 0111); <br>

OU <br>

Se tivermos valores booleanos novamente, receberemos 0 ou 1 como resposta ao invés de true ou false. <br>

`const joao = true;` <br>
`const manu = false;` <br>

`console.log(joao | manu);` Resultado: `1 = true;` <br>
`console.log(manu | joao);` Resultado: `1 = true;` <br>
`console.log(joao | joao);` Resultado: `1 = true;` <br>
`console.log(manu | manu);` Resultado: `0 = false;` <br>

Observação, fora as condicionais de bit, em booleano, | também irá retornar o mesmo que ||, sendo necessário pelo menos um dos valores ser verdadeiro. <br>

---------------------------------------

## • ! e !!
O operador de negação, na minha opinião, é mais simples de ser usado. <br>
Ele irá transformar o que é true, em false, e o que é false, em true. <br> 
Também podendo com: !! (dupla negação) transformar algo que é true, em true, ou algo que é false, em false <br>

Exemplos: <br>
`const joao = true` <br>
`const manu = false` <br>
<br>
`console.log(joao);` Resultado: `true;` <br>
`console.log(!joao);` Resultado: `false;` <br>
`console.log(!!joao);` Resultado: `true;` <br>
`console.log(manu);` Resultado: `false;` <br>
`console.log(!manu);` Resultado: `true;` <br>
`console.log(!!manu);` Resultado: `false;` <br>

---------------------------------------

# • Convenções e Padrões
(Padrões de nomenclatura, convenções e o que são variáveis)
<br>
### Variáveis (O que são ?)
Variáveis são como contêineres ou espaços de armazenamento na programação, usados para guardar e manipular dados. Elas são como "caixas" nomeadas onde você pode guardar diferentes tipos de informações, como números, texto, listas, objetos, entre outros. Imagine uma caixa onde você coloca algo dentro e pode alterar ou trocar seu conteúdo sempre que necessário. As variáveis funcionam de maneira similar na programação. Ao usar variáveis, você dá um nome a um pedaço de memória do computador para referenciar e manipular esses dados. Por exemplo, você pode ter uma variável chamada idade para armazenar a idade de uma pessoa.

Exemplo: <br>
`const nome = joao` <br>
`const idade = 23` <br>

(Assim como já estávamos fazendo anteriormente); <br>

---------------------------------------

### Convenções de nomes de variáveis

NOME_VARIAVEL = valores que servem de referência <br>
Este tipo de nomenclatura de variável serve para armazenarmos valores que teremos como padrões em nossa aplicação. <br>

Exemplo: <br>
Você tem uma aplicação de contas a pagar aonde este retona para você cálculos de tudo que entrou naquele mês a pagar e em todos os cálulos é adicionado 2% de imposto.
Estes 2% de imposto seria uma variável global, aonde o tipo de nomenclatura é seguido por: NOME_VARIAVEL
<br>
Fora este tópico, como padrão para todas as outras variáveis temos apenas que seguir as regras de nunca dar espaço, até porque o JavaScript não irá permitir uma variável de nome (Joao Guilherme), por exemplo, e também não colocar números, caractéres especiais ou começar com a minha letra maiúscula. (A primeira letra de qualquer variável deve ser sempre minúscula)
<br>
Exemplo: <br>
nomeDaMinhaVariavel = Padrão para qualquer nome de variável. <br>

---------------------------------------

### Palavras reservadas que não podem ser utilizadas em nome de variáveis
Palavras reservadas em JavaScript são termos que têm significados específicos dentro da linguagem e são utilizados para várias finalidades, como declaração de variáveis, definição de estruturas de controle (como loops e condicionais), definição de funções, entre outros. Essas palavras têm funções pré-definidas na linguagem e não podem ser usadas para outros propósitos, como nomear variáveis, funções ou classes. Por exemplo, palavras reservadas como if, else, for, while, function, var, let, const, entre outras, são usadas para definir a estrutura do código, e tentar utilizá-las como nomes de variáveis resultaria em erros no código JavaScript.
<br>
Mais exemplos de palavras reservadas: <br>
break, case, catch, class, const, continue, debugger, default, delete, do, else, enum, export, extends, false, finally, for, function, if, implements, import, in, instanceof, interface, let, new, null, package, private, protected, public, return, static, super, switch, this, throw, true, try, typeof, var, void, while, with, yield

---------------------------------------

### Diferenças entre Undefined e Null

##### • undefined:
É um valor primitivo que indica que uma variável foi declarada, mas ainda não foi atribuída com um valor.
Quando você declara uma variável e não a inicializa, seu valor padrão é undefined. Ou seja, quando é esperado um valor, porém, ele não existe. <br>
Também é o valor retornado por uma função que não tem uma declaração return explícita ou por acessar propriedades inexistentes em um objeto. <br>

##### • null:
Já o null é um valor especial que representa a ausência intencional de um valor ou a falta de um valor válido. <br>
Quando uma variável é declarada, mas nenhum valor é atribuído a ela, seu valor padrão é undefined. No entanto, quando você define explicitamente uma variável como null, está indicando que essa variável não possui nenhum valor ou referência a um objeto. <br>
<br>
Exemplos: <br>
`let exemploUndefined;` <br>
`console.log(exemploUndefined);` Resultado: `undefined` <br>

`let exemploNull = null;` <br>
`console.log(exemploNull);` Resultado: `null` <br>

---------------------------------------

### O que é um NaN? (not-a-number)
O NaN é uma abreviação de "Not-a-Number", que em português significa "Não é um número". <br>
Em JavaScript, NaN é um valor especial que representa um resultado de operação matemática inválida ou indefinida. Da qual por alguma questão lógica não pôde ser executada como deveria. <br>

Esse valor é retornado quando ocorrem operações aritméticas que não conseguem gerar um número válido. <br>
Por exemplo, dividir zero por zero ou realizar operações matemáticas com valores que não são números resultará em NaN. <br>

Exemplo: <br>
O NaN é uma abreviação de "Not-a-Number", que em português significa "Não é um número". <br>
Em JavaScript, NaN é um valor especial que representa um resultado de operação matemática inválida ou indefinida. Da qual por alguma questão lógica não pôde ser executada como deveria. <br>

Esse valor é retornado quando ocorrem operações aritméticas que não conseguem gerar um número válido. <br>
Por exemplo, dividir zero por zero ou realizar operações matemáticas com valores que não são números resultará em NaN. <br>

console.log("joao" * 5); // Resultado: NaN <br>
Isso ocorre porque "joao" é uma string somente, aonde não tem um valor atribuido, ou seja, "joao" não é um number <br>
<br>
porém caso atribuirmos um valor a joao dentro de uma variável, isso fica possível <br>
<br>
Exemplo funcional: <br>
<br>
const joao = 10; <br>
console.log(joao * 5); // Resultado: 50 <br>

PARTICULARIDADE DO JAVASCRIPT <br>
JavaScript permite para nós termos um número entre aspas, ou seja, strings, e ainda assim conseguir identificar este como número para concluirmos a operação. <br>
Exemplo de particulatidade: <br>

`console.log("10" / 2);` Resultado: 5 <br>
`console.log("20" / 2);` Resultado: 10 <br>

Porém, caso coloquemos uma letra dentro das aspas, mesmo que ainda haja um número, não irá funcionar e retornará: NaN <br>
Exemplo: <br>
`console.log("20w" * 5);` <br>

Outro ponto importante: Caso utilizarmos um número em strings " " e um número para fazer alguma operação, se fizermos uma soma utilizando + o JavaScript não irá consider <br>
a soma, e sim apenas adicionar o número em strings em frente ao número real <br>
Exemplo: <br>

`console.log("20" + 5);` Resultado: 205 <br>

---------------------------------------

# • Estruturas Condicionais

### Blocos de código
Para entendermos as estruturas condicionais, primeiro precisamos entender o que são os blocos de código.
Blocos de códigos são definidos por todo ou qualquer código que esteja dentro de chaves { }
<br>
Exemplo: <br>
`{` <br>
isso é um bloco de código <br>
tudo que estiver dentro de abertura e fechamento de chaves <br>
é bem simples <br>
`}` <br>

---------------------------------------

### IF, ELSE, ELSE IF
Literal para o português: (se, senão, senão se) <br>
Estruturas de controle são definidas por condições, a partir de medidas ou caminhos que precisamos tomar enquanto estamos codificando. <br>

Exemplo: <br>
Preciso que meu código faça x coisa, porém, caso aconteça y coisa, quero que ocorra z coisa. Se não, quero que retorne x coisa. Endenteu? São condições que precisamos atribuir com ações. <br>
Essas condições também são baseadas como true ou false, por exemplo, quando determinada ação for true, faça x, quando for false, faça y. <br>
O caminho para isso seria algo semelhante a isso aqui: Start -> Condição (true ou false) if true -> ação1 -> end, (if false) -> ação2 -> end. <br>

<table>
    <tr>
        <td> TEST EXPRESSION </td>
        <td> -----> </td>
        <td> TRUE </td>
        <td> -----> </td>
        <td> BODY OF IF </td>
        <td> -----> </td>
        <td> STATEMENT JUST BELOW IF </td>
    </tr>
    <tr>
        <td> TEST EXPRESSION </td>
        <td> -----> </td>
        <td> FALSE </td>
        <td> -----> </td>
        <td> ____________ </td>
        <td> -----> </td>
        <td> STATEMENT JUST BELOW IF </td>
    </tr>
</table>

Exemplo: <br>
`let resultado;` <br>
`const numero = 10;` <br>

`if (numero >= 0 && numero < 9) {` <br>
`resultado = "Número maior ou igual a 0 e menor que 9";` <br>
`} else if (numero >= 10 && numero < 33) {` <br>
`resultado = "Número maior ou igual a 10 e menor do que 33";` <br>
`} else {` <br>
`resultado = "Número maior do que 32";` <br>
`};` <br>
`console.log(resultado);`

---------------------------------------

### Variáveis -> ESCOPOS
Este aqui é o que já aprendemos sobre variáveis anteriormente <br>
-> Variáveis <br>
Variáveis são maneiras de armazenarmos informações para que possamos usar novamente no futuro <br>

`var nome1 = "João"` <br>
`let nome2 = "Manu"` <br>
`const nome3 = "Shake"` <br>

Porém, devemos entender agora o que é um escopo global, local ou em bloco/block.
<br>
Vamos pegar de referência os seguintes códigos: <br>
Código 1:
<br>

`const media = 10;` <br>
`if (media > 9) {` <br>
    `var resultado = "TESTE OK";` <br>
`}` <br>
`console.log(resultado);` Resultado: TESTE OK. (está correto!) -> var;
<br>
Porém, se: <br>
Código 2: <br>

`const mediaDois = 10;` <br>
`if (mediaDois > 9) {` <br>
    `let resultadoUm = "TESTE OK";` <br>
`}` <br>
`console.log(resultadoUm);` Resultado: Retornará erro, resultadoUm is not defined -> let;
<br>

Isso acontece porque resultadoUm está dentro do bloco de código. A variável existe, mas seu valor nunca foi utilizado.
<br>

E isso também acontece quando usamos const <br>
Código 3: <br>

`const mediaTres = 10;` <br>
`if (mediaTres > 9) {` <br>
    `const resultadoDois = "TESTE OK";` <br>
`}`
`console.log(resultadoDois);` Resultado: Retornará erro, resultadoDois is not defined -> const; <br>

Isso acontece porque resultadoUm está dentro do bloco de código. A variável existe, mas seu valor nunca foi utilizado.
Então para conseguirmos ter o resultado que buscamos mostrado na tela, precisamos colocar nosso console.log(); dentro do nosso bloco aonde está a variável que buscamos.

`const mediaQuatro = 10;` <br>
`if (mediaQuatro > 9) {` <br>
    `const resultadoTres = "TESTE OK";` <br>
    `console.log(resultadoTres);` Agora está tudo dentro do mesmo bloco!! <br>
`};`
<br>
<table>
    <tr>
        <td> </td>
        <td>
            VAR
        </td>
        <td>
            CONST
        </td>
        <td>
            LET
        </td>
    </tr>
    <tr>
        <td>
            SCOPE
        </td>
        <td>
            GLOBAL OR LOCAL
        </td>
        <td>
            BLOCK
        </td>
        <td>
            BLOCK
        </td>
    </tr>
    <tr>
        <td>
            REDECLARE?
        </td>
        <td>
            YES
        </td>
        <td>
            NO
        </td>
        <td>
            NO
        </td>
    </tr>
    <tr>
        <td>
            REASSIGN?
        </td>
        <td>
            YES
        </td>
        <td>
            NO
        </td>
        <td>
            YES
        </td>
    </tr>
    <tr>
        <td>
            HOISTED?
        </td>
        <td>
            YES
        </td>
        <td>
            NO
        </td>
        <td>
            NO
        </td>
    </tr>
</table>
<br>
Analisando está imagem podemos ver que:
Em programação, o escopo se refere à visibilidade e acessibilidade de variáveis em diferentes partes do código.
Em JavaScript, existem três tipos principais de escopo: global, local e de bloco.
Cada tipo determina onde as variáveis podem ser acessadas e utilizadas.
<br>
1: No escopo global, as variáveis são declaradas fora de qualquer função.
Isso significa que elas podem ser acessadas de qualquer lugar do código, seja dentro ou fora de funções.
Variáveis globais são acessíveis em todo o programa.
<br>
2: No escopo local, as variáveis são declaradas dentro de uma função.
Elas só podem ser acessadas dentro dessa função específica.
Variáveis locais existem apenas dentro do contexto em que são definidas, e não podem ser acessadas fora desse contexto.
<br>
3: O escopo de bloco foi introduzido com a introdução do let e const.
Variáveis declaradas com let e const têm escopo de bloco, o que significa que elas são visíveis apenas dentro do bloco de código em que são definidas.

---------------------------------------

### Truthy e Falsy
Em JavaScript, os conceitos de "truthy" e "falsy" se referem à forma como os valores são avaliados em contextos booleanos, como em estruturas condicionais (if, while, &&, ||, entre outros).

JavaScript reconhece todos os valores como verdadeiros em uma estrutura de condição, menos: <br>
• False <br>
• 0 <br>
• -0 <br>
• 0m <br>
• "" ou " ou `` <br>
• null <br>
• undefined <br>
• NaN <br>

Truthy: São valores que são considerados como verdadeiros quando avaliados em um contexto booleano.
Isso não significa que sejam estritamente iguais a true, mas são interpretados como verdadeiros.
Alguns exemplos de valores truthy são: true, números diferentes de zero (1, 2.5, -1), strings não vazias ("hello"), arrays e objetos não vazios, e até mesmo certos objetos vazios que são considerados truthy.

#### Exemplos de valores truthy:
`if ("hello") {` <br>
    `Este bloco será executado, pois a string "hello" é truthy` <br>
`}` <br>

Falsy: São estes valores que são considerados como falsos em um contexto booleano.
Assim como com "truthy", isso não significa que sejam estritamente iguais a false, mas são interpretados como falsos.
Alguns exemplos de valores falsy são: false, 0, null, undefined, NaN, strings vazias (""), null e undefined.

#### Exemplos de valores Falsy:
`if (0) {` <br>
     `Este bloco NÃO será executado, pois o valor 0 é falsy` <br>
`}` <br>

É importantíssimo entender estes conceitos quando trabalhar com condicionais em JavaScript, pois às vezes valores inesperados podem ser avaliados como verdadeiros ou falsos.
O que pode afetar a lógica do programa. O conhecimento sobre valores truthy e falsy é útil para escrever código mais conciso e compreensível.

Outros exemplos:

`if (true) {` <br>
    `console.log("true é truthy");` <br>
`}` <br>
`Resultado: true é truthy`


`if ("testando qualquer coisa") {` <br>
    `console.log("testando qualquer coisa é truthy");` <br>
`}` <br>
`Resultado: testando qualquer coisa é truthy`


`if ("") {` <br>
    `console.log("Aspas duplas vazias é truthy");` <br>
`} else {` <br>
    `console.log("Aspas duplas vazias é falsy");` <br>
`}` <br>
`Resultado: Aspas duplas vazias é falsy`


`if (0) {` <br>
    `console.log("0 é truthy");` <br>
`} else {` <br>
    `console.log("0 é falsy");` <br>
`}` <br>
`Resultado: 0 é falsy`

<br>

`if (-0) {` <br>
    `console.log("0 é truthy");` <br>
`} else {` <br>
    `console.log("0 é falsy");` <br>
`}` <br>
`Resultado: -0 é falsy`


`let alistamento;` <br>
`if (alistamento) {` <br>
    `console.log("Este rapaz se alistou no exército");` <br>
`} else {` <br>
    `console.log("Este rapaz ainda não se alistou no exército");` <br>
`}` <br>
`Resultado: Falsy, porque let alistamento é undefined;`

---------------------------------------

# • Operador Ternário:
Os operadores ternários são uma forma concisa e eficiente de escrever expressões condicionais em JavaScript (e em muitas outras linguagens de programação). Eles permitem que você tome decisões com base em uma condição, tudo em uma única linha. <br>

Em JavaScript, o operador ternário tem a seguinte estrutura: <br>

`condição ? valorSeVerdadeiro : valorSeFalso;` <br>

Condição: Uma expressão que é avaliada como verdadeira ou falsa. <br>
valorSeVerdadeiro: Valor retornado se a condição for verdadeira. <br>
valorSeFalso: Valor retornado se a condição for falsa. <br>

Exemplo: <br>
`let idade = 20;` <br>
`let status = (idade >= 18) ? 'Adulto' : 'Menor';` <br>
`console.log(status);` Saída: 'Adulto' <br>

Neste exemplo se a condição (idade >= 18) for verdadeira, a variável status receberá o valor 'Adulto'; caso contrário, receberá 'Menor'. <br>
Os operadores ternários são úteis em situações em que você precisa atribuir um valor com base em uma condição simples, evitando a necessidade de escrever blocos if...else mais longos. No entanto, o uso excessivo de operadores ternários em expressões complexas pode dificultar a leitura do código, portanto, é importante usar com moderação para manter a clareza e a legibilidade. <br>


Outros exemplos: <br>
`const media = 10;` <br>
`let resultado;` <br>

`if (media >= 7) {` <br>
`resultado = "Aprovado";` <br>
`} else {` <br>
`resultado = "Reprovado";` <br>
`};` <br>
`console.log(resultado);` <br>
`Resultado: Aprovado` <br>

Agora se usarmos o operador ternário para fazer a mesma função, teremos algo semelhante a isso: <br>

`resultado = media >= 7 ? "Aprovado" : "Reprovado";` <br>

O "?" simboliza o if (se), então caso seja maior que 7, então Aprovado, senão, Reprovado qualquer coisa abaixo de 7 <br>

A prática no uso de operadores ternários impacta positivamente a questão do código limpo. Pois assim evita-se o uso em excesso de if, else e else if. <br>

---------------------------------------

# • Switch Case (Diferenças entre if e swtich):

### Estrutura com if <br>
![image](https://github.com/Joaocosmala/Estudos_backend/assets/78692465/d66670bc-7eb5-4cfe-b80e-d0fe33c615d5)

### Estrutura com Switch <br>
![image](https://github.com/Joaocosmala/Estudos_backend/assets/78692465/d9f5cf7b-c2f5-4075-9873-65603182d7b5)

<br>

Swtich Case: <br>
O switch em JavaScript é uma estrutura de controle que permite avaliar uma expressão em comparação com vários casos. Dependendo do valor da expressão, o código executa diferentes blocos de código. <br>

A estrutura básica do switch é a seguinte: <br>
`switch (expressao) {` <br>
  `case valor1:` <br>
        `Código a ser executado se expressao for igual a valor1` <br>
    `break;` <br>
  `case valor2:` <br>
        `Código a ser executado se expressao for igual a valor2` <br>
    `break;` <br>
  `// ...` <br>
  `default:` <br>
        `Código a ser executado se nenhum caso corresponder a expressao` <br>
`}` <br>

A partir disso também temos outras condições para utilizarmos junto ao Switch Case. <br>

#### expressao:
É a expressão que será avaliada. O valor dela será comparado com os valores dos casos. <br>

#### case valorN:
Cada case representa um valor específico que a expressão pode ter. Se a expressão for igual a valorN, o código dentro desse case será executado. <br>

#### break:
É usado para sair do bloco switch após um case ser executado. Se esquecido, o código continuará executando no próximo case mesmo se não houver correspondência de valor. <br>

#### default:
É opcional e é executado se nenhum dos casos corresponder à expressão. Funciona como um "caso padrão". <br>

---------------------------------------

Exemplos: <br>
Utilizando exemplos com if para demonstração: <br>

`const nome = "Manu";` <br>
`if (nome == "João") {` <br>
    `console.log("O nome é João");` <br>
`} else if (nome === "Manu") {` <br>
    `console.log("O nome é Manu");` <br>
`} else {` <br>
    `console.log("Sem nome na lista");` <br>
`};` <br>


`Utilizando Swtich Case:` <br>
`const nomeDois = "Pitoco";` <br>

`switch(nomeDois) {` <br>
    `case "Shake" :` -> Case === caso, se... Exemplo: Caso for... então... semelhante ao uso do if e else e else if <br>
        `console.log("O nome é Shake");` <br>
        `break;` -> Adicionamos o break para que o cósigo não continue correndo para as próximas linhas <br>
        `case "Pitoco" :` <br>
            `console.log("O nome é Pitoco");` <br>
            `break;` <br>
           `default :` <br>
            `console.log("Sem nome na lista");` <br>
`};` <br>

---------------------------------------

# • Loops:
Os loops em JavaScript são estruturas que permitem executar um bloco de código repetidamente enquanto uma condição específica é verdadeira. <br>
Eles ajudam a automatizar tarefas repetitivas sem a necessidade de escrever o mesmo código várias vezes. <br>

Existem vários tipos de Loops em JavaScript, os principais são: <br>
• while <br>
• do while <br>
• for <br>
• for of <br>

Em alguns momentos precisamos que algumas estruturas de códigos se repitam várias vezes, e os loops fazem este serviço muito bem. <br>

Aqui abaixo citarei os principais e demonstrarei exemplos em seguida. <br>

---------------------------------------

### • while:
A declaração do tipo While cria um laço que executa especificamente enquanto a condição de teste for avaliada como verdadeira. Sendo assim a condição avaliada antes da execução da rotina. <br>

Exemplos while: <br>
`let n = 0;` <br>
`let x = 0;` <br>

`while (n < 3) {` -> Se n for menor que 3 (lembrando que n é 0) <br>
    `n++;` -> Então adicionamos 1 n a mais <br>
    `console.log(x);` <br>
`};` <br>

-> Do 0 até 10 <br>
`let number = 0;` <br>
`while (number <= 9) {` <br>
    `number++;` <br>
    `console.log(number);` <br>
`}` <br>
`Resultado: 0 até 10` <br>

---------------------------------------

-> Do 300 até 0 <br>
`let numeroMaximo = 300` <br>
`while (numeroMaximo > 0) {` <br>
    `numeroMaximo--` <br>
    `console.log(numeroMaximo);` <br>
`}` <br>
`Resultado: 300 Até 0` <br>

---------------------------------------

### • do while:
A declaração do tipo do while cria um laço de repetição que executa uma declaração até que o teste da condição for false (false). A condição é avaliada depois que o bloco de código é executado, resultando que uma declaração seja executada pelo menos uma vez. <br>

Exemplos de do while: <br>
`let resultado = "";` <br>
`let i = 0;` <br>
`do {` <br>
`i += 1;` <br>
`resultado += i + " ";` <br>
`} while (i < 5);` <br>
`console.log(resultado);` <br>

---------------------------------------

`let resultadoDois = "";` <br>
`let i = 0;` <br>
`do {` <br>
    `i++;` <br>
    `resultadoDois += i + "";` <br>
`} while (i < 5);` <br>
`console.log(resultadoDois);` <br>

A estrutura do while é semelhante ao if, porém, a sintaxe do "do while" é um pouco diferente. <br>

---------------------------------------

### • for:
A instrução for cria um loop que consiste em 3 expressões opcionais, dentro de parênteses e separadas por ponto e vírgula, seguidas essa de uma declaração ou uma sequência de declarações executadas em sequência. <br>
for é uma das estruturas de repetição mais usadas e mais conhecidas, também está presente em muitas outras línguagens. <br>

Exemplo: <br>
-> Contando de 0 a 20 <br>
`for (var i = 0; i < 20; i++) {` <br>
`console.log(i);` <br>
`};` Resultado: 0 a 20 <br>

-> Contando de 0 a 10 <br>
`for (let e = 0; e <= 10; e++) {` <br>
    `console.log(e);` <br>
`};` Resultado: 0 a 10 <br>

---------------------------------------

### • for of:
O Loop for of percorre objetos iterativos, chamando uma função personalizada com instruções a serem executadas para o valor de cada objeto distinto. <br>
A estrutura do for of se utiliza de um array. <br>

Exemplos: <br>
`let iterable = [10, 20, 30];` <br>
    `for (let value of iterable) {` <br>
    `console.log(value);` <br>
`};` Resultado: 10, 20, 30 <br>

---------------------------------------

A estrutura do for of se utiliza de um array para percorrer uma lista de nomes, números ou o que precisar. <br>

`const peoples = [` <br>
    `"Bruno",` <br>
    `"Marco",` <br>
    `"Pedro",` <br>
    `"Nadia",` <br>
    `"Isa",` <br>
`];` <br>

`for (let people of peoples) {` <br>
    `console.log(people);` <br>
`};` Resultado: Bruno, Marco, Pedro, Nadia, Isa. <br>

Ele retorna para nós os dados que estão dentro deste array, no caso, os nomes postos. <br>

---------------------------------------

Porém, também é possível escrever este mesmo código ainda usando o que vimos até agora sobre o for padrão. <br>

`for(let i = 0; i < peoples.length; i++ ) {` <br>
    `console.log(peoples[i]);` <br>
`};` <br>

Ele ainda irá percorrer a lista de nomes, mesmo que o código seja escrito de outra maneira. <br>

---------------------------------------

# • Funções:
Funções são reaproveitamento de código, exatamente para não precisarmos ficar reescrevendo o mesmo código toda vez que precisarmos deste. <br>
Elas ajudam a modularizar o código, tornando-o mais organizado, legível e reutilizável. <br>
Entre as princípais características das funções estão: <br>

### Reutilização de Código:
As funções permitem definir um bloco de código que pode ser chamado várias vezes em diferentes partes do programa, evitando a repetição do mesmo código. <br>

---------------------------------------

### Nomeação:
As funções podem ter um nome que as identifica, permitindo referenciar e chamar a função pelo nome em qualquer parte do código. <br>

---------------------------------------

### Parâmetros e Argumentos:
Podem receber valores chamados de parâmetros quando são definidas e valores chamados de argumentos quando são chamadas. <br>
Esses valores permitem que as funções sejam flexíveis e capazes de lidar com diferentes inputs. <br>

---------------------------------------

### Retorno de Valores:
Podem retornar um valor de volta para a parte do código que chamou a função. <br>
O return é usado para especificar o valor que a função deve produzir como resultado. <br>

---------------------------------------

### Escopo:
As variáveis definidas dentro de uma função têm um escopo local, o que significa que não podem ser acessadas fora da função, a menos que sejam explicitamente retornadas. <br>

--------------------------------------- 

### Declaração e Expressão de Funções:
Podem ser declaradas utilizando a palavra-chave function ou podem ser expressas como funções anônimas (atribuídas a variáveis ou passadas como argumentos). <br>

---------------------------------------

## Como utilizar funções:

- Exemplo de função sem parâmetro: <br>
`function mostrarNome( ) {` <br>
    `console.log("João");` <br>
`};` <br>
`mostrarNome( );` Resultado: João. <br>

---------------------------------------

- Exemplo de função com parâmetro: <br>
`function mostrarAlgumNome(name) {` <br>
    `console.log(name);` <br>
`};` <br>
`mostrarAlgumNome("João");` Este é o parâmetro que eu quero que apareça. <br>

---------------------------------------

Mais exemplos de funções: <br>

-> Sem parâmetro: <br>
`function showMyName() {` <br>
    `console.log("João");` <br>
  `};` <br>
`showMyName();` <br>


-> Com parâmetro: <br>
`function showRandomName(name) {` <br>
    `console.log(name);` <br>
`};` <br>
`showRandomName("João");` <br>
`showRandomName("Paulo");` <br>
`showRandomName("Sebastião");` <br>
`showRandomName("Carolina");` <br>
`showRandomName("Manu");` <br>
Resultado: João, Paulo, Sebastião, Carolina, Manu. <br>

Observe que passamos quantos parâmetros forem necessários. <br>

---------------------------------------

Agora para variarmos um pouco na utilização de exemplos, vamos criar uma função que faz a soma de 3 ou mais números: <br>

Exemplo: <br>
`function somarNumeros(numero1, numero2, numero3, numero4) {` <br>
    `console.log("O Resultado da soma de todos os números é: ", numero1 + numero2 + numero3 + numero4);` <br>
`};` <br>
`somarNumeros(10, 48, 39, 64);` <br>
Resultado: 161; <br>

---------------------------------------

# Funções com Return:
As funções com return em JavaScript são blocos de código que executam uma tarefa específica e retornam um valor como resultado. <br>
Estas são as principais caracteristícas: <br>

### Execução de Tarefa Específica:
As funções são usadas para agrupar um conjunto de instruções que realizam uma tarefa particular. <br>
Essas tarefas podem ser desde cálculos simples até processamentos mais complexos. <br>

---------------------------------------

### Palavra-chave return:
O return é usado para especificar o valor que a função deve produzir como resultado quando ela é chamada. <br>
Essa declaração interrompe a execução da função e retorna imediatamente o valor especificado. <br>

---------------------------------------

### Valores de Retorno:
As funções podem retornar qualquer tipo de valor em JavaScript, como strings, números, objetos, arrays ou até mesmo valores booleanos (verdadeiro ou falso). <br>

---------------------------------------

### Utilidade em Operações e Avaliações:
O return é útil para retornar resultados de operações matemáticas, processamento de dados, validações condicionais ou qualquer lógica que produza um resultado a ser utilizado em outro lugar do código. <br>


Exemplo: <br>
`function soma(a, b) {` <br>
  `return a + b;` <br>
`}` <br>

`let resultado = soma(3, 5);` <br>
`console.log(resultado);` <br>
Resultado: 8 <br>

---------------------------------------

Mais Exemplos: <br>
`function somarAllNumeros(n1, n2, n3, n4) {` <br>
    `const somatoria = n1 + n2 + n3 + n4;` <br>
    `console.log(somatoria);` <br>
`};` <br>
`somarAllNumeros(20, 40, 238, 127);` <br>
Resultado: 425 <br>

---------------------------------------

Outros exemplos: <br>
Neste exemplo agora estamos utilizando de funções com return para criar uma função que retorna a media dos 4 números dispostos. <br>
`function somarTodos(n1, n2, n3, n4) {` <br>
    `const somandoNumbers = n1 + n2 + n3 + n4;` <br>
    `return somandoNumbers;` <br>
`};` <br>

`function media(somandoNumbers) {` <br>
    `const estudanteMedia = somandoNumbers / 4;` <br>
    `return estudanteMedia` <br>
`};` <br>

`const scoreDoEstudante = somarTodos(10, 10, 10, 10);` <br>
`if (media(scoreDoEstudante) === 10) {` <br>
    `console.log("Você é fera!!!!!!!!");` <br>
`} else if (media(scoreDoEstudante) <= 5 ) {` <br>
    `console.log("Sinto muito, mas está de recuperação.");` <br>
`} else {` <br>
    `console.log("Passou!!!!");` <br>
`}` <br>

---------------------------------------

# Arrays
Array se assemelham a listas. É um objeto global que é muito útil quando é preciso lidar com muitas informações, ou passa-las de alguma maneira. <br>
Você pode armazenar diversas informações dento de uma variável. <br>

Observação: Em Arrays, a contagem de números não se inicia do 1, mas sim do 0 <br>
`const listaNomes = [` <br>
    `"Pedro",` -> 0 <br>
    `"Fabiana",` -> 1 <br>
    `"Marcelo",` -> 2 <br>
    `"Isadora",` -> 3 <br>
    `"Marlene",` -> 4  <br>
    `"Renato",` -> 5 <br>
    -> Total de itens no Array: 6 <br>
`];` <br>
`console.log(listaNomes);` Resultado: (6), Pedro, Fabiana, Marcelo, Isadora, Marlene, Renato; <br>
`console.log(listaNomes.length);` Resultado: 6 (Ele trará a quantidade de itens que está no array); <br>
`console.log(listaNomes[3]);` Resultado: Isadora (Trará o terceiro nome que está na lista); <br>
`console.log(listaNomes[7]);` Resultado: Undefined pois a posição número 7 não existe em nosso array; <br>

`console.log("Percorrendo o Array");` Percorrendo o Array <br>
`for (let listaNome of listaNomes) {` <br>
    `console.log(listaNome);` <br>
`};` <br>

`console.log("Armazenando Números");` Armazenando Números <br>
`const numeros = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15];` <br>
`console.log(numeros);` Resutado: (15) 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15; <br>

---------------------------------------

### Propriedades e Métodos de Arrays
• length -> Retorna o tamanho do Array <br>
• filter -> Filtra um Array baseado em uma condição <br>
• find -> Encontra um elemento dentro do Array baseado em uma condição <br>
• findIndex -> Encontra o índice de um elemento dentro do Array <br>
• forEach -> Cria um Loop para percorrer as opções do Array <br>
• map -> Percorre todas as opções do Array <br>
• push -> Adiciona um novo elemento ao Array <br>
• pop -> Remove o último item do Array <br>
• splice -> Remove um item específico do Array <br>
• reverse -> Inverte a posição dos elementos do Array <br>

---------------------------------------

Array:
`const pessoas = ["João", "Pedro", "Steh", "Maysa", "Théo", "Aurora" ];` <br>

### Console.log(pessoas):
Observando itens do Array: <br>
`console.log(pessoas);` <br>
Resultado: (6) ["João", "Pedro", "Steh", "Maysa", "Théo", "Aurora" ] <br>

---------------------------------------

### LENGTH:
`console.log("Utilização do Length: ", pessoas.length);` <br>
Resultado: Utilização do Length:  6 <br>

---------------------------------------

### [ ]
Filtrando itens específicos do Array [ ]: <br>
`console.log("Posição no Array: ", pessoas[2]);` <br>
Resultado: Posição no Array:  Steh <br>
(Lembrando que Array se inicia contando do 0, logo, ele passou por João que é 0 e Pedro que é 1 para chegar em Steh que é 2) <br>

Adicionando Matheus: <br>
`pessoas.push("Matheus");` <br>
`console.log("Adicionando Matheus ao Array: ", pessoas[6]);` <br>
Resultado: Adicionando Matheus ao Array: Matheus (Na posição 6) <br>

---------------------------------------

### POP
Removendo o último item do Array <br>
`pessoas.pop();` <br>
`console.log("Removendo o último elemento do Array: ", pessoas[6]); // Resultado: Undefined (Mateheus foi removido do Array);` <br>

---------------------------------------

`const videogames = ["Playstation 1", "Playstation 2", "Nintendo 64", "Super Nintendo", "Master System", "PSP", "Xbox 360", "Xbox One", "Xbox Series X"];` <br>
`console.log(videogames);` <br>
Resultado: (9) ["Playstation 1", "Playstation 2", "Nintendo 64", "Super Nintendo", "Master System", "PSP", "Xbox 360", "Xbox One", "Xbox Series X"] <br>

### Reverse:
Invertendo ordem do Array com reverse: <br>

`videogames.reverse();` <br>
`console.log(videogames);` <br>
Resultado: (9) ['Xbox Series X', 'Xbox One', 'Xbox 360', 'PSP', 'Master System', 'Super Nintendo', 'Nintendo 64', 'Playstation 2', 'Playstation 1'] <br>

---------------------------------------

### ForEach:
forEach irá percorrer todos os elementos do Array <br>
Utilizando forEach com um callback retornando uma função: <br>

`function posicoesDeLog(item) {` <br>
    `console.log(item);` <br>
`}` <br>
`videogames.forEach(posicoesDeLog);` <br>
Resultado: <br>
Xbox Series X <br>
Xbox One <br>
Xbox 360 <br>
PSP <br>
Master System <br>
Super Nintendo <br>
Nintendo 64 <br>
Playstation 2 <br>
Playstation 1 <br>

Agora fazendo a mesma coisa de uma maneira mais simplificada: <br>
Utilizando forEach com um callback retornando uma função2 (Simplificada): <br>
`videogames.forEach((item) => console.log(item));` <br>
Resultado: <br>
Xbox Series X <br>
Xbox One <br> 
Xbox 360 <br>
PSP <br>
Master System <br>
Super Nintendo <br>
Nintendo 64 <br>
Playstation 2 <br>
Playstation 1 <br>

Map irá percorrer e retornar um novo Array cpm base no último Array manipulado ou selecionado para este. No caso, videogames <br>
`const otherVideoGames = videogames.map((game) => game);` <br>
`console.log(otherVideoGames);` <br>
Resultado: (9) ['Xbox Series X', 'Xbox One', 'Xbox 360', 'PSP', 'Master System', 'Super Nintendo', 'Nintendo 64', 'Playstation 2', 'Playstation 1'] <br>

---------------------------------------

`const marcasTecnologia = ["Apple", "Microsoft", "IBM", "Lenovo", "Dell", "Acer", "Sony"];` <br>
`console.log(marcasTecnologia);` <br>
Resultado: (7) ["Apple", "Microsoft", "IBM", "Lenovo", "Dell", "Acer", "Sony"]; <br>

### FIND: 
Utilizando find para encontrar um nome específico dentro do Array <br>

`const posicaoIBM = marcasTecnologia.find((item) =>  item === "IBM");` <br>
`console.log(posicaoIBM);` <br>
Resultado: IBM <br>

`const posicaoMicrosoft = marcasTecnologia.find((item) =>  item === "Microsoft");` <br>
`console.log(posicaoMicrosoft);` <br>
Resultado: Microsoft <br>

Porém se passarmos um nome que não existe, então retornará Undefined <br>
`const posicaoNomeInexistente = marcasTecnologia.find((item) =>  item === "Gucci");` <br>
`console.log(posicaoNomeInexistente);` <br>
Resultado: Undefined <br>

---------------------------------------

### FINDINDEX:
Buscando a posição do index <br>

findIndex: <br>
`const posicaoNoIndex = marcasTecnologia.findIndex((item) => item === "IBM");` <br>
`console.log(posicaoNoIndex);` <br>
Resultado: 2 (Pois IBM está na posição 2); <br>

Buscando posição inexistente do index: <br>
`const semPosicaoNoIndex = marcasTecnologia.findIndex((item) => item === "NaoExiste");` <br>
`console.log(semPosicaoNoIndex);` <br>
Resultado: -1 (Pois não existe nada com este nome no Array); <br>

---------------------------------------

`const marcasDeGrife = ["Gucci", "Prada", "Versaci", "Balanciaga", "Louis Vuitton"];` <br>
`console.log(marcasDeGrife);` <br>

### Filter:

Filtrando no Array somente os itens possuintes de mais de 10 caractéres <br>
`const filtermarcasDeGrife = marcasDeGrife.filter((item) => item.length > 10);` <br>
`console.log("Filtrando Array marcasDeGrife: ", filtermarcasDeGrife);` <br>
Resultado: (1) Louis Vuitton (Único item no Array que possui mais de 10 caractéres) <br>

Filtrando no Array somente os itens possuintes de mais de 5 caractéres: <br>
`const filtermarcasDeGrifeDois = marcasDeGrife.filter((item) => item.length > 5);` <br>
`console.log("Filtrando Array marcasDeGrife 2: ", filtermarcasDeGrifeDois);` <br>
Resultado: (3) Versaci, Balanciaga, Louis Vuitton (Itens no Array que possuem mais de 5 caractéres) <br>

---------------------------------------

`const avioes = ["Airbus A380", "Boeing 747", "Airbus A340", "Boeing 777", "Antonov"];` <br>
`console.log(avioes);` <br>

### Splice:
Utilizando Splice para remover itens do Array: <br>
`avioes.splice(3);` <br>
`console.log(avioes);` <br>
Resultado: (3) Airbus A380, Boeing 747, Airbus A340 <br>

