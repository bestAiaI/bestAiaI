# BestFood AI

Asystent AI z elementami agentowymi do prowadzenia dziennika żywieniowego. Rozpoznaje dania ze zdjęć i opisów, szacuje masę i kaloryczność, obsługuje skróty do powtarzalnych posiłków oraz – po udostępnieniu odpowiedniego narzędzia – zapisuje zatwierdzone wpisy do prywatnego arkusza.

## Funkcje
- Rozpoznawanie widocznych składników; rozdzielenie faktów ze zdjęcia od przypuszczeń.
- Szacowanie porcji (g) i energii (kcal) wraz z zaznaczeniem niepewności.
- Ewidencja według daty posiłku i korekty wcześniejszych wpisów.
- Konfigurowalne skróty do typowych posiłków, np. `/trening` i `/nietrening`.
- Tryb `fitatu`: składniki z pierwszej widocznej potrawy w jednej linii, bez tłumaczenia nazw; oddzielnie szacowana masa i kalorie.
- Opcjonalna analiza dziennych i tygodniowych sum – wyłącznie na podstawie faktycznie dostępnych danych.

## Uruchomienie
1. Utwórz prywatny projekt w ChatGPT i dołącz [REGULY.md](REGULY.md) jako instrukcje/źródło reguł.
2. Uruchom [START.md](START.md). Uzupełnij własne skróty i informacje o sposobie zapisywania wyników. Nie udostępniaj danych prywatnych w publicznym repozytorium.
3. Jeśli chcesz przechowywać historię, utwórz prywatny arkusz zgodnie z [SETUP.md](SETUP.md) i podłącz dostępny konektor. Bez faktycznej integracji asystent nie powinien deklarować, że cokolwiek zapisał.
4. Przetestuj dodanie potrawy, zmianę daty, korektę gramatury oraz ponowne podsumowanie.

**Ograniczenia:** rozpoznanie i kalorie są szacunkowe; zdjęcie nie podaje dokładnego składu, gramatury ani zawartości oleju. System nie jest dietetykiem ani urządzeniem medycznym. Działa głównie po otrzymaniu polecenia – nie prowadzi samodzielnego monitorowania bez osobno skonfigurowanej automatyzacji.

**Prywatność:** to repo zawiera wyłącznie szablony. Nie umieszczaj w nim zdjęć prywatnych posiłków, historii jedzenia, danych zdrowotnych, identyfikatorów arkuszy ani kluczy dostępowych.
