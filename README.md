#include<stdio.h>
    int main(){
    int n,i,max;
    printf("Enter the size of the array : ");
    scanf("%d",&n);
    int arr[n];
    printf("enter %d elements",n);
    for(i=0;i<=n;i++)
        {
        scanf("%d", &arr[i]);
        }
    max=arr[0];
    for(i=1;i<=n;i++)
    {
        if(arr[i]>max)
        {
            max=arr[i];
        }
    }
    printf("The largest element in the given array is : %d\n",max);
    return 0;
}
