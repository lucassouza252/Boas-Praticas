# Boas-Práticas

<p>Aqui neste tópico abordarei sobre boas práticas, padrões de codificação, entre outros, do qual creio ser o melhor para entendermos o nosso código , e de outras pessoas, isto é, deixa o código mais legível.</p>

## Estes padrões sao bem aplicados para as linguagens:
<ul>
    <li> C; </li>
    <li> C++; </li>
    <li> C#; </li>
    <li> Java. </li>
</ul>

<p>Porem nada impede de utilizar em outras linguagens, obedecendo as boas práticas da propria comunidade da linguagem, é claro. </p>

### Nomeclaturas
<p>Como  primeiro passo vamos falar sobre nomeclaturas. </p>

<p>Para classes, usamos o nome com a primeira letra maiuscula. </p>

<p>Exemplo: </p>

#### Errado!!!
<pre><code>class casa {

    ...
    
};</code></pre>


#### Certo!!!
<pre><code>class Casa {

    ...
    
};</code></pre>

<p>Para variáveis, métodos entre outros, usamos a primeira letra do nome menúscula. Caso seja um nome composto, usamos o estilo 'camelCase'.
Ou seja, como as corcovas de um camêlo, que quando visto, é como ondas, ou curvas... Isto demonstra que, no meio da palavra em menúscula terá letras maiuscula
que será a primeira letra da segunda, ou mais palavras, da nomeclatura composta.</p>

<p>Exemplo: </p>

#### Errado!!!
<pre><code>var NomedeFulano;

public void Fatorialdefibonnaci(int[] vet);

String[] alunosdaescola;</code></pre>

#### Certo!!!
<pre><code>var nomeDeFulano;

public void fatorialDeFibonnaci(int[] vet);

String[] alunosDaEscola;</code></pre>

### Espaços

<p>Para tornar mais legível seu código, é uma boa pratica manter um certo espaço, seja da indentação, entre métodos, ou ate mesmo em blocos de códigos.</p>

<p>Para melhor visualização do seu código, é boa prática sempre usar uma tabulação(tab) para a implementação dentro de cada método, classe, ou bloco de código.</p>
<p>Alem da indentação, é sempre bom saltar uma linha para começar a implementação do método ou classe, também saltar linha entre métodos e comandos. Afinal tudo junto fica difícil ler, correto?</p>

<p>Exemplo: </p>

#### Errado!!!
<pre><code>void imprimirAlgo(){
Console.WriteLine("Algoooo");
}
for(int i=0; i!=5; i++){
i = i--;
}</code></pre>

#### Certo!!!
<pre><code>void imprimirAlgo(){

    Console.WriteLine("Algoooo");
}

for(int i=0; i!=5; i++){
    i = i--;
}</code></pre>

<p>Uma boa prática quando for usar bloco de código de apenas uma linha, ou algum tipo de JSON, é bom ter espaço entre palavras e parêntesis. Claro que não interfere em nada, Mas é questão de organização.</p>

<p>Exemplo: </p>

#### Errado!!!
<pre><code>{"nome":"Lucas", "type":string}
{8 > 6 ? print("Maior") : print("Menor")}</code></pre>

#### Certo!!!
<pre><code>{ "nome": "Lucas", "type": string }
{ 8 > 6 ? print("Maior") : print("Menor") }</code></pre>

<p>Tudo isto que apresentei aqui não é obrigatorio a ninguem. Porem, como ja foi dito antes, é uma questão de padrão adotado pela maioria dos programadores, alem de tornar mais facil e menos cansativa a leitura do seu código.
Claro que ainda tem mais coisas, mas isto é escolha sua, caro programador, usar ou não.</p>
