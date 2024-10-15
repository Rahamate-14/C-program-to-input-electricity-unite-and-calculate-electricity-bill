# C-program-to-input-electricity-units-and-calculate-the-electricity-bill-
#include<stdio.h>
void main()
{
int units;
float tot_bill;
printf("enter units :");
scanf("%d",&units);
if(u<=50)
       {
       tot_bill=units*0.5;
       printf(" total bill is %f ",tot_bill);
       }
else if(u<=150&&u>50)
      {
      tot_bill=units*0.75;
      printf(" total bill is %f ",tot_bill);
       }
else if(u<=250&&u>150)
      {
       tot_bill=units*1.2;
       printf(" total bill is %f ",tot_bill);
      }
else
    {
     tot_bill=units*1.5;
     printf(" total bill is %f ",tot_bill);
     }
     }
