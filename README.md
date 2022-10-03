# While-
while循环（复习）



int main()
{
	int i = 1;
	while (i <= 10)
	{
		printf("%d", i);
		i++;
	}
	return 0;
}




int main()
{
	int i = 1;
	while (i <= 10)
	{
		if (i == 5)
			break;
		printf("%d", i);
		i++;
	}
	return 0;
}
//在循环中遇到break，停止后面所有循环，直到终止所有循环



int main()
{
	int i = 1;
	while (i <= 10)
	{
		if (i ==  5)
			continue;
		printf("%d", i);
		i++;
	}
	return 0;
}
continue用于终止本次循环，本次循环中continue后面的代码不会再执行，而是直接跳转到while语句判断部分，进行下一次循环入口判断。

