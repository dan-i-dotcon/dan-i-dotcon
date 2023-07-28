Proceso operaciones
	// leer 2 numeros ,si son iguales que los multiplique ,si el primero es mayor que el segundo que los reste y si no que los sume .
	Definir numero1, numero2, resultado Como Entero;
	
	Escribir "Ingrese el primer número";
	Leer numero1;
	
	Escribir "Ingrese el segundo número";
	Leer numero2;
	
	Si numero1 = numero2 Entonces
		resultado <- numero1 * numero2;
	SiNo
		Si numero1 > numero2 Entonces
			resultado <- numero1 - numero2;
		SiNo
			resultado <- numero1 + numero2;
		FinSi
	FinSi
	
	Escribir "El resultado es: ", resultado;
	
FinProceso
