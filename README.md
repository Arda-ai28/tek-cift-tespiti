#include <stdio.h>
#include <stdlib.h>

/* run this program using the console pauser or add your own getch, system("pause") or input loop */

int main() {
	
	int sayi;
printf("Sayiyi giriniz: ");
scanf("%d",&sayi);
	if (sayi%2==0)
	{
		printf("Giridiginiz deger cifttir");
	}
	else
	{
		printf("Girdiginiz deger tektir");
	}
	return 0;
}
