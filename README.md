# IET_and_RET-BP

# IET a RET Simulátor

Tento projekt slouží k simulaci a vizualizaci dynamických systémů založených na výměně intervalů (IET) a obdélníků (RET). Programy umožňují provádět přesné matematické výpočty (v kvadratických tělesech) bez zaokrouhlovacích chyb a generovat symbolická slova trajektorií.

## Funkce
- **Přesné výpočty:** Využití `sympy` pro práci s iracionálními čísly (odmocniny).
- **Simulace IET:** Podpora pro výměnu 2 a 3 intervalů.
- **Simulace RET:** 2D transformace s vizualizací trajektorií v jednotkovém čtverci.
- **Vizualizace:** Generování interaktivních grafů (`matplotlib` s posuvníky) a export výsledků do PDF.

## Struktura projektu
- `main.py`: Vstupní bod pro spuštění a testování funkcionalit.
- `Interval_Exchange_Transformation.py`: Jádro pro výměnu intervalů (IET), generování slov a vykreslování.
- `Rectangle_Exchange_Transformation.txt`: Skript pro 2D RET simulaci a generování PDF výstupů.
- `RET_Animation.txt`: Interaktivní animace RET transformací a rotací.

## Požadavky
Projekt vyžaduje Python 3.x a následující knihovny:
numpy, matplotlib, sympy
