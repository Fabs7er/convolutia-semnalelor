# D4-T2 | Convolutia Semnalelor

Acest proiect contine un script in Python dezvoltat pentru generarea a doua semnale discrete cu forma sinusoidala, avand parametrii definiti de utilizator, calcularea convolutiei acestora si vizualizarea grafica a rezultatelor.

## Membrii Echipei (22-E6)
* SCĂRLĂTESCU BIANCA-MARIA
* URETU FABIAN-ŞTEFAN

---

## Functionalitati
1. Generator de Semnale: Permite configurarea axei de timp (durata, numar de puncte de esantionare) si a parametrilor fiecarui semnal (amplitudine, frecventa, faza) direct din consola.
2. Convolutie Matematica: Calculeaza convolutia discreta completa (mode='full') a celor doua semnale folosind biblioteca numpy.
3. Vizualizare si Salvare: Genereaza un grafic organizat cu trei subploturi (Semnal 1, Semnal 2 si Convolutia rezultata) utilizand matplotlib si salveaza automat o copie locala in format imagine (semnale_convolutie.png).

---

Surse și resurse utilizate:
- https://numpy.org/doc/2.1/reference/generated/numpy.sin.html
- https://numpy.org/doc/stable/reference/generated/numpy.convolve.html
- https://matplotlib.org/
"""
