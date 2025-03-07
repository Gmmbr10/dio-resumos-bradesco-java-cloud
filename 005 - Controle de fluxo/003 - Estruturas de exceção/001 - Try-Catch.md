**`try`** permite que você define um bloco de código a ser testado enquanto não houver erros enquanto está sendo executado.

**`catch`** permite definir um bloco de código a ser executado, caso ocorra um erro no bloco try.

**`finally`** permite definir um bloco de código a ser executado independente de ocorrer erro ou não.

As palavras `try` e `catch` são obrigatórias, enquanto o `finally` é opcional.

Estrutura de um bloco try-catch:

```java
try {
	// bloco de código conforme o esperado
} catch (Exception e) { // sabemos qual erro temos
	// bloco de código que captura as exceções que podem acontecer
	// em caso de fluxo inesperado
}
```