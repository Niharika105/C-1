# C-1
program to find maximum and minimum of two numbers without using any 
#include<stdio.h>
#include<stdlib.h>
int main()
{
	int a=-22, b=4;
	printf("max=%d\n",((a+b)+abs(a-b))/2);
	printf("min=%d\n",((a+b)-abs(a-b))/2);
	return 0;
}
