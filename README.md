# pointer-in-c
#include <stdio.h>
#include <stdlib.h>
void update(int *a,int *b) 
{
    // Pointers in C - 
    int x,y;
    x = *a + *b;
    y = *a - *b;
    *a = x;
    *b =abs(y); 
    // Pointers in C - 
}

int main() 
{
    int a, b;
    int *pa = &a, *pb = &b;
    
    scanf("%d %d", &a, &b);
    update(pa, pb);
    printf("%d\n%d", a, b);

    return 0;
}
