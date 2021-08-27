#include <conio.h>
#include <iostream>
#include <stdio.h>
using namespace std;

int main()
{
system ("color a");
printf(" ______________");
printf("\n| MEMBER LOGIN |\n");
printf("|______________|\n\n\n");
system ("color e");
string user, pass;
cout<<"[•] username : " ; cin>>user;
cout<<"[•] password : " ; cin>>pass;
if (user == "w" && pass == "w"){
system ("color a"); cout<<"berhasil masuk!\n\n"<<endl;
}
else {
 system ("color c"); cout<<"[×] username tidak sesuai\n\n";
}

system ("color e");
cout<<"selamat datang di kelompok teman-teman bulu burung!\n";
printf("ini adalah program yang tidak ada gunanya.\n");
system ("color f");

char enter;
cout<<"\ntekan enter untuk melanjutkan";
enter=getch();

getch();
clrscr();

system ("color b");	printf("============================================================\n");
printf("                     SALAM SATU KONTOL\n");
printf("============================================================\n");

system ("color f");
char apakah = 'y';
int counter = 0;

  cout<<endl<<endl;
  do {
 cout<<"apakah anda mempunyai kontol? (y/t) : ";

 cin>>apakah;
 // increment counter
 counter++;
 if (apakah == 't'){
 cout<<"harus punya!"<<endl;
 }
  } while(apakah == 't');
  
 cout<<endl;
  char kontol;
cout<<"[•] input ukuran kontol anda (5 - 20cm) : "; 
    cin>>kontol;
    if (kontol == '5'){
    	cout<<"kecil amat\n";
}
 else if (kontol == '8'){
 	cout<<"kurang mantab\n";
}
else if (kontol = '20'){
	cout<<"kontol yang bagus!\n"<<endl;
}

cout<<"apakah anda pernah bersetubuh?\n";

   cout<<"[1] tidak pernah\n";
   cout<<"[2] setiap saat\n";
   cout<<"[3] astagfirullah\n\n";
   char pilihan;
  cout<<"pilihan anda : ";
  pilihan=getche();
  cin>>pilihan;
 if (pilihan == '1'){
 cout<<"stay suci ea\n";
 }

 else if (pilihan == '3'){
   cout<<"subhanallah brother ^_^"<<endl;
  }
  else if (pilihan == '2'){
  cout<<"mati aja"<<endl;
  }
else {
cout<<"pilih yang bener goblok";
}
  
  cout<<endl;
  system ("color b"); printf("============================================================");return 0;
}
