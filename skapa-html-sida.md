# Skapa en första HTML-sida

### Verktyg

Du behöver två saker för att kunna köra en sida, en **textredigerare** samt en **webbläsare**. Vilken textredigerare som helst fungerar egentligen men det finns vissa som föredras av webbutvecklare eftersom de har en del verktyg inbyggda som vanliga textredigerare saknar. Samma sak gäller med webbläsare.

* **Textredigerare**
  * [_Atom_ skapad av GitHub](https://atom.io/)
  * [_Visual Studio Code_ skapad av Microsoft](https://code.visualstudio.com/)
  * [_Sublime Text_ skapad av glada entusiaster](https://www.sublimetext.com/)

* **Webbläsare**
  * [_Chrome_ skapad av Google](https://www.google.com/chrome/browser/desktop/index.html)
  * [_Firefox_ skapad av Mozilla](https://www.mozilla.org/en-US/)
  * [_Edge_ skapad av Microsoft](https://www.microsoft.com/en-us/windows/microsoft-edge)

Ladda ner någon av ovan genom att gå till deras hemsida och tryck på **Download**, brukar oftast vara en stor grön knapp. Installera sedan den textredigeraren du laddat ner och starta den.

### Skapa en sida

Det __varje__ sida behöver och det första man kommer till när man besöker en hemsida är filen `index.html`. Den ska vi nu skapa.

1. Skapa en ny mapp som heter `html-intro`
2. I den mappen, skapa en fil som heter `index.html`
3. Öppna `index.html` med textredigeraren som du laddade ner och installerade innan detta.
4. Lägg till följande kod i dokumentet framför dig, dv.s. `index.html:

```html
<html>
  <head>
  </head>
  <body>
  <body>
<html>
```

_`<html>`-taggen indikerar att innehållet är `html`, vårt **Markup Language**. Inuti `<head>` hamnar all **"metadata"**, all extra information kring hur sidan ska visas upp etc. Det mesta vi kommer att göra kommer dock att ligga inuti `<body>`-taggen. Det är där allt som är synligt på sidan hamnar._
5. Lägg till följande tagg inuti `<head>`-taggen:

```html
<title> Första sidan </title>
```

Fråga: _Varför lägger vi denna kodrad i `<head>` och inte i `<body>`? Var visas texten upp på sidan?_
 
Svar: Texten visas inte upp på själva sidan, inuti dokumentet. Texten visas som en överskrift på den tabb som vi har öppen i webbläsare. Därför ska texten inte ligga i `<body>`.

### Sammanfattning

Varje hemsida måste ha en `<html>`-tagg som innehåller en `<head>`-tagg och en `<body>`-tagg. Detta stämmer för alla hemsidor i hela världen!

**Nu har vi faktiskt en fungerande hemsida, dock så har vi inget innehåll men det löser vi i nästa uppgift!**