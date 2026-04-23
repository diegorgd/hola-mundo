#include <iostream>
using namespace std;

int main()
{
    int op;
    float pesos, resultado, tipoCambio;

    cout << "Escribe el numero de la opcion que necesitas:\n";
    cout << "1. Peso a yenes\n";
    cout << "2. Peso a dolar\n";
    cout << "3. Peso a quetzal\n";
    cin >> op;

    cout << "Ingresa la cantidad en pesos: ";
    cin >> pesos;

    cout << "Ingresa el tipo de cambio: ";
    cin >> tipoCambio;

    if (op == 1) {
        resultado = pesos / tipoCambio;
        cout << "Equivalente en yenes: " << resultado << endl;
    }
    else if (op == 2) {
        resultado = pesos / tipoCambio;
        cout << "Equivalente en dolares: " << resultado << endl;
    }
    else if (op == 3) {
        resultado = pesos / tipoCambio;
        cout << "Equivalente en quetzal: " << resultado << endl;
    }
    else {
        cout << "Opcion no valida." << endl;
    }

    return 0;
}
