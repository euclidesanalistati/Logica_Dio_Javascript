# 🧙‍♂️ Desafio JavaScript – Classificador de Nível de Herói

![JavaScript](https://img.shields.io/badge/javascript-es6-yellow)
![Status](https://img.shields.io/badge/status-conclu%C3%ADdo-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)

## 📌 Descrição

Este desafio tem como objetivo praticar **lógica de programação em JavaScript**, utilizando variáveis e estruturas condicionais para classificar o **nível de um herói** de acordo com sua **experiência (XP)**.

Com base no valor de XP informado, o sistema atribui um **título** ao herói e exibe o resultado no console.

---

## 🎯 Objetivo do Desafio

* Receber o **nome do herói**
* Receber a quantidade de **XP**
* Classificar o herói conforme as regras de nível
* Exibir uma mensagem final com o nome e o título do herói

---

## 🧠 Regras de Classificação

| XP do Herói             | Título     |
| ----------------------- | ---------- |
| Menor que 1.000         | Ferro      |
| 1.001 a 2.000           | Bronze     |
| 2.001 a 5.000           | Prata      |
| 5.001 a 7.000           | Ouro       |
| 7.001 a 8.000           | Platina    |
| 8.001 a 9.000           | Ascendente |
| 9.001 a 10.000          | Imortal    |
| Maior ou igual a 10.001 | Radiante   |

---

## 📤 Saída Esperada

Ao executar o programa, deverá ser exibida a seguinte mensagem:

```text
O Herói de nome {nome} está no nível de {titulo}
