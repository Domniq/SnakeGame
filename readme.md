Prosta gra konsolowa zaimplementowana w j�zyku C#. Jest to klasyczna gra Snake, w kt�rej gracz kontroluje w�a poruszaj�cego si� po planszy. Celem gry jest zdobywanie punkt�w przez zjadanie owoc�w, jednocze�nie unikaj�c zderzenia z �cianami lub z w�asnym cia�em.

### Spos�b uruchamiania

Upewnij si�, �e masz zainstalowane �rodowisko .NET na swoim komputerze.
Pobierz lub sklonuj repozytorium z kodem �r�d�owym gry.
Otw�rz projekt w �rodowisku programistycznym, takim jak Visual Studio lub Visual Studio Code.
Skompiluj projekt i uruchom plik wykonywalny.
Gra uruchomi si� w oknie konsoli.

### Sterowanie

Strza�ki kierunkowe: Poruszanie w�em (g�ra, d�, lewo, prawo).

### Zasady gry

Gra rozpoczyna si� po naci�ni�ciu klawisza Enter.
W�� porusza si� po planszy w wybranym kierunku (za pomoc� strza�ek kierunkowych).
Celem jest zjadanie owoc�w (reprezentowanych przez symbol *), kt�re pojawiaj� si� losowo na planszy.
Za ka�dy zjedzony owoc w�� wyd�u�a si�, a gracz otrzymuje punkt.
Gra ko�czy si�, gdy w�� zderzy si� ze �cian� lub z w�asnym cia�em.
Po zako�czeniu gry wy�wietlany jest ostatni wynik gracza.

### Metody i klasy pomocnicze

Pixel: Klasa reprezentuj�ca pojedynczy piksel na planszy, zawieraj�ca informacje o pozycji, znaku i kolorze.
Direction: Enum reprezentuj�cy cztery mo�liwe kierunki ruchu w�a.
GenerateFood(): Metoda odpowiedzialna za losowe generowanie nowego owocu na planszy.
DrawBoard(): Metoda odpowiedzialna za rysowanie planszy, w�a i owocu.
ShowScore(): Metoda wy�wietlaj�ca aktualny wynik gracza.
WaitForKey(): Metoda obs�uguj�ca wej�cie od gracza (ruchy strza�kami).
MoveSnake(): Metoda aktualizuj�ca pozycj� w�a na podstawie wybranego kierunku.
CheckCollision(): Metoda sprawdzaj�ca, czy w�� zderzy� si� ze �cian� lub z w�asnym cia�em.
CheckFoodCollision(): Metoda sprawdzaj�ca, czy w�� zjad� owoc, oraz wyd�u�aj�ca w�a i generuj�ca nowy owoc.