Systemy
=======
                                                            BASH

Zad1.Napisz skrypt pobierający z wiersza poleceń 2 argumenty będące bokami prostokąta i obliczający jego pole. 
#!/bin/bash
funkcja_z_parametrami()
{
echo -n "Podaj dlugosc pierwszego boku: "
read liczba1
echo -n "Podaj dlugosc drugiego boku: "
read liczba2
echo
pole=$[liczba1*liczba2]
echo "Pole prostokata wynosi: $pole" 
}
funkcja_z_parametrami "2" "4"


Zad2
#!/bin/bash

funkcja_z_parametrami()
{
if [ $1 -gt 0 ]
then echo "funkcja f(x) wynosi 1"
elif [ $1 -eq 0 ]
then echo "funkcja f(x) wynosi 0"
else echo "funkcja f(x) wynosi -1"
fi
}
funkcja_z_parametrami "0"

