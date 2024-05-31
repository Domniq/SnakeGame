Prosta gra konsolowa zaimplementowana w jêzyku C#. Jest to klasyczna gra Snake, w której gracz kontroluje wê¿a poruszaj¹cego siê po planszy. Celem gry jest zdobywanie punktów przez zjadanie owoców, jednoczeœnie unikaj¹c zderzenia z œcianami lub z w³asnym cia³em.

### Sposób uruchamiania

Upewnij siê, ¿e masz zainstalowane œrodowisko .NET na swoim komputerze.
Pobierz lub sklonuj repozytorium z kodem Ÿród³owym gry.
Otwórz projekt w œrodowisku programistycznym, takim jak Visual Studio lub Visual Studio Code.
Skompiluj projekt i uruchom plik wykonywalny.
Gra uruchomi siê w oknie konsoli.

### Sterowanie

Strza³ki kierunkowe: Poruszanie wê¿em (góra, dó³, lewo, prawo).

### Zasady gry

Gra rozpoczyna siê po naciœniêciu klawisza Enter.
W¹¿ porusza siê po planszy w wybranym kierunku (za pomoc¹ strza³ek kierunkowych).
Celem jest zjadanie owoców (reprezentowanych przez symbol *), które pojawiaj¹ siê losowo na planszy.
Za ka¿dy zjedzony owoc w¹¿ wyd³u¿a siê, a gracz otrzymuje punkt.
Gra koñczy siê, gdy w¹¿ zderzy siê ze œcian¹ lub z w³asnym cia³em.
Po zakoñczeniu gry wyœwietlany jest ostatni wynik gracza.

### Metody i klasy pomocnicze

Pixel: Klasa reprezentuj¹ca pojedynczy piksel na planszy, zawieraj¹ca informacje o pozycji, znaku i kolorze.
Direction: Enum reprezentuj¹cy cztery mo¿liwe kierunki ruchu wê¿a.
GenerateFood(): Metoda odpowiedzialna za losowe generowanie nowego owocu na planszy.
DrawBoard(): Metoda odpowiedzialna za rysowanie planszy, wê¿a i owocu.
ShowScore(): Metoda wyœwietlaj¹ca aktualny wynik gracza.
WaitForKey(): Metoda obs³uguj¹ca wejœcie od gracza (ruchy strza³kami).
MoveSnake(): Metoda aktualizuj¹ca pozycjê wê¿a na podstawie wybranego kierunku.
CheckCollision(): Metoda sprawdzaj¹ca, czy w¹¿ zderzy³ siê ze œcian¹ lub z w³asnym cia³em.
CheckFoodCollision(): Metoda sprawdzaj¹ca, czy w¹¿ zjad³ owoc, oraz wyd³u¿aj¹ca wê¿a i generuj¹ca nowy owoc.