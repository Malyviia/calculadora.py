# calculadora.py
# 🧮 Calculadora de Notas com Média e Classificação

Este é um projeto simples em Python que simula uma **calculadora de notas escolares**, permitindo ao usuário inserir quatro notas e obter a **média aritmética**. Com base na média final, o sistema classifica o desempenho do aluno como:

- ✅ **Aprovado**: média maior ou igual a 7
- ⚠️ **Recuperação**: média maior ou igual a 5 e menor que 7
- ❌ **Reprovado**: média menor que 5

---

## 💡 Objetivo do Projeto

Este projeto foi desenvolvido com o objetivo de praticar os conceitos básicos de **entrada de dados**, **estrutura condicional** (`if`, `elif`, `else`) e **saída formatada** com `print()` em Python. É também meu primeiro repositório publicado no GitHub!

---

## 📋 Tecnologias Utilizadas

- **Python 3**

---

## 🔢 Como funciona

1. O usuário é solicitado a digitar quatro notas (valores `float`).
2. O programa calcula a média das notas.
3. A média é usada para determinar a classificação final:
   - Se `média >= 7`: Aprovado
   - Se `5 <= média < 7`: Recuperação
   - Se `média < 5`: Reprovado
4. O resultado é exibido no console, com a média e a classificação.

---

## 🖥️ Exemplo de Uso

Digite a primeira nota: 6
Digite a segunda nota: 7.5
Digite a terceira nota: 8
Digite a quarta nota: 5
A média das notas é: 6.63
Classificação: Recuperação
