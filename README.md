# Fundamentos de HTML

```
 <!DOCTYPE html>
```

tag de configuração informado que vai usar as configurações do HTML5

<hr>

# Títulos:

```
<h1>título</h1> - Título nível 1
<h2>título</h2> - Título nível 2
<h3>título</h3> - Título nível 3
```

E assim por diante, vai até o nível 6

<hr>

# Linha Horizontal
```
<hr> faz uma linha horizontal como esta abaixo:
```

<hr>

# Parágrafo:

```
<p>loremhafhdasfjisdfmafhaufdasjifdanksfauhsf</p>
```



<hr>

# Quebra de Linha:

```
Tag <br> - broken roll

Exemplo: 

<p> O rato roeu<br> a roupa <br> do rei de roma.</p>

Ficaria assim: 

O rato roeu
a roupa
do rei de roma
```

<hr>

# Mostrar tags em formato de texto:

```
Para mostrar tags como "<br>" sem quebrar o texto coloque:
&lt - Less Than - Menor que(<)
&gt - Greater Than - Maior que(>)

Estes comandos mostram o sinal de menor e maior na tela sem causar o efeito de abrir ou fechar tags.
Por exemplo: &ltbr&gt ficaria assim:

<br>

``` 

# Comentários

```

No Visual Studio Code: <!-- -->

```

# Termo em Negrito:

```

<b>lorem</b> OU   👈 Só marca a palavra como negrito, é só design.
<strong>lorem</strong>   👈 O correto semanticamente é este pois os mecanismos de busca entendem que a palavra é importante

```

Resultado:

**lorem**


<hr>

# Termo em Itálico:

```

<i>lorem</i> 👈 termo em itálico simplesmente
<em>lorem</em> 👈 semanticamente correta já que os mecanismos de busca entendem que o termo está com ênfase.

```

Resultado:

<i>lorem</i>


<hr>

# Emojis 😁😋🤣😎😀

```

Encontre o código do emoji desejado por exemplo: U+1F525 (emoji code fire)
e troque U+ por &#x - &#x1F525.

Ou de um jeito mais fácil, cique no **botão do Windows** mais o botão de **ponto final** que vai abrir a lista de emojis do windows. 
Ou no Linux clique no botão **Command** e no botão de **ponto final** que irá abrir a lista.
Obs: Nesse segundo método não é 100% certo que o emoji vai aparecer em todos os navegadores.

```

Resultado:

# 🔥

<hr>

# <del>Texto Riscado</del>

```

Para fazer o Texto riscado utilize a tag del.
Exemplo:

<del>lorem</del>

```

Resultado:

<del>lorem</del>


<hr>

# <ins>Texto Sublinhado</ins>

```

Para fazer o texto sublinhado utilize as tags u ou ins. Exemplo:

<u>lorem</u>   👈Tag apenas para sublinhar. só design
<ins>lorem</ins>  👈Forma semanticamente correta de sublinhar, já que os mecanismos de busca o entendem
como um termo inserido.

```

Resultado:

<ins>lorem</ins>

<hr>

# Tag Code - Inserir códigos em HTML

```

A tag code coloca todos os espaços das letras com a mesma distância. Ideal
para ler códigos.

Exemplo:

<code>getElementById()</code>

```

Resultado:

<code>getElementById()</code>

<hr>

# MARCA TEXTO

```
Utilize a tag <mark> para usar o marca texto como se fosse em uma folha de papel.

Exemplo:

<mark>lorem</mark>

```

Resultado:

![lorem marca texto](https://user-images.githubusercontent.com/78625466/208302170-f9a976f7-2b3f-4121-af88-74ab85def3a8.PNG)


```

Obs: você pode mudar a cor do marca texto através do style, se usar a cor preta no mark, fica com aquele efeito de "arquivo secreto"

Exemplo:

<pre>
<p>
nacionalidade: Brasil
UF: Minas Gerais
conta no banco: <mark style="background-color:black">lorem</mark>
senha da conta no banco: <mark style="background-color: black">lorem</mark>
</p>
</pre>

```

Resultado: 

![arquivo confidencial](https://user-images.githubusercontent.com/78625466/208302378-c74f8f28-df51-4e1b-8878-18dde683fea9.PNG)


<hr>

# Texto identado e com formatação

```

A tag pre mostra o texto exatamente como foi escrito:

Exemplo:

<pre>
  <p>
     Um prato de trigo
     para três tigres tristes
     Um prato de trigo 
     para três tigres tristes
     Um prato de trigo
     para três tigres tristes
   </p>
</pre>

```

Resultado

<pre>
  <p>
     Um prato de trigo
     para três tigres tristes
     Um prato de trigo 
     para três tigres tristes
     Um prato de trigo
     para três tigres tristes
   </p>
</pre>

Ideal para escrever códigos junto com a tag code.

<hr>

# Listas Ordenadas:

```
Cria listas em ordem; tag <ol> define a lista, e tag <li> define o elemento.

Ex: 

<ol>
  <li>Acordar</li>
  <li>Escovar os Dentes</li>
  <li>Se exercitar</li>
</ol>

```

Resultado:

<ol>
  <li>Acordar</li>
  <li>Escovar os Dentes</li>
  <li>Se exercitar</li>
</ol>


A partir do HTML5 o <li> tornou-se opcional, pode declará-lo ou não que o resultado será o mesmo.
Existem tipos de ordenação para as listas ordenadas veja os exemplos:
 
 <h2> Tipos: </h2>
 <h3>"a"</h3>
 
 ```
 type="a" - enumera em letras minúsculas.
 
 Ex: 
 <ol type="a"> 
  <li>dar</li>
  <li>Escovar os Dentes</li>
  <li>Se Exercitar</li>
 </ol>
 
 ```
 
 Resultado:
 
  ![listas lists](https://user-images.githubusercontent.com/78625466/208975938-bafc00b4-2ee3-443c-8f8c-938a4c5fae47.PNG)

 
 
 <h3>"A"</h3>
 
 ```
 type= "A" - enumera em letras maiúsculas
 
 Ex:
 <ol type="A> 
  <li>dar</li>
  <li>Escovar os Dentes</li>
  <li>Se Exercitar</li>
 </ol>
 ```
 
 Resultado:
           
 <ol type="a"> 
  <li>dar</li>
  <li>Escovar os Dentes</li>
  <li>Se Exercitar</li>
 </ol>
