              Zadanie analizy śmiertelnych interwencji policyjnych w USA z wykorzystaniem Pandas
Spis treści

    Informacje ogólne
    Użyte technologie
    Instalacja
    Użycie
    Kontakt

Informacje ogólne

To zadanie polega na analizie danych dotyczących śmiertelnych interwencji policyjnych w USA. W ramach zadania przetwarzane są dane ofiar według rasy, oznak choroby psychicznej, a także zestawienie incydentów względem populacji każdego stanu. Celem jest zdobycie umiejętności analizy danych przy użyciu biblioteki Pandas oraz wizualizacji wyników w środowisku JupyterLab.

Użyte technologie:

    Python - wersja 3.x
    Pandas - do przetwarzania i analizy danych
    Matplotlib - do wizualizacji danych
    JupyterLab - do interaktywnego pisania i uruchamiania kodu

Instalacja

    Sklonuj repozytorium na swój komputer:

    bash

        git clone <adres-repozytorium>

Upewnij się, że masz zainstalowany Python 3.x oraz wymagane biblioteki:

    bash
    
    pip install pandas matplotlib jupyterlab

Uruchom JupyterLab:

    bash
    
        jupyter lab
    
Użycie:

Zadanie zawiera kilka kroków analitycznych, które można uruchomić w JupyterLab:

    Wczytanie danych dotyczących śmiertelnych interwencji z pliku CSV dostępnego na stronie internetowej.
    Analiza interwencji według rasy i oznak choroby psychicznej:
        Stworzenie zestawienia liczby ofiar według rasy oraz oznak choroby psychicznej.
        Dodanie kolumny wskazującej odsetek ofiar z oznakami choroby psychicznej w każdej grupie rasowej.
    Dodanie kolumny z dniem tygodnia:
        Dodanie informacji o dniu tygodnia dla każdej interwencji oraz zliczenie liczby incydentów dla każdego dnia.
        Wizualizacja danych w postaci wykresu kolumnowego, uporządkowanego od poniedziałku do niedzieli.
    Analiza incydentów względem populacji stanu:
        Pobranie danych o populacji stanów i ich skrótach z internetu.
        Połączenie tych danych i obliczenie liczby incydentów na 1000 mieszkańców w każdym stanie.

Kontakt

Stworzone przez @Quick-witted-flower  - zapraszam do kontaktu!
