A linguagem Java dispõe de uma variedade de classes que representam exceções, e estas classes são organizadas em uma hierarquia denominadas **Checked and Unchecked Exceptions** ou *Exceções Checadas e não Checadas*.

## Tipos de exceções

**Exception:** você trata a exceção
**RuntimException:** os desenvolvedores não querem que você trate determinada exceção

## Criando uma exceção personalizada

Criamos um arquivo para a classe de exceção e colocamos o seguinte
```java
public class NomeException extends Exception {}
```

Já no arquivo do projeto nós fazemos o seguinte
```java
import NomeException;
public class Exemplo {
	private static String metodoExemplo() throws NomeException {
		//quando for disparar a exceção
		throw new NomeException();
	}
	public static void main(String[] args) {
		// consumindo algo com exceção
		try {
			// código a ser executado
		} catch (NomeException error) {
			// tratar exception
		}
	}
}
```