# Sistema bancário com Python 🏦

Este é um desafio do bootcamp DIO, cujo objetivo é desenvolver um sistema bancário com as operações: saque, depósito e visualização de extrato.

## Desafio 💻
Fomos contratador por um grande banco para desenvolver o seu novo sistema. Esse banco deseja modernizar suas operações e para isso escolheu a linguagem Python. Para d primeira versão do sistema devemos implementar apenas 3 operações: depósito, saque e extrato.

## Regras 

### 1. Operações de depósito 🤑
• Deve ser possível depositar valores positivos para a conta bancária. 
• Todos os depósitos devem ser armazenados em uma variável e exibidos na operação de extrato. 

### 2. Operações de saque 💸
• O sistema deve permitir realizar 3 saques diários com limite máximo de R$500,00 por saque.
• Caso o usuário não tenha saldo em conta, o sisteme deve exibir mensagem informando que não será possível sacar o dinheiro por falta de saldo.
• Toddos os saques devem ser armazenados em uma variável e exibidos na operação extrato.

### 2. Operações de extrato 📃
• Essa operação deve listar todos os depósitos e saques realizados na conta;
• No final da listagem deve ser exibido o saldo atual da conta. 
• Se o extrato estiver em branco, exibir a mensagem: "Não foram realizadas movimentações".
• Os valores devem ser exibidos utilizando o formato R$ xxx.xx, por exemplo:
1500.45 = R$1500.45.
