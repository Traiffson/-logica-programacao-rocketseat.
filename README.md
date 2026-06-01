Projeto

# 📚 **Prática - Conectivos Lógicos**
**Aluno:** Traiffson Dev
**Data:** 31/05/2026
**Curso:** Algoritmos e Lógica de Programação - Rocketseat

---
---

## 📌 **Regras dos Conectivos Lógicos (Para Consulta Rápida)**
🔹 **E (∧):** Verdadeiro **apenas se ambas as proposições forem V**
🔹 **OU (∨):** Verdadeiro se **ao menos uma proposição for V**
🔹 **SE ENTÃO (→):** Falso **apenas quando p=V e q=F**
🔹 **SE E SOMENTE SE (↔):** Verdadeiro quando **p e q são iguais** (VV ou FF)

---

---

## ✅ **Exercícios Resolvidos**

---

### 🔹 **Exercício 1**
**Frase:** *"Eu estudei para a prova **e** fiz todos os exercícios."*

- **Expressão Lógica:** `p ∧ q`
  - p: Eu estudei para a prova
  - q: Fiz todos os exercícios

- **Tabela Verdade:**

| **p** | **q** | **p ∧ q** |
|:-----:|:-----:|:----------:|
|   V   |   V   |     **V**  |
|   V   |   F   |      F     |
|   F   |   V   |      F     |
|   F   |   F   |      F     |

---

### 🔹 **Exercício 2**
**Frase:** *"Eu vou ao cinema **ou** fico em casa assistindo séries."*

- **Expressão Lógica:** `p ∨ q`
  - p: Eu vou ao cinema
  - q: Fico em casa assistindo séries

- **Tabela Verdade:**

| **p** | **q** | **p ∨ q** |
|:-----:|:-----:|:----------:|
|   V   |   V   |     **V**  |
|   V   |   F   |     **V**  |
|   F   |   V   |     **V**  |
|   F   |   F   |      F     |

---

### 🔹 **Exercício 3**
**Frase:** *"**Se** eu acordar cedo, **então** conseguirei pegar o ônibus."*

- **Expressão Lógica:** `p → q`
  - p: Acordar cedo
  - q: Conseguirei pegar o ônibus

- **Tabela Verdade:**

| **p** | **q** | **p → q** |
|:-----:|:-----:|:----------:|
|   V   |   V   |     **V**  |
|   V   |   F   |     **F**  |
|   F   |   V   |     **V**  |
|   F   |   F   |     **V**  |

---

### 🔹 **Exercício 4**
**Frase:** *"**Se** eu estudar muito, **então** passarei na prova **e** ganharei um presente."*

- **Expressão Lógica:** `p → (q ∧ r)`
  - p: Estudar muito
  - q: Passarei na prova
  - r: Ganhar um presente

- **Tabela Verdade:**

| **p** | **q** | **r** | **q ∧ r** | **p → (q ∧ r)** |
|:-----:|:-----:|:-----:|:----------:|:----------------:|
|   V   |   V   |   V   |     **V**  |        **V**    |
|   V   |   V   |   F   |      F     |        **F**    |
|   V   |   F   |   V   |      F     |        **F**    |
|   V   |   F   |   F   |      F     |        **F**    |
|   F   |   V   |   V   |     **V**  |        **V**    |
|   F   |   V   |   F   |      F     |        **V**    |
|   F   |   F   |   V   |      F     |        **V**    |
|   F   |   F   |   F   |      F     |        **V**    |

---

### 🔹 **Exercício 5**
**Frase:** *"Eu vou jogar videogame **ou** vou estudar lógica de programação."*

- **Expressão Lógica:** `p ∨ q`
  - p: Jogar videogame
  - q: Estudar lógica de programação

- **Tabela Verdade:**

| **p** | **q** | **p ∨ q** |
|:-----:|:-----:|:----------:|
|   V   |   V   |     **V**  |
|   V   |   F   |     **V**  |
|   F   |   V   |     **V**  |
|   F   |   F   |      F     |

---

### 🔹 **Exercício 6** ⚠️ **CORRIGIDO**
**Frase:** *"Eu comi pizza **e** tomei refrigerante."*

- **Expressão Lógica:** `p ∧ q` *(Correção: antes estava como OU, mas a frase usa "e")*
  - p: Comi pizza
  - q: Tomei refrigerante

- **Tabela Verdade:**

| **p** | **q** | **p ∧ q** |
|:-----:|:-----:|:----------:|
|   V   |   V   |     **V**  |
|   V   |   F   |      F     |
|   F   |   V   |      F     |
|   F   |   F   |      F     |

---

### 🔹 **Exercício 7**
**Frase:** *"**Se** eu tiver dinheiro, **então** viajarei nas férias."*

- **Expressão Lógica:** `p → q`
  - p: Tiver dinheiro
  - q: Viajarei nas férias

- **Tabela Verdade:**

| **p** | **q** | **p → q** |
|:-----:|:-----:|:----------:|
|   V   |   V   |     **V**  |
|   V   |   F   |     **F**  |
|   F   |   V   |     **V**  |
|   F   |   F   |     **V**  |

---

### 🔹 **Exercício 8**
**Frase:** *"Eu lerei um livro **se e apenas se** terminar meu trabalho."*

- **Expressão Lógica:** `p ↔ q`
  - p: Eu lerei um livro
  - q: Terminar meu trabalho

- **Tabela Verdade:**

| **p** | **q** | **p ↔ q** |
|:-----:|:-----:|:----------:|
|   V   |   V   |     **V**  |
|   V   |   F   |      F     |
|   F   |   V   |      F     |
|   F   |   F   |     **V**  |

---

### 🔹 **Exercício 9**
**Frase:** *"**Se** estiver sol, **então** irei à praia **ou** ao parque."*

- **Expressão Lógica:** `p → (q ∨ r)`
  - p: Estiver sol
  - q: Irei à praia
  - r: Irei ao parque

- **Tabela Verdade:**

| **p** | **q** | **r** | **q ∨ r** | **p → (q ∨ r)** |
|:-----:|:-----:|:-----:|:----------:|:----------------:|
|   V   |   V   |   V   |     **V**  |        **V**    |
|   V   |   V   |   F   |     **V**  |        **V**    |
|   V   |   F   |   V   |     **V**  |        **V**    |
|   V   |   F   |   F   |      F     |        **F**    |
|   F   |   V   |   V   |     **V**  |        **V**    |
|   F   |   V   |   F   |     **V**  |        **V**    |
|   F   |   F   |   V   |     **V**  |        **V**    |
|   F   |   F   |   F   |      F     |        **V**    |

---
---
### 🔹 **Exercício 10**
**Frase:** *"Eu farei um bolo **se e apenas se** comprar os ingredientes."*

- **Expressão Lógica:** `p ↔ q`
  - p: Eu farei um bolo
  - q: Comprar os ingredientes

- **Tabela Verdade:**

| **p** | **q** | **p ↔ q** |
|:-----:|:-----:|:----------:|
|   V   |   V   |     **V**  |
|   V   |   F   |      F     |
|   F   |   V   |      F     |
|   F   |   F   |     **V**  |

---
---
## 🎯 **Observações Finais**
✅ **Todos os exercícios foram resolvidos** seguindo as regras dos conectivos lógicos.
✅ **Tabelas verdade foram construídas** para todas as combinações possíveis.
✅ **Exercício 6 foi corrigido** (de `p ∨ q` para `p ∧ q`).





📝 PRARICA-ALGORITIMO

---
### 🔹 Exercício 1: Imprimir um número em tela
ALGORITMO ImprimirNumero
  INÍCIO
    ESCREVA("Digite um número:")
    LEIA num
    ESCREVA("Você digitou:", num)
  FIM

---
---
### 🔹 Exercício 2: Somar dois números
ALGORITMO SomarDoisNumeros
  INÍCIO
    LEIA num1
    LEIA num2
    soma ← num1 + num2
    ESCREVA("Resultado:", soma)
  FIM

---
---
### 🔹 Exercício 3: Contar de 1 até 10 usando loop
ALGORITMO ContarAte10
  INÍCIO
    i ← 1
    ENQUANTO i <= 10 FAÇA
      ESCREVA(i)
      i ← i + 1
    FIM_ENQUANTO
  FIM

---
---
### 🔹 Exercício 4: Verificar se o número é par ou ímpar
ALGORITMO VerificarParImpar
  INÍCIO
    LEIA num
    SE num % 2 = 0 ENTÃO
      ESCREVA("Par")
    SENÃO
      ESCREVA("Ímpar")
    FIM_SE
  FIM

---
---
### 🔹 Exercício 5: Verificar se número é positivo, negativo ou zero
ALGORITMO VerificarPositivoNegativoZero
  INÍCIO
    LEIA num
    SE num > 0 ENTÃO
      ESCREVA("Positivo")
    SENÃO SE num < 0 ENTÃO
      ESCREVA("Negativo")
    SENÃO
      ESCREVA("Zero")
    FIM_SE
  FIM

---
---
### 🔹 Exercício 6: Calcular média de 3 notas
ALGORITMO CalcularMedia
  INÍCIO
    LEIA n1, n2, n3
    media ← (n1 + n2 + n3) / 3
    ESCREVA("Média:", media)
  FIM

---
---
### 🔹 Exercício 7: Verificar se aluno foi aprovado (com média ≥ 5)
ALGORITMO VerificarAprovacao
  INÍCIO
    LEIA nota1, nota2
    media ← (nota1 + nota2) / 2
    SE media >= 5 ENTÃO
      ESCREVA("Aprovado")
    SENÃO
      ESCREVA("Reprovado")
    FIM_SE
  FIM

---
---
### 🔹 Exercício 8: Maior entre dois números
ALGORITMO MaiorEntreDois
  INÍCIO
    LEIA a, b
    SE a > b ENTÃO
      ESCREVA("Maior:", a)
    SENÃO
      ESCREVA("Maior:", b)
    FIM_SE
  FIM




🛡️FLUXOGRAMA 

   (Início)
      |
      v
 [Entrada: N]
      |
      v
[Processo: D = N * 2]
      |
      v
 [Saída: D]
      |
      v
    (Fim)


   (Início)
      |
      v
 [Entrada: N]
      |
      v
   <N < 10?>
   /      \
  v        v
[Saída:   [Saída:
 "Sim"]    "Não"]
   \        /
    \      /
      v  v
      (Fim)


   (Início)
      |
      v
[Processo: I = 1]
      |
      v
   <I <= 5?>
   /      \
  v        v
[Saída:   (Fim)
  I]
  |
  v
[Processo: I = I + 1]
  |
  v
 (volta para a decisão)


