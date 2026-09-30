# Men-simple-con-switch
Mostrar el nombre del día según un número del 1 al 5. 

??? 

#include <iostream> 

using namespace std; 

 

int main() { 

 int opcion; 

 

 cout << "Ingrese un numero del 1 al 5: "; 

 cin >> opcion; 

 

 switch(opcion) { 

 case 1: cout << "Lunes"; break; 

 case 2: cout << "Martes"; break; 

 case 3: cout << "Miercoles"; break; 

 case 4: cout << "Jueves"; break; 

 case 5: cout << "Viernes"; break; 

 default: cout << "Opcion no valida"; 

 } 

 

 return 0; 

} 

 
