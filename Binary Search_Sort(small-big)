#include <stdio.h>
#include <stdio.h>

int main()
{
  int a[30], n, i, t, low, mid, high, found=0;
  printf("\n Enter the NO. of element in the array:");
  scanf("%d", &n);
  if(n>30)
  {
    printf("\n Too many Numbers");
    exit(0);
  }  
  printf("\n Enter the elements of the array:");
  for (i =0; i< n; i++ )
    scanf("%d",&a[i]);
  printf("\n Enter the element to search: ");
  scanf("%d",&t);
  low=0;
  high= n-1;
while(high>=low)
  {
    mid=(low+high)/2;
    if (a[mid]==t)
    {
      found =1;
      break;
    }
    else if (t<a[mid])
      high = mid -1;
    else 
      low = mid +1;
  }
  if (found==0)
    printf("\n NOT Found");
  else 
    printf("\n Found at %d", mid);
  return 0;
}