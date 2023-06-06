Algoritmo Actividad_1
	
	Definir calf Como Real
	Definir Estudiante Como Caracter
	Escribir "Ingrese el nombre del estudiante: "
	Leer Estudiante 
	Escribir "Ingrese la calificacion del estudiante"
	Leer calf
	Si Calf >= 1.0 y   Calf <= 7.0 entonces
		Si Calf <= 4.0
			Escribir "La Calificacion de el/la Alumno/a: ",Estudiante," Es de: ",Calf, " : Reprovado"
		Sino 
			Escribir "La Calificacion de el/la Alumno/a: ",Estudiante," Es de: ",Calf, " : Aprovado"
		FinSi
	sINO
		Escribir "La calificacion ingresada es mayor a la solicitada"
		Escribir "Recuerde que la calificacion no puede sobrepasar el 7.0"
		Escribir "Intente nuevamente"
		Leer Calf
	FinSi	
	
FinAlgoritmo
