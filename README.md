#include <cs50.h>
#include <stdio.h>

int main(void)
{
    int n;
    
    do
    {
        n = get_int("Height: ");    
    }
    while (n < 1 || n > 8);
    int p =0;
    int x =n;
    for (int i = 0; i < n; i++)
    {
        p++;
        x--;
        
        
        for (int j = 0; j<x; j++)
        {
            printf(" ");
        }
            for (int m = 0; m<p; m++)
            {
                printf("#");
            }
            printf("  ");
             for (int a = 0; a<p; a++)
             {
                printf("#"); 
             }
             
        
        printf("\n");
    }
}

