##
<span style="color:orange">#### Fecha: 8 de noviembre 2022</span> 

# GIT HUB
Configurar Nombre que salen en los commits

	git config --global user.name "dasdo"

Configurar Email

	git config --global user.email dasdo1@gmail.com

Subimos al repositorio

	git push origin master

El comando git pull se usa para obtener actualizaciones del repositorio remoto.

	git pull <remote>

<span style="color:orange">#### Fecha: 9 de noviembre 2022</span>  


# GIT

Iniciamos GIT en la carpeta donde esta el proyecto

	git init


Añadimos todos los archivos para el commit

	git add .

Cargar en el HEAD los cambios realizados

	git commit -m "Texto que identifique por que se hizo el commit"

Lista un estado actual del repositorio con lista de archivos modificados o agregados

	git status


git gc limpiará archivos innecesarios y optimizará el repositorio local.

	git gc

Nos muestra la carpeta actual en la que nos encontramos.

	git pwd

Nos permite ver los archivos de la carpeta donde estamos actualmente

	git ls

<span style="color:orange">#### Fecha: 11-14 de noviembre 2022</span> 
#### Fecha: 11-14 de noviembre 2022

# Introducción a la programación
IDE: entorno de desarrollo integrado 
>Herramientas a utilizar
 1. Visual Studio Code
 2. Compiladores
 3. Git bash
 4. Git hub
 5. Theme VSCode
>Comandos mas utilizados en VSCode

## ----General----

**Abrir paleta de comandos**.................Ctrl + Shift + P 

**Abrir archivo**..........................	Ctrl + P


**Nueva ventana**......................	Ctrl + Shift + N


**Cerrar ventana**......................	Ctrl + Shift + W


**Ajustes del perfil**.................	Ctrl + ,


## ----Usabilidad----

**Crear un nuevo archivo**...........	Ctrl + N

**Abrir archivo**	.................................Ctrl + O

**Guardar archivo**	...........................Ctrl + S

**Cerrar**................................................	Ctrl + F4

**Abrir Consola**.................................	Ctrl + Ñ

**Panel de problemas**....................	Ctrl + Shift + M

>MAS COMANDOS EN EL SIGUIENTE 
[Link](https://soka.gitlab.io/blog/post/2020-11-02-curso-vscode-1/img/03.png "Atajos de teclado VSCode"). 

<span style="color:orange">#### Fecha: 16 de noviembre 2022</span>

# INTRO TO C

 **Primer programa en c*

__Proceso:__
 > code
``` c
# include <stdio.h>

int main()
{
    printf("Hello OscarTV23!\n");
    return (0);       
}
```

<span style="color:orange">#### Fecha: 18 de noviembre 2022</span>

# Programar en C

> Requisitos previos

Para llamar a la libreia utilizamos
``` c
#include <nombre de la librería>
```
Para imprimir un mensaje: 
``` c
printf("El valor es %d.\n", contador);
```
[Link](https://www.it.uc3m.es/pbasanta/asng/course_notes/input_output_printf_example_es.png "Explicación"). 

Para capturar datos
``` c
scanf (cadena de control, lista de argumentos);
```
### Cadena de control
----
En la **cadena de control** se incluyen grupos individuales de caracteres cada uno de los cuales deben comenzar por **%**.

>CarácterㅤㅤㅤㅤㅤㅤㅤSignificado

cㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ Lee un carácter simple

dㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ Lee un entero decimal 

iㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ Lee un entero decimal, octal o hexadecimal

eㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ Lee un número en punto flotante

fㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ	Lee un número en punto flotante

gㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ	Usa %e o %f, el más corto en long.

oㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ	Lee un entero octal corto

sㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ	Lee una cadena de caracteres

uㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ	Lee un entero decimal sin signo

xㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ	Lee un entero hexadecimal 

<span style="color:orange">#### Fecha: 21 de noviembre 2022</span>

# Variables
### Tipos de Datos
----
Tipos de Datosㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ  	 Descripción  

intㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ ㅤㅤㅤㅤCantidad entera

charㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ ㅤㅤㅤ  Carácter	

floatㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ  ㅤㅤㅤAlmacena valores reales en punto flotante.	

doubleㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ ㅤㅤAlmacena valores reales en doble precisión.

voidㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ ㅤㅤㅤSe utiliza para definir una función que no devuelve ningún valor o declarar punteros genéricos 

<span style="color:orange">### Fecha: 22 de noviembre 2022</span>

# Algoritmia 

> Pseudocódigo

Ejemplo 1:
``` c
ALGORITMO Mostrar;
VAR
    ENTERO entrada;
INICIO
    ESCRIBIR("Dame un número");
    LEER( entrada );
    ESCRIBIR( entrada );
FIN
```
Ejemplo 2:
``` c
ALGORITMO Sumar;
VAR
    ENTERO Numero1, Numero2, Resultado;
INICIO
    ESCRIBIR("Dime dos números para sumar: ");
    LEER(Numero1, Numero2);
    Resultado <- Numero1 + Numero2;
    ESCRIBIR("La suma es: ", Resultado);
FIN
```

> Diagrama de Flujo

![Esta es una imagen de ejemplo](https://www.areatecnologia.com/informatica/imagenes/simbolos-diagramas-de-flujo.jpg)

Ejemplo de un diagrama de flujo

![Esta es una imagen de ejemplo](https://www.areatecnologia.com/informatica/imagenes/diagrama-flujo-suma-numeros.jpg)
![Esta es una imagen de ejemplo](https://www.areatecnologia.com/informatica/imagenes/diagrama-flujo-numeros.jpeg)

<span style="color:orange">### Fecha: 06 de diciembre 2022</span>
# Analisis de algoritmos
> Codificación

``` c
#include <stdio.h>

int main()
{
   int a, b, c;

   printf( "\n   Introduzca el primer n%cmero (entero): ", 163 );
   scanf( "%d", &a );
   printf( "\n   Introduzca el segundo n%cmero (entero): ", 163 );
   scanf( "%d", &b );
   c = a + b;
   printf( "\n   La suma es: %d", c );

   return 0;
}
```

> Trace

![Esta es una imagen de ejemplo](https://karolay13.files.wordpress.com/2015/03/alg.png)

<span style="color:orange">### Fecha: 07 de diciembre 2022</span>


# Estructura general de un programa

``` c
(#include <stdio.h>
#include <stdlib.h>
#include <conio.h>)//, son para instrucciones de entreda y salida (libreria).
int main(), //es donde  se empieza el programa
{  //,los corchete  indica que los van adentro son programa (inicia)
//int , sirve para indicarle al compilador

int a,b , c, //son las variables

//printf es para imprimir lo que esta escrito
scanf(«%d», &a); //permite escribir la variables
printf(«\n»);

printf(«Introduzca el valor de b : «);//introduce el valor que queremos

printf («\n La suma es : %d «, suma);//permite ver e imprimir el resultado

system(«pause»); //indica detener el programa

}//, termina el progama.
```

![Esta es una imagen de ejemplo](https://static.wixstatic.com/media/ba6498_eec44001588c4418aefed6e98b4060ad.png/v1/fill/w_553,h_402,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/ba6498_eec44001588c4418aefed6e98b4060ad.png)

Primer deber:

> Cuadrado
```c
#include <stdio.h>

int main()
{

    int num, a, b;

    printf("Numero de signos para el cuadrado:");
    scanf("%d",&num);

    for(b=1; b <= num; b++)
    {
        for(a=1; a<= num; a++)
        {
            if(b==1 || b== num)
            {
                if (a%2==0)
                printf("+ ");
                else
                printf("- ");
                
            }else if(a==1 || a== num){
                if (b%2==0)
                    printf("+ ");
                else
                    printf("- ");
            }else{

                printf("  ");
            }
        }
        printf("\n");
    }
}
```

Segundo deber 

> Escalera 
```c
#include <stdio.h>

int main()
{

    int num, a, b;

    printf("Numero de signos para el cuadrado:");
    scanf("%d",&num);

    for(b=1; b <= num; b++)
    {
        for(a=1; a<= num; a++)
        {
            if(b==1 || b== num)
            {
                if (a%2==0)
                printf("+ ");
                else
                printf("- ");
                
            }else if(a==1 || a== num){
                if (b%2==0)
                    printf("+ ");
                else
                    printf("- ");
            }else{

                printf("  ");
            }
        }
        printf("\n");
    }
}
```
<span style="color:orange">### Fecha: 09 de diciembre 2022</span>


# Tipos, operadores y expresiones
>C incluye los operadores unarios siguientes:

Símboloㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ ㅤㅤㅤㅤ	NOMBRE

 ~ - !ㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ ㅤㅤㅤㅤOperadores de negación y complemento

 & *ㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ ㅤㅤㅤㅤ 	Operadores de direccionamiento indirecto y address-of

_Alignofㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ ㅤㅤOperador de alineación (desde C11)

sizeofㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ ㅤㅤㅤOperador de tamaño

+ㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ ㅤㅤㅤㅤ	 Operador unario más

++ --ㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ ㅤㅤㅤOperadores unarios de incremento y decremento

>Otras operaciones 

Símboloㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ ㅤㅤㅤㅤ	NOMBRE

*ㅤ / %ㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ ㅤㅤㅤㅤOperadores de multiplicación

+ㅤ -ㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ ㅤㅤㅤㅤ	Operadores aditivos

<< >>ㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ ㅤㅤㅤㅤ	Operadores de desplazamiento

< > <= >= == !=ㅤㅤㅤㅤㅤㅤㅤㅤㅤOperadores relacionales

& | ^ㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ ㅤㅤㅤㅤ	Operadores bit a bit

&& ||ㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ ㅤㅤㅤㅤ	Operadores lógicos

,ㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ ㅤㅤㅤㅤ	Operador de evaluación secuencial

<span style="color:orange">### Fecha: 13 de diciembre 2022</span>

# Array

>Un array es un conjunto de variables del mismo tipo que tienen el mismo
nombre y se diferencian en el índice.

Para acortar un poco el programa podríamos hacer algo así: 
``` c
#include <stdio.h>
int main()
 {
 /* Declaramos 24 variables, una para cada hora del dia */
int temp1, temp2, temp3, temp4, temp5, temp6, temp7,
temp8;
int temp9, temp10, temp11, temp12, temp13, temp14, temp15,
temp16;
int temp17, temp18, temp19, temp20, temp21, temp22, temp23,
temp0;
 int media;
 /* Ahora tenemos que dar el valor de cada una */
printf( "Introduzca las temperaturas desde las 0 hasta las 23
separadas por un espacion: " );
 scanf( "%i %i %i ... %i", &temp0, &temp1, &temp2, ... &temp23 );

 media = (temp0+temp1+temp2+temp3+temp4+ ... +temp23)/24;
 printf( "\nLa temperatura media es %i\n", media );
 } 
```
Y esto con un ejemplo que tiene tan sólo 24 variables, ¡¡imagínate si son más!!

Y precisamente aquí es donde nos vienen de perlas los **arrays.** Vamos a hacer el
programa con un array. Usaremos nuestros conocimientos de bucles for y de scanf. 

``` c
#include <stdio.h>
int main()
 {
 int temp[24];/*Con esto ya tenemos declaradas las 24 variables */
 float media;
 int hora;
 /* Ahora tenemos que dar el valor de cada una */
 for( hora=0; hora<24; hora++ )
 {
 printf( "Temperatura de las %i: ", hora );
 scanf( "%i", &temp[hora] );
 media += temp[hora];
 }
 media = media / 24;
 printf( "\nLa temperatura media es %f\n", media );
 } 

```

> Declaración de un Array 

La forma general de declarar un array es la siguiente:
``` c
  tipo_de_dato nombre_del_array[ dimensión ];
```

El **tipo_de_dato** es uno de los tipos de datos conocidos (int, char, float...). En el ejemplo era int.

El **nombre_del_array** es el nombre que damos al array, en el ejemplo era temp.

La **dimensión** es el número de elementos que tiene el array. 

Ejemplo.-
> Letra Nombre
```c
#include<stdio.h>

void MatrizInicialNombre(){

    int mc[8][8];
int fila = sizeof(mc)/sizeof(mc[0]); 
int columna = sizeof(mc[0])/sizeof(mc[0][0]); 

for(int fi=0;fi < fila; fi++){       

        for(int ci=0;ci <columna; ci++){  
            if((fi==0)||(ci==0)||(fi==7)||(ci==7))
                printf("*", mc[fi][ci]);
            else
            printf(" ");  
    }
    printf("\n");
}
}
int main(void){
MatrizInicialNombre();
}

```
<span style="color:orange">### Fecha: 13 de diciembre 2022</span>

# Estructuras y uniones
TIPOS DE FUNCIONES Y PROCEDIMIENTOS

> FUNCIONES

- Funciones de Librería.

Ya están hechas y vienen compiladas en unos archivos llamados Archivos de Librería, y sus declaraciones están en los Archivos de Cabecera.

Dentro del archivo stdio.h están declaradas las funciones printf y scanf.

- Funciones definidas por el Usuario.

Se las debe programar y pueden ser ejecutadas todas las veces que se quiera desde el programa principal o desde cualquier otra función o procedimiento definidos por el usuario con sola condición que antes de utilizarse estén declaradas.

En este caso la función fibo es llamada desde la función principal (main)

- Sintaxis     : variable = nomb_función (parámt_actuales);
- Propósito   : Llamar desde el programa principal o desde algún procedimiento a una función requerida por su nombre.
- Ejemplo     : 
``` c
  y = acumulativa (m, x);
```
Ejemplo 1.-

``` cpp
int main()    {
    int k = 15;
    cout<<sum(k)<<k;
              }
   int sum(int z)  {
     z = z + z;
    return(z);    }
```

>Procedimientos 

![Esta es una imagen de ejemplo](https://ccia.ugr.es/~jfv/ed1/c/cdrom/images/Buzon1.gif)

![Esta es una imagen de ejemplo](https://player.slideplayer.es/10/2750294/data/images/img9.jpg)

En el siguiente link encontrara una explicaion de lo que son los procedimientos:

[Link](http://4.bp.blogspot.com/-1pVdXsuCcE8/TZ-H2SLFxtI/AAAAAAAAAUY/rO8I3Mkx3ug/s1600/Llamado.bmp "Explicación").

>Declaración de un Procedimiento
- Sintaxis      : 
```cpp
void nombre_procedim (parám_formals)  {
      Variables locales
      Líneas de código de cuerpo de procedimiento
                        }
```
- Propósito    : Declarar un procedimiento indicando nombre y especificando que es un subprograma sin valores de retorno (void). 

- Ejemplo
```cpp
void reportar (int n, float lista[20])  {
                        int i;              // Definición de variables locales
                        for(i=1;i<=n;i++) cout<<lista[i];
                        // Cuerpo del procedimiento
                        }
```

<span style="color:orange">### Fecha: 16 de noviembre 2022</span>

# Workshop - laboratorioteórico práctico

```cpp
#include<stdio.h>
#include <string.h>

void MatrizInicialNombre(){
    char nomb1 [50];
    char nomb2 [50];
    char nomb3 [50];
    char nomb4 [50];
    char nomb5 [50];
    char nomb6 [50];
    char nomb7 [50];
    int tamano;

    printf("Nombre y apellido Persona 1: "); gets(nomb1);
    printf("Nombre y apellido Persona 2: "); gets(nomb2);
    printf("Nombre y apellido Persona 3: "); gets(nomb3);
    printf("Nombre y apellido Persona 4: "); gets(nomb4);
    printf("Nombre y apellido Persona 5: "); gets(nomb5);
    printf("Nombre y apellido Persona 6: "); gets(nomb6);
    printf("Nombre y apellido Persona 7: "); gets(nomb7);

    /*printf("%s", nomb1);
    printf("%s", nomb2);
    printf("%s", nomb3);
    printf("%s", nomb4);
    printf("%s", nomb5);
    printf("%s", nomb6);
    printf("%s", nomb7);*/

    printf("Ingrese el tamano de la letra: "); scanf("%i",&tamano);

    while (tamano<5)
    {
        printf("Tamano no valido, ingrese nuevamente: "); scanf("%i",&tamano);
    }

    char signo[1];
    int mc[tamano][tamano];

printf("Ingresa el signo deseado: "); scanf("%s",&signo);


int fila = sizeof(mc)/sizeof(mc[0]); 
int columna = sizeof(mc[0])/sizeof(mc[0][0]); 

for(int fi=0;fi < fila; fi++){       

        for(int ci=0;ci <columna; ci++){  
            if((fi==0)||(ci==0)||(fi==tamano+1)||(ci==tamano+1))
                printf("%s",signo);
            else
            printf(" ");  
    }
    printf("\n");
}
}
int main(void){
MatrizInicialNombre();
}
```

<span style="color:orange">### Fecha: 04 de enero del 2023</span>

# Archivos 
> Abrir archivos

```cpp
#include<fstream.h>
int main()
{
 ofstream f;
 int i;
 // APERTURA del fichero
 f.open("datos.txt");
 if(!f)
 cout << "Error abriendo el fichero" << endl;
 else
 {
 // OPERACIONES sobre el fichero
 for(i = 1; i <= 10; i++)
 f << i << endl;
 // CIERRE del fichero
 f.close();
 }
 return 0;
}
```

> Escritura en archivos


```cpp
#include<fstream.h>
#include<iostream.h>
int main()
{
 ofstream f;
 int i;
 f.open("datos.bin");
 if(!f)
 cout << "Error abriendo el fichero" << endl;
 else
 {
 for(i = 1; i <= 10; i++)
 f.write((char *)(& i), sizeof(i) );
 f.close();
 }
 return 0;
}
```
