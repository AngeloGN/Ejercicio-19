#include <iostream>
#include <cmath>
using namespace std;

int main() {
	float x1, y1, x2, y2, Distancia;

	cout << "Ingrese las Coordenadas del Primer Punto (x1, y1): ";
	cin >> x1 >> y1;
	cout << "Ingrese las Coordenadas del Segundo Punto (x2, y2): ";
	cin >> x2 >> y2;

	x1 = abs(x1);
	y1 = abs(x1);
	x2 = abs(x1);
	y2 = abs(x1);

	Distancia = sqrt(pow(x2 - x1, 2) + pow(y2 - y1, 2));

	cout << "La Distancia entre los dos Puntos es: " << Distancia << endl;

	return 0;
}
