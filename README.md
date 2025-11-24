Maria Beatriz


Este repositório tem três programas desenvolvidos em linguagem C, cada um com uma finalidade específica: geração de tabuadas, realização de operações aritméticas básicas e cálculo de IMC (Índice de Massa Corporal).

1. Tabuada 
<img width="584" height="557" alt="Captura de tela 2025-11-24 111300" src="https://github.com/user-attachments/assets/c7654ec3-a659-4d88-82bb-7be00d7b6f15" />

Objetivo

Gerar a tabuada de um número informado pelo usuário, variando de 1 a 10.

Funcionamento

O programa solicita ao usuário um número inteiro. Em seguida, utiliza um laço for para percorrer os valores de 1 a 10, exibindo, linha por linha, o resultado da multiplicação entre o número digitado e o valor atual do laço.

Pontos importantes

Uso da função scanf para entrada de dados.

Emprego da estrutura de repetição for para gerar as linhas da tabuada.

Saída formatada utilizando printf.

2. Calculadora Aritmética
<img width="529" height="458" alt="Captura de tela 2025-11-24 111058" src="https://github.com/user-attachments/assets/1496dd05-6d86-42ab-8b76-43ec496bf237" />

Objetivo

Realizar uma operação aritmética básica entre dois números, podendo ser soma, subtração, multiplicação ou divisão.

Funcionamento

O programa lê dois números reais e um operador aritmético informado pelo usuário. A operação é selecionada por meio de uma estrutura switch, que determina qual cálculo deve ser executado.
O código também faz uma verificação para evitar divisão por zero, encerrando a execução caso isso ocorra.

Pontos importantes

Uso de variáveis do tipo float para permitir operações com números reais.

Leitura do operador com tratamento de espaço para evitar problemas na captura do caractere.

Validação de divisão por zero.

Seleção de operações com a instrução switch.

3. Calculadora de IMC
<img width="529" height="744" alt="Captura de tela 2025-11-24 110746" src="https://github.com/user-attachments/assets/8d37afb4-9f56-4761-8c6d-5cc51efddfb8" />


Objetivo

Calcular o Índice de Massa Corporal (IMC) com base no peso e na altura informados pelo usuário, exibindo também a classificação correspondente ao valor calculado.

Funcionamento

O programa solicita o peso (em quilogramas) e a altura (em metros). O IMC é calculado utilizando a fórmula:

IMC = peso / (altura * altura)


Após o cálculo, o valor é exibido com duas casas decimais. Em seguida, uma série de condicionais classifica o IMC nas faixas estabelecidas: abaixo do peso, peso normal, sobrepeso ou obesidade.

Pontos importantes

Uso de variáveis float devido à necessidade de cálculos com casas decimais.

Estrutura condicional encadeada (if, else if, else) para definir a classificação.

Saída formatada com duas casas decimais.
