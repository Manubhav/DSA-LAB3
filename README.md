# DSA-LAB3
## PROGRAM TO PRINT PYRAMID STAR PATTERN
    #include <stdio.h>
    int main()
    {
      int i, j, n, s;
      printf("Enter the number of rows:\n");
      scanf("%d", &n);
      s=n;
      for (i=1;i<=n;i++)  // Loop to print rows
      {
        for (j=1;j<s;j++)  // Loop to print spaces in a row
          	{
			printf(" ");
		}
        s--;
        for (j=1;j<=2*i-1;j++) // Loop to print stars in a row
         	{
		  	printf("*");
    		}
	 	printf("\n");
      }
      return 0;
    }
