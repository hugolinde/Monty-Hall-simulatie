# Het Mony Hall probleem gesimuleerd

Wie kent niet de beroemde scene in de film 21 waarbij de verlegen maar briljante Ben Campbell (Jim Sturgess) tijdens college het goede antwoord geeft op het Monty Hall probleem. Een erg tegen-intuitief antwoord. De docent (gespeeld door Kevin Spacey) is vervolgens zo onder de indruk dat hij hem vraagt aan te sluiten bij een selecte groep topstudenten die elk weekend naar Las Vegas gaan om veel geld met Black Jack te winnen.

Het **Monty Hall-probleem** zelf is gebaseerd op de oude spelshow *Let's Make a Deal*, gepresenteerd door Monty Hall. Je moet kiezen uit drie deuren: achter één zit een auto, achter de andere twee een geit. Nadat je een deur kiest, opent Monty (die weet wat erachter zit) een andere deur met een geit. Dan mag je bij je keuze blijven of wisselen.

Hoewel compleet tegen-intuïtief, is de kans op winst **2/3 als je wisselt van deur**, en maar **1/3 als je bij je originele keuze blijft**. Wisselen vergroot dus je kans om de auto te winnen.

Om aan te tonen dat deze kansverdeling in de praktijk ook echt klopt, simuleert dit programma aantal keer het spel en geeft aan hoe vaak in beide gevallen de juiste deur is gekozen.


## How does it work?

Simpel: run het Python programma en er verschijnt een invoerbox waarin je kan aangeven hoeveel simulaties je wil doen.
Na invoer en enter wordt het aantal keren dat de juiste deur is geopend gegeven, zowel voor geval dat speler bij zijn origionele keuze is gebleven, als dat hij toch naar de andere deur is geswitched

### Execute

monty.py (geen bijzondere environment nodig, naast Python zelf)

```bash

