让气球飞起来
#include<stdio.h>
#include<time.h>
#include<stdlib.h>
int sub(int a, int b);
int main()
{
	int N;
	int i;
	int redn = 0, greenn = 0, bluen = 0;//记录各个颜色的数目；
	int max;  //存放颜色大的；
	srand((unsigned)time(NULL));
	N = rand() % 100 + 1;
	printf("%d\n", N);
	int a[100];
	for (i = 0; i < N; i++)
	{
		a[i] = rand() % 3 + 1;  //1 表示红色，2表示绿色，3表示蓝色；
	}
	for (i = 0; i < N; i++)
	{
		switch (a[i])
		{
		case 1:printf("red\n"); break;
		case 2:printf("green\n"); break;
		case 3:printf("blue\n"); break;
		}
	}
	for (i = 0; i < N; i++)
	{
		switch (a[i])
		{
		case 1:redn++; break;
		case 2:greenn++; break;
		case 3:bluen++; break;
		default:
			break;
		}
	}
	max = sub(redn, greenn);
	max = sub(max, bluen);
	if (max == redn)
		printf("\n\n\nred\n");
	if (max == greenn)
		printf("\n\n\ngreen\n");
	if (max == bluen)
		printf("\n\n\nblue\n");

	




}
int sub(int a, int b)
{
	if (a > b)
		return a;
	if (a < b)
		return b;
}
