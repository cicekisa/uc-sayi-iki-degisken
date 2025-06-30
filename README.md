//Klavyeden girilen üç farklı tam sayının toplamını sadece 2 değişken kullanarak gerçekleştiren 
//programı yazınız. (Değişkenler: int toplam, sayi; şeklinde 2 tane olmalı, Başka değişken 
//kullanılmayacaktır.)
# uc-sayi-iki-degisken

#include <stdio.h>

int main(){
int sayi,toplam=0;
printf("1.sayiyi giriniz: ");;
scanf("%d",&sayi);
toplam += sayi;

printf("2.sayiyi giriniz: ");;
scanf("%d",&sayi);
toplam += sayi;

printf("3.sayiyi giriniz: ");;
scanf("%d",&sayi);
toplam += sayi;

printf("girilen sayilarin toplami: %d",toplam);


return 0;
}
