# hola-mundo
este repositorio es para praticar el flujo de github en implementa software de sistemas informaticos
soy diego perez regalado, tengo 16 años, me gusta jugar futbol y jugar COD mobile 
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
