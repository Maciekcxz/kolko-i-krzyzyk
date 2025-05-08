# TicTacToe - README
To prosty skrypt w JS, który umożliwia grę w kółko i krzyżyk dla dwóch graczy na planszy 3x3.

## Jak z niego korzystać?
Po uruchomieniu skryptu pojawi się plansza 3x3 (9 pól). Gracze na zmianę umieszczają swoje znaki (X lub O). W przypadku wygranej, gra informuje o tym, pokazując komunikat z nazwiskiem zwycięzcy oraz rysując czerwoną linię wzdłuż pól, które spełniają warunki wygranej.

## Jakie *funkcje* występują w tym skrypcie?
- **createBoard()** - Tworzy planszę do gry w formacie 3x3.
- **handleCellClick(event)** - Obsługuje kliknięcie w pole. Na klikniętym polu pojawia się odpowiedni znak gracza (zależnie od tury). Funkcja sprawdza również warunki wygranej, remisu oraz zmianę gracza.
- **checkWin()** - Sprawdza, czy któryś z graczy spełnił warunki wygranej, porównując aktualny stan z kombinacjami zwycięskimi.
- **drawWinningLine()** - Rysuje linię na planszy wzdłuż pól, które spełniają warunki wygranej.
- **resetGame()** - Czyści planszę i resetuje wszystkie ustawienia, aby rozpocząć grę od nowa.

## Jakie *zmienne globalne* występują w tym skrypcie?
- __*board*__ - Element HTML, w którym znajduje się plansza.
- __*messageTur*__ - Element HTML, w którym wyświetlany jest komunikat o turze.
- __*resetBtn*__ - Element HTML, który jest przyciskiem do resetowania gry.
- __*currentPlayer*__ - Zmienna wskazująca na aktywnego gracza.
- __*gameBoard*__ - Tablica przechowująca aktualny stan planszy.
- __*winningCombo*__ - Tablica zawierająca zwycięskie kombinacje.
- __*gameOver*__ - Zmienna, która wskazuje, kiedy gra dobiegnie końca.
