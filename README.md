# Calculadora de IMC (Índice de Massa Corporal) 🧮

Este programa em linguagem C realiza o cálculo do **IMC (Índice de Massa Corporal)** com base no peso e altura informados pelo usuário, e classifica o resultado em categorias como: "Abaixo do peso", "Peso normal", "Sobrepeso", etc.

---

## 📌 Funcionalidades

- Solicita o peso e a altura do usuário.
- Calcula automaticamente o IMC com base na fórmula:
  
  \[
  \text{IMC} = \frac{\text{peso}}{\text{altura}^2}
  \]

- Exibe o valor do IMC com uma casa decimal.
- Informa em qual faixa de classificação o usuário se encontra:

| Faixa de IMC        | Classificação         |
|---------------------|------------------------|
| Menor que 18.5      | Abaixo do peso         |
| 18.5 a 24.9         | Peso normal            |
| 25.0 a 29.9         | Sobrepeso              |
| 30.0 a 34.9         | Obesidade grau 1       |
| 35.0 a 39.9         | Obesidade grau 2       |
| 40.0 ou mais        | Obesidade grau 3       |

---
