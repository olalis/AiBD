
# Analiza i Bazy Danych
## Laboratoria 2: TIER protocol i tidy data
Opracowany zbiór danych zawiera informacje na temat średniej ilości alkoholu (piwo, wino, wódka, ogólna ilość czystego alkoholu) spożywanej przez jedną osobę z podziałem na kraje w 2010 r.

Oryginalne dane znajdują się w `..\Original Data\drinks.csv`. Opis tych danych zamieszczony jest w  `..\Original Data\MetaData\MetaData.md`.

### Przetwarzanie danych
Aby przetworzyć otrzymane dane i uzyskać ich opracowanie należy uruchomić skrypty z rozszerzeniem  `.ipynb` znajdujące się w `..\Command Files` w kolejności:

 1. `AiBD_lab2_aleksandralis_cz1.ipynb` - plik zawiera kod tworzący kopię oryginalnych danych ze mienionymi nazwami kolumn i zapisuje je do pliku `..\Analysis Data\drinks_changed.csv`, tworzy również pliki: `..\Analysis Data\drinks_top_of_beer.csv`, `..\Analysis Data\drinks_top_of_spirit.csv`, `..\Analysis Data\drinks_top_of_wine.csv` oraz `..\Analysis Data\drinks_total.csv` zawierające dane na temat 10 krajów w których spożycie danego alkoholu/suma spożycia czystego alkoholu jest najwyższa.
 2. `AiBD_lab2_aleksandralis_cz2.ipynb` - na podstawie plików utworzonych przed wcześniej użyty skrypt, tworzy on cztery wykresy prezentujące dane w nich zawarte.

### Dodoatkowe informacje
W pliku `..\Documents\DataApendix.md` znajdują się podstawowe informacje statystyczne o przetwarzanym zbiorze danych.