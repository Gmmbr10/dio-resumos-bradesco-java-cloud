**Break** significa quebrar, parar, freiar, interromper. E é isso que ele faz quando é utilizado.

**Continue**, como o nome diz, ele continua o laço.

### Break vs Continue

O **break** para o laço, enquanto o **continue** para somente a iteração atual.

## Exemplo

```java
for (int i = 1 ; i <= 5 ; i ++) {  
    if (i == 3)  
        break;  
    System.out.println(i);  
}
```

Resultado: contou até 2

```java
for (int i = 1 ; i <= 5 ; i ++) {  
    if (i == 3)  
        continue;  
    System.out.println(i);  
}
```

Resultado: contou até 5, mas pulou o 3