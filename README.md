# Bootcamp Potência Tech Powered by IFood Desafio Sistema Bancário-1
Criando um Sistema Bancário com Python


### Sobre o desafio:

Desafio realizado no Bootcamp  Bootcamp Potência Tech Powered by IFood na plataforma da comunidade DIO.
O desafio consiste em  cria uma sistema bancário com a linguagem <b>Python</b>. Para a
primeira versão do sistema devemos implementar apenas 3 operações: depósito, saque e extrato.

<b>Operação de depósito</b> Deve ser possível depositar valores positivos para a 
conta bancária. A v1 do projeto trabalha apenas com 1 usuário,
dessa forma não precisamos nos preocupar em identificar qual
é o número da agência e conta bancária. Todos os depósitos
devem ser armazenados em uma variável e exibidos naoperação de extrato.

<b>Operação de saque </b> O sistema deve permitir realizar 3 saques diários com limite
máximo de R$ 500,00 por saque. Caso o usuário não tenha
saldo em conta, o sistema deve exibir uma mensagem
informando que não será possível sacar o dinheiro por falta de
saldo. Todos os saques devem ser armazenados em uma
variável e exibidos na operação de extrato.

<b>Operação de extrato</b> Essa operação deve listar todos os depósitos e saques
realizados na conta. No fim da listagem deve ser exibido o
saldo atual da conta. Se o extrato estiver em branco, exibir a
mensagem: Não foram realizadas movimentações.
Os valores devem ser exibidos utilizando o formato R$ xxx.xx,
exemplo:
1500.45 = R$ 1500.45
