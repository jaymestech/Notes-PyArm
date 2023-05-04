# Notes-PyArm
anotações sobre o trabalho no projeto do braço eeg


----------------------------------------------------------------------------------------------------------------------------------
04/05 13:00 - 16:00

Ja fiz a leitura do material disponivel para incialização do projeto no Notion, o objetivo do dia é aprender amis sobre servo mtores:


notas copiadas dos textos que eu achar importante:

1. Graças à biblioteca Servo.h, que acompanha o IDE do Arduino,é muito fácil controlar
servos

2.Você pode conectar até 12 servos a um Arduino Duemilanove (ou equivalente), e até
48 no Arduino Mega — o que é perfeito para aplicações de controle robótico

3. Um servo é uma pequena caixa, contendo um motor elétrico CC, um conjunto de
engrenagens entre o motor e um eixo de saída, um mecanismo sensor de posição,
e um circuito de controle. O mecanismo sensor de posição transmite a posição do
servo para o circuito de controle, que utiliza o motor para ajustar o braço do servo
na posição que ele deve ocupar.

4.Em um servo padrão, a posição central é atingida fornecendo pulsos em intervalos
de 1,5 milissegundo; a posição de -45 graus com pulsos de 0,6 milissegundo e a po-
sição de +45 graus com pulsos de 2,4 milissegundos. Você terá de ler o datasheet de
seu servo para descobrir as larguras de pulso necessárias para os diferentes ângulos.

Coloquei em pratica o uso do servomotor sem a biblioteca do servo.h, e notei que será necessário para o futuro do projeto, o uso dos servos sem essa biblioteca, para maior precisão

https://www.tinkercad.com/things/2zc4rnfLigo-funky-leelo/editel?sharecode=keQBGWePIhdxBTL-dM07kpEPL3UBDzZDDYgGo_xUiR8 , nesse exemplo foi usado a biblioteca pois usei 2 servos, meu proximo objetivo é a utilização de varios servos sem a biblioteca, 
