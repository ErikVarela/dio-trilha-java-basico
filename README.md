# 🏦 Simulação de Conta Bancária no Terminal em Java

Este repositório contém um exercício simples e didático que simula a criação de uma conta bancária no terminal, utilizando a linguagem **Java** e entrada de dados via `Scanner`.

## 🎯 Objetivo

Demonstrar o uso de entrada de dados no console com Java e como estruturar um programa simples de interação com o usuário. Ideal para iniciantes que estão aprendendo:

- Entrada e saída de dados (`Scanner`)
- Tipos primitivos
- Operadores de comparação
- Boas práticas de organização de código

## 💻 Como funciona

O programa solicita ao usuário o número da agência e, se for compatível com o valor pré-definido, exibe uma mensagem personalizada com os dados da conta.

### 🧾 Exemplo de fluxo:

1. O usuário digita o número da agência.
2. Se o número corresponder ao valor esperado (`067-8`), o programa exibe:

Olá MARIO ANDRADE, obrigado por criar uma conta em nosso banco, sua agência é 067-8 conta 1021 e seu saldo 237.48 já está disponível para saque
## 🧩 Componentes do código

- `Scanner` para entrada de dados do usuário
- Variáveis com dados simulados da conta (`agência`, `número`, `cliente`, `saldo`)
- Condicional `if` para validar a entrada

## 🛠️ Tecnologias Utilizadas

- Java 8 ou superior
- IDE ou terminal de sua preferência

## 🚀 Como Executar

1. Compile o código:
```bash
javac ContaTerminal.java
```
