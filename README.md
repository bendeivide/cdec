# datascience
Estudando ciência dos dados

## Integrantes

- [Ben Dêivide (DEFIM/UFSJ)](http://bendeivide.github.io)
- [Gessyca Moreira (Eng. Telecom./UFSJ)](https://www.linkedin.com/in/gessyca-moreira-907041209/)
- [Lucas Rebouças (Eng. Civil/UFSJ)](https://www.linkedin.com/in/lucasreboucas)
- [Matheus Fernando (Eng. Mec/UFSJ)](https://www.linkedin.com/in/matheus-fernando-santos-219555b0)

## Ementas para referência

- [Ementa 1](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiDy5HUksfvAhWRHrkGHRThDjEQFjADegQIFBAD&url=https%3A%2F%2Fwww.ime.usp.br%2F~pam%2Fprog_5905.pdf&usg=AOvVaw3Ov8IOktdwSRpN07uJInvK)

## Materiais interessantes
- [Introdução à ciência de dados](http://www.ime.usp.br/~jmsinger/MAE5755/cdados2020set30.pdf)
- [Data Science with R](https://r4ds.had.co.nz/)
- [Visão Geral da Ciência de Dados](https://geessyca.github.io/VisaoGeralCienciadeDados/#1)

## Família de pacotes a serem estudados

### Pacotes R

- [Família tidyverse](https://www.tidyverse.org/)

# Linguagens de programação

## Linguagem R

## Linguagem Python

### Introdução ao Python
Por volta dos anos 1980, o holandês [Guido Van Rossum](https://gvanrossum.github.io/), que até então trabalhava no time de desenvolvimento da linguagem ABC no CWI (Centrum Wiskunde & Informatica), o instituto nacional de pesquisa em matemática e ciência da computação da Holanda, se tornaria a principal figura responsável pela criação do Python, uma linguagem de programação com ampla aplicabilidade que atingiu alta popularidade entre desenvolvedores, acadêmicos e empresas (incluindo gigantes como Google, YouTube e Dropbox).

Sucintamente, podemos descrever o Python como uma linguagem de programação open source de alto nível, interpretada, interativa e orientada a objetos. Sua aplicação é bastante versátil e inclui desenvolvimento de aplicativos, páginas da web, análise de dados, automatização de rotinas e até mesmo desenvolvimento de jogos. 

O Python está disponível para muitos sistemas operacionais, incluindo os populares Linux, Mac OS e Windows. A versão mais recente para seu processador e sistema operacional (SO) pode ser encontrada para download na [página oficial do Python](https://www.python.org/).

Após a instalação, você poderá utilizar a linguagem por meio do seu terminal ou prompt de comando, além do IDLE, o ambiente de desenvolvimento integrado (do inglês, Integrated Development Environment, ou IDE) padrão do Python, criado pelo já citado fundador da linguagem, [Guido Van Rossum](https://gvanrossum.github.io/). A utilização de outros IDE's, além do próprio IDLE, podem tornar a experiência com a linguagem mais didática e/ou dinâmica, porém trata-se uma escolha que fica a critério do estudante/programador. Algumas alternativas de IDE's para programação Python são o [Spyder](https://www.spyder-ide.org/), o [Pycharm](https://www.jetbrains.com/pycharm/download/) e o [RStudio](https://www.rstudio.com/products/rstudio/download/). 

### Primeiros comandos no Python
Com o Python já disponível na sua máquina, é o momento de inaugurar a experiência com a linguagem. Tipicamente, o código mais básico para iniciar os estudos é retornar **"Olá, Mundo!"** na tela.


**Código**

Print('Olá, Mundo!')

**Output**

Olá, Mundo!


Finalmente, temos nosso primeiro programa no Python! É válido citar que as aspas utilizadas podem ser simples ou duplas.

Para a construção de um código bem estruturado, é importantíssimo adicionar comentários conforme o trabalho avança, garantindo que a leitura do programa fique o mais dinâmica possível, permitindo melhor compreensão e facilitando o ajuste de possíveis erros. 

Por padrão, os comentários no Python são inseridos utilizando o símbolo **#** + 1 espaço + comentário. É recomendável utilizar ao menos **2 espaços** entre a última linha de código e um comentário, conforme o exemplo a seguir.


**Código**

var = 'Olá, Mundo!'  # Exemplo de comentário 1

Print(var)  # Exemplo de comentário 2

**Output**

'Olá, Mundo!'


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

**Output**

<class 'bool'>

<class 'int'>

<class 'float'>

<class'str'>

1

-3



### Módulos Python para Data Science
Python é hoje em dia considerado a linguagem para cientistas de dados, isso se dá pelo fato de ela possuir vários módulos que facilitam a construção do algoritmo além de permitir em alguns casos a utilização de computação em GPU, tornando o processo muito mais rápido. Hoje os principais módulos usados são os seguintes:
* **Numpy:** NumPy é um projeto open source que permite executar computação numérica com Python de forma rápida e fácil, quase todas as ferramentas seguintes, se não todas, usam do poder de computação de arrays e matrizes de Numpy.
* **Scipy:** SciPy é um pacote de módulos Python open source voltados para ciência, matemática e engenharia. Dentro deste pacote são incluídos módulos como NumPy, Matplotlib (usado principalmente para plotagem de gráficos) e Pandas.
* **Theano:** Theano é um módulo Python que te permite definir, otimizar, e avaliar expressões matemáticas envolvendo arrays multi-dimensionais eficientemente. Ele é construído em cima de NumPy. Theano também te permite fazer computações de dados usando a GPU, aumentando a performance em até 140x.
* **TensorFlow:** TensorFlow é um módulo Python open source para machine learning. Ele tem um ecossistema abrangente e flexível de ferramentas, bibliotecas e recursos da comunidade que permite aos pesquisadores levar adiante ML de última geração e aos desenvolvedores criar e implantar aplicativos com tecnologia de ML.
* **Keras:** Keras é uma API desenvolvida para facilitar o desenvolvimento de modelos de machine learning diminuindo o número de ações que o usuário necessita fazer para casos comuns, além de mostrar mensagens de erro claras e que permitem encontrar a causa de forma mais fácil. Keras também possui uma documentação extensa e guias para o desenvolvedor. Hoje em dia é considerado uma das 5 melhores para deep learning.
* **PyTorch:** Assim como TensorFlow, PyTorch é um módulo Python open source para machine learning. Ele é baseado na biblioteca Torch que também está disponível para C++.
* **Pandas:** Pandas é uma ferramenta open source essencial para análise de dados em Python. Ele é rápido, flexível e fácil de usar. Com ele é possível fazer a criação e manipulação de Data Frames, além de poder fazer um resumo estatístico do Data Frame com um único comando. 

# Estudando RMarkdown e Markdown

- [Rmarkdown](https://geessyca.github.io/Rmarkdown/#1)


