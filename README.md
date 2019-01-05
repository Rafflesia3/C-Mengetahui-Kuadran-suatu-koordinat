# C-Mengetahui-Kuadran-suatu-koordinat

    #include <iostream>
    #include <stdio.h>
    #include <conio.h>

    using namespace std;

    int main()
    {
    int x,y;

    cout << "\t\t Pelita Bangsa \n\n" << endl;
    cout << "=========================================\n" << endl;
    cout << "Nama    : Rafi Alwan Setyawan \nNIM     : 311810325 \nKelas   : TI.18.D7 \n" << endl;
    cout << "=========================================\n" << endl;

    cout<< "\t     Fungsi Mengetahui Kuadran Dari Input Koordinat X dan Y\n" << endl;


    cout<<"Masukan nilai x : ";cin>>x;
    cout<<"Masukan nilai y : ";cin>>y;

    if(x>0&&y>0)
        printf("KUADRAN I");
    if(x>0&&y<0)
        printf("KUADRAN II");
    if(x<0&&y<0)
        printf("KUADRAN III");
    if(x<0&&y>0)
        printf("KUADRAN IV");
    if(x==0&&y==0)
        printf("TITIK PUSAT");
    getch();
    }
    
Hasil
![img](https://github.com/Rafflesia3/C-Mengetahui-Kuadran-suatu-koordinat/blob/master/C++%20Mengetahui%20kuadran%20suatu%20koordinat.png?raw=true)
