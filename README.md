# 🧮 BMI Calculator | Calculadora de IMC

🇺🇸 This is a simple **BMI (Body Mass Index)** calculator built with Python.  
🇧🇷 Esta é uma simples **calculadora de IMC (Índice de Massa Corporal)** feita em Python.

The user enters their weight and height, and the program calculates the BMI and returns a classification based on the **World Health Organization (WHO)** standards.  
O usuário informa seu peso e altura, e o programa calcula o IMC e retorna a classificação com base nos padrões da **Organização Mundial da Saúde (OMS)**.

Additionally, the program displays the **healthy weight range** based on the user's height.  
Além disso, o programa mostra a **faixa de peso saudável** com base na altura informada.

---

## 📌 What is BMI? | O que é o IMC?

**BMI** is a number calculated using a person's weight and height.  
**IMC** é um número calculado a partir do peso e da altura de uma pessoa.

It helps determine if the person is underweight, at a healthy weight, or overweight.  
Ajuda a identificar se a pessoa está abaixo, dentro ou acima do peso ideal.

**Formula | Fórmula:**
```
BMI = weight / (height × height)
IMC = peso / (altura × altura)
```

---

## 🧠 Classification Table | Tabela de Classificação

| BMI / IMC         | Classification (EN)     | Classificação (PT)     |
|-------------------|--------------------------|--------------------------|
| Less than 18.5    | Underweight              | Abaixo do peso          |
| 18.5 – 24.9       | Normal weight            | Peso normal             |
| 25.0 – 29.9       | Overweight               | Sobrepeso               |
| 30.0 – 34.9       | Obesity Class I          | Obesidade grau I        |
| 35.0 – 39.9       | Obesity Class II         | Obesidade grau II       |
| 40.0 and above    | Obesity Class III        | Obesidade grau III      |

---

python bmi_calculator.py

## ✅ Example Output | Exemplo de Saída

```
Enter your weight (kg): 70
Enter your height (m): 1.75

📊 BMI Classification
------------------------
Your BMI is: 22.9
You are classified as: Normal weight

✅ Healthy weight range for your height:
Between 56.6 kg and 76.2 kg
```
