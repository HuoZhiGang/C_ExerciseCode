#include <stdio.h>
int main()
{
	int a=8;//101
	int b=5;//110

	a=a^b;//
	b=a^b;
	a=a^b;
	printf("a=%d b=%d",a,b);
	return 0;
}
