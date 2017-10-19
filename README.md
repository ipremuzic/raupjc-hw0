
# Pitanje 1:
Primjećujem još dvije dodatne datoteke, ClassLibrary1.dll i ClassLibrary1.pdb datoteku.
Ako maknem .dll datoteku aplikacija se ne pokreće, dolazi do FileNotFoundException iznimke jer CLR ne može pronaći ClassLibrary1 asemblij koji mu je potreban za pokretanje.
Poslao bih izvršnu ConsoleApplication.exe datoteku i ClassLibrary1.dll datoteku.

# Pitanje 2:
Konzolna aplikacija je koristila novu verziju class library asemblija, tj. prikazala je novi string. Koristila je novu verziju class library asemblija zato što se prilikom pokretanja aplikacije automatsku pokrene i build asemblija.

# Pitanje 3:
Aplikacija je normalno pokrenuta, prilikom builda je dohvaćen NuGet paket. U packages direktoriju se ponovno nalazi NodeTime direktorij.
