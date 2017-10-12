# raupjc-hw0

# Pitanje 1:
Primjeæujem još dvije dodatne datoteke, ClassLibrary1.dll i ClassLibrary1.pdb datoteku.
Ako maknem .dll datoteku aplikacija se ne pokreæe, dolazi do FileNotFoundException iznimke jer CLR ne može pronaæi ClassLibrary1 asemblij koji mu je potreban za pokretanje.
Poslao bih izvršnu ConsoleApplication.exe datoteku i ClassLibrary1.dll datoteku.


# Pitanje 2:
Konzolna aplikacija je koristila staru verziju class library asemblija, tj. prikazala je stari string. Zato što nije obavljen build projekta,
tj. asemblij nije ažuriran.

# Pitanje 3:
Aplikacija je normalno pokrenuta, prilikom builda je dohvaæen NuGet paket. U packages direktoriju se ponovno nalazi NodeTime direktorij.