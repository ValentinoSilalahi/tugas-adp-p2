#include <iostream>
#include <cmath>

using namespace std;

int main()
{
    cout << " Nama : Valentino Silalahi "<<endl;
    cout << " Nim  : 2310431015 "<<endl;
    //Program Limas Segi Empat Beraturan

    float v,l,h,s,t;

    cout << " Masukkan panjang sisi alas = "; cin >> s;
    cout << " Masukkan panjang tinggi limas = "; cin >> t;

    h=sqrt((t*t)+((s/2)*(s/2)));

    l=(s*s)+(4*s*h*1/2);
    cout << " Luas permukaan limas segi empat beraturan = ";
    cout <<l<<endl;

    v=s*s*t*1/3;
    cout << " Volume Limas Segi Empat Beraturan = ";
    cout <<v<<endl;
}
