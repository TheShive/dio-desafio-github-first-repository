# C# Basic 

#### Tipos de Dados

- string :arrow_forward:caracteres 
- char   :arrow_forward:caracter único
- bool   :arrow_forward:verdadeiro ou falso
- int      :arrow_forward: números inteiros  >não possui casas decimais<
  	- Byte :arrow_right: números de 0 - 255
  	- Uint :arrow_right: números de 0 - 4 Bi
   - Short :arrow_right: números de -32.000 - 32.000
  	- Ulong :arrow_right: números negativos até 18Qi
  	- Long :arrow_right: número -/+ até 9Qi
- object :arrow_forward: qualquer tipo
- decimal :arrow_forward: valores decimais ( melhor usado expressando valores monetários)
  - double :arrow_right: capacidade de números decimais > "decimal" (ex: coordenadas)
  - float :arrow_right: capacidade de números decimais > "decimal"; precisão < "double"



#### O que é Classe

**É o bloco de construção básico da programação orientada a objetos e é reutilizável**. Uma classe C# define propriedades, campos, eventos, métodos, etc.



#### Operador de Atribuição

O operador de atribuição é representado no C# por (=), e tem por objetivo ligar a variável do lado esquerdo a ao lado direito dando valor.

####  Variáveis

É um nome qualquer dado há uma informação que vária o valor dentro do código.

##### Exemplo de Manipulação de variável (VS Code C#)

 // string apresentacao = "Hi, seja bem-vindo";



// int quantidade = 1;



// double altura = 1.80;



// decimal preco = 1.80M;



// bool condicao = true;



// Console.WriteLine(apresentacao);

// Console.WriteLine("Valor da variavél quantidade: " + quantidade);

// Console.WriteLine("Valor da variavél altura: " + altura.ToString("0.00"));

// Console.WriteLine("Valor da variavél preco: " + preco);

// Console.WriteLine("Valor da variavél condicão: " + condicao);

#### Sistema de Conversão de data base

é o sistema do csharp que transforma os tipos de dados, por exemplo do tipo int --> string ou vice-versa.

// Cast - Casting - Nome mais utilizado na comunidade Dev C#

// primeiro método

int a = Convert.ToInt32("5");

Console.WriteLine(a);

// Segundo método

int h = int.Parse("5");

Console.WriteLine(h)

// Se diferem com a maneira que lidam com valores Nulos-Nulls

// Convert: transforma em 0

//Parse: dá erro

###### Exceção - Conversão para String

Não é possível utilizar "Parse" com "String", Somente o Comando "Convert.ToString", Porém de certa forma se torna redundante já que tbm é possível utilizar a seguinte expressão:

//Int inteiro = 5

//string a = inteiro.ToString()

//Console.WriteLine(a)

###### Cast ímplicito

é representado quando os valores são convertido automaticamente na compilação.

Só ocorre em valores que são proporcionais, exemplo: int -> double ou int -> long.








#### **_Referência_**

[Data-Types](https://www.softwaretestisnghelp.com/c-sharp/csharp-data-types-and-variables/)







