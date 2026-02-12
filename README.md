# Conversão de Temperatura: Celsius para Fahrenheit em Python

## Descrição

Este código em Python tem como finalidade realizar a **conversão de temperatura da escala Celsius para Fahrenheit**, utilizando a fórmula matemática padrão adotada internacionalmente.

---

## Código-Fonte

```python
temperaturaC = float(input('Informe a temperatura em Celsius: '))
temperaturaF = (((9 * temperaturaC) / 5) + 32)
print('A temperatura de {} ºC corresponde a {} ºF'.format(temperaturaC, temperaturaF))
