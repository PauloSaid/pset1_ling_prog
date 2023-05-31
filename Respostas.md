# PSet1 - MIT: Paulo Said
<h3>Respostas para as perguntas do projeto.</h3>

---

***Professor: Abrantes Araujo Silva Filho***

***Aluno: Paulo André Ribeiro Said***

***Matrícula: 202299417***

---

## Questão 1: 
***se você passar essa imagem pelo filtro de inversão, qual seria o
output esperado? Justifique sua resposta.***

Resposta: Primeiramente, para que possamos encontrar o output esperado, é necessário calcular o valor de cada pixel, cujo calculo seria:

**Primeiro pixel: 255 - 29 = 226**

**Segundo pixel: 255 - 89 = 166**

**Terceiro pixel: 255 - 136 = 119**

**Quarto pixel: 255 - 200 = 55**


Desta forma, o output esperado seria uma nova imagem com os pixels: [226,116,119,55]

## Questão 2: 

A imagem solicitada, com o filtro de inversão aplicada, está exibida a seguir:

![Imagem Q2](https://github.com/PauloSaid/pset1_ling_prog/blob/main/questao2.png)

## Questão 3:

Os cálculos a seguir foram realizados para, posteriormente, descobrir o valor do pixel central:

**3 Pixels de cima: 0.00 * 80 + (-0.07) * 53 + 0.00 * 99 +**

**3 Pixels do meio: (-0.45) * 129 + 1.20 * 127 + (-0.25) * 148 +**

**3 Pixels de baixo: 0.00 * 175 + (-0.12) * 174 + 0.00 * 193**

**Somando todos os resultados: 0 + (-3.71) + 0 + (-58.05) + 152.4 + (-37) + 0 + (-20.88) + 0 = 32.76**

Portanto, o pixel central valerá, aproximadamente, **32.86.**

## Questão 4:

A imagem solicitada, com os cálculos de kernel aplicado, está exibida a seguir:

![Imagem Q4](https://github.com/PauloSaid/pset1_ling_prog/blob/main/questao4.png)

## Questão 5:

Resposta: Para calcular toda imagem nítida com apenas uma correlação, é preciso usar um kernel k que seja é a diferença entre um kernel de nitidez e o kernel de desfoque de caixa 3x3.

Ou seja, a correlação é realizada pixel a pixel, multiplicando os valores dos pixels correspondentes na imagem e no kernel e somando-os.
Exemplo: 
Imagem = 
[10, 10, 10]

[10, 10, 10]
    
[10, 10, 10]

Cálculo:
resultado = 

(10 * k(x, y) + (10 *  k(x, y)) + (10 *  k(x, y)) +

(10 *  k(x, y)) + (10 *  k(x, y)) + (10 *  k(x, y)) +

(10 *  k(x, y)) + (10 *  k(x, y)) + (10 *  k(x, y))

**Imagem da Questão 5.1:**

![Imagem 5.1](https://github.com/PauloSaid/pset1_ling_prog/blob/main/questao51.png)
