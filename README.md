# metNum2020.2

Trabalho necessário para nota da disciplina de métodos númericos I
Prof.: Joaquim Bento
Equipe: 
Adislania Martins
Belchior Dameao
Leonardo Monteiro
João Victor
Tiago Lisboa

Descrição do Trabalho:

O deslocamento da extremidade de um foguete espacial ao entrar na atmosfera da terra é dado pela equação
f(d) = a*d – d*ln(d), onde d é o deslocamento medido em cm e a é um parâmetro de ajuste para que se projete
um foguete com a máxima segurança e eficiência possível. Caso esse deslocamento passe dos 2 cm esse
foguete irá explodir, causando sérios danos e um prejuízo gigantesco. Vários testes e simulações são feitos de
modo a garantir que o foguete seja desenvolvido com toda segurança possível. Desenvolva um sistema para
calcular esse deslocamento d da extremidade de um foguete espacial considerado com os requisitos abaixo:
a) Implementar algoritmo para calcular d pelo método da Bisseção.
b) Implementar algoritmo para calcular d pelo método da Posição Falsa.
c) Implementar algoritmo para calcular d pelo método de Newton-Raphson.
d) Testar os seus resultados usando como padrão a = 1, isolamento = (2, 3) e e = 10-5
.
e) Fornecer um quadro resposta, variando os valores de a para vários foguetes.
f) Fornecer um quadro comparativo, com isolamento, raízes e dados para cada método.
g) Analisar o efeito da variação do valor de a de cada foguete, para cada método dado.
Dados de entrada: n (número de foguetes), a (de cada foguete) e e (precisão).
Dados de saída: quadros resposta (com d, EA para cada foguete e método) e comparativo.
