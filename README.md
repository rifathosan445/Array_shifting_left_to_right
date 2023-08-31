# Array_shifting_left_to_right
i want to shift the elements in the array left to right ..



    #include<stdio.h>

    int main() {
    int a[5]={1,2,3,4,5},i,k;
    scanf("%d",&k);
    for(i=4;i>=k;i--)
    {
       a[i]=a[i-k];

    }
    for(i=0;i<k;i++)
    {
       a[i]=0;
    }

    for(i=0;i<5;i++)
    {
       printf("%d,",a[i]);
    }
    return 0;
    }
