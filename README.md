# 📐 Cálculo de Áreas Geométricas em C#

Este projeto em C# realiza o cálculo de áreas de diferentes figuras geométricas com base em três valores fornecidos pelo usuário. Ele é ideal para treinar entrada de dados, manipulação de arrays, operações matemáticas e formatação de saída com `ToString()`.

---

## 🧮 Figuras calculadas

- 🔺 Triângulo (base × altura / 2)
- 🟣 Círculo (π × raio²)
- 🔷 Trapézio ((base1 + base2) × altura / 2)
- ◼️ Quadrado (lado²)
- ▭ Retângulo (base × altura)

---

## 📌 Exemplo de entrada

3.0 4.0 5.2

## 📤 Saída esperada

TRIANGULO: 7.800
CIRCULO: 85.415
TRAPEZIO: 18.200
QUADRADO: 16.000
RETANGULO: 12.000

📚 Conceitos aplicados
Leitura de múltiplos valores com Split()

Conversão de string para double com double.Parse()

Cálculos matemáticos com precisão

Uso de CultureInfo.InvariantCulture para evitar problemas com separadores decimais

Saída formatada com .ToString("F3")
