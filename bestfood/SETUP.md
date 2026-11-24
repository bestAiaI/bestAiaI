# BestFood – konfiguracja prywatnego dziennika

## Opcjonalny arkusz
Utwórz prywatny arkusz Google Sheets (lub równoważny) o nazwie wybranej przez siebie. Przykładowe nagłówki:

`id_wpisu | data | posilek | opis | ilosc_g | kcal | bialko_g | tluszcz_g | weglowodany_g | zrodlo | pewnosc | aktualizacja`

- `id_wpisu` powinien identyfikować rekord przy korekcie; bez identyfikatora należy przed zmianą odnaleźć jednoznaczny wpis.
- `zrodlo`: użytkownik / etykieta / oszacowanie AI.
- B/T/W zostaw puste, gdy brak wiarygodnych danych.
- Skróty posiłków trzymaj w osobnej prywatnej zakładce `Skroty`: `skrot | opis | gramatura_g | kcal | bialko_g | tluszcz_g | weglowodany_g | wazne_od`.
- Nie przechowuj publicznie identyfikatora arkusza ani dostępu do niego.

## Integracja
Połącz prywatny arkusz tylko za pomocą konektora, który faktycznie obsługuje odczyt i edycję. Sprawdź uprawnienia i wykonaj test zapisu i odczytu. Sam prompt nie tworzy integracji ani harmonogramu.

## Test
1. Podaj opis testowego posiłku oraz datę.
2. Wydaj polecenie zapisania i zweryfikuj rekord w arkuszu.
3. Popraw porcję tego samego posiłku – wynik powinien zastąpić poprzednią wartość.
4. Wyświetl sumę dnia i sprawdź, czy nie ma duplikatu.
5. Sprawdź tryb `fitatu` na zdjęciu testowym.

## Bezpieczeństwo
Historia posiłków i ewentualne informacje zdrowotne pozostają prywatne. Nie przesyłaj do repozytorium zdjęć, danych osobowych, sekretów ani identyfikatorów prywatnych dokumentów.
