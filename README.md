# DiceGame

## Krav

- Java JDK måste vara installerat.
- För att använda startfilen behöver du Windows.

## Kör spelet

### Windows

Öppna projektmappen och dubbelklicka på `run-game.bat`. Filen kompilerar
projektet och startar spelet.

### Starta manuellt

Öppna en terminal i projektmappen och kör:

```shell
javac *.java Helper\TerminalColors.java
java DiceGame
```

## Projektstruktur

- `DiceGame.java` – spelets startpunkt. Frågar efter antal rundor, tärningens
  sidor och spelarens namn.
- `GameStart.java` – hanterar spelrundorna, poäng, vinstvillkor och frågan om
  att spela igen.
- `Player.java` – håller reda på spelarens namn och poäng.
- `Die.java` – representerar tärningen och slumpar fram ett värde vid varje
  kast.
- `PlayerInput.java` – läser och validerar spelarens inmatning.
- `Helper/TerminalColors.java` – innehåller färgkoder för texten i terminalen.

## Medverkande

Phatchari Jansson, Cajsa Lermark och Damian Dzafic.
