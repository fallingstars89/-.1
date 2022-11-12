#include <stdio.h>
#include <math.h>
int main()
{
	float x, y;
	printf("请输入x:");
	scanf("%f", &x);
	if (x < 1)
	 y = 2 * x + 1;
	else if (1 <= x < 10)
	    y = 1;
	else
        y = sqrt(x);
	printf("x=%f,y=%f\n", x, y);
}
