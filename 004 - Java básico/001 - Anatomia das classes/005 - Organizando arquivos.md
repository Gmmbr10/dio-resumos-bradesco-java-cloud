
Conforme o sistema vai evoluindo, surgirão diversos arquivos no projeto. Isso exige que a organização destes arquivos através de pacotes.

## Convenção dos sub-diretórios

Geralmente usamos um prefixo para separar, parecido com extensões de sites.

Comercial - com
Organizacional - org
OpenSource - org, opensource

> **Exemplo**
> 
> com.empresa.nomedafuncionalidade.finalidade

## Na prática

Dentro da pasta `src/` você irá criar uma pasta para cada . (ponto), dependendo de como for a sua IDE você pode criar direto com o nome do pacote que ela já ira criar cada pasta.

> **Deve ficar assim:**
> 
> com/
> 	empresa/
> 		nomedafuncionalidade/
> 			finalidade/
> 				Classe.java

### No arquivo...

Terá o seguinte código no início

```java
package nome.do.pacote;
```