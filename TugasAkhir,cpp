#include <iostream>
using namespace std;
	
int main(){
	
	char nama[30],pembeli[30];
	int harga, jumlah, total, jumtotal, jumbayar, kembalian, potongan;
	string input, kode;
	
	awal:
	cout<< "      THE SOE'JA SALON    "<<endl;
	cout<<"====================================="<<endl;
	cout<<"Nama Pembeli :";
	cin>> pembeli;
	cout<<"Pilihan Treatment"<<endl;
	cout<<"001 - Potong Rambut dan Cuci Rambut - Rp.150.000"<<endl;
	cout<<"002 - Smoothing - Rp.300.000"<<endl;
	cout<<"003 - Creambath - Rp.50.000"<<endl;
	
	cout << endl;
	cout << endl;
	cout<< "Treatment yang dipilih   :" ;
	cin>>kode;
	cout<< "Jumlah Treatment         :";
	cin>>jumlah;
	
	if (kode == "001"){
		cout << "Potong Rambut dan Cuci Rambut";
		harga = 150000;
	} else if (kode == "002"){
		cout << " Smoothing";
		harga = 300000;
	} else if (kode == "003"){
		cout << " Creambath";
		harga = 50000;
	} else {
		cout <<"Treatment tidak tersedia";
	}
	
	cout << endl;
	cout <<"=================================="<<endl;
	cout <<"Struk Pembayaran"<<endl;
	cout <<"=================================="<<endl;
	cout <<"Nama Pembeli    :"<<pembeli<<endl;
	cout <<"Harga           :"<<harga<<endl;
	cout <<"Jumlah          :"<<jumlah<<endl;
	
	
	total = harga * jumlah;
	
	cout << "Total           :"<<total<<endl;
	
	cout <<endl;
	
	if (total == 150000 || total < 200000){
		potongan = 0.05 * total;
	}else if (total > 200000){
		potongan = 0.10 * total;
	} else {
		potongan = 0;
	}
		
		
		cout <<"Potongan        :"<<potongan<<endl;
		cout << "=================================="<<endl;
		
		jumtotal = total-potongan;
		
		cout << " Total Keseluruhan   :"<<jumtotal<<endl;
		cout << "Uang Bayar   :";
		cin>> jumbayar;
		
		
		kembalian = jumbayar - jumtotal;
		cout << "Uang Kembalian  :"<<kembalian<<endl;
		cout << "=================================="<<endl;
		
		cout << "Mau Input Lagi [Y/N]  :";
		cin >> input;
		
		if (input == "y" || input == "Y"){
			goto awal;
		}else{
			return 0;
		}
		
		
}
