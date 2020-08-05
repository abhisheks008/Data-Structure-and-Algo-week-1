#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>
int main() {
/* Enter your code here. Read input from STDIN. Print output to STDOUT */
int n, i,j,max;
scanf("%d",&n);
int a[n];
for(i=0;i<n;i++)
scanf("%d\n ",&a[i]);
for(i=0;i<n;i++)
{
for(j=i+1;j<n;j++)
{
if(a[i]>a[j])
{
max=a[i];
a[j]=a[i];
a[j]=max;
}
}
}
printf("%d ",a[n-2]);
return 0;
}
