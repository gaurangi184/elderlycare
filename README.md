# elderlycare
#include <stdio.h>
#include <conio.h>
char name[50];
float blood_sugar;
float creatinine;
float vit_d;

void main()
{
printf(" please enter your name ");
scanf("%s",name);
printf(" please enter blood sugar level ");
scanf("%f%f%f",&blood_sugar,&creatinine,&vit_d);
void warning()

}
void warning(float blood_sugar,float creatinine,float vit_d)
{
if(blood_sugar>=200)
printf("DIABETES");
elseif(creatinine>15)
printf("KIDNEY DISEASE");
elseif(vit_d<10)
printf("deficiency in vitamin d");
elseif(creatinine>15)
printf("KIDNEY DISEASE");
}


