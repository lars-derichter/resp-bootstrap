# 📘 Bootstrap start HTML
## CSS framework

Bootstrap is een open source CSS framework. Een CSS framework is een verzameling CSS-stijlen en meestal ook Javascript-componenten die helpen om snel een website te maken.

In hun eigen woorden:

>Quickly design and customize responsive mobile-first sites with Bootstrap, the world’s most popular front-end open source toolkit, featuring Sass variables and mixins, responsive grid system, extensive prebuilt components, and powerful JavaScript plugins.

## Installeren

Je kan Bootstrap downloaden van [www.getbootstrap.com (Koppelingen naar een externe site.)](http://www.getbootstrap.com/) of ernaar verwijzen met een link-tag vanuit je head.

Omdat het vrij grote files zijn, gaan we ervoor kiezen om van de CSS-file (en JavaScript file) een lokale kopie te gebruiken en die in een lokale CSS directory in je ontwikkelomgeving te bewaren. (Anders moeten ze bij elke reload van je pagina opnieuw geladen worden over het netwerk.)

Om Bootstrap dan te gebruiken in je HTML pagina, heb je een verwijzing nodig naar de Bootstrap-stylesheet. We gebruiken best **bootstrap.min.css**. Dit is de geminimaliseerde versie en bevat alle CSS onderdelen van bootstrap. Als je ook wil gebruik maken van de Bootstrap JavaScript functionaliteit, zal je daarvoor ook de nodige referentie moeten voorzien in je HTML pagina.

Als je uiteindelijk je web-pagina on-line gaat plaatsen, kan je wel best je lokale referentie veranderen en wijzen naar een Content Distribution Network site, bijvoorbeeld :

```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-rbsA2VBKQhggwzxH7pPCaAqO46MgnOM80zW1RWuH61DGLwZJEdK2Kadq2F9CUG65" crossorigin="anonymous">
```

Als je ook de Javascript functionaliteiten wil (bijv. voor de uitklapbare navbar), voeg je de volgende lijn toe vlak voor je de body-tag sluit:

```html
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-kenU1KFdBIe4zVF0s0G1M5b4hcpxyD9F7jL+jjXkk+Q2h455rYXK/7HAuoJl+0I4" crossorigin="anonymous"></script>
```

## Voor en nadelen

Front-end frameworks zoals Bootstrap hebben een aantal sterktes, maar ook een aantal zwakke punten..

<table style="border-collapse: collapse;">
    <tbody>
        <tr style="height: 28px;">
            <td style="width: 50.0043%; height: 28px;"><strong>Voordelen</strong></td>
            <td style="width: 50.0043%; height: 28px;"><strong>Nadelen</strong></td>
        </tr>
        <tr style="height: 28px;">
            <td style="width: 50.0043%; height: 28px;">Snel een good enough design</td>
            <td style="width: 50.0043%; height: 28px;">Sites lijken allemaal op elkaar / Saai.</td>
        </tr>
        <tr>
            <td style="width: 50.0043%;">Weinig of geen eigen CSS nodig</td>
            <td style="width: 50.0043%;">Divitis en classitis</td>
        </tr>
        <tr style="height: 28px;">
            <td style="width: 50.0043%; height: 28px;">Eenvoudiger dan CSS (als alles goed gaat toch)</td>
            <td style="width: 50.0043%; height: 28px;">Veelvuldig gebruik van class leidt tot vermenging structuur en design (tight coupling)</td>
        </tr>
        <tr style="height: 28px;">
            <td style="width: 50.0043%; height: 28px;">Responsive Design/Mobile First is ingebakken</td>
            <td style="width: 50.0043%; height: 28px;">Geen controle over break points</td>
        </tr>
        <tr style="height: 28px;">
            <td style="width: 50.0043%; height: 28px;">Veel herbruikbare componenten</td>
            <td style="width: 50.0043%; height: 28px;">Minder flexibel dan zuivere CSS</td>
        </tr>
    </tbody>
</table>

Dit gezegd zijnde, Bootstrap is één van de populairste en meest gewaardeerde projecten op Github en miljoenen sites gebruiken het. Je maakt er misschien niet de mooiste of meest innovatieve designs mee, maar voor de meeste sites en apps is het goed genoeg. Het design dat je met Bootstrap krijgt is vaak veel beter dan wat de gemiddelde programmeur zelf kan ontwerpen.

## Versie

Op dit moment is versie 5.2 de standaard versie. We zullen die dus ook gebruiken en aanleren. Het is natuurlijk mogelijk dat je in je werk of bij het werkplekleren geconfronteerd zal worden met oudere of nieuwere versies. Die zullen lichtjes afwijken van deze versie, maar de basisprincipes blijven wel altijd dezelfde. Bootstrap voorziet tussen major versies telkens ook documentatie hoe je een bestaande site zou kunnen migreren naar de nieuwere versie van Bootstrap. Bijv. [Migrating to v5.](https://getbootstrap.com/docs/5.1/migration/) Rechtsbovenaan op de documentatiepagina’s heb je bovendien een menu om naar de documentatie van andere versies te navigeren.

## Andere CSS frameworks

Bootstrap is niet het enige front-end framework en ook niet het oudste.

[Foundation](https://get.foundation/), [Materialize](https://materializecss.github.io/materialize/) en [Tailwind](https://tailwindcss.com/) zijn een paar andere voorbeelden, waar je misschien ooit mee te maken zal krijgen. Het principe is bij al deze frameworks wel gelijklopend: goede typografie en kleuren voor de meeste basis-elemnten, een responsive grid-systeem om elementen makkelijk te positioneren en een aantal voorgedefinieerde componenten die je kan hergebruiken (navigatiebalken, accordeons, ‘cards’ …
