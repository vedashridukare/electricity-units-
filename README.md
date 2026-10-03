#include<studio.h>
int main ()
{
 flot units;
 printf("Enter electricity units:");
 scanf ("%f", & units);
 if (units <= 100)
 { 
  printf("Low Consumption");
 }
else if (units <= 200)
{
 printf("Normal Consumption");
 
}
else if (units <=500)
{ 
 printf ("High Consumption");
} 
else
{ 
printf ("Very High Consumption");
}
return 0;
}