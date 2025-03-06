Quando ocorre uma validação de execução de fluxo somente quando a condição for positiva, consideramos como uma estrutura **simples**.

Exemplo:

```java
double saldo = 25.0;  
double valorSolicitado = 26.0;  
  
if (valorSolicitado < saldo) {  
    saldo = saldo - valorSolicitado;  
}  

System.out.println(saldo);
```

> **Atenção**
> 
> Se a instrução tiver apenas uma linha, as chaves {} não são necessárias.
> Caso contrário coloque as chaves {} e siga a escrita do código.
> 
> Exemplo:
```java

if (valorSolicitado < saldo)
    saldo = saldo - valorSolicitado;  
 
if (valorSolicitado < saldo) {  
    saldo = saldo - valorSolicitado;  
    System.out.println(saldo);
}
```

