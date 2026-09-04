# Poradnik: Jak cofnąć wersję Among Us na Epic Games

Ten poradnik pokazuje, jak pobrać starszą wersję gry Among Us na platformie Epic Games, aby móc zainstalować mody takie jak Town of Us.

## Krok 1: Pobranie skryptu
1. Przejdź na stronę [EpicGamesDowngrader na GitHubie](https://github.com/whichtwix/EpicGamesDowngrader/releases/latest).
2. Pobierz plik o nazwie `DowngradeEpic.ps1`.

## Krok 2: Uruchomienie skryptu
1. Kliknij pobrany plik `DowngradeEpic.ps1` prawym przyciskiem myszy i wybierz **Uruchom z programem PowerShell**.
2. *Rozwiązywanie problemów:* Jeśli okno natychmiast się zamyka, otwórz program PowerShell ręcznie, przejdź do folderu pobrane (np. wpisując `cd Downloads`), wpisz `Set-ExecutionPolicy Unrestricted -Scope Process`, wciśnij Enter, a następnie uruchom skrypt komendą `./DowngradeEpic.ps1`.

## Krok 3: Autoryzacja konta Epic
Po uruchomieniu skryptu otworzy się okno przeglądarki z kodem.
1. Znajdź i skopiuj długi ciąg znaków znajdujący się zaraz po tekście `"authorizationCode":"`.
2. Wklej ten kod do czarnego okna konsoli w miejscu `Enter Code:` i wciśnij Enter. Pamiętaj, aby zrobić to sprawnie, ponieważ kod szybko wygasa.
3. Skrypt automatycznie pobierze starszą wersję gry i zapisze ją w nowym folderze na Twoim komputerze.

## Krok 4: Instalacja modów
1. Wejdź do nowo utworzonego folderu ze starszą wersją gry.
2. Pobierz mody [Town of Us: Mira](https://townofus.pl/instalacja-tou)
3. Wypakuj bezpośrednio do niego wszystkie pliki wybranego moda.
4. Gotowe! Grę uruchamiaj **zawsze** za pomocą pliku `EpicGamesStarter.exe`, który znajduje się w tym folderze. Nie włączaj gry przez oficjalną aplikację Epic Games.

## Poradnik Youtube
[Among Us na Epic Games](https://youtu.be/rQqqKsRTPHM)
