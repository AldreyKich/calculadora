# calculadora
Calculadora em JAVA
<img width="650" height="506" alt="image" src="https://github.com/user-attachments/assets/e54b3fb4-2f71-4d16-902c-aa284e970b65" />


Leitura dos valores de entrada:

Os valores digitados nos campos txtPrimeiro e txtSegundo são lidos e convertidos para inteiros (num1 e num2).

Cálculo das operações matemáticas:

Soma: num1 + num2

Subtração: num1 - num2

Divisão: num1 / num2 (resultado armazenado como double e formatado com duas casas decimais).

Multiplicação: num1 * num2 (resultado armazenado como double e formatado com duas casas decimais).

Exibição dos resultados:

Os resultados são exibidos nos campos de saída correspondentes:

txtSoma para o valor da soma.

txtSubtracao para o valor da subtração.

txtDivisao para o valor da divisão.

txtMultiplicacao para o valor da multiplicação.

Tratamento de erros:

Caso o usuário informe um valor inválido (não numérico ou segundo número 0 que náo permite divisão), é disparada uma exceção NumberFormatException.

Neste cenário, uma janela de mensagem (JOptionPane) informa ao usuário que apenas números inteiros são aceitos.
