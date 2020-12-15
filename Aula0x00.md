***Conteudo retirado, adaptado e traduzido do site [SoloLearn](https://www.sololearn.com/)***.

# Aula 00

## Bem-vindo ao Python!

Python é uma linguagem de programação de alto nível, com aplicações em diversas áreas, incluindo programação da Web, scripts, computação científica e inteligência artificial.

É muito popular e usado por organizações como Google, NASA, CIA e Disney.

> Neste curso, aprenderemos a versão 3 do Python, que é a versão principal mais recente do Python.


## Imprimindo Texto

Vamos começar criando um programa curto que exibe "Hello world!".
Em Python, usamos a instrução print para produzir texto.

```Python
print('Hello world!') # => Hello world!
```
A declaração `print` precisa ser seguida por parênteses, que incluem a saída que queremos gerar.

A instrução `print` também pode ser usada para gerar várias linhas de texto.

Por exemplo:

```Python
print('Hello world!') # => Hello world!
print('Hello world!') # => Hello world!
print('Spam and eggs...') # => Spam and eggs...
```
Cada instrução `print` produz texto em uma nova linha.


## Operações Simples

Python tem a capacidade de realizar cálculos.
Insira um cálculo diretamente na instrução `print`:

```Python
print(2 + 2) # => 4
print(5 + 4 - 3) # => 6
```

> Os espaços em torno dos sinais de mais e menos aqui são opcionais (o código funcionaria sem eles), mas facilitam a leitura.

Python também realiza multiplicação e divisão, usando um asterisco `*` para indicar a multiplicação e uma barra `/` para indicar a divisão.

Use parênteses para determinar quais operações são realizadas primeiro.

```Python
print( 2 * (3 + 4) ) # => 14
print( 10 / 2 ) # => 5.0
```

> Usar uma única barra para dividir os números produz um decimal (ou float, como é chamado na programação).


## Floats

Floats são usados em Python para representar números que não são inteiros.
Alguns exemplos de números representados como floats são 0.5 e -7.8237591.
Eles podem ser criados diretamente inserindo um número com um ponto decimal ou usando operações como divisão em inteiros.

```Python
print( 3/4  # => 0.75
print( 0.42 )
```

> Os computadores não podem armazenar floats com precisão perfeita, da mesma forma que não podemos escrever a expansão decimal completa de 1/3 (0,333333333333333 ...). Tenha isso em mente, porque muitas vezes leva a bugs irritantes!

Como você viu anteriormente, dividir quaisquer dois inteiros produz um float.
Um float também é produzido executando uma operação em dois floats, ou em um float e um inteiro.

```Python
print( 8 / 2 ) # => 4.0
print( 6 * 7.0 ) # => 42.0
print( 4 + 1.65 ) # => 5.65
```

> Um float pode ser adicionado a um inteiro, porque o Python converte silenciosamente o inteiro em um float.


## Quociente

A divisão do tipo floor é feita usando duas barras e é usada para determinar o quociente de uma divisão (a quantidade produzida pela divisão de dois números).

Por exemplo:

```Python
print( 20 // 6 ) # => 3
```

O código acima produzirá 3, porque 6 cabe em 20 três vezes.

> Você também pode usar a divisão floor em floats.

## Restante

O operador de módulo é executado com um símbolo de porcentagem (%) e é usado para obter o restante de uma divisão.

Por exemplo:

```Python
print(20 % 6) # => 2
print(1.25 % 0.5) # => 0.25
```

> Todos os operadores numéricos também podem ser usados com floats.


## Exercícios

#### (1) Crie um programa que imprima este padrão no console:

```
#
##
###
```


#### (2) Qual o resultado da expressão `25 // 7` ?


#### (3) Qual o resultado da expressão `8 % (25 // 7)`


#### (4) As expressões `(3 + 4) * 7` e `3 + 4 * 7` geram o mesmo resultado?


#### (5) Quais os valores inteiros que voce pode usar no espaço em branco marcado por `___` para que a expressão `___ // 3` retorne o valor `4`?