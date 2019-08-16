#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>
#include <stdlib.h>
#include <conio.h>
#include <math.h>


int main() {

	char ad0[10], ad1[10], ad2[10], ad3[10], ad4[10];
	char soyad0[10], soyad1[10], soyad2[10], soyad3[10], soyad4[10];
	int a, b, c;
	int ortalama[10];
	
		    printf("ad soyad gir:");
			scanf("%s%s", &ad0, &soyad0);

			printf("ad soyad gir:");
			scanf("%s%s", &ad1, &soyad1);

			printf("ad soyad gir:");
			scanf("%s%s", &ad2, &soyad2);

			printf("ad soyad gir:");
			scanf("%s%s", &ad3, &soyad3);

			printf("ad soyad gir:");
			scanf("%s%s", &ad4, &soyad4);

			for (int i = 1; i < 6; i++)
			{
				printf("notlarý gir:");
				scanf("%d%d&d", &a, &b, &c);
				ortalama[i] = (a + b + c)/ 3;



			}

			printf("%s%s%d",&ad0,&soyad0,&ortalama[0]);

			printf("%s%s%d",ad1,soyad1,ortalama[1]);

			printf("%s%s%d",ad2,soyad2,ortalama[2]);

			printf("%s%s%d",ad3,soyad3,ortalama[3]);

			printf("%s%s%d",ad4,soyad4,ortalama[4]);



}