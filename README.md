# CDEC - Ciência de Dados: Estatística e Computação
Estudando ciência de dados

## Integrantes

- [Ben Dêivide (DEFIM/UFSJ)](http://bendeivide.github.io)
- [Marcelo Carlos Ribeiro/UFOP](http://lattes.cnpq.br/7535255933317217)
- [Matheus Fernando (Eng. Mec/UFSJ)](https://www.linkedin.com/in/matheus-fernando-santos-219555b0)

## Ementas para referência

- [Ementa 1](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiDy5HUksfvAhWRHrkGHRThDjEQFjADegQIFBAD&url=https%3A%2F%2Fwww.ime.usp.br%2F~pam%2Fprog_5905.pdf&usg=AOvVaw3Ov8IOktdwSRpN07uJInvK)

## Materiais interessantes
- [Introdução à ciência de dados](http://www.ime.usp.br/~jmsinger/MAE5755/cdados2020set30.pdf)
- [Data Science with R](https://r4ds.had.co.nz/)
- [Visão Geral da Ciência de Dados](https://geessyca.github.io/VisaoGeralCienciadeDados/#1)
- [Introduction to Data Science](https://rafalab.github.io/dsbook/)

# Estudando RMarkdown e Markdown

O entendimento sobre o RMarkdown e o Markdown será muito importante para desenvolvermos os nossos materiais. Segue uma apresentação preliminar:

- [Rmarkdown](https://geessyca.github.io/Rmarkdown/#1)

# Como usar o GitHub

Para entender como usar o GitHub e nossos projetos R/Python/RStudio, assista a série [rapidinahs do R (0005 - 00011)](https://youtube.com/playlist?list=PL-20Z1XFWKR1YPXb12UMmXRsAKelZhzca).

# Linguagens de programação

Iremos iniciar a falar sobre as duas principais linguagens que iremos trabalhar, o ambiente R e o Python.

## Ambiente R

### Família de pacotes a serem estudados

- [Família tidyverse](https://www.tidyverse.org/)

### Estudando o R

Temos um curso em desenvolvimento que vale a pena estudar, seguido por vídeo-aulas, materiais escritos e exercícios. Acesse: <http://bendeivide.github.io/cursor>.


## Linguagem Python

### Introdução ao Python
Por volta dos anos 1980, o holandês [Guido Van Rossum](https://gvanrossum.github.io/), que até então trabalhava no time de desenvolvimento da linguagem ABC no CWI (Centrum Wiskunde & Informatica), o instituto nacional de pesquisa em matemática e ciência da computação da Holanda, se tornaria a principal figura responsável pela criação do Python, uma linguagem de programação com ampla aplicabilidade que atingiu alta popularidade entre desenvolvedores, acadêmicos e empresas (incluindo gigantes como Google, YouTube e Dropbox).

Sucintamente, podemos descrever o Python como uma linguagem de programação open source de alto nível, interpretada, interativa e orientada a objetos. Sua aplicação é bastante versátil e inclui desenvolvimento de aplicativos, páginas da web, análise de dados, automatização de rotinas e até mesmo desenvolvimento de jogos.

O Python está disponível para muitos sistemas operacionais, incluindo os populares Linux, Mac OS e Windows. A versão mais recente para seu processador e sistema operacional (SO) pode ser encontrada para download na [página oficial do Python](https://www.python.org/).

Após a instalação, você poderá utilizar a linguagem por meio do seu terminal ou prompt de comando, além do IDLE, o ambiente de desenvolvimento integrado (do inglês, Integrated Development Environment, ou IDE) padrão do Python, criado pelo já citado fundador da linguagem, [Guido Van Rossum](https://gvanrossum.github.io/). A utilização de outros IDE's, além do próprio IDLE, podem tornar a experiência com a linguagem mais didática e/ou dinâmica, porém trata-se uma escolha que fica a critério do estudante/programador. Algumas alternativas de IDE's para programação Python são o [Spyder](https://www.spyder-ide.org/), o [Pycharm](https://www.jetbrains.com/pycharm/download/) e o [RStudio](https://www.rstudio.com/products/rstudio/download/).

### Primeiros comandos no Python
Com o Python já disponível na sua máquina, é o momento de inaugurar a experiência com a linguagem. Tipicamente, o código mais básico para iniciar os estudos é retornar **"Olá, Mundo!"** na tela.


**Código**
```Python
print('Ola, Mundo!')
```
**Output**
```
Ola, Mundo!
```

Finalmente, temos nosso primeiro programa no Python! É válido citar que as aspas utilizadas podem ser simples ou duplas.

Para a construção de um código bem estruturado, é importantíssimo adicionar comentários conforme o trabalho avança, garantindo que a leitura do programa fique o mais dinâmica possível, permitindo melhor compreensão e facilitando o ajuste de possíveis erros.

Por padrão, os comentários no Python são inseridos utilizando o símbolo **#** + 1 espaço + comentário. É recomendável utilizar ao menos **2 espaços** entre a última linha de código e um comentário, conforme o exemplo a seguir.


**Código**
```Python
var = 'Ola, Mundo!'  # Exemplo de comentário 1
print(var)  # Exemplo de comentário 2
```
**Output**
```
Ola, Mundo!
```

Cada código trará suas informações no formato que mais se adeque ao seu objetivo, sendo assim, o Python apresenta diferentes tipos de dados possíveis. Para os primeiros passos, os tipos de dados mais utilizados serão os demonstrados abaixo:


* **str:** Dado no formato texto, `string` representa uma sequência de caracteres

Exemplos de strings: "Olá, Mundo!", "CDEC", "Python"...

* **int:** Dado numérico no formato inteiro (integer)

Exemplos de números de tipo integer: 1, -2, -5, 15...

* **float:** Dado numérico no formato "flutuante", apresentando casas decimais após a parte inteira

Exemplos de números de tipo `float`: 1.20, -13.444, 15.89...

* **bool:** Dado no formato "booleano", tendo como característica os valores `True` e `False`

Os únicos valores possíveis para uma variável booleana são `True` e `False`


A função `type()` pode nos mostrar o tipo da variável, enquanto as funções `str()`, `int()`, `float()` e `bool()`
permite fazer os valores transitarem entre diferentes tipos, como pode ser observado nos exemplos abaixo:

```Pycon
>>> a = True
>>> x = 1
>>> y = -3.50
>>> z = "Olá, Mundo!"
>>> print(type(a))
<class 'bool'>
>>> print(type(x))
<class 'int'>
>>> print(type(y))
<class 'float'>
>>> print(type(z))
<class'str'>
>>> print(str(x))
1
>>> print(int(y))
-3
```

Além dos tipos de variáveis comuns à todas as liguagens de programação explicada acima, também existem outros tipos
menos comuns ou exclusivas de Python. Esses outros tipos de variáveis, na grande maioria são relacionados a tipos
iteráveis, ou seja, que podem conter mais de um único elemento. Esses tipos são:

* `list`: Como o nome sugere, é uma lista onde podemos armazenar vários outros tipos de variáveis, até mesmo outras
  listas;

* `tuple`: É o mesmo que a lista, com a diferença de que ela não pode ser modificada depois que inicializada;

* `dict`: É um tipo de lista que cada elemento possui uma chave e um valor atrelado a ela, também conhecido
  como dicionário;

* `set`: É muito parecido com listas, a diferença é que não é possível mudar os valores contidos nele,
  mas é possível adicionar novos, além disso, `set` só aceita um elemento do mesmo, ou seja, se outro elemento
  identico for adicionado ao `set`, ele será descartado;

Agora que sabemos da existência desses tipos de variáveis, vamos analisá-los um pouco mais a fundo separadamente,
começando com `list`.

### List

Como visto anteriormente, `list`s são listas que podem armazenar diferentes elementos. Essas listas são indexadas com
valores que começam em 0 para o primeiro elemento e n-1 para o último elemento, sendo n
o número total de elementos na lista. Agora vamos compreender como
utilizar esse tipo de variável em código.
```pycon
>>> # O character de hashtag (#) é usado para comentar partes do código e não será executado
>>> # inicializando uma lista vazia
>>> a = []
>>> # inicializando uma lista com elementos
>>> b = [1, 3.1415926, 'python', True]  # Note que são todos de tipos diferentes
>>> # adicionando elementos em uma lista
>>> a.append(42)
>>> a
[42]
>>> b.append(42)
>>> b
[1, 3.1415926, 'python', True, 42]
>>> # acessando um item da lista
>>> b[1]
3.1415926
>>> # índices negativos funcionam também, pensando na lista como se o primeiro e o último
>>> # índice estivessem conectados formando um círculo, se o 0 é o primeiro índice, o -1 
>>> # fica sendo o último, o -2 o penúltimo e assim sucessivamente.
>>> b[-1]
42
>>> # Acessando cortes ou slices da lista.
>>> b[:2]  # Cria uma lista com os dois primeiros elementos.
[1, 3.1415926]
>>> b[2:]  # Cria uma lista com os últimos elementos a partir do terceiro.
['python', True, 42]
>>> b[1:4]  # Cria uma lista do segundo elemento até o quarto elemento (último índice não incluso).
[3.1415926, 'python', True]
>>> # Criando uma lista bidimensional
>>> c = [
...   [1, 2, 3],
...   [4, 5, 6],
...   [7, 8, 9]
... ]
>>> # Acessando índices em uma lista bidimensional
>>> c[1]  # Retorna a segunda linha completa
[4, 5, 6]
>>> c[1][1]  # Retorna o segundo elemento da segunda linha
5
>>> # Removendo um elemento da lista e retornando esse mesmo elemento
>>> pi = b.pop(1)  # pop recebe o índice que queremos remover como parâmetro
>>> pi
3.1415926
>>> b
[1, 'python', True, 42]
>>> # Removendo elementos da lista sem retornar nenhum valor
>>> del b[-1]  # Dessa forma também é possível remover slices utilizando a notação apresentada acima
>>> b
[1, 'python', True]
>>> # Mudando um valor da lista
>>> b[0] = 2
>>> b
[2, 'python', True]
```

Aqui vimos o básico sobre listas, veremos mais sobre elas em tópicos mais para frente. Para criação e acesso de listas
n-dimensionais, basta continuar criando listas dentro de listas, e colchetes para cada nível que for adicionado.

### Tuple

Como visto anteriormente, `tuple`s são listas imutáveis e, por esse motivo ela não tem grande parte das funções
mostradas na sessão de listas. Entretanto, a criação de uma `tuple` é tão simples quanto a de lista e o acesso é
idêntico.

```pycon
>>> # Criando uma tuple
>>> a = (1, 3.1415926, 'python', True)
>>> # Acessando elementos
>>> a[1]
3.1415926
>>> # Tentando mudar um valor da tuple
>>> a[1] = 3
Traceback (most recent call last):
  File "/usr/lib/python3.9/code.py", line 90, in runcode
    exec(code, self.locals)
  File "<input>", line 1, in <module>
TypeError: 'tuple' object does not support item assignment
```

Como podemos ver, `tuple` é um tipo de variável bem simples de compreender, e quando tentamos modificar algum valor
nela, o programa levanta um erro.

### Dict

Também visto anteriormente, `dict` ou dicionários são um outro tipo de lista que possuem pares de chaves e valores
`{"key": value}`, dessa forma conseguimos acessar um determinado elemento não pelo seu índice, mas pela sua chave.
Veremos agora como utilizar `dict`s em código.

```pycon
>>> # Inicializando um dict vazio.
>>> a = {}
>>> # Inicializando um dict com chaves e valores.
>>> b = {'linguagem': 'Python', 'versão': 3.9, 'descrição': 'Script para ensinar a utilização de dicionários'}
>>> # Adicionando um par de chave, valor.
>>> a['resposta'] = 42
>>> a
{'resposta': 42}
>>> # Acessando um item do dict.
>>> b['versão']
3.9
>>> # Removendo um item do dict e retornando esse item.
>>> c = b.pop('versão')  # Retorna apenas o valor da chave.
>>> c
3.9
>>> b
>>> {'linguagem': 'Python', 'descrição': 'Script para ensinar a utilização de dicionários'}
>>> # Removendo um item do dict sem retornar
>>> del b['descrição']
>>> b
{'linguagem': 'Python'}
>>> # Mudando um valor do dict
>>> b['linguagem'] = 'Python3'
>>> b
{'linguagem': 'Python3'}
```

Veremos mais utilidades de dicionários na sessão de loops.

### Set

Como visto anteriormente, `set` é muito parecido com listas, a diferença é que não é possível mudar os valores
contidos nele, mas podemos adicionar novos. Lembrando, um mesmo elemento não será adicionado ao `set`.
Vamos ver em código como isso funciona.

```pycon
>>> # Inicializando um set
>>> a = {'Python', 3.9, 'dev'}
>>> # Adicionando um item ao set
>>> a.add('test')
>>> a
{'Python', 'dev', 3.9, 'test'}
>>> # Não aceita itens duplicados
>>> a.add('test')
>>> a
{'Python', 'dev', 3.9, 'test'}
>>> # Juntando dois sets
>>> b = {1, 2, 3}
>>> a.update(b)  # Funciona com qualquer tipo iterável.
>>> a
{'dev', 1, 3.9, 'test', 2, 3, 'Python'}
>>> # Removendo um item do set
>>> a.remove('test')  # Se o item especificado não existir, ocorrerá um erro.
>>> a
{'dev', 1, 3.9, 2, 3, 'Python'}
>>> a.discard('dev')  # Se o item especificado não existir, NÃO ocorrerá um erro.
>>> a
{1, 3.9, 2, 3, 'Python'}
>>> b = a.pop()  # Remove o primeiro item e o retorna.
>>> b
1
>>> a
{3.9, 2, 3, 'Python'}
```

Aqui vemos que `set` é um tipo de variável bem específico, outra característica importante dele é que ele é desordenado
e não possui uma forma de indexação, existem outras formas de verificar o que há dentro de um `set` que veremos na
próxima sessão.

### Condições em Python

Nessa sessão veremos como são usadas condições em Python. Veremos dois tipos diferentes e quando é melhor usar cada um.

#### if, elif e else

Como as outras linguagens mais conhecidas, Python também usa a notação `if` e `else` para criar
condições, entretanto, o que outras linguagens usam como `else if`, Python abrevia para `elif`.
Outra coisa muito importante é que Python não utiliza chaves `{}` como indicador de bloco de comando (escopo),
ele utiliza a própria identação para dizer qual parte do código é pertencente ao escopo. Vamos ver em código
como tudo isso funciona.

```python
# Inicializando variáveis para comparações
a = 3.1415926
b = 42
# Comparando usando if e else.

# Comparadores:
# igualdade: ==
# desigualdade: !=
# menor que: <
# maior que: >
# menor ou igual: <= 
# maior ou igual: >=
# contido em: in

# Operações booleanas
# negação: not
# e: and
# ou: or

if a == b:  # Sabemos que isso é falso, logo
    print("A é igual a B")
else:  # Esse será o resultado que veremos quando rodarmos o script
    print("A é diferente de B")

# Agora vamos utilizar uma entrada de usuário:
c = input("Escreva um número: ")  # Essa função nos permite escrever algo na tela e receber uma string do usuário.
c = float(c)  # Como o que recebemos é uma string, vamos convertê-la para float.

# Podemos usar vários elif para realizar as comparações. O primeiro resultado que for verdadeiro acaba com
# as comparações, ou seja, os outros elif e else dessa corrente de comparações não seram avaliados.

if c < a:
    print("O valor digitado é menor que A")
elif c == a:
    print("O valor digitado é igual a A")
elif c < a:
    print("O valor digitado é maior que A")
else:
    print("O valor digitado é inválido")

# Podemos criar um if dentro de outro if, também conhecido como if aninhado.
if a <= c <= b:  # Essa notação é usada para saber se o valor c está entre os dois valores especificados.
    if c > (a + b) / 2:
        print("O valor digitado está mais próximo de B")
    elif c < (a + b) / 2:
        print("O valor digitado está mais próximo de A")
    elif c == (a + b) / 2:
        print("O valor digitado está no centro de A e B")
    else:
        print("Algo de errado ocorreu.")

# Agora vamos ver como utilizar os operadores booleanos.
if not c == a:  # o operador not inverte o resultado.
    print("C não é igual a A")
if c >= a and c <= b:  # o operador and só retorna verdadeiro se todas as comparações forem verdadeiras.
    print("C está entre A e B")
if c == a or c == b:  # o operador or retorna verdadeiro se uma ou mais comparações forem verdadeiras.
    print("C é igual a A ou B")

# Por último veremos o comparador in
# função range(x, y, z), cria uma lista com números que começa em x, vai até y (y não incluso) com passo z. 
if c in range(10):  # se só um valor for passado, começa em zero e vai até o valor especificado.
    print("C é um número inteiro de 0 a 9")
# o comparador in também pode ser usado especialmente com o tipo de variável set para saber se um elemento está
# ou não dentro dele.
```

Aqui vimos como é o funcionamento do fluxo de comparações usando `if`, `elif` e `else`. Esse método é usado
principalmente para grandes comparações. Como visto, não utilizamos `;` no final de cada linha de comando e o que separa
os blocos de função são espaços de identação, normalmente um tab. Caso algo estranho esteja acontecendo com o seu
código Python, existe uma grande chance de ser um erro de identação.

#### Inline if-else

Outra forma de fazer comparações, nesse caso comparações simples e que necessitam apenas de um `if` e um `else`, podemos
usar a comparação em linha única. Vamos ver em código como funciona.

```python
idade = int(input("Digite sua idade: "))  # Convertemos a string para um inteiro agora
#    faço esse pedaço          se             caso contrário        faço esse
print("Você é maior de idade") if idade >= 18 else print("Você é menor de idade")

# também podemos usar esse método para colocar algum valor numa variável
# retorna    esse  se            senão   esse
situacao = "maior" if idade >= 18 else "menor"
print(situacao)  # Para confirmar qual foi escolhido.
```
#### Match case

A partir da versão 3.10 do Python, foi adicionado um novo método para fazer comparações que se assemelha com o que
conhecemos nas outras linguagens como switch case. Essa função é chamada de `match`, ela funciona como uma cadeia de
`if-else` tendo uma variável para realizar as comparações. Essa variável passa por `case`s de cima para baixo e o `case`
que combinar (match) será o executado. Vamos ver em código como isso funciona:

```python
# Vamos receber um valor representando a escolha do usuário.
valor = input("""
Escolha um animal:
1 - Cachorro
2 - Gato
3 - Hamster
4 - Cavalo
""")

# Poderíamos usar uma cadeia de if else para identificar o animal escolhido,
# mas, match é mais usado em casos de múltiplas escolhas.
match valor:
    # Como não convertemos valor para int, podemos comparar com str. 
    case '1':
        print("Você escolheu Cachorro!")
    case '2':
        print("Você escolheu Gato!")
    case '3':
        print("Você escolheu Hamster!")
    case '4':
        print("Você escolheu Cavalo!")
```

Diferente das outras linguagens, não é necessário colocar um `break` depois de cada `case`. O primeiro que for encontrado
será o único executado. Os valores comparados em cada `case` não precisam ser do mesmo tipo, isso nos permite,
por exemplo, identificar o tipo da variável e executar a função correta. Veremos funções mais adiante.

### Loops

Nesta sessão falaremos sobre os tipos de laços de repetições ou loops existentes em Python, apenas dois, mas
muito poderosos e flexíveis. Vamos começar com o mais simples de ser explicado dos dois, o `while`.

#### While

O laço de repetição `while` é normalmente utilizado para casos em que não sabemos quando uma determinada ação repetida
irá terminar, ou seja, ela não tem uma quantidade específica de vezes que ela deve ser executada. Dessa forma, é
necessário o desenvolvedor implementar uma condição de parada desse loop, caso contrário o programa não irá parar de
outro jeito se não diretamente pelo gerenciador de tarefas ou por um `break` dentro do loop.
Vamos ver como ele funciona em código.

```python
valor = float(input("Digite um valor entre 0 e 1: "))
while not 0 <= valor <= 1:
    valor = float(input("Digite um valor válido entre 0 e 1: "))
print(f"O valor digitado foi {valor}!")

# O mesmo pode ser feito usando break da seguinte forma.
while True:
    valor = float(input("Digite um valor válido entre 0 e 1: "))
    if 0 <= valor <= 1:
        break
print(f"O valor digitado foi {valor}!")
```

No primeiro laço de repetição, só entraremos no loop se a condição for verdadeira, caso contrário, o loop será completamente
ignorado e o fluxo do código continuará normalmente, entretanto, no segundo exemplo, pelo menos um loop será executado,
já que a condição será sempre verdadeira. Como dito anteriormente, isso pode causar problemas de laço infinito, então precisamos
colocar uma condição de parada dentro desse loop. Para os mais familiarizados com C/C++, o primeiro exemplo se assemelha com o
`while` e o segundo com o `do while`.

Além de sair completamente do laço usando o `break`, podemos também pular um único ciclo usando `continue`, dessa forma
podemos pular partes desnecessárias do código dado uma determinada condição. Vamos ver em código como isso funciona.

```python
# Vamos pedir um valor para o usuário, se esse valor não for igual o requerido, continuaremos o ciclo pedindo o valor
# novamente, caso o valor inserido seja correto, seguiremos o fluxo do código faremos aplicaremos uma potência de 2
# e sairemos do loop com um break.
while True:
    valor = float(input("Digite um valor válido entre 0 e 1: "))
    if 0 > valor > 1:
        continue
    valor **= 2
    break
print(f"O valor digitado elevado a dois é {valor}!")
```

Nesse caso, nós poderíamos utilizar apenas um `if else` para resolver esse problema, porem aqui compreendemos como ele pode
ser usado.

Outra coisa não muito comum dos loops em Python é a de podermos usar um `else` com eles. Apesar de incomum, isso nos
permite criar lógicas mais complexas conforme a necessidade. Vamos ver em código como isso funciona:

```python
# Não criaremos aqui um código complexo. Apenas veremos como utilizar o else após um loop.
# Vamos usar um dos exemplos anteriores.
valor = float(input("Digite um valor entre 0 e 1: "))
while not 0 <= valor <= 1:
    valor = float(input("Digite um valor válido entre 0 e 1: "))
else:
    # Esse bloco sempre será executado quando o loop anterior terminar.
    # Porem, isso não útil dessa forma. 
    print(f"O valor digitado foi {valor}!")

# Se usarmos o loop anterior, mas agora adicionando uma condição que leva a um break,
# veremos como essa junção pode ser interessante.
valor = float(input("Digite um valor entre 0 e 1: "))
while not 0 <= valor <= 1:
    valor = float(input("Digite um valor entre 0 e 1 ou -1 para sair: "))
    if valor < 0:  # Como estamos comparando floats, vamos considerar qualquer valor menor que zero.
        print("Saindo...")
        break
else:
    # Como dito anteriormente, esse bloco sempre será executado quando o loop anterior terminar,
    # mas SOMENTE se ele terminar, ou seja, se ele for terminado por um break esse print não será
    # exibido.
    print(f"O valor digitado foi {valor}!")
```

Usando essa técnica nós podemos executar diferentes códigos no caso do loop ser completamente executado e,
também no caso de o loop ser interrompido.

### For

O laço de repetição `for` é provavelmente o mais usado em Python. Ele é principalmente utilizado para iterar quantidades
conhecidas de vezes ou, sobre elementos duma lista ou objeto iterável (tuple, chaves de dicionários, sets, dataframes, etc).
Além disso, ele também pode ser usado dentro duma lista para a inicializar. Vamos ver como ele funciona em código.

```python
# Exemplo clássico de todas as linguagens de programação. Vamos contar de 1 até 10 e mostrar os resultados.
for i in range(1, 11):  # A função range retorna uma lista com os valores de range(início, final, passo)
    print(i)
# Também funciona como um for each (para cada elemento, faça...)
for fruta in ['maçã', 'banana', 'goiaba', 'abacaxi', 'melão']:
    print(fruta)
# break e continue também funcionam com for.
for fruta in ['maçã', 'banana', 'goiaba', 'abacaxi', 'melão']:
    if fruta == 'banana':  # Se a fruta for banana
        continue  # Esse loop termina aqui e outro ciclo é iniciado.
    elif fruta == 'abacaxi':  # Se a fruta for abacaxi
        break  # O loop é quebrado e os próximos elementos da lista não serão printados!
    print(fruta)  # Caso nada de cima acontecer, aqui as frutas vão aparecer.

# Também podemos fazer loops aninhados, ou seja, um loop dentro de outro loop.
# Aqui temos um exemplo de treinamento da tabuada.
for a in range(1, 11):  # Criamos um loop que vai de 1 a 10 e adicionamos esse valor em "a".
    for b in range(1, 11):  # Criamos outro loop que vai de 1 a 10 e adicionamos esse valor em "b".
        # Pedimos pro usuário o valor da operação abaixo e transformamos o resultado em um número inteiro.
        resultado = int(input(f'Quanto é {a} x {b}? \n'))  # \n é o mesmo que enter, ou quebra de linha.
        while not resultado == a * b:  # Se o resultado não for correto, entramos num loop while.
            print("Esse não é o valor correto, tente novamente!")
            resultado = int(input(f'Quanto é {a} x {b}? \n'))
        print("Valor correto!")  # Saindo do loop ou não entrando nele, chegamos aqui.

# Agora vamos iniciar uma lista com 10 elementos com valor igual à 0.
zeros = [0 for _ in range(10)]  # Simples assim
# Quando o valor que recebemos da lista não importa, podemos usar o character "_" para ignorá-lo, isso é valido em
# qualquer outro lugar além de loops.
# Para fazer uma lista bidimensional iniciada com zeros é tão simples quanto o mostrado acima.
zeros2x2 = [[0 for _ in range(10)] for _ in range(10)]  # Só não é muito intuitivo.
# O mesmo vale para qualquer outra dimensão, porém existem outras formas melhores para isso utilizando numpy.
```

Com o `for` nós também podemos usar `else` como mostrado no `while`. Vamos ver um exemplo simples:

```python
# Só a fins didáticos, vamos criar um loop de 0 a 9 e printar todos os valores menores que 7,
# caso o valor for maior, terminaremos o loop com um break.
for i in range(10):
    if i >= 7:
        break
    print(i)
else:
    print("Esse bloco nunca será executado...")

# Se tirarmos o break do loop, o else sempre será executado quando o loop terminar.
for i in range(10):
    print(i)
else:
    print("Esse bloco sempre será executado...")
```

### Tratamento de erros

Nessa sessão entenderemos como tratar erros e impedir que o programa simplesmente feche quando algum erro conhecido
ocorrer. Para isso, usaremos uma estrutura muito conhecida e utilizada nas outras linguagens de programação, conhecida
como `try-catch`, em Python `catch` é chamado `except` e temos duas outras palavras, `else` e `finally`. Vamos ver como
tudo isso funciona em código:

```python
# Primeiro vamos analisar o que cada keyword faz.
try:
    # Como o nome sugere, tenta executar um código
    print("Tentando executar...")
except:
    # Caso algo errado acontecer no código executado em try, esse bloco será executado
    # Obs.: Nunca use apenas except, sempre especifique qual o tipo de erro a ser tratado...
    print("Deu erro no try...")
else:
    # Esse bloco só será executado se não houver erro no try.
    print("Não deu erro no try...")
finally:
    # Esse bloco SEMPRE será executado, não importando se deu erro no try ou não.
    # Uma das possíveis utilizações é para fechar arquivos, criar logs ou coisas semelhantes.
    # Esse bloco só não será executado no caso do programa ser fechado forçadamente.
    # Ex.: os._exit()
    print("Sempre executado...")

# Não é necessário utilizar todas as keywords, apenas quando precisa.
# Para os casos mais genéricos, try e except são os únicos usados.
# Vamos ver um exemplo simples para tratar divisão por zero.

a = float(input("Digite um número: "))
b = float(input("Digite outro número: "))
try:
    # Vamos tentar dividir "a" por "b"
    print(f"{a} dividido por {b} é: {a / b}")
except Exception as e:
    # Aqui chamamos a exceção de "e" e verificamos se ela é do tipo ZeroDivisionError.
    # Se outro erro for encontrado, por exemplo ValueError, o código será fechado.
    if type(e) == ZeroDivisionError:
        # Se essa condição for verdadeira, o print abaixo é executado e o programa continua
        # sua execução normalmente.
        print("Divisão por 0 é indeterminada.")


# Agora vamos utilizar o else para adicionar elementos a uma lista apenas se não houver erros.
sair = False
while not sair:
    # Enquanto a opção sair não for verdadeira, continuaremos o loop.
    try:
        a = float(input("Digite um número: "))
        b = float(input("Digite outro número: "))
        # Vamos tentar dividir "a" por "b" guardar em "c"
        c = a / b
    except Exception as e:
        if type(e) == ZeroDivisionError:
            print("Divisão por 0 é indeterminada.")
        # Vamos verificar ValueError também
        if type(e) == ValueError:
            print("Valor digitado não é válido!")
    else:
        # Se não ocorrer nenhum erro no try, printamos o resultado de "c".
        print(f"O valor da divisão de {a} por {b} é {c}")
    # Agora vamos perguntar se o usuário deseja sair.
    # Se o valor digitado pelo usuário fizer parte dos valores contidos na lista,
    # sair vai receber True.
    sair = input("Digite S para sair ou N para continuar.") in ['s', 'S', 'sim']

# Também podemos passar diretamente o(s) tipo(s) a serem tratados no except.
try:
    # Algum código que possa dar erro!
    a = float(input("Um número não vai dar erro, uma letra vai..."))
    print("Eu posso dar erro...")
except ValueError:
    # Só trataremos o caso de ValueError.
    print("Um valor incorreto foi digitado...")

# No caso de tratamento de vários possíveis erros, usamos uma tuple com os problemas a serem tratados.
try:
    # Outro código que pode dar erro!
    a = float(input("Letra dá erro, número não..."))
    b = float(input("Letra dá erro, número não 2..."))
    # Como vimos anteriormente, divisão por zero também é um problema.
    c = a / b
except (ValueError, ZeroDivisionError):
    # Qualquer um desses problemas vai chamar esse except.
    # Mas aqui não vamos saber qual dos dois foi o erro causado.
    print("Deu erro, foi ValueError ou ZeroDivisionError")
```

Até aqui vimos alguns tipos de erro que podem ocorrer, mas nós também podemos **levantar** nosso próprio erro e,
dessa forma podemos fazer o tratamento necessário. Vamos ver em código como isso funciona:

```python
# Para levantar um erro é extremamente simples.
try:
    # raise -> levantar
    # Chamamos Exception com o nome do erro como parâmetro e pronto.
    raise Exception("NomeDoMeuErro")
except Exception as e:
    # Agora um pouco diferente dos anteriores,
    # vamos verificar se o nome que passamos está nos argumentos de "e".
    if "NomeDoMeuErro" in e.args:
        print("Meu erro foi levantado...")
```

Existem outras formas de criar uma exceção, mas elas requerem o conhecimento de classes, que ainda não
vimos. Com o que aprendemos até aqui, a maioria dos casos pode ser tratados facilmente. 

### Definindo funções em Python

Para definir uma função em Python é muito simples, apenas precisamos utilizar a palavra `def` seguida pelo nome da função
e parêntesis. Assim como os loops, também é necessário adicionar `:` para indicar o começo da função, também precisamos
lembrar que a identação em Python é essencial para identificar o escopo da função. Vamos ver em código como isso funciona:
```python
# Definindo uma função que não faz nada.
def faz_nada():  # Python não usa Camel Case para funções por convenção, ou seja, fazNada() não seria um bom nome.
    pass  # Não faz nada, literalmente. pass é muito usado em tratamento de erros (try, except).

# Agora vamos definir uma função que recebe um valor e duplica ele.
def print_dobrador(valor):
    """
    Documentação de função é feita com três pares de aspas.
    Esse pedaço funciona da mesma forma que um comentário.
    -------------------------------------------------------
    
    Essa função pode receber qualquer tipo de variável, e vai tentar multiplicar esse valor, caso essa operação
    não seja possível, o programa vai fechar com um erro do tipo TypeError.
    """
    print(valor * 2)

# Agora vamos definir uma função parecida com a de cima, mas com algumas coisas extras, e retornar o valor final.
def dobrador(valor: float) -> float:
    """
    Aqui definimos que o valor que queremos é do tipo float, e retornaremos também um float.
    Isso é o que gostaríamos, porém, a função ainda recebe qualquer tipo de variável. A diferença, é que agora
    a IDE que for usada sabe o que esperar daquela variável e, além disso, conseguirá identificar potenciais erros.
    O mesmo vale para o tipo que será retornado pela função. Só serve para ajudar a IDE e manter o programa organizado.
    """
    return valor * 2  # Retorna o valor multiplicado por 2.

# Uma função também pode ter um valor default.
def faz_nada2(valor1: int, valor2: float = 10.0, valor3: str = "Olá") -> None:  # Retorna nada.
    """
    Utilizando o sinal de igual (=) podemos atribuir um valor default para qualquer parâmetro da função, porém, todo
    parâmetro que vier a seguir também precisa ter um valor default.
    Esse formato também é válido:
    def faz_nada2(valor = 10)
    """
    pass

# Podemos passar quantidades indefinidas de variáveis também.
def gera_polinomio(*args: float) -> str:
    """
    Nessa função, vamos receber valores que correspondem as n constantes de um polinômio e vamos retornar uma
    string com esse polinômio. O argumento operador * nos permite receber vários argumentos e juntá-los em uma tuple. 
    """
    grau = len(args) - 1  # A função len retorna o tamanho de variáveis iteráveis. (list, tuple, str, ...).
    polinomio = ""  # Inicia uma string vazia.
    for i in range(grau, -1, -1):  # Contando do grau do polinômio até 0.

        # Se i não for igual ao grau da função o lado esquerdo do if é retornado.
        # O operador += tem o mesmo funcionamento que o código a = a + b. Funciona com os outros operadores também.
        polinomio += f" + {args[grau - i]}X^{i}" if not i == grau else f"{args[grau - i]}X^{i}"
    return  polinomio  # Retorna a string com o polinômio.

# Também podemos receber vários pares de chave-valor usando **, mas como essa é uma introdução ao python, não iremos
# explicar como funcionaria esse caso.

# Por último, nesse tutorial, vamos retornar mais de um valor na mesma função.
def duplica_triplica(valor: float) -> (float, float):
    """
    Aqui mostramos que iremos retornar uma tuple com dois valores do tipo float.
    """
    return valor * 2.0, valor * 3.0  # Simples assim, apenas separamos por vírgula.

# Após definir as funções, precisamos chamá-las.
a = duplica_triplica(3)  # Só precisamos passar o valor necessário do argumento, se houver.
# Nesse caso, a variável 'a' terá uma tuple com os valores (6, 9).
# Também podemos receber o resultado de outra forma.
b, c = duplica_triplica(4)  # Assim b recebe 8 e c recebe 12.
```

### Programação orientada a objeto em Python

Nessa sessão, nós vamos aprofundar um pouco mais em Python utilizando uma estrutura de dados complexa
muito utilizada também em outras linguagens, conhecida como **classe**. Mas antes disso, vamos compreender um
pouco o que é programação orientada a objeto (em Python), para isso, vamos primeiro definir o que é um objeto.

Quando programamos em Python, nós utilizamos objetos o tempo todo, apenas não vemos isso claramente. Como
vimos nos primeiros passos com Python, quando *printamos* na tela qual é o tipo de uma determinada variável,
nós recebemos como resposta algo do tipo:
```pycon
<class 'float'>
<class 'int'>
<class 'str'>
```

Aqui vemos uma palavra-chave em todas elas, `class` indica a criação de uma classe ou que a variável em questão
é um **objeto** do tipo especificado assim como mostrado acima. No final das contas, praticamente tudo em Python é
um objeto, até mesmo uma função é um objeto, ou seja, toda vez que criamos alguma variável ou definimos uma função,
por trás dos panos, estamos criando um objeto. Okay, e qual é a diferença entre classe e objeto? Para deixar um pouco
mais fácil, vamos pensar na classe como sendo uma receita de bolo genérica de qualquer sabor e no objeto como
sendo o bolo. Dessa forma temos a classe como a definição do objeto, e o objeto sendo o que vamos interagir diretamente.

Usando a analogia do bolo e da receita, podemos dizer que esse bolo precisa de ovos, massa pronta de qualquer sabor e
leite. Veja bem, não indicamos quantidade e nem o sabor. Esses são atributos da classe bolo que podem ser gravados em
um objeto. Vamos ver em código como isso funciona:

```python
# Para criar uma classe, só precisamos usar a palavra-chave class e o nome da classe
# Por convenção, criamos classes em Python usando letras maiúsculas para todas as primeiras letras
# Exemplos: Bolo, Carro, Animal, RedeNeural, RedeNeuralRecursiva.
class Bolo:
    def __init__(self, sabor: str, ovos: int, leite: float):
        """
        __init__ é o que chamamos de construtor em outras linguagens, ele será chamado bem no começo
        da classe, assim como o nome sugere, ele é o inicializador da classe.
        
        self (próprio) é uma palavra-chave para indicar que um objeto está contido, dentro, pertence
        a esse objeto apenas.
        
        Assim como vimos em como definir funções, as funções dentro das classes, ou melhor, métodos,
        são definidos praticamente da mesma forma, com a diferença que os métodos quando definidos
        sempre deverão ser inicializados com o argumento self como primeiro argumento.
        """
        # Aqui armazenamos os valores passados como parâmetro nos atributos desse objeto.
        # Mais uma vez, o self indica que algo é desse objeto, então self.sabor fala qual o sabor
        # desse bolo, não o de todos os bolos.
        self.sabor = sabor
        self.ovos = ovos
        self.leite = leite
        self.assado = False

# Aqui criamos um objeto do tipo bolo, chamado bolo_chocolate.
bolo_chocolate = Bolo("Chocolate", 3, 500)
# Podemos mudar os atributos desse bolo assim.
bolo_chocolate.leite = 450  # Apesar de possível, não é recomendado acessar um atributo dessa forma.
```

Bom, dessa forma, criamos nossa classe `Bolo` e nosso objeto `bolo_chocolate`, mas eles são quase um
`dict` do jeito que estão, ainda assim, muito melhor, pois não precisaremos definir a estrutura desse `dict` toda vez que
criarmos um objeto novo. Agora, vamos criar métodos nessa classe.

```python
class Bolo:
    def __init__(self, sabor: str, ovos: int, leite: float):
        """
        Mesma classe, mas sem os comentários.
        """
        self.sabor = sabor
        self.ovos = ovos
        self.leite = leite
        self.assado = False

    def qual_sabor(self):  # Lembrando, método sempre tem self como primeiro argumento.
        # Mesmo fora do escopo do método __init__, temos acesso a todos os atributos da classe
        # usando self.atributo.
        print(self.sabor)
        return self.sabor  # Métodos também podem retornar valores.

    def bater(self):
        # Primeiro vamos verificar se as quantidades são as corretas.
        if self.ovos == 3 or self.leite == 500:
            print("Batendo...")  # Caso correto
            return True  # Retornamos True para continuar.
        else:  # Caso contrário
            print("Quantidade de ingredientes fornecidos não são compatíveis com a receita")
            return False  # Retornamos False para cancelar.
    def assar(self):
        if self.bater():  # Se o método bater retornar True
            print("Assando...")  # Assamos o bolo.
            print("...30 minutos depois...")
            self.assado = True  # Mudamos o status de assado para True

bolo_chocolate = Bolo("Chocolate", 3, 500)
# Para acessar um método em um objeto, basta usar . e o nome do método com parêntesis.
bolo_chocolate.qual_sabor()
bolo_chocolate.assar()
# Por enquanto temos apenas um objeto do tipo bolo. Então vamos criar mais alguns.
bolo_baunilha = Bolo("Baunilha", 3, 450)  # Criando um objeto tipo Bolo, com sabor Baunilha.
bolo_cenoura = Bolo("Cenoura", 2, 500)  # Criando um objeto tipo Bolo, com sabor Cenoura.
# Podemos agora provar que apesar de serem do mesmo tipo, esses objetos têm atributos com
# valores diferentes.
bolo_baunilha.qual_sabor()  # Vai dar "Baunilha".
bolo_cenoura.qual_sabor()  # Vai dar "Cenoura".
# Se tentarmos assar esses bolos, teremos o erro de quantidade errada de ingredientes.
bolo_baunilha.assar()
bolo_cenoura.assar()
# Se mudarmos os atributos para os valores corretos
bolo_baunilha.leite = 500
bolo_cenoura.ovos = 3
# agora podemos assar sem problemas.
bolo_baunilha.assar()
bolo_cenoura.assar()
```

Aqui vimos como definir uma classe, criar um objeto dessa classe e criar uma estrutura de dados que represente
o objeto em questão. Mas ainda podemos melhorar essa classe. Por enquanto, nós só podemos fazer um bolo por
vez, e a receita sempre pede a mesma quantidade de ingredientes. Mas e se quisermos mudar a quantidade de bolos
ou a receita do bolo mudar com o tempo? Nesse caso teríamos que mudar todos os valores de comparação toda vez que
mudarmos a receita ou a quantidade de bolos. E se quisermos saber também quantos bolos foram criados? Teriamos
que criar uma variável para manter a contagem de objetos criados e somar mais 1 toda vez que um novo objeto for criado.
Isso além de ser trabalhoso, também possui uma grande possibilidade de esquecermos de contar um ou mais objetos.
Daí temos uma solução muito melhor para resolver esse problema, que são as variáveis estáticas da classe.
Essas variáveis são compartilhadas por todos os objetos do mesmo tipo, ou seja, o mesmo valor que estiver em
`bolo_chocolate` estará em `bolo_baunilha`. Vamos ver como isso funciona em código.
```python
class Bolo:
    """
    Para criar uma variável estática, basta criarmos ela fora do __init__ e sem a palavra-chave self
    """
    quantidade_ovos = 3
    quantidade_leite = 500
    quantidade_bolos_por_vez = 1
    quantidade_bolos_assados = 0

    def __init__(self, sabor: str, ovos: int, leite: float):
        """
        Mesma classe, só que sem os comentários.
        """
        self.sabor = sabor
        self.ovos = ovos
        self.leite = leite
        self.assado = False

    def qual_sabor(self):
        print(self.sabor)
        return self.sabor

    def bater(self):
        # Para acessar as variáveis estáticas dentro da classe, ainda precisamos usar self
        # ou o tipo da classe Ex.: Bolo.quantidade_ovos.
        # Dica: Coloque a condição do if entre parêntesis quando a linha ficar muito grande,
        # dessa forma podemos quebrar a linha em várias partes.
        if (self.ovos == self.quantidade_ovos * self.quantidade_bolos_por_vez or
                self.leite == self.quantidade_leite * self.quantidade_bolos_por_vez):
            print("Batendo...")
            return True
        else:
            print("Quantidade de ingredientes fornecidos não são compatíveis com a receita")
            return False
    def assar(self):
        if self.bater():
            print("Assando...")
            print("...30 minutos depois...")
            self.assado = True
            # Para alterar o valor da variável estática, precisamos usar o tipo da classe no lugar
            # da palavra-chave self ou um método de classe que veremos depois.
            Bolo.quantidade_bolos_assados += 1  # Soma 1 a quantidade de bolos assados.

# Primeiro vamos manter os valores padrões e vamos verificar se a quantidade de bolos aumenta
# quando assamos o primeiro bolo.
bolo_chocolate = Bolo("Chocolate", 3, 500)
bolo_chocolate.assar()

print(Bolo.quantidade_bolos_assados)  # bolo_chocolate.quantidade_bolos_assados mostra o mesmo valor.
# Agora vamos mudar a quantidade de bolos por vez.
Bolo.quantidade_bolos_por_vez = 2
bolo_baunilha = Bolo("Baunilha", 6, 1000)
bolo_baunilha.assar()
print(Bolo.quantidade_bolos_assados)
# Agora vamos mudar a quantidade de ingredientes para cada bolo.
Bolo.quantidade_ovos = 4
Bolo.quantidade_leite = 450
bolo_cenoura = Bolo("Cenoura", 8, 900)
bolo_cenoura.assar()
print(Bolo.quantidade_bolos_assados)
```

Outra forma de modificarmos as variáveis estáticas de uma classe é usando um método estático que chamamos em
Python de método de classe. Para isso, vamos precisar utilizar um decorador para identificar o método como estático.
Vamos ver em código como isso funciona.

```python
class Bolo:

    quantidade_ovos = 3
    quantidade_leite = 500
    quantidade_bolos_por_vez = 1
    quantidade_bolos_assados = 0

    def __init__(self, sabor: str, ovos: int, leite: float):
        """
        Mesma classe, só que sem os comentários.
        """
        self.sabor = sabor
        self.ovos = ovos
        self.leite = leite
        self.assado = False

    def qual_sabor(self):
        print(self.sabor)
        return self.sabor

    def bater(self):
        if (self.ovos == self.quantidade_ovos * self.quantidade_bolos_por_vez or
                self.leite == self.quantidade_leite * self.quantidade_bolos_por_vez):
            print("Batendo...")
            return True
        else:
            print("Quantidade de ingredientes fornecidos não são compatíveis com a receita")
            return False
    def assar(self):
        if self.bater():
            print("Assando...")
            print("...30 minutos depois...")
            self.assado = True
            Bolo.quantidade_bolos_assados += 1  # Soma 1 a quantidade de bolos assados.

    @classmethod  # Esse é o decorador do método.
    def muda_receita(cls, qt_ovos: int, qt_leite: float):
        """
        Aqui usamos a palavra chave cls no lugar de self.
        Essas são as únicas modificações necessárias para criar um método estático.
        Uma coisa importante é que esse método não tem acesso as variáveis não estáticas.
        """
        # Para obter acesso as variáveis da classe, usamos a palavra chave cls.
        cls.quantidade_ovos = qt_ovos
        cls.quantidade_leite = qt_leite


bolo_chocolate = Bolo("Chocolate", 2, 400)  # Vamos colocar um valor diferente do default
bolo_chocolate.muda_receita(2, 400)  # e assim mudamos a receita para combinar.
bolo_chocolate.assar()
```

Executando o código anterior não gera erro e completa todas as ações com sucesso. Esse tipo de método é
também usado para criar classes de funções. Por exemplo, temos um banco de dados e queremos organizar as funções
para realizar mudanças nesse banco num único lugar, para isso podemos criar uma classe que contenha todas as
ações necessárias. Vemos ver em código como isso funciona.

```python
# Não veremos como acessar bancos de dados ainda.
# Aqui nós vamos apenas criar uma classe com métodos estáticos para representar a ideia proposta.
class DBCore:
    """
    Essa é a nossa classe organizadora, ela será usada apenas com esse intuito.
    """
    @classmethod  # Não podemos esquecer do decorador.
    def ler(cls, **kwargs):
        """
        Quando recebemos um **kwarg, devemos passar sempre pares de valores, sendo que o
        primeiro valor do par é a chave do dicionário e o segundo é o valor.
        Ex: ler("sabor", "chocolate") -> {"sabor" : "chocolate"}
        """
        # Lê o banco de dados de acordo com o que foi passado em **kwargs.
        pass

    @classmethod
    def escrever(cls, **kwargs):
        # Escreve no banco de dados de acordo com o que foi passado em **kwargs.
        pass

    @classmethod
    def delete(cls, **kwargs):
        # Deleta algo no banco de dados de acordo com o que foi passado em **kwargs.
        pass

    @classmethod
    def atualizar(cls, **kwargs):
        # Atualiza algo no banco de dados de acordo com o que foi passado em **kwargs.
        pass

# Dessa forma, podemos acessar todos esses métodos pela classe DBCore.
# Para abrir um dicionário e separá-lo em chave e valor, utilizamos o operador **
DBCore.ler(**{"id": 3})
DBCore.escrever(**{"sabor" : "baunilha"})
DBCore.delete(**{"id" : 1})
DBCore.atualizar(**{"id" : 5, "sabor": "chocolate"})
```

Com isso, terminamos a nossa introdução a programação orientada a objeto em Python!

### Módulos Python para Data Science
Python é hoje em dia considerado a linguagem para cientistas de dados, isso se dá pelo fato de ela possuir vários módulos que facilitam a construção do algoritmo além de permitir em alguns casos a utilização de computação em GPU, tornando o processo muito mais rápido. Hoje os principais módulos usados são os seguintes:
* **Numpy:** NumPy é um projeto open source que permite executar computação numérica com Python de forma rápida e fácil, quase todas as ferramentas seguintes, se não todas, usam do poder de computação de arrays e matrizes de Numpy.
* **Scipy:** SciPy é um pacote de módulos Python open source voltados para ciência, matemática e engenharia. Dentro deste pacote são incluídos módulos como NumPy, Matplotlib (usado principalmente para plotagem de gráficos) e Pandas.
* **Theano:** Theano é um módulo Python que te permite definir, otimizar, e avaliar expressões matemáticas envolvendo arrays multi-dimensionais eficientemente. Ele é construído em cima de NumPy. Theano também te permite fazer computações de dados usando a GPU, aumentando a performance em até 140x.
* **TensorFlow:** TensorFlow é um módulo Python open source para machine learning. Ele tem um ecossistema abrangente e flexível de ferramentas, bibliotecas e recursos da comunidade que permite aos pesquisadores levar adiante ML de última geração e aos desenvolvedores criar e implantar aplicativos com tecnologia de ML.
* **Keras:** Keras é uma API desenvolvida para facilitar o desenvolvimento de modelos de machine learning diminuindo o número de ações que o usuário necessita fazer para casos comuns, além de mostrar mensagens de erro claras e que permitem encontrar a causa de forma mais fácil. Keras também possui uma documentação extensa e guias para o desenvolvedor. Hoje em dia é considerado uma das 5 melhores para deep learning.
* **PyTorch:** Assim como TensorFlow, PyTorch é um módulo Python open source para machine learning. Ele é baseado na biblioteca Torch que também está disponível para C++.
* **Pandas:** Pandas é uma ferramenta open source essencial para análise de dados em Python. Ele é rápido, flexível e fácil de usar. Com ele é possível fazer a criação e manipulação de Data Frames, além de poder fazer um resumo estatístico do Data Frame com um único comando.
### Introdução ao Numpy
Primeiramente, antes de usar o módulo numpy, é necessário que ele esteja instalado no computador ou virtual environment
de desenvolvimento. Para isso, assim como quase todos os módulos para Python, podemos fazer essa instalação utilizando o
`pip` ou `conda`.

`pip install numpy` ou `conda install numpy`

Agora com o módulo instalado podemos utilizá-lo em código. Para isso precisamos primeiro importar esse módulo da
seguinte forma:
```python
import numpy as np
```
Essa é a forma que o módulo numpy é normalmente importado. Esse código nos permite escrever apenas `np` quando formos
utilizar alguma função Numpy, esse mesmo formato será visto posteriormente.

Numpy contem arrays multidimensionais e matrizes como estrutura de dados. Ele disponibiliza um tipo de dado chamado
`ndarray` que como o nome sugere, é um array multidimensional. Esse tipo de dado contém vários métodos para fazer
operações sobre ele de forma eficiente e facilmente, a maioria das vezes mais rápido que listas nativas do Python.
`ndarray` juntamente com Numpy, adicionam estruturas de dados cálculos eficientes com arrays e matrizes e ainda
disponibilizam uma grande gama de funções matemáticas de alto nível que operam nesses arrays e matrizes.

Para criar um `ndarray` inicializado com todos os indices como 0 ou 1 basta seguir o código abaixo:
```python
>>> import numpy as np
>>> # Inicializa um ndarray com 10 elementos todos com o valor 0
>>> a = np.zeros(10)
>>> # Inicializa um ndarray com 10 elementos todos com o valor 1
>>> b = np.ones(10)
```
Para criar um `ndarray` usando uma lista Python é necessário fazer o seguinte:
```python
>>> c = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
>>> d = np.array(c)  # Também é possível utilizar a lista diretamente como parâmetro
```
Os cálculos básicos como soma, subtração, multiplicação e divisão são tão simples quanto as operações de variáveis
numéricas:
```python
>>> e = b + d
>>> e
array([ 2.,  3.,  4.,  5.,  6.,  7.,  8.,  9., 10., 11.])
>>> e = b - d
>>> e
array([ 0., -1., -2., -3., -4., -5., -6., -7., -8., -9.])
>>> f = e * d
>>> f
array([  0.,  -2.,  -6., -12., -20., -30., -42., -56., -72., -90.])
>>> f = e / d
>>> f
array([ 0.        , -0.5       , -0.66666667, -0.75      , -0.8       ,
        -0.83333333, -0.85714286, -0.875     , -0.88888889, -0.9       ])
```
Para criar `ndarrays` multidimensionais existem algumas formas, como usar uma lista
Python multidemensional ou simplesmente iniciar um `ndarray` com valores aleatórios. Esses não são os
únicos métodos para realizar essa tarefa, mas já é um bom começo para se habituar ao Numpy.
```python
>>> # Utilizando Python list
>>> g = [[1, 2, 3], [4, 5, 6]]
>>> h = np.array(g)
>>> h
array([[1, 2, 3],
       [4, 5, 6]])
>>> # Inicializando com método empty.
>>> h = np.empty((2, 2))
>>> h
array([[1.5711153e-316, 0.0000000e+000],
       [0.0000000e+000, 0.0000000e+000]])
```

As mesmas regras de operações entre matrizes também são aplicadas aos `ndarrays`, ou seja,
se tivermos uma matriz 2x2 e tentarmos multiplicar por um vetor de tamanho 3 teremos um erro no código
e o programa irá levantar uma exceção.

```python
>>> h = np.empty((2, 2))
>>> a = np.random.rand(2)  # Inicializa um vetor de tamanho 2 com números aleatórios
>>> a
array([0.22500409, 0.32657332])
>>> a * h  # Operação com sucesso
array([[3.535074e-317, 0.000000e+000],
       [0.000000e+000, 0.000000e+000]])
>>> a = np.random.rand(3)  # Vetor agora com 3 números aleatórios
>>> a * h  # Essa operação gera erro
Traceback (most recent call last):
File "/usr/lib/python3.8/code.py", line 90, in runcode
exec(code, self.locals)
File "<input>", line 1, in <module>
ValueError: operands could not be broadcast together with shapes (3,) (2,2)

```

Como podemos ver pelo erro, a operação não foi sucedida pelo fato de não terem formatos compatíveis.

Agora que sabemos como inicializar `ndarrays` e fazer operações com eles, ainda precisamos saber como
acessar os valores dentro destes `ndarrays`. Para isso, utilizamos uma sintaxe muito parecida com a nativa do Python.

```python
import numpy as np

>>> a = np.arange(10)  # Inicia um ndarray de 0 a 9
>>> a
array([0, 1, 2, 3, 4, 5, 6, 7, 8, 9])
>>> # Acessando um único valor
>>> a[2]
2
>>> # Acessando o último valor
>>> a[-1]
9
>>> # Criando um slice, ou corte, do ndarray de 0 a 2
>>> a[:3]
array([0, 1, 2])
>>> # Criando um slice, ou corte, do ndarray de 3 a 9
>>> a[3:]
array([3, 4, 5, 6, 7, 8, 9])
>>> # Criando um slice, ou corte de 3 a 6
>>> a[3:7]
array([3, 4, 5, 6])
>>> # Acessando um único valor em uma matriz
>>> b = np.array([[1, 2, 3], [4, 5, 6]])
>>> b[1][0]
4
```

O mesmo que foi feito com o vetor pode ser feito para conseguir slices das matrizes, com a diferença que é possível
utilizar a notação de slice em todos os campos de índice.

Para obter mais informações, visite o site da documentação do [Numpy](https://numpy.org/doc/stable/user/whatisnumpy.html).

### Introdução ao Pandas

Assim como **Numpy**, **Pandas** também necessita ser instalado antes de ser usado. Para isso, podemos usar tanto `pip` quanto
`conda`:

`pip install pandas` ou `conda install pandas`

Após instalado, **Pandas** agora pode ser importado para ser utilizado no seu script assim como vimos
anteriormente com o **Numpy**

```python
import pandas as pd
```

Assim quando formos usar as funções, classes e métodos do **Pandas** nós precisamos escrever apenas `pd`.

Existem várias formas de criar um _DataFrame_ usando **Pandas**. Aqui veremos dois métodos básicos, um criado a partir
de um dicionário Python e outro importando de um CSV.

```python
>>> # Criando DataFrame com dicionários Python.
>>> import pandas as pd
>>>
>>> # Cria um dicionário com as chaves iguais ao nome das colunas e com os valores
>>> # iguais a listas de valores.
>>> dict_data = {"a": [1, 2, 3],
                 ...              "b": [4, 5, 6],
                                       ...              "c": [7, 8, 9]}
>>> # (Opcional) Cria uma lista de nomes para os índices.
>>> index = ["experimento 1", "experimento 2", "experimento 3"]
>>> # Cria o DataFrame passando o dicionário como primeiro parâmetro e a lista
>>> # de índices como segundo parâmetro
>>> dict_data_frame = pd.DataFrame(dict_data, index=index)
>>> dict_data_frame
a  b  c
experimento 1  1  4  7
experimento 2  2  5  8
experimento 3  3  6  9
```

Aqui criamos um DataFrame usando dicionários Python. O parâmetro de índice é opcional, caso ele não seja colocado,
no lugar dos nomes escolhidos serão adicionados valores incrementais, ou seja, 1, 2, 3, ... n, em que n é o número de
linhas no seu DataFrame.

Agora veremos como importar um CSV como DataFrame usando **Pandas**
```python
>>> # Criando um DataFrame importando um CSV.
>>> import pandas as pd
>>>
>>> # Utilizamos a função read_csv(local do arquivo, separador, index_col=índice ou nome da coluna)
>>> csv_data_frame = pd.read_csv('./recursos/introducao pandas/csvData.csv', ";", index_col=0)
>>> csv_data_frame
a  b  c
Experimento 1  1  4  7
Experimento 2  2  5  8
Experimento 3  3  6  9
```

Aqui podemos ver como é simples importar um CSV como DataFrame usando o **Pandas**. O arquivo
utilizado para este teste pode ser encontrado no nosso GIT na pasta recursos, introducao pandas.


