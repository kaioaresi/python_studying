# Python

A linguagem python foi criado por Guido van Rossum em meados de 1989 e lançada oficialmente em 1991. Python é uma linguagem de alto nível de tipagens dinâmica, sua principal característica na minha opinião é a curva de aprendizado. Uma curiosidade da linguagem é que seu nome foi escolhido devido ao famoso grupo de humor britânico `Monty Python` e não pela cobra.


---
## Operadores matemáticos

__Ordem de predecessão__


A ordem de predecessão é a mesma utilizada na matemática, em caso de operadores com mesmo nível deve-se **sempre realizar a operação da esquerda para a direita** salvo quando utilizar parenteses, pois ele sobrepõem todos os demais

Maior Prioridade | Simbolo | Nome
:---:|:---:|:---:|
0 | ( ) | parenteses |
1 | ** | Exponecial |
2 | % | Resto |
2 | // | Divisão inteira |
2 | * | Multiplicação |
3 | - | Subtração |
3 | + | Adição |

---

## Tipos de dados

No python basicamente existem três tipo de dados `int`, `float` e `string`.

O valor `int` são número inteiros que não possuem `.` ou `,`, já os valores
'float' são valor que possuem `.` ou `,`, as string como o nome já diz são basicamente texto puro.

---

## Declaração de variável

Para declarar uma variável em python basta definir um nome de acordo com os padrões, seguido de ** apenas um ** `=` seguido do valor segue exemplo:

```
nome = 'Kaio Cesar'
```

---
## Comentário


Quando se está aprendendo algo é sempre bom realizar anotações ou comentário com informações relevantes para facilita o entendimento posterior, na programação isso não é diferente segue abaixo exemplos de como realizar comentários de linhas ou blocos

### Comentário básico

Deve-se colocar apenas um  `#` que tudo a direita será desconsiderado.

```
# Esse é um exemplo de comentário
3 + 3

# saída
6
```
### Comentário em bloco

Deve-se utilizar três sinais de `'''` para iniciar e fechar o comentário em bloco

```
'''
Esse bloco de comentários será
desconsiderado no seu código.
'''
3 + 2

```

---

## Saída de dados

Para exibir dados em python você poderá utilizar a função `print()` que a forma mais simples de se exibir dados, segue exemplo:


```
# Definindo uma variável do tipo string com valor 'kaio cesar'
nome = 'Kaio Cesar'

# Exibindo o valor da variável nome
print(nome)

# saída
kaio Cesar
```

## Entrada de dados

Para captura uma entrada de dado, você pode utilizar a função `input`, segue exemplo:


```
# Solicitando ao usuário que digite seu nome e guardando esse valor em uma variável chamada nome e convertendo esse valor para string.
nome = str(input('Digite seu nome: '))

print('Seu nome é:', nome)
```


---

## Concatenação de dados

Exitem algumas forma de concatenar uma saída no python com `,` ou `+`, qual utilizar depende de cada caso segue alguma exemplos

```
nome = "Kaio Cesar"
idade = 27

# Aqui vamos contatenar o nome com a idade em forma um única frase.

# Teste 1 - se tentamos imprimir essa mensagem com contatenando com `+` sendo que o tipo da variavel `idade` é inteiro o interpretador irá tentar somar o mesmo, o jeito será utilizar a `,`.

print('Seu nome é ', nome, 'e você tem ' + idade)

print('Seu nome é ', nome, 'e você tem ' , idade)

```
> Dica: um regrinha que pode ser utilizada é sempre contatenar apenas string com `+`.


> Extra: Existe um outro operador que pode ser utilizado que é o `*` seguido de um numero, ele basicamente multiplica a string anterior não é bem uma forma de concatenação, mas é muito útil  a ele exemplo:


```
nome = 'Kaio'

print('kaio' * 3)

# saída

kaiokaiokaio
```

As forma de concatenação mais simples apresentadas acima para pequenas mensagens funciona muito bem, porém a medida que as mensagem ficam maior fica muito ruim de escreve-las. Agora vamos aprender como exibir dados de forma mais polida digamos assim.

__%S__

Esse é um mode de realizar concatenação muito utilizado na versão 2.x, mas ainda funciona na versão 3.x, na posição da variável você declara um `%s` e declara as variáveis na posição correta, segue abaixo como utilizar.

```
nome = 'Kaio Cesar'

idade = 28

print('Seu nome é %s e você tem %s anos' % (nome,idade))
```

__Format()__

A função formate permite realizar a concatenação da um mensagem de forma mais organização, a mesma pode ser utilizada apenas na versão 3.x +, seu funcionamento consistem em colocar um `{}` no lugar ao qual será subsistido a variável e depois devemos declarar a variável na ordem em que queremos que seja exibida, separados por virgula.

```
nome = 'Kaio Cesar'
idade = 28

print('Seu nome é {} e você possui {}'.format(nome, idade))
```

__F()__

Esse a forma atualizada para realizar concatenação mais atualizada, podendo ser utilizada na versão 3.6+ do python, na linha opinião é a mais clara de se utilizar. para utilizar você deve adciona um `f` antes do aspas sendo da função print e ao declara o `{}` você coloca o nome da variável no local desejado.


```
nome = 'Kaio Cesar'
idade = 27

print(f'Seu nome é {nome} e você tem {idade} anos')

```

---

## Funções básicas

Quase tudo em python é tratado com objeto e todo objeto possui funções vamos ver algumas importantes:

nome função | utilizade | exemplo | saída
:---:|:---:|:---:|:---:|
`print()` | permite exibir dados na tela | print('Hello world!') | Hello world!
`len()` | conta o número de caracteres | len('kaio') | 4
`str()` | transforma um valor em string | str(4) | '4'
`int()` | transforma um número em inteiro | int('4') | 4
`float()` | transforma um número em float | float(4) | 4.0

---


# Resumo

O que aprendi neste primeiro nível:

- Como declarar um variável;
- Tipo de dados comuns;
- Como receber e exibir dados;
- Funções importantes.

---

# Exercicios

1. Crie um programa que receba dois valores sendo um do tipo string e outro do tipo int e exiba na tela.

2. Crie um programa que receba dous números e some ambos e exiba o resultado ao usuário.

3. Crie um programa que apenas exiba um menu com cinco opções, segue exemplo:


```
##### Menu de opções ######
1 - Pizza
2 - Açai
3 - Pão de queijo
4 - Suco de frutas
5 - Cerveja
##########################
```
