# 200s-javascript-prov

## Fråga 1 - Variabler
Skapa en variabel som heter <b>radie</b> som tilldelas värdet 5.<br>
Skapa sedan en variabel <b>omkrets</b> som tilldelas omkretsen av en cirkel med hjälp av radie variabeln.<br>
Formeln för omkrets är <i>O = 2&pi;r</i> och värdet på &pi; får man ut från JavaScript inbyggda **Math.PI**.

Skriv ut värdet på omkretsen med <i>alert()</i>.


## Fråga 2 - If-satser
Läs in ett namn med <i>prompt()</i> och lagra det i en variabel som heter <b>name</b>.
Använd if-satser för att kontrollera ifall namnet är <i>Jeton</i> eller <i>Joakim</i>.<br>
Är fallet sådan skriver du ut "Du är en programmeringslärare!".<br>
Är namnet något annat så skriver du ut "Du är inte programmeringslärare!".


## Fråga 3 - For-loopen
 
Skapa en for-loop som loopar igenom talen 1 till 21 och skriver ut talet till konsolen.


## Fråga 4 - For-loop på lista med objekt

Du har en lista nedan med objekt som innehåller information om städer.

```
[{id: 1, name: 'Västerås', county: 'Västmanland'},
{id: 2, name: 'Karlstad', county: 'Värmland'},
{id: 3, name: 'Borlänge', county: 'Dalarna'},
{id: 4, name: 'Malmö', county: 'Skåne'},
{id: 5, name: 'Helsingborg', county: 'Skåne'},
{id: 6, name: 'Kiruna', county: 'Lappland'}]
```
Tilldela listan till en variabel som heter **cities**.
Loopa sedan igenom listan och skriv ut information om varje list-objekt på följande format:
**name - county**, för första objektet skulle det se ut så här **Västerås - Västmanland**.

## Fråga 5
Skapa tre funktioner **add**, **subtract** och **multiply** för matematiska operationer som tar in 3 parametarar **x**, **y** och **z**.
Varje funktion ska addera, subtrahera och multiplicera parametrarna i den ordningen ni själva bestämmer.

Anropa sedan varje funktion med valfria värden på parametrarna och skriv ut resultatet till konsolen.


## Fråga 6
Du har en lista nedan med objekt som innehåller information om städer.

```
[{id: 1, name: 'Västerås', county: 'Västmanland'},
{id: 2, name: 'Karlstad', county: 'Värmland'},
{id: 3, name: 'Borlänge', county: 'Dalarna'},
{id: 4, name: 'Malmö', county: 'Skåne'},
{id: 5, name: 'Helsingborg', county: 'Skåne'},
{id: 6, name: 'Kiruna', county: 'Lappland'}]
```
Tilldela listan till en variabel som heter **cities**.

Skapa en funktion som heter findCity(), findCity tar in en parameter på ett Id,
använd Id't för att filtrera ut objektet med det Id't från cities och returnera det.

Använd inbyggda find funktionen för att filtrera: <https://www.w3schools.com/jsref/jsref_find.asp>

Anropa findCity med ett Id som finns i listan och skriv ut namnet på objektet på formatet: 
**name - county**, för första objektet skulle det se ut så här **Västerås - Västmanland**.
