#include <stdio.h>
int main()
{
int arr[100] = { 0 };
int i, x, pos, n = 10;
// initial array of size 10
arr[0]=7;
arr[1]=10;
arr[2]=1;
arr[3]=20;
arr[4]=25;
arr[5]=30;
arr[6]=40;
arr[7]=45;
arr[8]=35;
arr[9]=6;
// element to be inserted
x = 35;
// position at which element
// is to be inserted
pos = 7;
// increase the size by 1
n++;
// shift elements forward
for (i = n; i >= pos; i--)
arr[i] = arr[i - 1];
// insert x at pos
arr[pos - 1] = x;
// print the updated array
for (i = 1; i < n-2; i++)
printf("%d\n", arr[i]);
printf("\n");
return 0;
}
