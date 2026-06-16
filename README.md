# Simulador de Empréstimo Consignado e Cartão

## 📌 Descrição

Este projeto foi desenvolvido em Java com o objetivo de realizar simulações de crédito consignado e cartão consignado para diferentes instituições financeiras.

O sistema permite informar o salário e a margem consignável do cliente, calculando automaticamente os valores disponíveis para empréstimo, cartão e valor total liberado, utilizando coeficientes específicos de cada banco.

---

## 🚀 Funcionalidades

- Simulação de empréstimo consignado.
- Simulação de cartão consignado.
- Simulação de empréstimo + cartão.
- Simulação baseada em valor mínimo desejado.
- Cálculo automático das parcelas.
- Comparação entre diversos bancos.
- Interface simples via terminal.
- Utilização de cores ANSI para melhor visualização.

---

## 🏦 Bancos Disponíveis

- FACTA
- ICRED
- PROSPECTA FINTECH
- C6
- QUALY
- AGIL
- BANCO NBC
- BANCO PRESENÇA

Cada banco possui um coeficiente próprio utilizado para o cálculo da liberação de crédito.

---

## 📋 Menu de Opções

### Opção 1 - Empréstimo + Cartão

Calcula:

- Valor consignado
- Valor do cartão (5%)
- Valor total liberado
- Parcela total em 96 vezes

### Opção 2 - Apenas Empréstimo

Calcula:

- Valor consignado
- Parcela em 96 vezes

### Opção 3 - Apenas Cartão

Calcula:

- Valor do cartão consignado
- Parcela em 96 vezes

### Opção 4 - Valor Menor do Empréstimo

Permite informar um valor mínimo desejado para o empréstimo e calcular:

- Empréstimo
- Cartão
- Total liberado
- Parcela total

### Opção 5 - Encerrar

Finaliza o programa.

---

## ⚙️ Fórmulas Utilizadas

### Margem Consignável

```java
valorMargem = salario * (margem / 100)


Main
│
├── CoresANSI
├── Banco
├── Porcentagem
├── ValorTotal
├── Simulacao
├── MenuSimulacao
└── Main

| Classe        | Função                            |
| ------------- | --------------------------------- |
| CoresANSI     | Define cores do terminal          |
| Banco         | Armazena nome e coeficiente       |
| Porcentagem   | Realiza cálculos percentuais      |
| ValorTotal    | Soma valores e calcula parcelas   |
| Simulacao     | Realiza cálculos financeiros      |
| MenuSimulacao | Exibe o menu e controla as opções |
| Main          | Inicializa e executa o programa   |


SALARIO: R$ 3000

MARGEM (%): 35

=================== MENU DE SIMULACAO ===================

1 - EMPRESTIMO + CARTAO
2 - APENAS EMPRESTIMO
3 - APENAS CARTAO
4 - VALOR MENOR DO EMPRESTIMO
5 - ENCERRAR

OPCAO: 1


Conceitos Aplicados
Programação Orientada a Objetos (POO)
Encapsulamento
Classes e Objetos
Vetores de Objetos
Métodos Estáticos
Estruturas de Repetição
Estruturas de Decisão
Entrada e Saída de Dados


Autor

Projeto desenvolvido por Fabrício para estudos e prática de desenvolvimento em Java.



