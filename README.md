# raupjc-hw0

# Pitanje 1:
Primje�ujem jo� dvije dodatne datoteke, ClassLibrary1.dll i ClassLibrary1.pdb datoteku.
Ako maknem .dll datoteku aplikacija se ne pokre�e, dolazi do FileNotFoundException iznimke jer CLR ne mo�e prona�i ClassLibrary1 asemblij koji mu je potreban za pokretanje.
Poslao bih izvr�nu ConsoleApplication.exe datoteku i ClassLibrary1.dll datoteku.


# Pitanje 2:
Konzolna aplikacija je koristila staru verziju class library asemblija, tj. prikazala je stari string. Zato �to nije obavljen build projekta,
tj. asemblij nije a�uriran.

# Pitanje 3:
Aplikacija je normalno pokrenuta, prilikom builda je dohva�en NuGet paket. U packages direktoriju se ponovno nalazi NodeTime direktorij.