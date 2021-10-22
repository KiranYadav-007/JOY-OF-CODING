#include<stdio.h>
#include<stdlib.h>
void main()
{
	int*a,n,i,j;
	printf("Enter the number of elements\n");
	scanf("%d",&n);
	a=(int*)malloc(n*sizeof(int));
	for(i=0;i<n;i++)
	{
		printf("Enter the element\n");
		scanf("%d",&a[i]);
	}
	printf("The elements in the box\n");
	for(i=0;i<n;i++)
	{
		for(j=i+1;j<n;j++)
		{
			if(a[i]==a[j])
				a[j]=10;
		}
		if(a[i]<10&&a[i]>-1)
			printf("%d\t",a[i]);
	}
	printf("\n");
}
