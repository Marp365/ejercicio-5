#include <iostream>
using namespace std;

int main() {
    int arreglo1[10], arreglo2[10], iguales = 0;

    cout << "Llenar el primer arreglo:" << endl;
    for (int i = 0; i < 10; i++) {
        cin >> arreglo1[i];
    }

    cout << "Llenar el segundo arreglo:" << endl;
    for (int i = 0; i < 10; i++) {
        cin >> arreglo2[i];
    }

    for (int i = 0; i < 10; i++) {
        if (arreglo1[i] == arreglo2[i]) {
            iguales++;
        }
    }

    cout << "Cantidad de elementos iguales en la misma posición: " << iguales << endl;

    return 0;
}
