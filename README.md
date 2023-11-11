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

```
A partir do HTML5 o <li> tornou-se opcional, pode declará-lo ou não que o resultado será o mesmo.
Existem tipos de ordenação para as listas ordenadas veja os exemplos:
```
 
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
 <ol type="A"> 
  <li>dar</li>
  <li>Escovar os Dentes</li>
  <li>Se Exercitar</li>
 </ol>
 ```
 
 Resultado:
           
 <ol type="A"> 
  <li>dar</li>
  <li>Escovar os Dentes</li>
  <li>Se Exercitar</li>
 </ol>

             
             
<h3>"1"</h3>        
       
```
type="1" é o padrão, enumera em números normais
        
Ex:
        
 <ol type="1"> 
  <li>dar</li>
  <li>Escovar os Dentes</li>
  <li>Se Exercitar</li>
 </ol>       
```
 
 Resultado:
 
  <ol type="1"> 
  <li>dar</li>
  <li>Escovar os Dentes</li>
  <li>Se Exercitar</li>
 </ol>   
       


<h3>"i"</h3>

```
type="i" - enumera em algarismos romanos minúsculos.

Ex:
<ol type="i"> 
  <li>dar</li>
  <li>Escovar os Dentes</li>
  <li>Se Exercitar</li>
  <li>Estudar</li>
  <li>ir para a faculdade</li>
 </ol>

```

Resultado:

![algarismos romanovsky](https://user-images.githubusercontent.com/78625466/208977765-1ebe3810-1a05-4a92-8b76-f39addfcaf22.PNG)



<h3>"I"</h3>

```
type="I" - enumera em algarismos romanos maiúsculos.

Ex: 

<ol type="I"> 
  <li>dar</li>
  <li>Escovar os Dentes</li>
  <li>Se Exercitar</li>
  <li>Estudar</li>
  <li>ir para a faculdade</li>
 </ol>

```

Resultado:


<ol type="i"> 
  <li>dar</li>
  <li>Escovar os Dentes</li>
  <li>Se Exercitar</li>
  <li>Estudar</li>
  <li>ir para a faculdade</li>
 </ol>


# Listas Não Ordenadas

```
Crie listas sem ordem hierárquica(tipo itens a comprar no supermercado, requisitos para conseguir uma vaga de emprego e etc...),
A tag <ul> define a lista não ordenada e a tag <li> define os itens/elementos da lista.

Exemplo: 

<ul>
   <li>Arroz</li>
   <li>Feijão</li>
   <li>frutas</li
</ul>

```

<strong>Resultado: </strong>

<ul>
   <li>Arroz</li>
   <li>Feijão</li>
   <li>frutas</li
</ul>

ao invés de colocar a bolinha, se você quiser pode colocar outros símbolos como o quadradinho por exemplo.

```
Exemplo 1: 
 
<ul type="disc">
   <li>Arroz</li>
   <li>Feijão</li>
   <li>frutas</li
</ul>
```
    
<strong>Resultado: </strong>
    
    
<ul type="disc">
   <li>Arroz</li>
   <li>Feijão</li>
   <li>frutas</li
</ul>
    
    
    
```
Exemplo 2: 
 
<ul type="circle">
   <li>Arroz</li>
   <li>Feijão</li>
   <li>frutas</li
</ul>
```
    
<strong>Resultado: </strong>
 
<ul type="circle">
   <li>Arroz</li>
   <li>Feijão</li>
   <li>frutas</li
</ul>

    
    
```
Exemplo 3: 
 
<ul type="square">
   <li>Arroz</li>
   <li>Feijão</li>
   <li>frutas</li
</ul>
```
    
<strong>Resultado: </strong>
    
 <ul type="square">
   <li>Arroz</li>
   <li>Feijão</li>
   <li>frutas</li
</ul>


# Colocar link(Âncora) no site

```
<a href="https://github.com/BrunoSilva03">meu repositório público no GitHub</a>

```

<strong>Resultado: </strong>

<a href="https://github.com/BrunoSilva03">meu repositório público no GitHub</a>

<strong>href</strong> é referância hypertexto é o link do site ou página que você vai mandar o usuário.

Sempre que for colocar link para um site externo no seu site adicione <strong>target="_blank"</strong>, assim quando o
usuário clicar no link vai ser aberta uma nova aba no navegador e o usuário não vai sair do seu site. Veja abaixo um Exemplo:

```
<a href="https://www.linkedin.com/in/bruno-silva-rodrigues-62b6a51b0/" target="_blank" rel="external">Meu perfil no Linkedin(Bruno Silva)</a>

```

<strong>Resultado: </strong>


<a href="https://www.linkedin.com/in/bruno-silva-rodrigues-62b6a51b0/" target="_blank" rel="external">Meu perfil no Linkedin(Bruno Silva)</a>

<strong>Obs.</strong> Por algum motivo o target="_blank" no está funcionando no GitHub, deve ser alguma configuração específica do site 😅
mas em sites HTML funciona normalmente👍👍👍


<strong>rel="next"</strong> - informa que o link é a próxima página<br>
<strong>rel="prev"</strong> - informa que o link é a página anterior<br>
<strong>rel="nofollow"</strong> - quando você não sabe se o site que o link está referenciando é confiável.<br>

<strong>target="_blank"</strong> - quando clica no link abre uma nova aba no navegador.<br>
<strong>target="_self"</strong> - informa que você vai continuar no seu site. só que em outra página<br>

👆Tudo isso é bom para rankear bem no Google e em outros sites de buscas.👆


# Acessar lugares no projeto:


 ./ -  <strong>mesma pasta</strong>

 ../ - <strong>pasta anterior</strong>


 # Fazer download de algo no site:

 ```
 <a href="meulivro.pdf" download="meulivro.pdf" type="application/pdf">Download do meu livro em PDF.</a>

 <a href="livro/meulivro.zip" download="meulivro.zip" type="application.zip">Download do livro em formato .ZIP</a>


 ```
<h3>Não dá para fazer o exemplo prático aqui porque aqui não é um programa e sim um README.md</h1>

