## Introduktion till Variabler och Datatyper i Node.js

Längst ned i den här filen finns ett antal övningar.

i filen "vars.js" finns några exempel.
Ladda ner filen och öppna i Visual Studio Code.
Kör filen och försök förstå vad som händer.

Du kör filen genom att välja Run/Run without debugging och sedan välja node. Eller kör via terminalen

    $ node vars.js


du behöver ha node installerat.



### En variabel 
är som en namngiven behållare för att lagra data i ett program/en app. 
I node använder vi nyckelordet "var" eller "let" för att deklarera variabler.
Rekeommderat är att använda "let".

Exempel: 

    let age = 25; eller let name = 'Alice';


### Datatyper 
definierar vilken typ av data en variabel kan innehålla.

Vanliga datatyper inkluderar:

    String/Textsträngar: "Hej, världen!"
    Integer/Heltal: 42
    Decimal, Float/Flyttal: 3.14
    Boolean/Booleska värden: true eller false
    Array/Arrayer: [1, 2, 3]

Exempel:

    let name = 'Anna';
    let age = 30;
    let temperature = 25.5;
    let isActive = true;
    let numbers = [1, 2, 3, 4];

### Operatorer
Operatorer används för att utföra operationer på variabler och datatyper.

Exempel:
        
        Addition: let sum = 10 + 5;
        Strängkonkatinering: let greeting = 'Hej ' + 'världen';
        Jämförelse: let isGreater = 10 > 5;

Variabler och datatyper är grundläggande byggstenar i programmering. Genom att förstå hur man deklarerar variabler och arbetar med olika datatyper kan du skapa kraftfulla och dynamiska program. 


# Övningar

### Övning 1: Variabeldeklaration
Skapa en variabel med namnet name och tilldela den ditt eget namn. Skriv ut värdet på variabeln i terminalen.

### Övning 2: Heltal och Addition
Deklarera två variabler, num1 och num2, och tilldela dem två heltal. Använd sedan en operator för att beräkna deras summa och skriv ut resultatet.

### Övning 3: Textsträngar och Konkatinering
Deklarera två variabler, firstName och lastName, och tilldela dem ditt förnamn och efternamn. Använd sedan operatorn + för att sätta samman dem och skriv ut hela ditt namn.

### Övning 4: Flyttal och Subtraktion
Deklarera två variabler, num3 och num4, och tilldela dem två flyttal. Använd sedan en operator för att beräkna deras differens och skriv ut resultatet.

### Övning 5: Booleska Värden och Jämförelse
Deklarera två variabler, isSunShining och isRaining, och tilldela dem booleska värden. Använd sedan jämförelseoperatorerna för att kontrollera om det är soligt och/eller regnar, och skriv ut resultaten.

### Övning 6: Array och Indexering
Skapa en array med namnet fruits som innehåller några olika frukttyper (t.ex. äpple, banan, apelsin). Använd indexering för att skriva ut den andra frukten i arrayen.

### Övning 7: Ändra Värde i Array
Ändra värdet på den andra frukten i arrayen från övning 6 till en ny frukt och skriv ut den uppdaterade arrayen.

### Övning 8: Längd på en Array
Använd arrayen från övning 6 och skriv ut antalet element (frukter) i arrayen.

### Övning 9: Logiska Operatorer
Skapa två booleska variabler, isSunny och isWarm. Använd logiska operatorer (&&, ||) för att skapa olika villkor och skriv ut resultatet av varje villkor.

### Övning 10: Blandad Typ i Array
Skapa en array med namnet mixedData som innehåller olika datatyper, inklusive textsträngar, heltal och flyttal. Skriv ut varje element i arrayen.

Du kan använda Visual Studio Code för att skapa en JavaScript-fil och testa dessa övningar. Använd console.log() för att skriva ut resultatet i terminalen när du kör filen med Node.js. Detta kommer att hjälpa dig att förstå och öva på variabler, datatyper och operatorer i Node.js. Lycka till!