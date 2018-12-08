# praktikum7

**Alur Argoritma**
 1.Mulai program tersebut
2.Input interger fungsi (int, int) 
3.Input interger a dan b dan deskripsikan a=0, dan b=1. 
4.Jika nilai suku satu (b) adalah =1 dan jika nilai suku dua (a) adalah =0. 
2.Input interger fungsi (int, int)
3.Input interger a dan b dan deskripsikan a=0, dan b=1.
4.Jika nilai suku satu (b) adalah =1 dan jika nilai suku dua (a) adalah =0.
5.Maka cetak rumus fungsi iteratif menggunakan for intruksikan fungsi fibonacci di awali dengan 2 dan di akhiri dengan indexs suku.
6.Deskripsikan variable untuk mencetak fuungsi selanjutnya. 
6.Deskripsikan variable untuk mencetak fuungsi selanjutnya.
7.Cetak suku fibonacci menggunakan pemanggilan fungsi itertif.
 **Pseudecode**
@@ -72,12 +72,12 @@ CMD1
 **Alur Argoritma**
 1.Mulai program tersebut 
2.Input interger fungsi (int a, int b). 
3.Jika nilai interger (b==0) return 0. 
4.Jika nilai (b>0) intruksikan return a + type data (a, b - 1). 
5.Sebaliknya return (-a) + type Data (a, b+1) 
6.Masukkan variabel a,b untuk menginput nilai awal dan dibagi degan nilai selanjutnya. 
1.Mulai program tersebut.
2.Input interger fungsi (int a, int b).
3.Jika nilai interger (b==0) return 0.
4.Jika nilai (b>0) intruksikan return a + type data (a, b - 1).
5.Sebaliknya return (-a) + type Data (a, b+1).
6.Masukkan variabel a,b untuk menginput nilai awal dan dibagi degan nilai selanjutnya.
7.Cetak nilai perkalian dengan memanggil fungsi rekursif menggunakan type datanya.
 **Pseudecode**
@@ -127,10 +127,10 @@ Hasil2
 **Alur Argoritma**
 1.Mulai program tersebut 
2.Input menggunakan intruksi void dan menggunakan pointer untuk menetapakan void typedata (char s) 
3.Jika nilai s!=0--> menggunakan Pointer() maka masukkan intruksi membalik (&s[1]) 
4.Masukkan char untuk intruksi kata yang ingin kita ubah dan intruksi balik 
1.Mulai program tersebut.
2.Input menggunakan intruksi void dan menggunakan pointer untuk menetapakan void typedata (char s).
3.Jika nilai s!=0--> menggunakan Pointer() maka masukkan intruksi membalik (&s[1]).
4.Masukkan char untuk intruksi kata yang ingin kita ubah dan intruksi balik.
5.Cetak pembalikkan kata dengan memanggil fungsi rekursif menggunakan type datanya.
 **Pseudecoede**
@@ -139,12 +139,12 @@ Hasil2
#include
#include
void balik(char *k){
if(*k!=”){
if(*k!=”){
balik(&k[1]);
cout<
}
}main(){
char *kata=”....”;--> //untuk masukan kata
char *kata=”....”;--> //untuk masukan kata
balik(kata);
cout<
return 0;
@@ -173,4 +173,4 @@ int main()
```