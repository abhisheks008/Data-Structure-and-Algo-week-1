#include <stdio.h>
int main()
{
static int array[5] = { 200, 400, 600, 800, 1000 };
int sum;
int addnum(int *ptr);
sum = addnum(array);
printf("Sum of all array elements is:%d\n", sum);
return 0;
}
int addnum(int *ptr)
{
int index, total = 0;
for (index = 0; index < 5; index++)
{
total += *(ptr + index);
}
return(total);
}
