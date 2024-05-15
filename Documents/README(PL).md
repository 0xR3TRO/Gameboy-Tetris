## Opis projektu

### Cel:

Projekt "Gameboy-Tetris" ma na celu stworzenie nowoczesnej wersji klasycznej gry Tetris na konsolę Gameboy. Celem jest dostarczenie graczom nostalgicznych doświadczeń, jednocześnie wprowadzając nowe funkcje i usprawnienia, które wzbogacą rozgrywkę.

### Opis funkcji:

- **Klasyczna rozgrywka Tetris:** Użytkownicy mogą cieszyć się klasyczną mechaniką gry Tetris.
- **Tryby gry:** Wprowadzenie różnych trybów gry, takich jak klasyczny, wyzwania czasowe, tryb niekończący się itp.
- **Tablica wyników:** Przechowywanie najlepszych wyników graczy i możliwość rywalizacji.
- **Opcje personalizacji:** Możliwość wyboru różnych motywów graficznych i dźwiękowych.

## Analiza wymagań:

### Wymagania funkcjonalne:

- **Klasyczna rozgrywka:** Gra musi odwzorowywać klasyczną mechanikę Tetrisa z dokładnością.
- **Tryby gry:** Umożliwienie wyboru różnych trybów rozgrywki, takich jak klasyczny, czasowy, nieskończony.
- **Tablica wyników:** Implementacja systemu przechowywania wyników graczy i wyświetlania ich na tablicy.
- **Personalizacja:** Dodanie opcji zmiany motywów graficznych oraz dźwięków w grze.

### Wymagania niefunkcjonalne:

- **Wydajność:** Gra musi działać płynnie na konsoli Gameboy, bez opóźnień i zacięć.
- **Interfejs użytkownika:** Intuicyjny i łatwy w obsłudze interfejs, dostosowany do możliwości Gameboya.
- **Dźwięk i grafika:** Użycie wysokiej jakości dźwięków i grafik, które są zgodne z możliwościami Gameboya.

## Projekt interfejsu:

### Szkice/wizualizacje interfejsu:

- _Strona główna:_ Ekran startowy z opcjami wyboru trybu gry i dostępem do tablicy wyników.
- _Ekran gry:_ Widok klasycznego pola gry Tetris z aktualnym wynikiem, poziomem i nadchodzącymi klockami.
- _Tablica wyników:_ Lista najlepszych wyników z opcją wpisania swojego imienia po zakończeniu gry.

### Mapa strony:

- _Strona główna_
  - Opcje gry
  - Tablica wyników
- _Ekran gry_
  - Pole gry
  - Aktualne wyniki
  - Nadchodzące klocki
- _Tablica wyników_
  - Lista najlepszych wyników

## Architektura systemu:

### Opis struktury danych:

Gra przechowuje dane dotyczące:

- **Wyniki:** Najlepsze wyniki graczy z ich imionami.
- **Ustawienia gry:** Wybrane przez gracza motywy graficzne i dźwiękowe.
- **Stany gry:** Aktualny stan gry, w tym poziom, wynik i pozycje klocków.

### Diagramy architektury:

Architektura oparta jest na strukturze opakowanej, gdzie:

- **Model:** Odpowiada za logikę gry, w tym mechanikę Tetrisa, zarządzanie wynikami i stanami gry.
- **Widok (View):** Prezentuje interfejs użytkownika i wyświetla grafikę oraz dźwięki.
- **Kontroler (Controller):** Zarządza komunikacją między modelem a widokiem, reagując na działania użytkownika.

## Implementacja:

### Opis technologii:

- **Frontend:** Grafika i dźwięk zoptymalizowane pod możliwości konsoli Gameboy.
- **Backend:** Logika gry Tetris zaimplementowana w języku asemblera lub C dla Gameboya.

### Struktura kodu:

- _Katalogi/pliki_: Oddzielne pliki dla logiki gry, interfejsu użytkownika, zarządzania wynikami.
- _Style pisania kodu_: Modularność, czytelność kodu i szczegółowe komentarze.

## Testowanie:

### Plan testów:

- **Testy jednostkowe:** Sprawdzenie poprawności funkcji logicznych gry Tetris.
- **Testy integracyjne:** Upewnienie się, że wszystkie komponenty gry współpracują ze sobą bez problemów.
- **Testy interfejsu użytkownika:** Sprawdzenie interakcji użytkownika z grą na konsoli Gameboy.
- **Testy wydajnościowe:** Ocena płynności i responsywności gry na Gameboyu.

### Procedury testowania:

- Opracowanie zestawu przypadków testowych dla każdej funkcji gry.
- Ustalenie procedur raportowania i naprawiania znalezionych błędów.

## Wdrożenie i konserwacja:

### Plan wdrożenia:

- **Etapy wdrażania:** Testowanie, poprawki, publikacja na nośnikach dostępnych dla konsoli Gameboy.
- **Terminy:** Określenie dat planowanych etapów.

### Procedury konserwacji:

- **Wsparcie techniczne:** Ustanowienie kanałów komunikacji z użytkownikami w celu zgłaszania problemów.
- **Aktualizacje:** Planowanie ewentualnych aktualizacji i poprawek na podstawie feedbacku użytkowników.

## Harmonogram:

### Plan projektu:

- **Etapy realizacji:** Podział prac na konkretne zadania (np. implementacja mechaniki gry, interfejsu, testowanie).
- **Terminy:** Określenie czasu potrzebnego na każdy etap.

## Kosztorys:

### Szacunkowe koszty:

- **Rozwój gry:** Wg godzin pracy zespołu programistów.
- **Koszty utrzymania:** Serwery do przechowywania wyników, ewentualne opłaty za usługi zewnętrzne, wsparcie techniczne.
