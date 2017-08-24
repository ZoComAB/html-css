# Lägg till CSS

CSS kan läggas till på flera olika sätt. Men det vanligaste sättet man lägger till det är att lägga en länk i `<head>`-taggen och sättet man skriver det på ser alltid likadant ut.

1. I din mapp `html-intro`: skapa en ny fil som heter `style.css`
2. Lägg till detta __stylesheet__ genom att länka till det i `<head>`-taggen. Istället för `<a>`-taggen för att länka använder vi `<link>`-taggen men vi behöver fortfarande `href`-attributet för att länka in:

```html
<html>
    <head>
        <title>Min sida</title>
        <link rel="stylesheet" href="style.css" />
    </head>
    <body>

    </body>
</html>
```

`<head>` var som sagt till för metadata, här länkar vi in en fil som ska användas av vårt dokument men som inte är del av själva innehållet. Filen säger bara till HUR sidan ska se ut, inte vilket innehåll den har.

Attributet `rel` är där för att få vår webbläsare att förstå att det är ett stildokument, en `.css`-fil. Det finns mycket annat vi kan tänka oss att länka in så det är bra att vara tydlig.