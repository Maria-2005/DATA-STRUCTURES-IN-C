#include <stdio.h>
struct poly
{
          int coeff;
          int exp;
};
void main()
{
          int i,n;
          printf("Enter the number of terms in the polynomial:");
          scanf("%d",&n);
          struct poly p[10];
          printf("Enter the elements of the polynomial \n");
          printf("Enter the coefficient term and exponent term in descending order \n");
          for(i=0;i<n;i++)
          {
                 printf("Enter the coefficient term:");
                 scanf("%d",&p[i].coeff);
                 printf("Enter the exponent term:");
                 scanf("%d",&p[i].exp);
          }
          printf("The given polynomial is ");
          for(i=0;i<n;i++)
          {
                 printf("(%dx^%d)",p[i].coeff,p[i].exp);
                 if(i!=n-1)
                 {
                    printf("+");
                 }
          }  
}
