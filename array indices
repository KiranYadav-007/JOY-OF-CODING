#include<stdio.h>
#include<stdlib.h>
void main()
{
	int*a,n,i,j,sum,flag=1;
	printf("Enter the number of elements\n");
	scanf("%d",&n);
	a=(int*)malloc(n*sizeof(int));
	for(i=0;i<n;i++)
	{
		printf("Enter the element\n");
		scanf("%d",&a[i]);
	}
	printf("Enter the sum\n");
	scanf("%d",&sum);
	for(i=0;i<n;i++)
	{
		for(j=i+1;j<n;j++)
		{
			if(a[i]+a[j]==sum)
			{
				printf("Indices found at %d and %d (%d and %d)\n",i,j,a[i],a[j]);
				flag=0;
			}
		}
	}
	if(flag)
		printf("No indices found\n");
}
