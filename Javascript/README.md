# Aprendendo Javascript
    Este repositório mostrará minha evolução no aprendizado 
    desta linguagem de programação.
    Nele irei organizar e documentar passo a passo que estarei 

### Introdução
~~~Javascript
// As barras representam comentários feitos dentro do código Javascript.

/*
    Bloco de código comentando
*/

// Comando utilizado para imprimir conteúdo no terminal Javascript.

// String
console.log("Hello world!");
// Template string
console.log(`Hello world!`)

// Number

// parseInt
console.log(12345);
// parseFloat
console.log(10.2);


~~~~

---

### Navegador vs NodeJS

~~~~Javascript
alert("Utilizado para escrever em uma window web.");
document.write("Utilizado para escrever dentro de um documento web.");

console.log("Utilizado para escrever no terminal node ou web.");
~~~~

~~~~HTML
<!- Utilizado para ligar um arquivo javascript em um arquivo HTML. ->
<script src="caminho/do/arquivo/javascript"></script>
~~~~

---

### Variaveis
    Um espaço alocado na memória para guardar uma informação.

~~~~Javascript
// Variável alocada e declarada
let conteudo = "Utilização de let";

let nome = "Nathan";

console.log(`Bem-vindo, desenvolvedor júnior ${nome}`);

// Variável alocada mas sem valor declarado.
let idade;

// Regrinhas na criação de variáveis
/*
    - Nomes significativos
    - Não utilizar palavras reservadas
    - Não utilizar números no início
    - Não utilizar backspace no nome
    - Utilização de cameCase
    - Não podemos redeclarar uma variável utilizando let novamente.
    - caseSensitive: a diferenciação entre cameCase e VariavelNormal/variavelnormal/Variavelnormal.
    - NÃO UTILIZAR VAR, UTILIZAR LET.
*/
let startCode = "Javascript";
~~~~

~~~Javascript
const conteudo = "Utilização de const";

const nome = "Nathan";

// Regrinhas na criação de constante
/*
    - Uma constante não pode ser modificada
    - Uma variável pode ser atribuida a outra
*/

const primeiroNumero = 0;
const segundoNumero = 1;
const terceiroNumero = 2;

const calculo = primeiroNumero + segundoNumero + terceiroNumero;
console.log(calculo);
console.log(calculo * 2);

// Verificação de tipagem do dado alocado na variável
// typeof
console.log(typeof(primeiroNumero))

// Concatenar != somar
~~~~

---

### ECMAScript(ES6)
    É a padronização da documentação da linguagem Javascript.

### Tipos de dados
    * String - cadeia de caracteres
    * Number - números.
    * Boolean - true or false.
    * undefined - alocado, mas sem dado definido.
    * null - nenhum alocamento na memória.

~~~Javascript
let name = "Nathan"; // String
let number = 18; // Number
let boolean_1 = true; // true or false
let boolean_2 = false; // true or false
let undefined_type = undefined; // alocado, mas não definido
let null_type = null; // não alocado na memória
~~~

---

### Operadores

~~~Javascript
// + Concatena ou adiciona
// - subtração
// * multiplicação
// / divisão
// ** potenciação
// % resto da divisão

let number_1 = 4;
let number_2 = 8;

console.log(number_1 + number_2);
console.log(number_1 - number_2);
console.log(number_1 * number_2);
console.log(number_1 / number_2);
console.log(number_1 ** number_2);
console.log(number_1 % number_2);

// Ordem de precedência
/*
    - ()
    - * ou /
    - + ou -
*/
console.log(number_1++)
console.log(number_1--)

// Incremento e decremento
/*
    ++ incremento
    += (número)

    -- decremento
    -= (número)

    *= (número)
    /= (número)
*/

let name = "Nathan";

// NaN - not a number
console.log(number_1 * name)

// parseInt - número inteiro
// parseFloat - número decimal
let number = parseInt('18');
console.log(number);

number = parseFloat(18.5);
console.log(number);

~~~

### prompt, alert e confirm

~~~Javascript
let menssage = "Hello world!";

// Janela no navegador que exibe texto.
alert(menssage);

// Janela no navegadador que recebe um valor boolean(true or false).
confirm("Você é desenvolvedor?");
let devOrNo = confirm("Você é desenvolvedor?");

// Janela no navegadador que recebe um valor.
prompt("Digite o modelo do seu notebook: ");
let notebookModel = prompt("Digite o modelo do seu notebook: ");
~~~

