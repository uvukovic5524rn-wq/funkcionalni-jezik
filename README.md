# funkcionalni-jezik
# struktura jezika

Program je niz definicija funkcija. Funkcija može da ima više pravila, npr. `faktorijal(0) = 1` i `faktorijal(n) = n * faktorijal(n - 1)`.
Pravila se proveravaju redom, odozgo nadole, i koristi se prvo čiji se obrazac poklapa sa argumentima. To je taj pattern matching.
Obrazac može biti konkretan broj (`0`, `1`) ili ime promenljive (`n`).
Brojevi: `3` je ceo broj, a `3.0` realan.
Operatori: `+ - * / %`. Deljenje je celobrojno ako su oba broja cela, a realno ako je bar jedan realan. Zagrade imaju funkciju kao i inače.
Logičkih vrednosti još nema, pa 1 znači tačno, a 0 netačno.
Komentari počinju sa `//` i traju do kraja reda.
Svaki program je jedan fajl i ne uvozi ništa iz drugih fajlova.

## primeri
Primeri programa se nalaze u folderu `examples`.