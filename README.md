# DiceGame

Ett textbaserat tärningsspel skrivet i Java. Du väljer hur många rundor du vill spela och hur många sidor tärningen ska ha. Gissa tärningens värde för att samla poäng och försök nå 10 poäng för att vinna.

## Krav
- Java JDK måste vara installerat.
- För att använda startfilen behöver du Windows.

## Instruktioner
1. Öppna projektmappen **DiceGames** på din dator.
   1. Om du behöver starta spelet manuellt i VSCode klistra in `chcp 65001` i terminalen
2. Dubbelklicka på filen `run-game.bat`.
3. Följ instruktionerna i spelet:
   1. Välj hur många rundor du vill spela.
   2. Välj hur många sidor tärningen ska ha. Tärningen måste ha minst två sidor.
   3. Ange ditt namn.
   4. Gissa ett tal mellan 1 och det valda antalet sidor. Varje korrekt gissning ger 1 poäng.
   5. Efter varje gissning får du veta om du gissade rätt, hur många rundor som återstår och hur många poäng du har samlat ihop.
   6. Om du samlar ihop 10 poäng vinner du. Då får du ett vinnarmeddelande och kan välja om du vill spela igen genom att svara `yes` eller `no`.
   7. Om rundorna tar slut innan du har samlat ihop 10 poäng förlorar du. Då får du välja om du vill spela igen genom att svara `yes` eller `no`.

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
