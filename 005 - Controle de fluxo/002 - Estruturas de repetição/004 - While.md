O laço **`while`** determina que enquanto uma condição for válida, o bloco será executado. Esse tipo de laço testa a condição, se ela for verdadeira, ele executa ela, senão o bloco não será executado.

Estrutura:

```java
while ( expressão booleana ) {
	// código a ser executado
}
```

Exemplo:

```java
double mesada = 50.0;  
while (mesada > 0) {  
    double valorDoce = valorAleatorio();  // método não é obrigatório
    if ( valorDoce > mesada ) {  
        valorDoce = mesada;  
    }  
    System.out.println("Doce do valor: " + valorDoce + " Adicionando no carrinho");  
    mesada = mesada - valorDoce;  
}  
  
System.out.println("Mesada: " + mesada);  
System.out.println("Joãozinho gastou toda a sua mesada em doces");
```