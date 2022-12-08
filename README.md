#include <iostream>
#include <stdio.h>

using namespace std;

int main(){
	float uts;
	int nilai;
	string nilaihuruf;
	
	printf ("Masukkan Nilai Akhir anda : ");
	scanf ("%f", &uts);
	
	nilai = uts;
	
	switch (nilai){
		case 76 ... 100: nilaihuruf="A";
		break;
		case 66 ... 75: nilaihuruf="B";
		break;
		case 51 ... 65: nilaihuruf="C";
		break;
		case 0 ... 50: nilaihuruf="D";
		break;
		
		default :printf ("salah, nilai diluar jangkauan. \n");
	}
	printf("Nilai Akhir : %i", nilai);
	
	cout<<"\nNilai Anda : "<<nilaihuruf<<endl;
	
	return 0;
	
}
