1. Przygotuj funkcje, ktora sprawdzi czy localStorage jest dostepny. Funkcja powinna zwracac true/false.
2. Jezeli localStorage jest dostepny:
   1. Dodaj do niego pod kluczem `username` jakas wartosc typu string.
   2. Pobierz wartosc `username` z localStorage.
   3. Dodaj do niego pod kluczem `deleteMe` jakas wartosc typu number.
   4. Pobierz wartosc `deleteMe`. Jakiego typu jest ta wartosc?
   5. Usun klucz `deleteMe` z local storage.
3. Dopisz do skryptu kod, ktory sprawdzi czy localStorage (uzyj funkcji z 1) jest dostępny i jezeli jest dostępny to wyswietli w konsoli wartowsc klucza `username` jezeli zostal zapisany w localStorage. Jezeli klucz `username` nie jest dostępny dodaj go do localStorage z wartoscia string.
4. Sprawdz w narzedziach developerskich gdzie jest zapisywany localStorage. Wejdz na kilka stron i sprawdz czy cos dodaja do localStorage.