#include <stdio.h>

int main()
{
    int n, sum=0;
    printf("enter the number:\n");
    scanf("%d", &n);
    for(int i=1;i<=n;i++){
        if(i%2!=0){
            printf("%d",i);
        }
    }

    return 0;
}
