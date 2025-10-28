# 🎮 Ejemplos de Algoritmos con Estructuras Lineales/Secuenciales
## 🎨 Pseint

**Algoritmo IMC**
	
	// Variables 
	Definir peso, altura, IMC Como Real
	
	//Datos de entrada
	//Escribir  "Ingrese su peso" 
	Leer peso 
	Escribir "Ingrese  su altura"
	Leer altura
	
	//Proceso 
	IMC = peso	/ altura^2 
	
	//Salida
	Escribir "SU IMC es de ", IMC 
	Final algoritmo

  ## 🕹️ Diagrama de flujo 


  **<img width="830" height="996" alt="image" src="https://github.com/user-attachments/assets/7c8ebc98-d82a-484f-af65-791ba85014fa" />**

  ## 🧩 Código en C

    #include <stdio.h>

    int main() {
    // Declarar variables
    float peso, altura, imc;

    // Entrada de datos
    printf("Ingrese su peso en kg: ");
    scanf("%f", &peso);
    // Proceso
    imc = peso / (altura * altura);

    // Salida
    printf("Su IMC es: %.2f\n", imc);

    return 0;
    }

## ♣️ Terminal con el resultado del código

<img width="591" height="240" alt="image" src="https://github.com/user-attachments/assets/43163e6c-3be0-4cbc-8651-2358c884735e" />


## 🎨 Pseint

**Algoritmo suma de dos números**
    
  
	Algoritmo sin_titulo
	
	Definir a como real
	Definir b Como real
	//Datos de entrada
	Escribir "Ingrese el valor de a"
	Leer a;
	
	Escribir "Ingrese el valor de b"
	Leer b;
	
	//Proceso 
	resultado = a + b;
	
	//Salida
	Escribir "El resultado es: ", resultado;
	
	FinAlgoritmo

## 🕹️ Diagrama de flujo

**<img width="780" height="947" alt="image" src="https://github.com/user-attachments/assets/491dff4e-46fd-464c-a03c-02032e6874b3" />**

## 🧩 Código en C

    #include <stdio.h>

    int main(){

    int a, b;
    printf("Escriba un numero\n");
    scanf("%i",&a);
    printf("Escriba un segundo numero\n");
    scanf("%i",&b);
    int suma=a+b;

    printf("La suma de estos dos numeros es %i",suma);

    return 0;
    }

  ## ♣️ Terminal con el resultado del código

  **<img width="591" height="240" alt="image" src="https://github.com/user-attachments/assets/b235925d-758d-4901-9c49-b6716be7d1dd" />**


