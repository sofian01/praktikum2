# praktikum2
A. Latihan 1 membuat penentuan bilangan terbesar dari 3 variabel. mendeklarasikan variabel int a,b,c sebagai variabel input menginputkan nilai a,b,c membandingkan nilai a,b,c dengan rumus if berikut kodenya if (A>B){ if (A>C) cout<< "Bilangan Terbesar Adalah :" << A; else cout<< "Bilangan Terbesar Adalah :" << C; }else{ if ( B>C ) cout << "Bilangan Terbesar Adalah:" << B; else cout << "Bilangan Terbesar Adalah:" << C;

ini hasilnya :
![latihan1](https://user-images.githubusercontent.com/44091204/47215624-51904a80-d3cc-11e8-8739-5f7812632a3f.jpg)

B. Latihan2 membuat penentuan terbesar dan terkecil dari 4 variabel. -Mendeklarasikan variabel n,nilai sebagai variabel input -Mendeklarasikan variabel i sebagai pembatas inputan/perulangan -Mendeklarasikan max sebagai nilai terbesar dan min nilai terkecil -Menginputkan nilai n dimana menunjukan banyak angka yang akan di input -menginputkan nilai nilai yang akan di bandingkan. Berikut kode lengkapnya

int i,n,max,min,nilai;

cout<<"===Menentukan Bilangan Terbesar & Terkecil==="<< endl; cout<<"Masukan Banyak Bilangan:"; cin>> n; cout<<"Masukan Nilai ke ="; cin>> nilai;

max=nilai; min=nilai;

for(i=2;i<=n;i++) //dapat dibaca i akan membaca di nilai ke2 dimana i kurang dari samadengan n,i akan menambah 1 angka dan seterusnya. {

cout<<"Masukan Nilai Ke"<<i<<"=";
cin>>nilai;

if (nilai>max) max=nilai;
if (nilai<min) min=nilai;
} cout<<"Nilai Terbesar Adalah:" <<max<<"\nNilai Terkecil Adalah:"<<min;

Ini Hasilnya :
![latihan2](https://user-images.githubusercontent.com/44091204/47215693-8e5c4180-d3cc-11e8-8319-d49d33765eae.jpg)

