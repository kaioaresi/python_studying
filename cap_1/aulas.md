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





--

## Concatenação de strings

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
