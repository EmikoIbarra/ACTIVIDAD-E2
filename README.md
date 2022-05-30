# ACTIVIDAD-E2
##Título: Programas en c++ de Ibarra Emiko
#Información del autor
#AUTOR:
Ibarra Herrera Emiko Janeth 
#CORREO:
emiko.ibarra.herrera@utelvt.edu.ec
#ENLACE DEL VIDEO:
https://youtu.be/u6-lx7w2YIc
#Programas
IbarraEmiko-Compara.cpp
IbarraEmiko-CuentaMoneda.cpp
IbarraEmiko-PuntoVenta.cpp
IbarraEmiko-SumaN.cpp
IbarraEmiko-LaEdad.cpp
#Descripcion de los programas
#IbarraEmiko-Compara.cpp
El programa permite comparar dos numeros ingresados de manera manual por el usuario, y determinar cuando estos numeros son iguales o cuando uno de ellos es mayor al otro.
#IbarraEmiko-CuentaMoneda.cpp
El programa permite ingresar la cantidad de monedas que el usuario desee, repartidas en tres denominaciones (10, 25 y 50 centavos). Una vez ingresadas las monedas, el programa debe clasificar cuantas monedas de cada tipo se han ingresado, imprimir ese dato e imprimir el valor total del dinero ingresado.
#IbarraEmiko-PuntoVenta.cpp
El programa permite ingresar el valor de las comprar que el usuario desee, calcula el valor del IVA de la compra, aplica un descuento a elección del usuario, para finalmente, mostrar el valor bruto de la compra, el valor del IVA, el valor del descuento, y el precio final a pagar.
#IbarraEmiko-SumaN.cpp
Este progrma en C++ nos permite realizar la suma de varios numeros y tiene como finalidad que el usuario ingrese valores y asi le permita calcular la suma de varios numeros.
#IbarraEmiko-LaEdad.cpp
El programa permite calcular la edad exacta de una persona, mediante el ingreso de la fecha de nacimiento del usuario (dd/mm/yy) y el ingreso de la fecha actual (dd/mm/yy).
#Funcionalidad
#IbarraEmiko-Compara.cpp
En este programa vamos a usar variable de tipo decimal (float).
El programa nos permite ingresar las dos cantidades que deseamos comparar, las cuales van a estar almacenadas en ei_a y ei_b respectivamente.
Una vez ingresadas las variables, utilizaremos la función if para poder hacer una comparación lógica entre las cantidades ingresadas.
#IbarraEmiko-CuentaMoneda.cpp
int ei_a, ei_b= 0 , ei_b1= 0 , ei_b2= 0 ;
float ei_x, ei_m= 0 , ei_m1= 0 , ei_m2= 0 ;
	cout<< "Ingreso de la cantidad de monedas: " ;
	cin>>ei_a;
		cout<< " Ingrese el valor de las monedas (0.10,0.25): " ;
		cin>>ei_x;
#IbarraEmiko-PuntoVenta.cpp
int ei_b=0 , ei_e;
float ei_a=0 , ei_x, ei_t, ei_p, ei_pd, IVA= 0.12 , dsc=0.30 , ei_tt;
   cout<< " Ingresé cuántos elementos va a comprar: " ;
  cin>>ei_e;
	cout<< " Ingrese el valor: " ;
	cin>>ei_x;
#IbarraEmiko-SumaN.cpp
int ei_b=0, ei_a;
	float ei_d, ei_c=0;
	cout<<"Ingrese cuántos números va a sumar: "<<endl;
	cin>>ei_a;
		cout<<"Ingrese el número: "<<endl;
		cin>>ei_d;
#IbarraEmiko-LaEdad.cpp
int ei_a, ei_b, ei_c, ei_a1, ei_b1, ei_c1, ei_d, ei_q, ei_eu, ei_qq, ei_qq1;
	cout<< " Ingresé la fecha de hoy " ;
	cin>>ei_a>>ei_b>>ei_c;
	cout<< " Ingresé su fecha de nacimiento " ;
	cin>>ei_a1>>ei_b1>>ei_c1;
#Salidas
#IbarraEmiko-Compara.cpp
cout<<"Los números son iguales"<<endl;
		cout<<"El numero "<<ei_a<<" es mayor que "<<ei_b<<endl;
		cout<<"El numero "<<ei_b<<" es mayor que "<<ei_a<<endl;
#IbarraEmiko-CuentaMoneda.cpp
cout<< "La cantidad de monedas ingresadas es: " <<ei_b<<endl;
	cout<< "El total de dinero contado es: " <<ei_m<<endl;
	cout<< " La cantidad de monedas de 0.10c ingresadas es: " <<ei_b1<<endl;
	cout<< " Total de dinero en monedas de 0.10c: " <<ei_m1<<endl;
	cout<< "Cantidad de monedas de 0,25c ingresadas: " <<ei_b2<<endl;
	cout<< "La cantidad de dinero en monedas de 0.25c es: " <<ei_m2<<endl;
#IbarraEmiko-PuntoVenta.cpp
		cout<< " El IVA de su compra es:$ " <<ei_p<<endl;
		cout<< " El descuento de su compra es:$ " <<ei_pd<<endl; 
		cout<< " Usted aplica a descuento: " <<ei_t<<endl;
		cout<< " Su total a pagar es:$ " <<ei_tt<<endl;
#IbarraEmiko-SumaN.cpp
cout<<"La suma total es: "<<ei_c<<endl;
#IbarraEmiko-LaEdad.cpp
cout<< " Su edad es : " <<ei_eu<< " Años; " <<ei_q<< " Meses " << " y " <<ei_d<< " DIA " <<endl;
#Instalar los programas
Para poder descargar el repositorio en el que se encuentran los programas descritos en este post, tienes que realizar el siguiente proceso:
#Clonar el repositorio
Para clonar el repositorio en tu entorno de trabajo, debes usar el comando git clone, seguido de la dirección del repositorio en donde se encuentra el trabajo.

git clone https://github.com/EmikoIbarra/ACTIVIDAD-E2/edit/main/README.md

Una vez clonado en tu equipo, tienes que usar el comando git pull para poder descargar cualquier cambio que se haya podido realizar en el repositorio.

Usando el comando ls de termux, puedes verificar que se encuentran todos los archivos que acabas de descargar.

En caso de que necesites realizar y subir cambios en losp programas, recuerda usar los comandos git status (para ver que es lo que se somete a cambios), git add (para añadir esos cambios a la nube), git commit (para comentar esos cambios) y git push (para poder subir a github los cambios que introduciste).

#Compilar los programas
En caso de que desees compilar y correr los archivos .cpp, debes usar el comando g++ nombre_del_programa.cpp -o nombre_del_programa. 
