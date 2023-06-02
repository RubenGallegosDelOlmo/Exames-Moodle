Algoritmo Suma_De_Numeros

	Definir Suma, NU, Contador como Entero
	Contador <- 0
	Suma <- 0 
	Mientras Contador <= 9 Hacer
		Contador = Contador +1
		Escribir "Ingrese el numero ", Contador," "
		Leer NU
		Suma = Suma + NU
	FinMientras
	Escribir "La suma de los numeros es: ",Suma
	
FinAlgoritmo
