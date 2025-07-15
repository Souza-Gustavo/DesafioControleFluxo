# 🧮 Desafio DIO – Controle de Fluxo em Java

Desafio da Digital Innovation One (DIO), do módulo *Java Básico*, proposto pelo professor **Gleyson Sampaio**, com foco em estruturas de repetição e tratamento de exceções.

---

## 📋 Descrição

O programa deve receber **dois números inteiros** via terminal e, a partir deles:
1. Verificar se **o segundo número é maior** que o primeiro.
2. Se **válido**:
   - Calcular a diferença entre os valores.
   - Exibir no console cada número incrementado:  
     `"Imprimindo o número X"` (X cresce de 1 até a diferença).
3. Se **inválido** (primeiro ≥ segundo):
   - Lançar exceção customizada `ParametrosInvalidosException` com a mensagem:  
     `"O segundo parâmetro deve ser maior que o primeiro"` :contentReference[oaicite:1]{index=1}

Esse exercício reforça a prática de **for**, **entrada de dados**, e **tratamento de erros** :contentReference[oaicite:2]{index=2}.

---

## 🧠 Como Funciona

1. Executa `Contador.java`
2. Pede para digitar o **primeiro** e o **segundo** número.
3. Chama método `contar(param1, param2)`:
   - Se `param2 ≤ param1`: lança `ParametrosInvalidosException`
   - Caso contrário: usa `for` para exibir as mensagens incrementais.
4. Envolve a chamada em `try/catch` no `main` para capturar e exibir a mensagem da exceção.

---

## 📂 Estrutura sugerida

```text
src/
└── app/
    ├── Contador.java
    └── ParametrosInvalidosException.java
````



## 📚 Recursos e referências
* Github de colegas com estrutura similar: DIO - controle de fluxo em Java.
* Documentação DIO (módulo Java Básico) explicando o desafio.
