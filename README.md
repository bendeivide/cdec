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
Print('Ola, Mundo!')
```
**Output**
```Python
Ola, Mundo!
```

Finalmente, temos nosso primeiro programa no Python! É válido citar que as aspas utilizadas podem ser simples ou duplas.

Para a construção de um código bem estruturado, é importantíssimo adicionar comentários conforme o trabalho avança, garantindo que a leitura do programa fique o mais dinâmica possível, permitindo melhor compreensão e facilitando o ajuste de possíveis erros. 

Por padrão, os comentários no Python são inseridos utilizando o símbolo **#** + 1 espaço + comentário. É recomendável utilizar ao menos **2 espaços** entre a última linha de código e um comentário, conforme o exemplo a seguir.


**Código**
```Python
var = 'Ola, Mundo!'  # Exemplo de comentário 1

Print(var)  # Exemplo de comentário 2
```
**Output**
```Python
Ola, Mundo!
```

Cada código trará suas informações no formato que mais se adeque ao seu objetivo, sendo assim, o Python apresenta diferentes tipos de dados possíveis. Para os primeiros passos, os tipos de dados mais utilizados serão os demonstrados abaixo:


* **str:** Dado no formato texto, 'string' representa uma sequência de caracteres

Exemplos de strings: "Olá, Mundo!", "CDEC", "Python"...

* **int:** Dado numérico no formato inteiro (integer)

Exemplos de números de tipo integer: 1, -2, -5, 15...

* **float:** Dado numérico no formato "flutuante", apresentando casas decimais após a parte inteira

Exemplos de números de tipo float: 1.20, -13.444, 15.89...

* **bool:** Dado no formato "booleano", tendo como característica os valores "True" e "False"

Os únicos valores possíveis para uma variável booleana são "True" e "False"


A função type( ) pode nos mostrar o tipo de uma variável, enquanto as funções str( ), int( ), float( ) e bool( ) permite fazer os valores transitarem entre diferentes tipos, como pode ser observado nos exemplos abaixo:


**Código**
```Python
a = True

x = 1

y = -3.50

z = "Olá, Mundo!"

print(type(a))

print(type(x))

print(type(y))

print(type(z))

print(str(x))

print(int(y))
```
**Output**
``` Python
<class 'bool'>

<class 'int'>

<class 'float'>

<class'str'>

1

-3
```


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


