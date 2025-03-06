**Array:** conjunto de dados
- sempre inicia com o índice 0

Interagindo com array:

```java
String[] alunos = {"Adrian","Eduarda","Giovanne","Lara","Thalita"};  
  
for ( int indice = 0 ; indice < alunos.length ; indice ++ ) {  
    System.out.println("O aluno no índice " + indice + " é " + alunos[indice]);  
}
```

## For Each

Sempre ligado aos arrays

```java
for (String aluno : alunos) {  
    System.out.println(aluno);  
}
```