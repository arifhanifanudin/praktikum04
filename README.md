# Latihan01

" Membuat Program Penjualan Barang "

Deklarasi :

int kode, N, jumlah, banyak
 
Deskripsi :
	
1. input N sebagai banyak barang yang dibeli.
2  Kode sebagai kode barang
3. jumlah sebagai pengulang banyaknya pembelian
4. banyak sebagai nilai inputan 
5. total sebagai penentu harga sesuai banyaknya barang yang dipesan
6. diskon sebagai potongan harga
7. akhir sebagai penentu pembayaran setelah dikurangi diskon
8. bayar sebagai penentu banyaknya pembayaran
9. harga sebagai penentu harga barang
10. duit sebagai inputan
11. kembalian sebagai penentu uang kembalian.
12. menentukan perulangan untuk banyaknya pembelian.
13. menentukan perbandingan untuk menentukan diskon dalam setiap pembelian.

# Program C++

#include <iostream>
  
using namespace std;

int main()

{
    char pembelian;
    
int kode, N, jumlah, banyak;

long int total,diskon,akhir, bayar, harga,duit,kembalian;

atas:

cout<<" zzzzzzzzzzzzzzzzzzzzzz ARIF KOMPUTINDO zzzzzzzzzzzzzzzzzzzzzzzzz\n";

cout<<"\n";

cout<<"                HARGA PAS DIKANTONG & KUALITAS TERBAIK\n";

cout<<"\n";

cout<<"            <<<<<<<<<<DAFTAR BARANG>>>>>>>>>>\n";
  
cout<<" 1.  Laptop Asus\n";

cout<<" 2.  Laptop Acer\n";

cout<<" 3.  Laptop Lenovo\n";

cout<<" 4.  Laptop Thosiba\n";

cout<<" 5.  Hardisk 1 tera\n";

cout<<" 6.  Stick USB\n";

cout<<" 7.  Modem 4G\n";

cout<<" 8.  RAM 4gb DDR4\n";

cout<<" 9.  Mouse\n";

cout<<" 10. Keyboard\n";

cout<<" ===================Selamat Berbelanja===================\n";

cout<<"\n";

cout<<"Jumlah Barang Yang Dipesan = ";

cin>>banyak;

jumlah=1;

bayar=0;

for(jumlah=1;jumlah<=banyak;jumlah++)

{ulang:

 cout<<" \n\nMasukan Kode Barang = ";
 
cin>>kode;

cout<<"\n";

    if (kode==1)
    
{

    cout<<" Nama Barang     = Laptop Asus\n";
    
    cout<<" Harga           = Rp. 6500000,-\n";
    
    cout<<" Jumlah Barang   = ";
    
    cin>>N;
    
    harga=6500000;
    
    total=harga*N;
    
    cout<<" Total Harga     = Rp"<<total;
    
    cout<<"\n";
    
}

else

    if (kode==2)
    
{

    cout<<" Nama Barang     = Laptop Acer\n";
    
    cout<<" Harga           = Rp. 5000000,-\n";
    
    cout<<" Jumlah Barang   = ";
    
    cin>>N;
    
    harga=5000000;
    
    total=harga*N;
    
    cout<<" Total Harga     = Rp"<<total;
    
    cout<<"\n";
    
}

else

    if (kode==3)
    
{

    cout<<" Nama Barang     = Laptop Lenovo\n";
    
    cout<<" Harga           = Rp. 3500000,-\n";
    
    cout<<" Jumlah Barang   = ";
    
    cin>>N;
    
    harga=3500000;
    
    total=harga*N;
    
    cout<<" Total Harga     = Rp"<<total;
    
    cout<<"\n";
    
}

else

    if (kode==4)
    
{

    cout<<" Nama Barang      = Leptop Thosiba\n";
    
    cout<<" Harga            = Rp. 4300000,-\n";
    
    cout<<" Jumlah Barang    = ";
    
    cin>>N;
    
    harga=4300000;
    
    total=harga*N;
    
    cout<<" Total Harga      = Rp"<<total;
    
    cout<<"\n";
    
}

else

    if (kode==5)
{

    cout<<" Nama Barang     = Hardisk 1 tera\n";
    
    cout<<" Harga           = Rp. 750000,-\n";
    
    cout<<" Jumlah Barang   = ";
    
    cin>>N;
    
    harga=750000;
    
    total=harga*N;
    
    cout<<" Total Harga     = Rp"<<total;
    
    cout<<"\n";
    
}

else

    if (kode==6)
    
{

    cout<<" Nama Barang     = Stik USB\n";
    
    cout<<" Harga           = Rp. 60000,-\n";
    
    cout<<" Jumlah Barang   = ";
    
    cin>>N;
    
    harga=60000;
    
    total=harga*N;
    
    cout<<" Total Harga     = Rp"<<total;
    
    cout<<"\n";
    
}

else

    if (kode==7)
{

    cout<<" Nama Barang     = Modem 4G\n";
    
    cout<<" Harga           = Rp. 450000,-\n";
    
    cout<<" Jumlah Barang    = ";
    
    cin>>N;
    
    harga=450000;
    
    total=harga*N;
    
    cout<<" Total Harga     = Rp"<<total;
    
    cout<<"\n";
    
}

else

    if (kode==8)
    
{

    cout<<" Nama Barang     = RAM 4gb DDR4\n";
    cout<<" Harga           = Rp. 320000,-\n";
    cout<<" Jumlah Barang   = ";
    cin>>N;
    harga=320000;
    total=harga*N;
    cout<<" Total Harga     = Rp"<<total;
    cout<<"\n";
    
}

else

    if (kode==9)
    
{

    cout<<" Nama Barang     = Mouse\n";
    
    cout<<" Harga           = Rp. 20000\n";
    
    cout<<" Jumlah Barang   = ";
    
    cin>>N;
    
    harga=25000;
    
    total=harga*N;
    
    cout<<" Total Harga     = Rp"<<total;
    
    cout<<"\n";
    
}

else

    if (kode==10)
    
{

    cout<<" Nama Barang     = keyboard\n";
    
    cout<<" Harga           = Rp. 25000\n";
    
    cout<<" Jumlah Barang   = ";
    
    cin>>N;
    
    harga=15000;
    
    total=harga*N;
    
    cout<<" Total Harga     = Rp"<<total;
    
    cout<<"\n";
    
}

else

{

    cout<<"-Invalid Number-\a";
    
goto ulang;

}

bayar=bayar+total;

}

    cout<<"\nTotal Bayar\t\t        = Rp"<<bayar<<",-";
    
    cout<<"\n\n\Masukan Pembayaran  = Rp";cin>>duit;
    
if((bayar>1000000)){

diskon = bayar*0.10;

cout<<"\nKamu Dapat Diskon 10%\t";

}else

    if((bayar>=501000)&& (bayar<=1000000)){
    
diskon = bayar*0.05;

cout<<"\nKamu Dapat Diskon 5%\t";

}else

    if((bayar<501000)){
    
diskon = 0;

cout<<"\nKamu Dapat Diskon 0%\t";

}

else {

diskon = 0;

}

akhir       =bayar-diskon;

kembalian   =duit-akhir;

cout<<"\nKamu Dapat Diskon\t  = Rp"<<diskon<<",-";

cout<<"\nCash Back\t          = Rp"<<kembalian<<",-";

cout<<"\n\n\t\t\t(((( ===== TERIMA KASIH ===== ))))";

cout<<"\n\n\n\n\nPembelian Baru [y/t] ";cin>>pembelian;

if (pembelian=='y'||pembelian=='Y')

goto atas;

else

cout<<"\n\n\t\t\tProgram Logging Off....";

return 0;

}

# Foto Hasil
![img](https://raw.githubusercontent.com/arifhanifanudin/praktikum04/master/hasil01.PNG)
