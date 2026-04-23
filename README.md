
#include <iostream>
using namespace std;
int main()
{
float pesos, dolares,
tipocambio;
cout<<"ingresa la cantidad en pesos: ";
cin>>pesos;
cout<<"ingresa el tipo de cambio (pesos por dolar): ";
cin>>tipocambio;
dolares = pesos / tipocambio;
cout<<"equivalente en dolares: "<<dolares<<endl;

    return 0;
}
