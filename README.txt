REJESTRATOR PRZEBIEGU – instrukcja

1. Wypakuj folder.
2. Aby aplikacja była instalowalna na Androidzie, opublikuj zawartość folderu na hostingu HTTPS.
   Najprościej bezpłatnie: GitHub Pages.
3. Otwórz opublikowany adres w Chrome na Androidzie.
4. W menu Chrome wybierz „Zainstaluj aplikację” lub „Dodaj do ekranu głównego”.

Pierwsze uruchomienie:
- Otwórz Ustawienia.
- Dodaj samochód (możesz wpisać nazwę i rejestrację).
- Dodaj kategorie, np. Prywatnie, Praca, Służbowo.
- Wybierz „Dodaj przejazd” i wpisz datę, auto, kategorię oraz przebieg przed i po jeździe.

Dane:
- Dane przechowywane są lokalnie w pamięci przeglądarki (IndexedDB).
- Aplikacja działa offline po pierwszym załadowaniu.
- Eksportuj regularnie kopię JSON w zakładce Ustawienia.
- Import kopii zastępuje aktualne dane.

Uwaga:
- Usunięcie samochodu lub kategorii usuwa także przejazdy z nimi powiązane.
- Brak limitu aplikacji na liczbę wpisów, ale praktyczna pojemność zależy od pamięci urządzenia/przeglądarki.
- To jest wersja startowa. Nie synchronizuje danych między różnymi urządzeniami.
