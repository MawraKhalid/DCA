#include<stdio.h>
#include<conio.h>
int main()

{
   int score[7]={10,11,12,13,14,15,16};
   int count=0,sum=0,answer[7];
    float avg;
for(count=0;count<=7;count++) 
{
	sum+=score[count];
}
avg=sum/7;
printf("%d",sum);
printf("\n%f",avg);
printf("\n");

 for(count=0;count<7;count++)
 {
 	answer[7]=(score[count]-avg)*(score[count]-avg);
 	printf("\n%d",answer[7]);
 }
 return (0);
 getch();
}
