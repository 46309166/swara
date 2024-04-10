# swara
this is my 1st repository


   #include <stdio.h>

int main() {
    
    int qty,dis=0;
    float rate,tot;
    
    
    printf("enter quantity and rate");
    scanf("%d %f",&qty,&rate);
    
    if(qty>=200)
    {
        dis=10;
        tot=(qty*rate)-(qty*rate*dis/100);
        printf("Total Expense=Rs.%f\n",tot);
    }

    return 0;
}            
