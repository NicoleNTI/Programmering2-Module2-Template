# Glosförhör-program
Skriv ett program som anordnar ett glosförhör med Svenska och Finska ord.

## Programmet ska

1. Läsa in glosorna från en csv fil (ska fungera på filer med olika antal glosor).
2. Spara glosorna i en datastruktur.
3. Skriva ut en lista med glosorna.
4. Ordna ett förhör med alla glosor och räkna antal rätta svar.
4. Skriva ut antal korrekta svar efter förhöret.
5. Extrauppgift: Implementera att en användare kan spara sina highscores som sparas i en fil (.txt går bra)!

## Exempel på hur det kan se ut:

"
   Välkommen till glos programmet!
   1: Visa Gloslista
   2: Kör testet
   3: Avsluta?
   1
   våga                uskaltaa
   erbjuda             tarjota
   talesätt            sanonta
   utseende            ulkonäkö
   sinne               mieli
   näringstillskott    lisäravinne
   prestationskrav     suorituspaine
   skadlig             haitallinen
   kropp               keho
   skyddsnät           turvaverkko
   riskbeteende        riskikäyttäytyminen
   beskriva            kuvata
   balanserad          tasapainoinen
   kroppsbild          kehonkuva
   uppleva             kokea
   Välkommen till glos programmet!
   1: Visa Gloslista
   2: Kör testet
   3: Avsluta?
   2
   Välkommen till ditt glosförhör, skriv 'exit' för tt avsluta när som helst
   skyddsnät: keho
   keho is wrong, -1 point
   skadlig: haitallinen
   skyddsnät: turvaverkko
   kropp: keho
   prestationskrav: exit
   The test is done, your points: 2, wrong answers: skyddsnät,
   Välkommen till glos programmet!
   1: Visa Gloslista
   2: Kör testet
   3: Avsluta?
   3
   Bye Bye!
"