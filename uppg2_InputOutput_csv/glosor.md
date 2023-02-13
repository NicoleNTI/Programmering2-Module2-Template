# Glosförhör-program
Skriv ett program som anordnar ett glosförhör med Svenska och Finska ord.

## Programmet ska

1. Läsa in glosorna från en csv fil (ska fungera på filer med olika antal glosor).
2. Spara glosorna i en datastruktur.
3. Skriva ut en lista med glosorna.
4. Ordna ett förhör med alla glosor och räkna antal rätta svar.
4. Skriva ut antal korrekta svar efter förhöret.

## Exempel på hur det kan se ut:

    INDATA:
            1: Enter
            2: 1
            3: Enter
            4: Slips
            5: Nej
            6: Enter

    UTDATA:
            0: Tryck Enter för att köra igång!
            1: Vad vill du köra?
               1: albanska till svenska
               2: svenska till albanska
               Välj:
            2: Detta är ett glostest mellan albanska och svenksa
               Följande är de ord som testas!

               Pantallona | Byxa
               Triko      | Tröja
               Corape     | Strumpa
               xhakete    | Jacka
               Kravate    | Slips
               Kapak      | Mössa
               Shall      | Halsduk
               Rripa      | Skärp
               Doreze     | Vante

               Är du redo?
            3: (*^▽^*) * 50 

               Nu är det dags!
               Vad betyder Kravate på svenska?
            4: Rätt!
               Tryck enter för att fortsätta, annars skriv nej
            5: Du hadde 1 rätta svar!
               \n * 50
               Tryck enter för att köra igång!
