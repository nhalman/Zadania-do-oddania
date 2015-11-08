/*Zadanie #5
Napisz program, który wczyta dwie duże litery z wejścia, a następnie wypisze wszystkie litery
pomiędzy tymi dwiema.
Wejście
Na wejściu w pierwszej linii podawana jest ilość testów. Następnie w t-następnych liniach podawane
są dwie duże litery odzielone spacją.
Wyjście
Na wyjściu mają się pojawić dwie podane litery oraz ciąg liter pomiędzy tymi dwiema oddzielone
spacjami .*/

#include "stdafx.h"
#include <iostream>
#include <cstdlib>
//#define _CRT_SECURE_NO_WARNINGS
#define _CRT_SECURE_NO_DEPRECATE
using namespace std;

int main()
{
	int t; //ilość testów
	char p; //początkowa litera
	int pz; //zmienna do zrzucena p na inty
	char k; //końcowa litera
	int kz; //zmienna do zrzucena k na inty
	int litery; //ilosc liter do wypisania

	cin >> t;

	for (int j = 0; j < t; j++){
		cin >> p;
		cin >> k;

		pz = (int)p; //zrzutowanie początkowej litery na inta, żeby móc skorzystać z ASCII
		kz = (int)k; //zrzutowanie końcowej litery na inta, żeby móc skorzystać z ASCII
		litery = kz - pz; //ilość liter do wypisania

		for (int i = 0; i < litery; i++){
			printf("%c ", pz);
			pz++;
		}

		printf("%c\n", k);

	}
	
	system("PAUSE");
	return 0;
}
