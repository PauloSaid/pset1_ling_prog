# PSet1 - MIT: Paulo Said
<h3>Respostas para as perguntas do projeto.</h3>

---

***Professor: Abrantes Araujo Silva Filho***

***Aluno: Paulo André Ribeiro Said***

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

A imagem solicitada, com o filtro de inversão aplicada, está presente na imagem chamada 'questao2.png', nesse repositório.

## Questão 3:

Os cálculos a seguir foram realizados para, posteriormente, descobrir o valor do pixel central:

**3 Pixels de cima: 0.00 * 80 + (-0.07) * 53 + 0.00 * 99 +**

**3 Pixels do meio: (-0.45) * 129 + 1.20 * 127 + (-0.25) * 148 +**

**3 Pixels de baixo: 0.00 * 175 + (-0.12) * 174 + 0.00 * 193**

**Somando todos os resultados: 0 + (-3.71) + 0 + (-58.05) + 152.4 + (-37) + 0 + (-20.88) + 0 = 32.86**

Portanto, o pixel central valerá, aproximadamente, **32.86.**
