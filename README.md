# IET a RET 

Tento projekt slouží k simulaci a vizualizaci dynamických systémů založených na výměně tří intervalů (IET), resp. tří obdélníků (RET). Programy umožňují provádět numericky přesné výpočty bez zaokrouhlovacích chyb (v kvadratických tělesech), generovat symbolická slova trajektorií a generovat orbitu příslušného dynamického systému.

## Funkce
- **Přesné výpočty:** Využívá se knihovny `sympy` za účelem přesného symbolického porovnání algebraických (zpravidla iracionálních) výrazů.
- **Simulace IET a RET:** Program generuje slovo, jež odpovídá kódování příslušné fázové trajektorie pro výměny dvou nebo tří intervalů. V případě výměny obdélníků platí totéž, ale jen pro výměnu tří obdélníků.
- **Vizualizace:** Generují se grafy (`matplotlib`), které vizualizují fázovou trajektorii těchto dynamických systémů a vstupní parametry. Program RET_Animation navíc obsahuje interaktivní posuvník pro sledování toho, jak se na výstupu postupně vykreslují jednotlivé iterace počátečního bodu.

## Struktura projektu
- `main.py`: Vstupní bod pro spuštění a testování jednotlivých funkcí příslušných podprogramů.
- `Interval_Exchange_Transformation.py`: Program odpovídající za samotnou výměnu intervalů (IET), generování slov a vykreslování.
- `Rectangle_Exchange_Transformation.py`: Program pro vykreslení fázové trajektroie výměny tří obdélníků a generování odpovídajících kódování daných trajektorií.
- `RET_Animation.py`: Interaktivní animace RET transformací a rotací.

## Požadavky
Projekt vyžaduje Python 3.x a následující knihovny:
numpy, matplotlib, sympy
