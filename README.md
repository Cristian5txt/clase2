#include <iostream>

using namespace std;

int main()
{
    int suma;
    int int_variable;
    float float_variable;
    cout << "INGRESE EL VALOR VARIABLE ENTERO " << endl;
    cin>> int_variable;
    cout<< "INGRESE EL VALOR FLOTANTE "<<endl;
    cin >> float_variable;

    suma = int_variable + float_variable;

    cout<< "SU VALOR ES "<<suma<<endl;
    return 0;
}
