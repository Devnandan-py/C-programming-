#include <stdio.h>
#include <stdbool.h>
 void perfectnumber(int UpperLimit , int LowerLimit )
 {
	 int FactorSum;
	 for(int i=LowerLimit; i<=UpperLimit ; i++)
    {
        FactorSum = 0;
        for(int j=1; j<i; j++)
        {
            if(i % j == 0)
            {
                FactorSum += j;
            }
        }
        if(FactorSum == i)
        {
			printf("%d ",i);
		}
	}    
}

int main()
{
    int start, end;


    printf("Enter lower limit: ");
    scanf("%d", &start);
    printf("Enter upper limit: ");
    scanf("%d", &end);

    printf("All Perfect numbers between %d to %d:", start, end);
    perfectnumber(end,start);
    return 0;
}
