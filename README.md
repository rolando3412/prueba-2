#include<iostream>
using namespace std;

// Para leer variables de texto se utiliza el operador << del objeto cin, que
// lee solo una palabra. Para leer una linea completa (es decir, incluyendo los
// espacios en blanco) se debe utilzar getline (ej, reemplazar cin>>x por
// getline(cin,x)), pero obliga a agregar un cin.ignore() si antes del getline
// se leyó otra variable con >>.

// escriba un programa que calcule y despliege valores para Y cuando Y = X.Z/X-Z 
// su programa debera calcular Y para los valores de X que varian entre 1 y 5 y valores
// de Z que varian entre 2 y 6 la variable x debera controlar el ciclo 
// exterior e debera incrementarse en pasos de 1 y z debera incrementarse en pasos de 2.
// su  algoritmo debera desplegar tambien el mensaje funcion indefinida cuando sea necesario
// NOTA p = y por ser Y operador logico al no poder utilizarse




int main() {
	float p;
	float x;
	float z;
	// escriba un programa que calcule y despliege valores para Y cuando Y = X.Z/X-Z 
	// su programa debera calcular Y para los valores de X que varian entre 1 y 5 y valores
	// de Z que varian entre 2 y 6 la variable x debera controlar el ciclo 
	// exterior e debera incrementarse en pasos de 1 y z debera incrementarse en pasos de 2.
	// su  algoritmo debera desplegar tambien el mensaje funcion indefinida cuando sea necesario
	// NOTA p = y por ser Y operador logico al no poder utilizarse
	cout << " lectura de valores para Y = p " << endl;
	cout << "ingrese los valores de x que sean entre 1 y 5 " << endl;
	cin >> x;
	cout << "ingrese los valores para z que sean entre 2 y 6 " << endl;
	cin >> z;
	if (x<=5) {
		cout << "x entre parametros " << endl;
		cout << x << endl;
	} else {
		cout << "funcion indefinida para y " << endl;
	}
	if (z<=6) {
		cout << "z entre parametros " << endl;
		cout << z << endl;
	} else {
		cout << "funcion indefinida y " << endl;
	}
	cout << "el valor de y es " << endl;
	p = x*z/x-z;
	if (p==x*z/x-z) {
		cout << p << endl;
	} else {
	}
	cout << "el incremento de x en paso de 1  es " << endl;
	for (x=x;x<=6;x++) {
		cout << x << endl;
	}
	cout << "el incremento de z en paso de 2  es " << endl;
	for (z=z;z<=6;z+=2) {
		cout << z << endl;
	}
	return 0;
}

