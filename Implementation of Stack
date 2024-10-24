#include <stdio.h>
void push();
void pop();
void display();
int item,top=-1,A[20],i,maxsize;
void main()
{
     int ch;
     printf("Enter limit:");
     scanf("%d",&maxsize);
     while(ch!=4)
     {
           printf("1.Push\t 2.Pop\t 3.Display\t 4.Exit\n");
           printf("Enter choice:");
           scanf("%d",&ch);
           switch(ch)
           {
                 case 1:push();
                        break;
                 case 2:pop();
                        break;
                 case 3:display();
                        break;
                 case 4:printf("End of program");
                        break;
           }
     }
}
void push()
{
     if(top==maxsize-1)
     {
          printf("Overflow\n");
     }
     else
     {
          printf("Element to be pushed:");
          scanf("%d",&item);
          top++;
          A[top]=item;
     }
}
void pop()
{
     if(top==-1)
     {
          printf("Underflow\n");
     }
     else
     {
          item=A[top];
          top--;
          printf("Deleted item is %d\n",item);
     }
}
void display()
{
     if(top==-1)
     printf("The stack is empty\n");
     else
     printf("Stack is:\n");
     for(i=top;i>=0;i--)
     {
          printf("%d\n",A[i]);
     }
}
