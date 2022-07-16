Nome: Lucas Nardelli de Freitas Botelho Saar
Matricula: 6385

Como utilizar:
	Abrir o terminal na pasta SO_Trabalho2
	Executar o comando "gcc -Wall vmm.c -o vmm" para compilar o arquivo
	Para executar o programa gerado é necessário passar três parâmetros
		1- Nome_algoritmo (Exemplo random, aging, mfu, nru, fifo, second_chance)
		2- Inteiro para ser a frequência do relógio
		3- Nome do txt com as entradas
		
		Exemplo "./vmm random 10 < anomaly.dat"
		
Bugs conhecidos ou problemas:
	Programa não aceita numeros negativos como entrada
	Nome do algoritmo deve ser digitado todo minusculo
	Tipo de acesso a pagina virtual pode ser somente 'r' ou 'w'
