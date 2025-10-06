## O Que o Programa faz
Este programa é uma calculadora científica em C que oferece diversas operações matemáticas, como soma, subtração, multiplicação, divisão, potenciação, funções trigonométricas, logaritmos, cálculo de hipotenusa, fatorial, delta de equações quadráticas, determinante de matriz 2x2, entre outras funcionalidades. O usuário pode escolher a operação desejada através de um menu interativo.
## Tecnologias e recursos utilizados
-Linguagem: C

-Biblioteca padrão: stdio.h para entrada/saída

-Biblioteca matemática: math.h para funções como pow, sqrt, sin, cos, tan, log, etc.
## Como instalar, compilar e executar
1.Instalar um compilador C (exemplo: gcc no Linux/macOS, MinGW no Windows)

2.Salvar o código fonte em um arquivo, por exemplo: calculadora.c

3.Abrir o terminal na pasta do arquivo e compilar com o comando:

gcc calculadora.c -o calculadora -lm


O -lm é necessário para linkar a biblioteca matemática math.h.

4.Executar o programa:

No Linux/macOS:

./calculadora


No Windows:

calculadora.exe
## Exemplos de uso
-Ao executar, o programa mostrará o menu de operações numeradas.

-Para somar dois números, digite 1 e pressione Enter. Depois, insira os dois números.

-O resultado será exibido e o programa perguntará se deseja retornar ao menu (s para sim, n para não).

-Para sair, digite 0 no menu principal.

Exemplo de fluxo:

=====CALCULADORA-CIENTIFICA=====
Selecione a operação deseja: 
1) Soma
...
0) Sair
Digite a operação desejada: 1
Digite o primeiro número: 5
Digite o segundo número: 10
O resultado da soma é: 15.00
Deseja retornar ao menu? (s/n): s
## Informações adicionais
-Para operações trigonométricas, os ângulos devem ser informados em graus (não em radianos).

-Para o cálculo do fatorial, o número deve estar entre 0 e 20 para evitar overflow.

-Na divisão, o divisor não pode ser zero — o programa trata essa situação exibindo uma mensagem de erro.

-O programa roda em modo console e é ideal para aprendizado e testes simples em C.
## Autor

YAN GUTTO,LUIZ GUSTAVO , DANILO , RICARDO MISAEL GOMES, ELIDIO DUTRA JUNIOR