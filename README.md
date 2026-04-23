
#include <iostream>
using namespace std;
int main()
{
    float pesos, yenes, tipoCambio;
    
    std::cout<<"ingresa la cantidad de pesos: ";
    std::cin >> pesos;
    std::cout <<"ingresa el tipo de Cambio (pesos por yenes): ";
    std::cin >> tipoCambio;
    
    yenes = pesos / tipoCambio;
    
    std::cout <<"equivalente en yenes: "  << yenes << endl;
    
    return 0;
}
