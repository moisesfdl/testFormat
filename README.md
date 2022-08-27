# testFormat


#include <iostream>
#include <tchar.h>
#include <string>

using namespace std;
int main(int argc, char** argv)
{
	_tsetlocale;
	  int NumeroInterio{12};float NumeroReal{34.56};
	  char Caractere{'c'};int string;int printf;
	  	cout<<"Texto da String "<<string<<"\n";
	  	cout<<"Valor Printf = "<<'%d'<<printf<<"\n"
		  <<"Valor Numero Inteiro "<<NumeroInterio<<"\n";
		  cout<<"Valor Numero Real "<<'%f'<< NumeroReal;
	return 0;
}
