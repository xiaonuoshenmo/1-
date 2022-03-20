# 1-#include<stdio.h>

int main()
{
	printf("请输入你需要查找的句子（小写）");
	char a[100];
	gets(a);
	printf("请输入你要查找的字母或字母组（小写）");
	char b;
	gets(&b);
	int i=0,j=0;
	for(i;i<100;i++)
	{
		if(a[i]==b)
		j++;
	}
	printf("一共出现了%d\n",j);
	return 0;
}
