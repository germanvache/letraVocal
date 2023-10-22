# letraVocal
//Ejercicio pseudocódigo PSeInt, pedir una letra (texto) por pantalla y decir si es una vocal
Algoritmo sin_titulo
	//Definir las variables e inicializar
	Definir letra Como Texto
	letra = ""
	
	//Pedir una letra vocal y leerla
	Escribir "Esciba una letra vocal"
	Leer letra
	//Comprobar si la letra escrita es una vocal
	Si (letra = "a") O (letra = "e") O (letra = "i") O (letra = "o") O (letra = "u") Entonces
		Escribir "Es una vocal"
	SiNo 
		Escribir "No es una vocal"
	FinSi
FinAlgoritmo
