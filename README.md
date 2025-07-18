Dobrze, rozumiem\! To jest skrypt do generowania tekstu ASCII z użyciem różnych czcionek. Stworzę dla niego plik README.md.

-----

# ASCII-GEN

## Opis Projektu

`ASCII-GEN` to proste narzędzie w Pythonie, które pozwala użytkownikowi generować artystyczny tekst ASCII przy użyciu różnych stylów (czcionek) dostępnych w bibliotece `pyfiglet`. Aplikacja jest interaktywna, umożliwiając podanie własnego tekstu oraz wybór preferowanego stylu z listy dostępnych opcji. Wygenerowany tekst ASCII jest następnie wyświetlany w konsoli, a także generowany jest fragment kodu Pythona, który można wykorzystać do odtworzenia tego samego efektu.

## Funkcje

  * **Interaktywne generowanie tekstu ASCII**: Użytkownik wprowadza tekst i wybiera styl.
  * **Lista dostępnych stylów (czcionek)**: Program może wyświetlić przykłady różnych czcionek `pyfiglet` po wpisaniu `--list`.
  * **Podgląd wygenerowanego tekstu**: Wyświetla końcowy tekst ASCII bezpośrednio w konsoli.
  * **Generowanie fragmentu kodu**: Tworzy gotowy do użycia kod Pythona, który generuje dany tekst ASCII z wybranym stylem.

## Wymagania

Projekt wymaga Pythona 3.x oraz kilku bibliotek zewnętrznych.

## Instalacja

Aby uruchomić projekt, wykonaj następujące kroki:

1.  **Pobierz plik `ASCII-GEN.py`** (lub sklonuj repozytorium, jeśli jest dostępne).

2.  **Zainstaluj wymagane biblioteki** za pomocą `pip`. Możesz to zrobić, tworząc plik `requirements.txt` w tym samym folderze co skrypt, a następnie uruchamiając `pip install -r requirements.txt`.

    Zawartość pliku `requirements.txt` powinna wyglądać tak:

    ```
    pyfiglet
    rich
    ```

    Lub możesz zainstalować je ręcznie:

    ```bash
    pip install pyfiglet rich
    ```

## Użycie

Po zainstalowaniu zależności, możesz uruchomić skrypt `ASCII-GEN.py` z terminala:

```bash
python ASCII-GEN.py
```

Aplikacja poprowadzi Cię przez proces:

1.  Zostaniesz poproszony o **podanie tekstu**, który ma zostać przekonwertowany na ASCII.
2.  Następnie zostaniesz poproszony o **podanie rodzaju czcionki**. Jeśli nie znasz dostępnych czcionek, wpisz `--list`, aby wyświetlić listę z przykładami. Po zapoznaniu się z listą, ponownie zostaniesz poproszony o wybranie rodzaju.
3.  Po podaniu wszystkich danych, program wygeneruje i wyświetli:
      * Wygenerowany fragment kodu Pythona.
      * Podgląd tekstu ASCII.
