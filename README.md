# grrg#include <stdio.h>
#include <conio.h>
#include <math.h>

void main()

{#include <stdio.h>
#include <conio.h>

void main()

{
	float s, t, p;
	int n;
	clrscr();

	printf("Nhap so tien ban dau : ");
	scanf("%f", &s);
	printf("Nhap so tien can co : ");
	scanf("%f", &t);
	printf("Nhap lai suat %% nam : ");
	scanf("%f", &p);

	for (p = 0.01 *p, n = 0; s < t; s += s *p, n++);
	printf("So nam can gui tiet kiem = %d\n", n);
	printf("Sau %d nam gui tiet kiem, so tien co la : %4.2f", n, s);

	getch();
}
	float a, b, c, p, s;
	int deu, vuong, can;
	clrscr();
	printf("Nhap cac so thuc a, b, c : ");#include <stdio.h>
#include <conio.h>

void main()

{
	float s, t, p;
	int n;
	clrscr();

	printf("Nhap so tien ban dau : ");
	scanf("%f", &s);
	printf("Nhap so tien can co : ");
	scanf("%f", &t);
	printf("Nhap lai suat %% nam : ");
	scanf("%f", &p);

	for (p = 0.01 *p, n = 0; s < t; s += s *p, n++);
	printf("So nam can gui tiet kiem = %d\n", n);
	printf("Sau %d nam gui tiet kiem, so tien co la : %4.2f", n, s);

	getch();
}
	scanf("%f%f%f", &a, &b, &c);

	if (a + b > c && a + c > b && b + c > a)
	{
		printf("La ba canh mot tam giac ");
		deu = (a == b) && (b == c);
		vuong = (a *a + b *b == c *c) || (a *a + c *c == b *b) || (b *b + c *c == a *a);
		can = (a == b) || (a == c) || (b == c);

		if (deu) printf(" deu\n");
		else if (vuong && can) printf(" vuong can\n");
		else if (vuong) printf(" vuong\n");
		else if (can) printf(" can\n");
		else printf(" thuong\n");
		p = (a + b + c) / 2;
		printf("Chu vi = %4.2f, Dien tich = %4.2f", 2 *p, sqrt(p *(p - a) *(p - b) *(p - c)));
	}
	else printf("Khong phai la ba canh mot tam giac\n");
	getch();
}
