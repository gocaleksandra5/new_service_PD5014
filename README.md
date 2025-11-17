# Projekt new_service

## Opis usługi medycznej oraz dokumentów stworzonych w projekcie. 

### **Badania bakteriologiczne/mikrobiologiczne**

Opis: 
Stworzenie sieci historii pacjenta do której będą mieć dostęp lekarze, personel laboratoryjny oraz do podglądu pacjenci.  Lekarz zamieszcza informacje o przebytych chorobach, zleconych badaniach oraz badaniach, które odbywają się w trakcie. Diagności uzupełniają informacje o wynikach, możliwych konsekwencjach danych wyników, w tym przypadku o wychodowanych mikroorganizmach. Diagności wykazują wyniki antybiogramów oraz zalecanych dodatkowych badaniach nad silniejszymi antybiotykami w razie potrzeby.

### **Cele:** 
- Łatwiejsze i szybsze gromadzenie aktualnej dokumentacji medycznej. 
- Zwiększie dostępności do usług medycznych.
- Wygoda dla pacjętów.
- Skrócenie czasu wizyty.

### **Korzyści dla pacjentów: **
Cała dokumentacja medyczna w jednym miejscu.
W razie wypadku zagrożenia życia (przez np. wypadek samochodowy) lekarz tylko po danych pacjenta dostaje pełną historię alergii, aktualnych zażywanych lekach oraz dolegliwościach chorobowych.
Pacjent dostaje szybciej informacje o wynikach. 
Pacjent nie musi nosić ze sobą papierowej dokumentacji medycznej.


## Instrukcja dokumentów w repozytorium

- **opis_usługi.txt** — szczegółowy opis usługi.
- **plan_wdrożenia.txt** — etapy wdrożenia nowej usługi.
- **moje_notatki.txt** — plik prywatny, ignorowany przez GIT.
- **ryzyka.txt** — analiza ryzyk związanych z usługą.
- **ankieta_pacjentów.txt** — zestaw pytań dotyczących opinii pacjentów.
- **kampania_marketingowa.txt** — działania promocyjne usługi.
- katalog **images/** z plikiem `.gitkeep` oraz unikalnym logo usługi.
- **README.md** — dokument końcowy.

## Użyte polecenia GIT i ich zastosowanie
git touch # Tworzenie nowego pliku
git init # Inicjalizacja repozytorium
git add <plik> # Dodawanie plików do śledzenia
git commit -m "komentarz" # Zatwierdzanie zmian
git branch marketing # Tworzenie nowej gałęzi
git checkout marketing # Przełączanie gałęzi
git merge marketing # Scalanie gałęzi
git remote add origin <url> # Dodanie repozytorium zdalnego
git push -u origin master # Wypchnięcie zmian na GitHub
git tag -a v1.0 -m "wersja" # Tworzenie tagu
git push origin v1.0 # Wypchnięcie tagu na GitHub

