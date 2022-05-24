# c
关于C语言
#include<stdio.h>
#include <math.h>

int main()
{
	int i = 0,j=0;
	char arr[10] = { 15,2,3,8,57,6,7,8,10,9 };
	
		for (j = 1; j <10; j++)
		{

			if (arr[i] >= arr[j])
			{
				continue;
			}
			else if(arr[i]<arr[j])
			{
				i = j;

			}
		}
		
			printf("%d\n", arr[i]);
			printf("%d", i);
	
	
	return 0;
}
