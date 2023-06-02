Algoritmo Valor_de_X_Lapices

	Definir Cantidad, Costo como entero
	Escribir "Escribe la cantidad de lapices que va a comprar"
	Leer Cantidad 
	Si Cantidad >= 1000 Entonces
		Costo = (Cantidad * 85)
		Escribir "Centavos: ", Costo , " a Pesos ="
		Costo = (Costo / 100)
	Sino 
		Costo = (Cantidad * 90)
		Escribir "Centavos: ", Costo , " a Pesos ="
		Costo = (Costo / 100)
		
	FinSi
	Escribir "Usted va a comprar ", Cantidad ," Lapices "
	Escribir "Lo que va a pagar es un Total de: $ ",Costo 
	
FinAlgoritmo
