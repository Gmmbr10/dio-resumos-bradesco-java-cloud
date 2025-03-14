
## Impedindo que uma classe seja estendida

Vamos supor que você tem duas classes, `A` e `B`, onde A é a base e B é uma classe filha de A e não pode ser estendida.

Como impedir:

```java
// A.java
public class A {}
// B.java
public final class B extends A {}
```

Assim, quando você criar uma classe `C` por exemplo, você consegue estender somente de A, e para que não possa ser estendida coloca `final` antes de `class`.

## Escolhendo quem herda

Vamos supor que você têm uma classe A, B, C e D, mas somente as classes B e D podem ter a herança da classe A. Como permitir isso?

```java
// A.java
public sealed class A permits B, D {}

// B.java
public non-sealed class B extends A {}

// C.java
public class C {}

// D.java
public non-sealed class D extends A {}

```

> A classe que foi definida como filha deve ser `final`, `sealed` ou `non-sealed`.

## Verificando instância

Vamos supor que temos as classes A e B, e que B é filha de A. Mas quando você instância essa classe, você tipa ela como A, mas você quer usar um método de B. Como verificar se essa instância pode ser B e como executa-la?

```java
// A.java
public class A {
	public String name;
}

// B.java
public class B extends A {
	public void metodo() {
		System.out.println("Método de B");
	}
}

// Main.java
public class Main {
	public static void main (String[] args) {
		A classA = new B();

		if ( classA instanceof B variavelCasoSejaVerdade ) {
			variavelCasoSejaVerdade.metodo();
		}
	}
}

```