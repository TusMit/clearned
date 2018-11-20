排序：
int a [];
for(int i ;i<sizeof(a);i++)
  for(int j;j<sizeof(a);j++)
    {
      if(a[j]<= a[i])
      {
        int temp;
        temp = a[j];
        a[j] = a[i];
        a[i] = temp;
      }
      printf"%d",(a[i]);
    }

二分查找：
int teger(int a[],int number)
{
  int start =0;
  int end = sizeof(a);
  while(start <= end)
  {
    int mid = (start + end)/2;
    if(a[mid] == number)
    {
      return mid;
    }
    else if(a[mid] < number)
    {
      start = mid + 1;
    }
    else
      end = mid - 1;
  }
  return -1;
}
