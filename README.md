#include <iostream>
using namespace std;
struct mahasiswa
{
    char nim [15];
    char nama [50];
    char jurusan [40];
    int angkatan;
};
 
int main()
{
    mahasiswa mhs;
     
    cout<<"----- Data Mahasiswa-----"<<endl;
    cout<<"========================="<<endl;
     
    cout<<"NIM : ";cin.getline(mhs.nim,15);
    cout<<"Nama : ";cin.getline(mhs.nama,50);
    cout<<"Jurusan : ";cin.getline(mhs.jurusan,40);
    cout<<"Angkatan : ";cin>>mhs.angkatan;
     
    cout<<"Output Hasil"<<endl;
    cout<<"========================="<<endl;
    cout<<"NIM : "<< mhs.nim<<endl;
    cout<<"Nama : "<< mhs.nama<<endl;
    cout<<"Jurusan : "<< mhs.jurusan<<endl;
    cout<<"Angkatan : "<< mhs.angkatan<<endl;
     
    return 0;
}
