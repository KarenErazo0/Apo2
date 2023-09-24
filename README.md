![Logo Java](https://seeklogo.com/images/J/java-logo-7833D1D21A-seeklogo.com.png)

# MENU DE CALCULADORA

Este proyecto consiste en un menu de calculadora donde podras hacer conversiones, 
promedio, clasificacion de Equipos e identificador de numero par e impar

## Empezando

Estas instrucciones te permitirán tener una calculadora en el lenguaje de Java Script

### Requisitos previos

Tener eclipse en tu computador.
```
https://www.eclipse.org/downloads/packages/release/indigo/sr2/eclipse-ide-javascript-web-developers
```

### Instalación

Estos son los codigos que vamos a utilizar en cada caso:

--Importar clase--

```
import javax.swing.JOptionPane;
```
Este sirve para mostrar un dialogo grafico y para que funcionen los codigos compuestos por JOptionPane

--Para imprimir un mensaje--
```
JOptionPane.showMessageDialog(null, "-Mensaje", "Titulo", -1;
```
Este código se compone de parametros, cada parametros es separado por comas y va estructura con null,"Mensaje","Titulo",Numero(Icono)

## Ejecutando las pruebas
```
package proyectos;
import javax.swing.JOptionPane;
public class Menu {
public class ejercicio_7 {
public static void main(String[]args){
			int valor=0;
			while(valor!=5) {
JOptionPane.showMessageDialog(null, "-BIENVENIDOS AL MENU 2.0-\n", "MENU", -1);
valor= Integer.parseInt(JOptionPane.showInputDialog(null, "Elija entre las opciones\n"+"1.Conversor\n"+"2.Promedio\n"+"3.Clasificacion\n"+"4.Par_e_Impar\n"+"5.Salir\n","MENU",3));
			 
switch (valor){
case 1:

float dolares=0;
float pesos=0;
JOptionPane.showMessageDialog(null,"Bienvenido al conversor de monedas\n","Conversor de Monedas",-1);
pesos = Integer.parseInt(JOptionPane.showInputDialog(null, "ingrese el valor de pesos: ","Conversor de monedas",3));
dolares=(pesos/4150);
JOptionPane.showMessageDialog(null,"La cantidad en dolares es: "+dolares,"Conversor de Monedas",1);
break;
				
case 2:
				
JOptionPane.showMessageDialog(null,"Bienvenido al promedio de notas","Promedio Notas",-1);
float promedio=0;
int nota1=Integer.parseInt(JOptionPane.showInputDialog(null,"Ingrese nota 1","Promedio Notas",3));
int nota2=Integer.parseInt(JOptionPane.showInputDialog(null,"Ingrese nota 2","Promedio Notas",3));
int nota3=Integer.parseInt(JOptionPane.showInputDialog(null,"Ingrese nota 3","Promedio Notas",3));
promedio=(nota1+nota2+nota3)/3;
JOptionPane.showMessageDialog(null,"Su promedio de notas es: " + promedio,"Promedio Notas",1);
break;
				
case 3:

JOptionPane.showMessageDialog(null,"Bienvenido a la clasificacion de equipos","Clasificacion Equipos",-1);
int partidosGanados=Integer.parseInt(JOptionPane.showInputDialog(null,"¿Cuantos Partidos Ganaron? :","Clasificacion Equipos",3));
int partidosPerdidos=Integer.parseInt(JOptionPane.showInputDialog(null,"¿Cuantos partidos perdieron? :","Clasificacion Equipos",3));
int partidosEmpatados=Integer.parseInt(JOptionPane.showInputDialog(null,"¿Cuantos partidos empataron? :","Clasificacion Equipos",3));
int totalPuntos=0;
totalPuntos=partidosGanados*3+partidosPerdidos*0+partidosEmpatados*1;
JOptionPane.showMessageDialog(null,"Total de puntos: "+totalPuntos,"Clasificacion Equipos",1);
break;

case 4:

JOptionPane.showMessageDialog(null,"Bienvenido Par e Impar","Par e Impar",-1);
int numero=Integer.parseInt(JOptionPane.showInputDialog(null,"Ingrese el numero:","Par e Impar",3));
if(numero==0) {
JOptionPane.showMessageDialog(null,"El numero es cero\n ","Par e Impar",1);
			}
else if(numero%2==0){
JOptionPane.showMessageDialog(null,"El numero es par\n ","Par e Impar",1);	
			}
else{
JOptionPane.showMessageDialog(null,"El numero es impar\n ","Par e Impar",1);
			}
break;
			
case 5:

JOptionPane.showMessageDialog(null,"Usted salio del menu\n ","Salida",1);
break;
default:
JOptionPane.showMessageDialog(null,"Este numero no pertenece al menu :c\n","ERROR",0);
break;
	}
	}
	}
	}
}
```

### Dividir en pruebas de principio a fin

Explique qué prueban estas pruebas y por qué.

```
Give an example
```

### Y pruebas de estilo de codificación.

Explique qué prueban estas pruebas y por qué.

```
Give an example
```

## Construido con

Eclipse IDE for Java Script

## Versionado

Utilizamos la version de: Eclipse IDE for Java developers-2023-06

## Autores

* **Johan Serrano**
* **Karen Erazo** 

## Expresiones de gratitud (Acknowledgments)

* Aprovechar las herramientas que tenemos a nuestro alcance 
* Este proyecto fue realizado con el acompañamiento del Docente Mauricio Lopez 

