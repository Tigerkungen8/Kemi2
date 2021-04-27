# Kemi 2
Syftet med detta repo är att dela den information jag (?) har fått upp, antingen genom att läsa boken eller lyssnat på föreläsningarna, i kursen Kemi 2 när jag själv studerade inför prov (specifikt kap4-kap5). Hur man använder detta är upp för en själv. Ett komplement till boken och läraren, ett sätt att checka upp på ett visst begrepp eller bara något kul att ladda ner och se hur de olika begreppen passar ihop med varandra med Graph View, finns egentligen många saker.

## Använding?
Så, hur är detta byggt, och hur kan du använda detta? Jag skrev allt detta med ett program som heter [Obsidian](https://www.obsidian.md), vilket jag rekomendarar att du laddar ner, det är ett fantastiskt, *gratis* (för tillfället) verktyg för att skriva digitala anteckningar. Hur man laddar ner det och allt det finns på webbsidan (utan problem för alla OS:s förutom ChromeOS, står mer där). 

Här är hur du ska då ladda ner projektet:
1. Ladda ner Kemi2-repot genom att ladda ner en ZIP-fil.
2. Unzipa filen (självklart för de flesta system, men ifall du har en Chromebook, läs nästa *subheading*).
3. Nu har du alla filer! Nu är det enda som krävs att du lägger de filerna i ett speciellt folder (som Obsidian också har tillgång till). Sedan öppnar du upp Obsidian, där det kommer upp en flik om du vill "Open  folder as vault", "Create new vault" eller "Open help vault". Du kan skippa help-vaultet för tillfället.  
4. Eftersom att detta är endast *Markdown*-filer och folders behöver du bara trycka på "Open folder as vault", där du sedan väljer "Kemi2-main". Nu har du Obsidian uppe för Kemi2.

**Mindre anmärkning:** När du laddar ner detta kommer du automatiskt få min *theme*, den så kallade "ITS Theme". Detta kan du dock ändra genom att klicka på kugghjulet till vänster, öppna upp "Appereance" och sedan "Browse" för *community themes*. Du kan välja themes ifall du klickar på knappen ovanför Browse där det förmodligen står "ITS Theme" eller också "None". 

I alla fall, alla dessa anteckningar är byggd på ett "språk" som heter "Markdown", vilket är ett extremt lätt språk att lära sig (kunde inte det förrens jag laddade ner programmet, blev "flytande" nästan direkt efter) då det enda man använder är vanliga bokstävet och några tecken som stjärnor (\*) och hashtags (\#) för att skapa headers samt *italic* och **bold** text. Du kan även hitta lite $\LaTeX$-kod men det bara skapar fina ekvationer, som du lätt kan se om du trycker *Ctrl + E* då [Obsidian](https://www.obsidian.md) läser igenom det och "skapar" de fina reaktionerna. (Innebär att vilken Markdown-editor som helst kan läsa dessa filer).

Detta *repo* består av ca 130 filer, som är linkade med varandra på speciellt sätt med \[[]] som har namnet på andra filer. Man kan se hur kopplade visa filer som [[Kolhydrater]] eller [[Fetter]] är genom att trycka *Ctrl + G*, vilket öppnar "Graph View".

## Chromebook Obsidian
Eftersom att de flesta studenter som jag känner använder Chromebook samt ChromeOS, så måste jag skriva en guide till hur man ska ladda ner detta Obsidian för Chromebooks, så att detta projekt kan faktiskt bli användbar. 

0. (Ifall du redan har laddat ner Linux på din chromebook, skippa detta steg). För att ladda ner Linux på din dator behöver du gå in i "Inställningar", sedan gå in i "Utvecklare", sedan "Sätt på" för Linux (Beta).
1. Ladda ner Obsidian. Detta gör du genom att gå till deras webbsida ([Obsidian](https://obsidian.md/download)) och väljer ladda ner Obsidian **AppImage** (måste ta det, flat och snap är andra sätt som jag inte visar i denna *README*). Sedan flyttar du *AppImagen* till "Linux-filer", som du ska ha fått när du laddade ner Linux.
2. Nu ska du göra *AppImagen* till en *executable* genom att öppna upp terminalen (om du flyttade Obsidian-filen till Linux-filen ska den automatiskt vara "nåbar" i terminalen, vilket du kan testa genom att skriva "ls" och se Obsidian-filen) och skriv detta:

```
$ chmod a+x Obsidian*.AppImage
```
*Där \* står för fil-versionen. Kan slippa skriva siffrorna genom att trycka TAB*.

3. Nu kan du "aktivera" filen/*executablen* genom att skriva: 
```
$ ./Obsidian*.AppImage
```
*Kom dock ihåg att det är terminalen som kör Obsidian, så stänger du terminalen, så stänger du ner hela programmet.*
### Troubleshooting
4. Ifall du får ett fel där det står något i typen av detta:
```
...: error while leadng shared libraries: libnss3.so: cannot open shared object file: No such file or directory
```
Då ska du skriva detta:
```
$ sudo apt install libnss3-dev
```

Detta borde kunna fixa problemet. Testa att skriva om ./Obsidian*.AppImage, och så borde Obsidian-launchern öppnas upp.

### Fortsättning/Unzip
Ifal du har laddat ner Obsidian kan du nu ladda ner Kemi2 från Github, vilket det står mer om under *headingen* "Användning?". Ifall du vill unzippa filerna så går du in i "Filer" för chromebook, öppnar upp nedladdningar där ZIP:en kom, klicka på den, du kommer då se "Kemi2-main". Kopiera det foldret, gå ut ur "Kemi2-main.zip", klistra in "Kemi2-main" in i Linux-filerna (måste för att Obsidian ska få tiillgång till de) och boms, nu har du filerna unzippade och Obsidian kan nu skapa ett nytt vault.

## Open Source?
För tillfället så har jag det "closed", då jag inte är van med *Github* ännu. Skulle såklart vara hjälpsamt med eldsjälar som ville hjälpa till och utöka kunskapen, kanske genom att skapa nya filer, eller genom att utöka/korrektera de filer som redan finns som är väldigt tunna med information, som t.ex [[Aromatiska]]. Framtiden får säga vad jag gör.

## Egen kommentar/Försiktighet
**OBS:** Jag är en student som läser kemi 2, inte en pedagog/lärare som kan detta ämne väl. Begreppen som förklaras har jag skrivit för mig själv och att jag laddar upp detta är mer av en eftertanke som ett sätt att möjligen hjälpa studenter, inte för att göra någonting seriöst med detta. Ifall du misslyckas med ett prov för att jag inte förklarade ett begrepp på rätt sätt, eller tillochmed förklarade det fel, så är det ditt fel att du lyssna på en random kille på internet. Detta är endast ett kul projekt för mig för att lära mig lite om [Github](https://github.com).

En annan mindre kommentar är att *.obsidian*-filen är bara ett text-dokument som innehåller *themen* jag använder för Obsidian.