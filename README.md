#include <stdio.h>
void hello();
void printf_star();
void max(int x,int y,int z);
int main()
{
//	hello();
//	printf_star();
//	int a,b,c;
//	scanf("%d %d %d",&a,&b,&c);
//	max(a,b,c);
	return 0;
}

void hello()
{
	printf("Hello World !\n");
}

void printf_star()
{
	printf("****\n  ");
	printf("****\n    ");
	printf("****\n      ");
	printf("****\n");
}

void max(int x,int y,int z)
{
	int max;
	max = (x>y) ? x : y;
	max = (max>z) ? max : z;
	printf ("max = %d",max);
}
