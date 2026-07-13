# 🛠️ Rejestr Prac i Części (Mobilny Asystent Utrzymania Ruchu)

Prosta, szybka i lekka aplikacja webowa typu **Single Page Application (SPA)**, stworzona z myślą o mechanikach, automatykach i technikach Utrzymania Ruchu. Umożliwia błyskawiczne rejestrowanie wykonanych napraw, przeglądów oraz zużytych części bezpośrednio na ekranie smartfona w trakcie pracy przy maszynie.

Aplikacja działa w 100% lokalnie w przeglądarce (nie wymaga serwera ani bazy danych) i automatycznie zapisuje stan pracy.

---

## 🔥 Kluczowe Funkcje & Ergonomia (User-Friendly)

*   **Rozdzielenie Maszyn od Prac:** Logiczny podział na konkretne urządzenia oraz historię działań na nich prowadzonych.
*   **Inteligentne Scalanie Części:** Jeśli dopisujesz kolejną część do tej samej, aktualnie wykonywanej pracy, aplikacja nie tworzy nowego wpisu, lecz **automatycznie dokłada część do istniejącego bloku** (i sumuje ilości, jeśli część się powtórzy).
*   **Kontekstowa Pamięć Formularza:** Po zapisaniu wpisu, formularz czyści pola części, ale **zostawia wpisaną maszynę oraz opis pracy**. Możesz od razu wbijać kolejne elementy. 
*   **Automatyczny Reset przy Zmianie:** Jeśli ręcznie zmienisz maszynę lub wybierzesz inną z historii ostatnich urządzeń, pole opisu prac natychmiast się czyści, zapobiegając przypadkowemu przypisaniu starego opisu do nowej maszyny.
*   **Dzienny Akordeon Zestawienia:** Zakładka "Zestawienie" grupuje dane w czytelne, rozwijane karty maszyn z dokładną godziną każdego wpisu.
*   **Szybka Edycja Wpisów:** W zakładce "Zestawienie" możesz poprawić nazwę maszyny, opis wykonanej pracy oraz dane części bez konieczności usuwania i wpisywania wszystkiego od nowa.
*   **Automatyczne Sumowanie:** System na bieżąco generuje globalną listę zbiorczą wszystkich zużytych w ciągu dnia części (idealne do szybkiego zdania raportu lub pobrania z magazynu).
*   **Eksport do Pliku:** Możliwość pobrania całego dziennego raportu do czystego pliku `.TXT` jednym kliknięciem.

---

## 🚀 Jak uruchomić?

Aplikacja nie wymaga żadnej instalacji, kompilacji ani konfiguracji środowiska.

1. Pobierz plik `index.html`.
2. Otwórz go w dowolnej przeglądarce na komputerze lub smartfonie.
3. *Wskazówka mobilna:* Możesz dodać skrót do pliku na ekranie głównym swojego telefonu, aby korzystać z aplikacji jak ze zwykłej apki mobilnej.

---

## 💾 Technologia i Bezpieczeństwo Danych

*   **Frontend:** Czysty HTML5, CSS3 (zmienne CSS, Flexbox) oraz nowoczesny JavaScript (Vanilla JS).
*   **Przechowywanie danych:** Dane są zapisywane w pamięci podręcznej przeglądarki (`LocalStorage`). Wyczyszczenie danych aplikacji lub pamięci przeglądarki usunie wpisy. Aplikacja nie wysyła żadnych danych na zewnętrzne serwery – pełna prywatność.

---

## 📄 Licencja

Projekt udostępniany na licencji MIT. Możesz go dowolnie modyfikować i dostosowywać do własnych potrzeb w zakładzie produkcyjnym.
 