//练习题1
//计算n的阶乘
#include <stdio.h>
int main()
{
	int n ;
	int fact=1;
	printf("---------计算n的阶乘---------\n");
	printf("请输入n的值->:");
	scanf("%d", &n);
	for (int i = 1; i <= n; i++)
	{
		fact = fact * i;
	}
	printf("n的阶乘为：%d\n", fact);
	return 0;
}
