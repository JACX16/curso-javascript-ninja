# Desafio da semana #3

```js
// Declarar uma variável qualquer, que receba um objeto vazio.
//var objeto={};

/*
Declarar uma variável `pessoa`, que receba suas informações pessoais.
As propriedades e tipos de valores para cada propriedade desse objeto devem ser:
- `nome` - String
- `sobrenome` - String
- `sexo` - String
- `idade` - Number
- `altura` - Number
- `peso` - Number
- `andando` - Boolean - recebe "falso" por padrão
- `caminhouQuantosMetros` - Number - recebe "zero" por padrão
*/
//var pessoa={ nome:'joao', sexo:'M', idade:'20', alt:175, andando:false, caminho:0}

/*
Adicione um método ao objeto `pessoa` chamado `fazerAniversario`. O método deve
alterar o valor da propriedade `idade` dessa pessoa, somando `1` a cada vez que
for chamado.
*/
//pessoa.aniversario=function(){ pessoa.idade+=1;};

/*
Adicione um método ao objeto `pessoa` chamado `andar`, que terá as seguintes
características:
- Esse método deve receber por parâmetro um valor que representará a quantidade
de metros caminhados;
- Ele deve alterar o valor da propriedade `caminhouQuantosMetros`, somando ao
valor dessa propriedade a quantidade passada por parâmetro;
- Ele deverá modificar o valor da propriedade `andando` para o valor
booleano que representa "verdadeiro";
*/
//pessoa.andar=function(x){ pessoa.caminho+=x; pessoa.andando=true;};

/*
Adicione um método ao objeto `pessoa` chamado `parar`, que irá modificar o valor
da propriedade `andando` para o valor booleano que representa "falso".
*/
//pessoa.parar=function(){ pessoa.andando=false;};

/*
Crie um método chamado `nomeCompleto`, que retorne a frase:
- "Olá! Meu nome é [NOME] [SOBRENOME]!"
*/
//pessoa.saudar=function(){ console.log('Olá, eu sou '+pessoa.nome);};
/*
Crie um método chamado `mostrarIdade`, que retorne a frase:
- "Olá, eu tenho [IDADE] anos!"
*/
//pessoa.showAge=function(){ console.log('Olá, eu tenho '+pessoa.idade);};

/*
Crie um método chamado `mostrarPeso`, que retorne a frase:
- "Eu peso [PESO]Kg."
*/
//pessoa.showWeight=function(){ console.log('Eu peso : '+pessoa.peso)+'Kg.';};

/*
Crie um método chamado `mostrarAltura` que retorne a frase:
- "Minha altura é [ALTURA]m."
*/
//pessoa.showHight=function(){ console.log('Minha altura é '+pessoa.alt+' cm.');};

/*
Agora vamos brincar um pouco com o objeto criado:
Qual o nome completo da pessoa? (Use a instrução para responder e comentários
inline ao lado da instrução para mostrar qual foi a resposta retornada)
*/
//pessoa.saudar();

/*
Qual a idade da pessoa? (Use a instrução para responder e comentários
inline ao lado da instrução para mostrar qual foi a resposta retornada)
*/
//pessoa.showAge();

/*
Qual o peso da pessoa? (Use a instrução para responder e comentários
inline ao lado da instrução para mostrar qual foi a resposta retornada)
*/
//pessoa.showWeight();

/*
Qual a altura da pessoa? (Use a instrução para responder e comentários
inline ao lado da instrução para mostrar qual foi a resposta retornada)
*/
//pessoa.showHight();

/*
Faça a `pessoa` fazer 3 aniversários.
*/
//pessoa.aniversario();
//pessoa.aniversario();
//pessoa.aniversario();


/*
Quantos anos a `pessoa` tem agora? (Use a instrução para responder e
comentários inline ao lado da instrução para mostrar qual foi a resposta
retornada)
*/
//pessoa.showAge();
//23

/*
Agora, faça a `pessoa` caminhar alguns metros, invocando o método `andar` 3x,
com metragens diferentes passadas por parâmetro.
*/
/*
pessoa.andar(10);
pessoa.andar(15);
pessoa.andar(20);
*/
/*
A pessoa ainda está andando? (Use a instrução para responder e comentários
inline ao lado da instrução para mostrar qual foi a resposta retornada)
*/
//pessoa.andando;//true

/*
Se a pessoa ainda está andando, faça-a parar.
*/
//pessoa.parar();

/*
E agora: a pessoa ainda está andando? (Use uma instrução para responder e
comentários inline ao lado da instrução para mostrar a resposta retornada)
*/
//pessoa.andando;//false

/*
Quantos metros a pessoa andou? (Use uma instrução para responder e comentários
inline ao lado da instrução para mostrar a resposta retornada)
*/
//pessoa.caminho;//55

/*
Agora vamos deixar a brincadeira um pouco mais divertida! :D
Crie um método para o objeto `pessoa` chamado `apresentacao`. Esse método deve
retornar a string:
- "Olá, eu sou o [NOME COMPLETO], tenho [IDADE] anos, [ALTURA], meu peso é [PESO] e, só hoje, eu já caminhei [CAMINHOU QUANTOS METROS] metros!"

Só que, antes de retornar a string, você vai fazer algumas validações:
- Se o `sexo` de `pessoa` for "Feminino", a frase acima, no início da
apresentação, onde diz "eu sou o", deve mostrar "a" no lugar do "o";
- Se a idade for `1`, a frase acima, na parte que fala da idade, vai mostrar a
palavra "ano" ao invés de "anos", pois é singular;
- Se a quantidade de metros caminhados for igual a `1`, então a palavra que
deve conter no retorno da frase acima é "metro" no lugar de "metros".
- Para cada validação, você irá declarar uma variável localmente (dentro do
método), que será concatenada com a frase de retorno, mostrando a resposta
correta, de acordo com os dados inseridos no objeto.
*/

// Agora, apresente-se ;)
/*
pessoa.apresentacao=function(){
  var frase;
  if(pessoa.sexo==='M'){
    frase=' Olá, eu sou o '+pessoa.nome+',';
    }else{
      frase=' Olá, eu sou a '+pessoa.nome',';
      }
  if(pessoa.idade===1){
    frase+=' tenho '+pessoa.idade+' ano,';
    }else{
    frase+=' tenho '+pessoa.idade+' anos,';
    }
  if(pessoa.caminho===1){
    frase+=' meu peso é '+pessoa.peso+' e só hoje, eu já caminhei '+pessoa.caminho+' metro.';
    }else{
    frase+=' meu peso é '+pessoa.peso+' e, só hoje, eu já caminhei '+pesso.caminho+' metros.';
    }
 }//fimfunction
*/
