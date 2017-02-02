# Desafio da semana #2

Nesse exercício, você está livre para escolher os nomes para suas variáveis e funções! :smile:

```js
// Crie uma função que receba dois argumentos e retorne a soma dos mesmos.
function soma(1,2){ return a+b;};

// Declare uma variável que receba a invocação da função criada acima, passando dois números quaisquer por argumento, e somando `5` ao resultado retornado da função.
var resultado=soma(1,2)+5;

// Qual o valor atualizado dessa variável?
resultado; //8

// Declare uma nova variável, sem valor.
var X;

/*
Crie uma função que adicione um valor à variável criada acima, e retorne a string:
    O valor da variável agora é VALOR.
Onde VALOR é o novo valor da variável.
*/
?function modifica(X){ X=5; return X='O valor da variável agora é'+X;}

// Invoque a função criada acima.
modifica(X);

// Qual o retorno da função? (Use comentários de bloco).
/* O valor da variávle agora é 5 */
/*
Crie uma função com as seguintes características:
1. A função deve receber 3 argumentos;
2. Se qualquer um dos três argumentos não estiverem preenchidos, a função deve retornar a string:
    Preencha todos os valores corretamente!
3. O retorno da função deve ser a multiplicação dos 3 argumentos, somando `2` ao resultado da multiplicação.
*/
function calculo(a,b,c){ if(a!=undefinied && b!=undefinied && c!=undefinied){
return a*b*c+2;};
} else{ return 'Valores não preenchidos corretamente!}
};
// Invoque a função criada acima, passando só dois números como argumento.
calculo(1,2);

// Qual o resultado da invocação acima? (Use comentários para mostrar o valor retornado).
// Valores não preenchidos corretamente.
// Agora invoque novamente a função criada acima, mas passando todos os três argumentos necessários.
//calculo(1,2,3);

// Qual o resultado da invocação acima? (Use comentários para mostrar o valor retornado).
//8

/*
Crie uma função com as seguintes características:
1. A função deve receber 3 argumentos.
2. Se somente um argumento for passado, retorne o valor do argumento.
3. Se dois argumentos forem passados, retorne a soma dos dois argumentos.
4. Se todos os argumentos forem passados, retorne a soma do primeiro com o segundo, e o resultado, dividido pelo terceiro.
5. Se nenhum argumento for passado, retorne o valor booleano `false`.
6. E ainda, se nenhuma das condições acima forem atendidas, retorne `null`.
*/

/*function calculofinal(a,b,c){
var x;
if(a!=NaN && b!=NaN && c!=NaN){
if( a==x){
return false;
} else if(b==x){
return a;
} else if(c==x){
return a+b;
} else if(a!=x && b!=x && c!=x){
return (a+b)/c;
}
} else { return null;}
};
*/
// Invoque a função acima utilizando todas as possibilidades (com nenhum argumento, com um, com dois e com três.) Coloque um comentário de linha ao lado da função com o resultado de cada invocação.
?
`//calculofinal(1,2,3); //1
//calculofinal(1,2); //3
//calculofinal(2); //2
