#include <iostream>
#include <iomanip>
#include <windows.h>
#include <conio.h>
#include <stdio.h>

using namespace std;
struct data{
    char nama[20],jur[20],jk[20];
    int nomor,nil,rata;
};
main(){
    int nim=-1,i,j;
    int pilih, a,b,c,rata;
    data siswa[20];
    char get[20];
    menuutama:
        system("cls");
    nim++;
            cout<<"Masukkan NIM    :";cin>>siswa[nim].nomor;cin.getline(get,20);
            cout<<"Nama Lengkap    :";cin.getline(siswa[nim].nama,20);
            cout<<"Jenis Kelamin   :";cin.getline(siswa[nim].jk,20);
            cout<<"Jurusan         :";cin>>siswa[nim].jur;cin.getline(get,20);
            cout<<"Masukan nilai Harian Mahasiswa\n"<<endl;
            cout<<"Nilai Harian Pertama :";cin>>a;
            cout<<"Nilai Harian Kedua   :";cin>>b;
            cout<<"Nilai Harian ketiga  :";cin>>c;
            rata=(a+b+c)/3;
        cout<<"Apakah anda ingin menambah data atau menampilkan data(1=ya/2=tampil):";cin>>pilih;
        cout<<endl; 
        
        if(pilih==1){
            goto menuutama;
        }
        else if(pilih==2){
            goto tampilan;
        }
        tampilan:
            system("cls");
            cout.flags(ios::left);
        cout<<"=============================================================================\n";
                for(j=0;j<=nim;j++){
            
                    cout<<setiosflags(ios::left)<<setw(14)<<siswa[j].nomor;
                    cout<<setiosflags(ios::left)<<setw(14)<<siswa[j].nama;
                    cout<<setiosflags(ios::left)<<setw(14)<<siswa[j].jur;
                    cout<<setiosflags(ios::left)<<setw(14)<<siswa[j].jk;
                    cout<<setiosflags(ios::left)<<setw(14)<<rata;
                    cout<<endl;
                }
        
        cout<<endl;
        cout<<"Apakah anda ingin ke menu utama?(1=ya/2=tidak):";cin>>pilih;
        cout<<endl;
        if(pilih==1){
            goto menuutama;
        }
        else if(pilih==2){
            goto keluar;
        }
        keluar:
            system("cls");
            cout<<"Terima kasih";
            return 0;
    
    getch();
    return 0;
        
}
