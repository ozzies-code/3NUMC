# 3NUMC
In C Language when using Control Structures there is a need to use the IF conditional as well as comparison operators, the following example allows us to know which is the largest of 3 numbers

#include <stdio.h>
void main()
{   
    int a, b, c, mayor;     
    printf(" Introduzca tres numeros enteros:");
    scanf("%d %d %d", &a, &b, &c);
    if (a > b)
    if (a > c) mayor = a;
    else mayor = c;
    else
    if (a > c) mayor = a;
    {
       printf("%.2f %s", numero, "es mayor que cero\n");
       puts("Pruebe de nuevo introducioendo un numero negativo"); 
    }
    else if (numero < 0)
     {
       printf("%.2f %s", numero, "es menor que cero\n");
       puts("Pruebe de nuevo introducioendo un numero positivo"); 
    }
    else
     {
       printf("%.2f %s", numero, "es igual a cero\n");
       puts("porque no introduce otro numero?"); 
    }
    
}
