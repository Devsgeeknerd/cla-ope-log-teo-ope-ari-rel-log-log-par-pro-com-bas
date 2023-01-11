<!-- Título -->
# Operadores Lógicos — Teoria

***Conteúdo da Aula:***

Os operadores lógicos combinam duas ou mais expressões relacionais para criar uma lógica **verdadeira** ou **falsa**.

Os operadores lógicos são:

| Operador | Descrição |
| :------: | :-------: |
| E | Operador de conjunção |
| OU | Operador de disjunção |
| NÃO | Operador de negação |

## Operador Lógico “E”

O operador lógico **E** retornará verdadeiro somente se todas as expressões relacionais retornarem verdadeiro também.

A tabela abaixo representa seu funcionamento:

| Condição1 | Condição2 | Resultado |
| :-------: | :-------: | :-------: |
| Falsa | Falsa | Falso |
| Falsa | Verdadeira | Falso |
| Verdadeira | Falsa | Falso |
| Verdadeira | Verdadeira | Verdadeiro |

Vamos imaginar que temos as seguintes variáveis em nosso algoritmo:

```c
a : inteiro = 10;
b : inteiro = 7;
```

Nós podemos aplicar a condição **E** com estas duas variáveis inteiras.

O código seria o descrito abaixo:

```c
(a > b) E (b > a)
```

A condição acima será falsa.

Repare:

![Exemplo](https://d2v0x26thbzlwf.cloudfront.net/prod/14/img/rId15atocqyz2.3ab.png)

Agora, se invertermos a segunda parte da condição, deixando-a desse modo:

```c
(a > b) E (b < a)
```

Aí teremos como resultado da expressão **VERDADEIRO**, pois **A** é maior que **B** e **B** é menor que **A**, ou seja:

* Ambas as expressões são verdadeiras.

## Operador Lógico “OU”

O operador lógico **OU** retornará verdadeiro se pelo menos uma das expressões relacionais retornarem verdadeiro.

A tabela abaixo representa seu funcionamento:

| Condição1 | Condição2 | Resultado |
| :-------: | :-------: | :-------: |
| Falsa | Falsa | Falso |
| Verdadeira | Falsa | Verdadeiro |
| Falsa | Verdadeira | Verdadeiro |
| Verdadeira | Verdadeira | Verdadeiro |

Vamos fazer uma analogia ao exemplo que foi dado anteriormente: vamos às nossas duas variáveis mais uma vez:

```c
a : inteiro = 10;
b : inteiro = 7;
```

Vamos aplicar agora o operador **OU** da seguinte maneira:

```c
(a > b) OU (b > a)
```

Dessa vez, o resultado desta expressão será **VERDADEIRO** com o operador **OU**.

De fato, **B** não é maior que **A**; porém, a primeira expressão (**A** maior que **B**) é verdadeira.

Como pelo menos uma das condições foi satisfeita, ou seja, retornou **VERDADEIRO**, a expressão acima também retornará **VERDADEIRO**.

## Operador Lógico “NÃO”

O operador lógico **NÃO** inverte uma condição lógica.

Veja a sua tabela de funcionamento, também chamada de tabela-verdade:

| Condição | Resultado |
| :------: | :-------: |
| Verdadeira | Falso |
| Falsa | Verdadeiro |

Vamos mais uma vez às nossas variáveis **A** e **B**:

```c
a : inteiro = 10;
b : inteiro = 7;
```

Agora vamos imaginar a seguinte expressão:

```c
a > b;
```

Nós sabemos que esta expressão retornará verdadeiro, pois 10 é maior que 7.

Agora, se aplicássemos o operador **NÃO**...

```c
NÃO (a > b);
```

Na expressão acima, o resultado será **FALSO**, pois a expressão **“a > b”**, que retornara **VERDADEIRO**, passa a retornar **FALSO** por causa do operador de negação **NÃO**.

<!-- Information -->
## &#8505; Informações

![Visitors](https://api.visitorbadge.io/api/visitors?path=Devsgeeknerd%2Fcla-ope-log-teo-ope-ari-rel-log-log-par-pro-com-bas&label=Visitantes&labelColor=%23f9e64f&countColor=%23008000&style=plastic "Total de Visitas")
&nbsp;
![Followers](https://img.shields.io/github/followers/Devsgeeknerd?style=p&label=Seguidores&labelColor=f9e64f&color=008000 "Total de Seguidores")
&nbsp;
![Watchers](https://img.shields.io/github/watchers/Devsgeeknerd/cla-ope-log-teo-ope-ari-rel-log-log-par-pro-com-bas?style=p&label=Observadores&labelColor=f9e64f&color=008000 "Total de Observadores")
&nbsp;
![Stars](https://img.shields.io/github/stars/Devsgeeknerd/cla-ope-log-teo-ope-ari-rel-log-log-par-pro-com-bas?style=p&label=Estrelas&labelColor=f9e64f&color=008000 "Total de Estrelas")
&nbsp;
![Forks](https://img.shields.io/github/forks/Devsgeeknerd/cla-ope-log-teo-ope-ari-rel-log-log-par-pro-com-bas?style=p&label=Bifurcações&labelColor=f9e64f&color=008000 "Total de Bifurcações")
&nbsp;
![Repo Size](https://img.shields.io/github/repo-size/Devsgeeknerd/cla-ope-log-teo-ope-ari-rel-log-log-par-pro-com-bas?style=p&label=Tamanho&labelColor=f9e64f&color=008000& "Tamanho do Repositório")
&nbsp;
![License](https://img.shields.io/github/license/Devsgeeknerd/cla-ope-log-teo-ope-ari-rel-log-log-par-pro-com-bas?style=p&label=Licença&labelColor=f9e64f&color=008000 "Licença do Repositório")
