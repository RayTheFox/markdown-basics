#Básicos de Markdown

Markdown permite você usar um formato de texto fácil de ler, fácil de escrever, *o qual então é convertido para HTML válido para amostra no GitHub.*

##Escrita Básica

###Parágrafos

Parágrafos em Markdown são apenas uma ou mais linhas de texto consecutivo seguidas de uma ou mais linhas em branco.

```
Em 2 de julho, uma nave mãe alienígena entrou na órbita da Terra e dispensou alguns veículos espaciais “destroyer” com formato de pires, cada um com 15 milhas (24 km) de distancia.

Em 3 de julho, os Cavaleiros Negros, um esquadrão de F/A-18 Hornets da Marinha, participaram de uma invasão em um destroyer próximo à cidade de Los Angeles.
```

###Cabeçalhos

Você pode criar um cabeçalho adicionando um ou mais símbolos ```#``` antes do seu texto de cabeçalho. O número de # que você usa irá determinar o tamanho do cabeçalho.


```
# O maior cabeçalho (uma etiqueta <h1>)
## O segundo maior cabeçalho (uma etiqueta <h2>)
…
###### O sexto maior cabeçalho (uma etiqueta <h6>)
```

###Citações

Você pode indicar citações com um ```>```.

```
Nas palavras de Abraham Lincoln:

> Perdão meu amigo (?) 
```

###Personalizando texto

Você pode fazer do texto **negrito** ou *itálico*

```
*Esse texto será itálico*
**Esse texto será negrito**
```

Ambos **negrito** e *itálico* podem usar um ```*``` ou um ```_``` ao redor do texto para estilizar. Isso te permite combinar ambos negrito e itálico se necessario.

```
**Todos _devem_ comparecer ao encontro às 5 em ponto hoje.** 
```


##Listas## 

###Listas desordenadas 

Você pode fazer uma lista desordenada precedendo itens da lista com ```*``` ou ```–```
```
* Item
* Item 
* Item 

- Item 
- Item
- Item
```

###Listas ordenadas

Você pode fazer uma lista ordenada precedendo itens da lista com um número.

```
1. Item 1     
2. Item 2
3. Item 3
```

###Listas ninhadas

Você pode criar listas ninhadas paragrafeando itens da lista por dois espaços

```
1.  Item 1
    1. corolário para o ítem acima
    2. Ainda outro ponto para considerar
2. Item 2
    * Um corolário que não precisa ser ordenado.
       * Isso é paragrafado em 4 espaços, porque é dois espaços a mais do que o item acima
       *Você deve querer considerar fazer uma nova lista.
3. Item 3
```

##Formatação de código

###Formatos em linha

Use o acentos (``` ` ```) para formatar um texto em um formato de monoespaço especial. Tudo além das aspas aparece como é, com nenhum outro formato especial.

```
Aqui uma idéia: por que nós não pegamos `ProjetoSuperior` e tornamos isso em `**Projeto**Justo`.
```

Linhas multiplas

Você pode usar acentos em trio (<code>```</code>) para formatar texto como seu próprio bloco distinto.

```
Veja esse elegante programa que eu escrevi:


```
x = 0
x = 2 + 2
que é x
```

```


##Links

Você pode criar um link em linha cercando o texto do link em colchetes (```[ ]```), e então cercando o link em parenteses ( ```( )``` ).

Por exemplo, para criar um hyperlink para www.github.com, com um texto que diz, Visita GitHub!, 
