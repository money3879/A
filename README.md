# A
this is a program

#include <stdio.h>
#include <stdlib.h>

int main()
{
    int a, b;
    while( scanf( "%d %d", &a, &b ) != EOF ){
        if( a > b ){
            printf( "%d\n", a-b );
        }
        else{
            printf( "%d\n", b-a );
        }
    }
    return 0;
}
