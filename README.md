# DiceGame

Ett textbaserat tärningsspel skrivet i Java. Du väljer hur många rundor du vill spela och hur många sidor tärningen ska ha. Gissa tärningens värde för att samla poäng och försök nå 10 poäng för att vinna.

## Krav

- Java JDK måste vara installerat.
- För att använda startfilen behöver du Windows.

## Kör spelet

1. Öppna projektmappen **DiceGames** i din dator.
2. Dubbelklicka på filen `run-game.bat`.
   1. Om du behöver starta spelet manuellt i VSCode klistra in `chcp 65001` i terminalen.
3. Följ instruktionerna
4. Välj antal spelrundor, för att vinna måste du uppnå 10 poäng.
5. Välj hur många sidor tärningen ska ha. Tärningen måste ha minst två sidor.
6. Ange ditt namn.
7. Gissa ett tal mellan 1 och det valda antalet sidor. Varje korrekt gissning ger 1 poäng.
8. Efter varje gissning får du återkoppling på om du gissade rätt, hur många rundor som återstår och hur många poäng du har samlat ihop hittils.
9. När du når ditt valda antal rundor kommer du att få en sammanställning av dina samlade poäng och frågas om du vill spela igen, `yes/no`.

## Projektstruktur

- `DiceGame.java` – spelets startpunkt. Frågar efter antal rundor, tärningens
  sidor och spelarens namn.
- `GameStart.java` – hanterar spelrundorna, poäng, vinstvillkor och frågan om
  att spela igen.
- `Player.java` – håller reda på spelarens namn, poäng och tärning.
- `Die.java` – representerar tärningen och slumpar fram ett värde vid varje
  kast.
- `PlayerInput.java` – läser och validerar spelarens inmatning.
- `Helper/TerminalColors.java` – innehåller färgkoder för texten i terminalen.

## Medverkande

Phatchari Jansson, Cajsa Lermark och Damian Dzafic.
