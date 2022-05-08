
#include<stdio.h>
void main()
{
int arr[5],n,sum,i;

printf("\n Enter the Array value :");
scanf("%d",&n);

printf("Enter array :\n");
for(i=0; i<n; i++)

{
scanf("%d",&arr[i]);
}

for(i=0; i<n; i++)

sum=sum+arr[i];

printf("\n Sum of array=%d",sum);

}
