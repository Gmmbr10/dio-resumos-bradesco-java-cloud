# Tipos de dados

Tipos de dados, são palavras reservadas dentro da linguagem que indicam o tipo de dado que será usado na criação de um software.

## Os 8 tipos primitivos

**int , byte , short , long , float , double , boolean e char**

Eles não são considerados objetos, representando valores brutos, e serão armazenados diretamente na pilha de memória.

## Tabelas sobre os tipos

### Números inteiros

| Tipo  | Memória | Valor mínimo               | Valor máximo              |
| ----- | ------- | -------------------------- | ------------------------- |
| byte  | 1 byte  | -128                       | 127                       |
| short | 2 bytes | -32.768                    | 32.767                    |
| int   | 4 bytes | -2.147.483.648             | 2.147.483.647             |
| long  | 8 bytes | -9.223.372.036.854.775.808 | 9.223.372.036.854.775.807 |

> Sempre usamos `int` pois a JVM sempre converte para int, mesmo quando os valores são byte ou short.
>
> Caso o valor seja maior do que o permitido para int, a JVM converterá para `long`

### Números fracionários

| Tipo   | Memória | Mínimo          | Máximo        |
| ------ | ------- | --------------- | ------------- |
| float  | 4 bytes | - 3,4028E + 38  | 3,4028E + 38  |
| double | 8 bytes | - 1,7976E + 308 | 1,7976E + 308 |

> Mais comum usar `double`.

# Declaração de váriáveis

`<Tipo> <Nome da variável> = <Valor>;`

Exemplos:

```java
int idade; // Tipo "int", nome "idade", valor como não foi atribuído nada, será vazio
int anoFabricacao = 2000; // Tipo "int", nome "anoFabricacao", valor "2000"
double salarioMinimo = 1514.49; // Tipo "double", nome "salarioMinimo", valor "1.514,49"
```

> **Atenção**
>
> Os tipos de precisão, `double e float`, o `.` (ponto) representa a `,` (vírgula).
>
> Para escrever valores milhares, nos escrevemos eles sem ponto.
> Exemplo: R$ 2.000 (mundo real) -> 2000 (programação)

Alguns tipos de dados, devem ser declarados de maneira específica. Exemplo:

```java
byte idade = 123;
short ano = 2025;
int cep = 17406360; // se começar com zero, deve ser usado outro tipo de dado
long cpf = 12345678912L; // se começar com zero, também deve ser usado outro tipo de dado, sempre colocar 'l' no final
float pi = 3.14f; // sempre colocar 'f' no final
double salario = 3423.59;
```

> **Atenção**
>
> O tipo long, deve terminar com `L` e o float deve terminar com `F`
>
> O tipo char, deve ser inserido entre aspas simples `''`, enquanto a String deve ser entre aspas duplas `""`

## Cuidado

Java é fortemente tipado. Mas o que isso significa?

**Exemplo: Converter um número int para um short**
Vai funcionar, dependendo do valor e na teoria vai, no entanto, o java não permite de primeira.

**E como faço para ele permitir?**
***Casting***, essa técnica nada mais é do que você assumir que irá converter um tipo de dado para outro. Exemplo:

```java
short numeroCurto1 = 1;
int numeroNormal = numeroCurto1;
short numeroCurto2 = (short) numeroNormal; // casting
```
