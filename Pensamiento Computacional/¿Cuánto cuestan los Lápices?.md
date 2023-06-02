Algoritmo Valor_de_X_Lapices 

	Definir Cantidad, Costo como entero
	Escribir "Escribe la cantidad de lapices que va a comprar"
	Leer Cantidad 
	Si Cantidad >= 1000 Entonces
		Costo = (Cantidad * 85)
	Sino 
		Costo = (Cantidad * 90)
	FinSi
	Escribir "Usted va a comprar ", Cantidad ,"Lo que va a pagar es un Total de: $",Costo
  
FinAlgoritmo
