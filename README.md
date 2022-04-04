# Sis457lab01
codigo
#include <iostream>

using namespace std;

int main()
{
    string salir;
    do {
        cout << "Mi nombre es Joaquin Aramayo Valdez, naci en la Ciudad de Camargo, una provincia del departamento de Sucre. Tengo 19 a�os y estoy en tercer semestre de la carrera de ingeniera de sistemas en la universidad San Franciso de Sucre.Me encanta mucho el basquet y los videojuegos, toda mi vida la pase entrenando basquet y jugando los ultimos videojuegos pero sobre todo los shooter(Call of Duty) tengo 2 hermanos y una mascota en mi pueblo Camargo. Sobre mi educacion, toda mi formacion la tuve alla en Camargo, me considero una persona muy responsable y dedicada en lo que hago. Lamentablemente tuve un accidente mientras jugaba un partido de basquet golpiandome muy fuerte la cabeza. Gracias Dios me encuentro muy bien fisicamente pero perdi la memoria y varios de mis recuerdos y mi vida pasada anterior al accidente, pero ahi vamos mejorando cada dia y sin rendirse luchando por mis sue�os. En fin ese soy yo un chico dedicado que le encanta el deporte y los videojuegos" << endl << endl;

        cout << "¿DESEA SALIR? SI/NO: ";
        cin >> salir;

    } while (salir != "SI" && salir != "si" && salir != "Si");


    system("pause");
    return 0;
}
