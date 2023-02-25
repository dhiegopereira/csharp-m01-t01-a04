# cshap-m01-a04
Tipos de dados

> Em C#, os tipos de dados são usados para definir o tipo de valor que uma variável pode armazenar. Existem vários tipos de dados em C#, incluindo tipos numéricos, tipos de caracteres, tipos booleanos e tipos de referência. 

### Tipos numéricos
- Os tipos numéricos em C# são usados para armazenar valores numéricos. Existem vários tipos numéricos em C#, incluindo:
    - int: usado para armazenar números inteiros com sinal de 32 bits.
    - long: usado para armazenar números inteiros com sinal de 64 bits.
    - float: usado para armazenar números de ponto flutuante com precisão simples.
    - double: usado para armazenar números de ponto flutuante com precisão dupla.
> Existem outros tipos numéricos em C#, como short, byte, decimal, entre outros.
```C#
int idade = 27;
long populacao = 10000000000;
float preco = 2.99f;
double salario = 2500.50;
```
---
### Tipos de caracteres
- Os tipos de caracteres em C# são usados para armazenar caracteres individuais. Existem dois tipos de caracteres em C#:
    - char: usado para armazenar um único caractere Unicode.
    - string: usado para armazenar uma sequência de caracteres Unicode.
```C#
char letra = 'a';
string nome = "João";
```
---
### Tipos booleanos
- Os tipos booleanos em C# são usados para armazenar valores verdadeiro/falso. Existem dois tipos booleanos em C#:
    - bool: usado para armazenar valores verdadeiro/falso.
```C#
bool temContaBancaria = true;
bool maiorDeIdade = false;
```
---
### Tipos de referência
- Os tipos de referência em C# são usados para armazenar endereços de memória para objetos. Eles incluem:
    - object: usado como um tipo base para todos os tipos de objetos em C#.
    - dynamic: usado para suporte a tempo de execução de tipos dinâmicos.
    - var: usado para inferência de tipo.
```C#
object meuObjeto = new object();
dynamic valorDinamico = 42;
var meuNumero = 123;
```
---
> Além desses tipos de dados, C# também oferece tipos de dados enumerados e estruturas personalizadas. Em geral, é importante escolher o tipo de dados certo para armazenar um valor, já que isso pode afetar a precisão dos cálculos e o desempenho do programa.

> Esses são apenas alguns exemplos básicos de como esses tipos de dados podem ser usados em C#. É importante notar que, em alguns casos, os tipos de dados podem ser convertidos de um tipo para outro usando métodos como Convert.ToInt32 ou Convert.ToDouble.

```C#
string valor1 = "123";
int numero1 = Convert.ToInt32(valor1);
Console.WriteLine(numero1); // Output: 123

string valor2 = "3.14";
double numero2 = Convert.ToDouble(valor2);
Console.WriteLine(numero2); // Output: 3.14
```
> No primeiro exemplo, a variável valor1 é uma string que contém o valor "123". Usando o método Convert.ToInt32, a string é convertida em um número inteiro e atribuída à variável numero1. O valor de numero1 é então impresso no console.

> No segundo exemplo, a variável valor2 é uma string que contém o valor "3.14". Usando o método Convert.ToDouble, a string é convertida em um número de ponto flutuante e atribuída à variável numero2. O valor de numero2 é então impresso no console.

> É importante lembrar que, em alguns casos, a conversão de um tipo para outro pode resultar em perda de precisão ou truncamento de valores. Por exemplo, se você converter um número de ponto flutuante em um número inteiro, os valores decimais serão truncados. Por isso, é importante escolher o tipo de dados certo para armazenar um valor, para garantir a precisão dos cálculos e o desempenho do programa.




