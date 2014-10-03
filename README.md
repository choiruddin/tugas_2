#include <stdio.h>
#include <conio.h>
#include <stdlib.h>
main()

{
	char back;
   float T, K, X, B ;
   int a, b, pilihan ;

   printf("===== tugas dua [PIPOLONDO  ==> x,/,+,-] oleh choiruddin D3 M. Informatika=====\n\n");

   do{
   printf("\nMENU PROGRAM == \n\n");
   printf("1. PENJUMLAHAN \n");
   printf("2. PENGURANGAN \n");
   printf("3. PERKALIAN \n");
   printf("4. PEMBAGIAN \n\n");
   printf("Silahkan Pilih Salah Satu Pilihan : ");
   scanf("%d",&pilihan);

	switch (pilihan)
   {

   	case 1 :
      	printf("Masukkan Bilangan 1 : "); scanf("%d",&a);
         printf("Masukkan Bilangan 2 : "); scanf("%d",&b);
         T=a+b;
         printf("hasil penjumlahan adalah == %2.2f \n",T);
         break ;

      case 2 :
      	printf("Masukkan Bilangan 1 : "); scanf("%d",&a);
         printf("Masukkan Bilangan 2 : "); scanf("%d",&b);
         K=a-b;
         printf("hasil pengurangan  == %2.2f \n",K);
         break;

      case 3 :
      	printf("Masukkan Bilangan 1 : "); scanf("%d",&a);
         printf("Masukkan Bilangan 2 : "); scanf("%d",&b);
         X=a*b;
         printf("Hasil Dari Perkalian Adalah == %2.2f \n",X);
         break;

      case 4 :
      	printf("Masukkan Bilangan 1 : "); scanf("%d",&a);
         printf("Masukkan Bilangan 2 : "); scanf("%d",&b);
         B=a/b;
         printf("Hasil Dari Pembagian Bilangan Tersebut Adalah ===== %2.2f \n",B);
         break;

         default : printf("\n wrong / ERROR / masukan pilihan yang benar  \n");
 } printf("\n\nback to menu atau keluar ????? \nketik '0' untuk Kembali dan 'g' Keluar : "); scanf("%s",&back);
} while (back=='0' || back=='0');
}
