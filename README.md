# 🎣 Inglés con Buddy

**Een gratis app om Engels te leren op A1-niveau, gemaakt voor Spaanstalige vrienden.**

👉 **Speel hier:** https://sylvievvv.github.io/ingles-con-buddy/

<p align="center">
  <img src="media/demo.gif" alt="Demo van Inglés con Buddy op een telefoon" width="300">
</p>

<p align="center"><a href="https://sylvievvv.github.io/ingles-con-buddy/media/demo.mp4">▶️ Bekijk de demo als video (mp4)</a></p>

---

## Het verhaal

Een paar Spaanse vrienden van mij wilden Engels leren. Ze probeerden apps zoals Duolingo, maar vonden de betaalde abonnementen te duur. Daar kwam nog iets bij: hun grootste probleem was de **uitspraak**. Veel Engelse klanken bestaan in het Spaans niet, of klinken daar hetzelfde, en daar besteden de meeste apps weinig aandacht aan.

Daarom heb ik zelf een app voor ze gemaakt: **gratis, zonder reclame, zonder account**, en speciaal gericht op wat Spaanstaligen lastig vinden in het Engels.

## Het probleem en de oplossing

| Probleem | Oplossing in de app |
|---|---|
| Abonnementen op taalapps zijn duur | Helemaal gratis. Het is één webpagina die op elke telefoon werkt, zonder installatie of account. |
| Beginners kennen nog geen Engels, dus Engelse uitleg helpt niet | Alle uitleg, knoppen en tips zijn in het **Spaans**. |
| In het Spaans klinken V en B hetzelfde, en de H spreek je niet uit | Een apart onderwerp **"Sonidos del inglés"** met luisteroefeningen (minimal pairs). |
| Je hoort het verschil niet als je de taal nog niet kent | Eerst beide woorden apart beluisteren, de belangrijke letters gemarkeerd, en een hint over de mondstand (*"dientes sobre el labio"*). |
| Gesproken Engels gaat te snel | Elke zin heeft een 🔊-knop en een 🐢-knop om hem langzaam te horen. |
| Fouten maken voelt ontmoedigend | Buddy blijft positief. Wie iets fout heeft, krijgt een korte tip en de vraag komt later terug. |

## Wat zit erin

- **Buddy**, een vrolijke stier met een vissershoedje en een hengel. Hij springt op bij een goed antwoord en schudt zijn hoofd bij een fout.
- **6 onderwerpen op A1-niveau**: begroeten, getallen en tijd, familie, eten en drinken, dagelijkse routine, en de stad en de weg vragen. Elk onderwerp heeft 3 hoofdstukken van 8 vragen.
- **Uitspraak**: V/B, de L aan het eind, TH, de H, korte en lange klinkers, S aan het begin (geen "eschool"), SH/CH, J/Y en medeklinkers aan het eind.
- **Soorten vragen**: meerkeuze, zelf typen, zinnen bouwen met blokjes, luisteren, en woorden koppelen.
- **Woordoefeningen** waarbij nieuwe woorden binnenkomen en eerder geleerde woorden terugkomen ter herhaling.
- Tik op een Engelse zin om de Spaanse vertaling te zien.
- 5 levens per les, XP, een dagenreeks 🔥 en voortgangsstreepjes per hoofdstuk.
- Je kunt zelf een Engelse stem kiezen (🗣️ Voz).
- Alle hoofdstukken zijn meteen open, je hoeft niets vrij te spelen.

<p align="center">
  <img src="media/screenshot-home.png" alt="Beginscherm met Buddy" width="230">
  <img src="media/screenshot-les.png" alt="Een vraag in een les" width="230">
  <img src="media/screenshot-uitspraak.png" alt="Uitleg over de V en B" width="230">
</p>

## Hoe het werkt (techniek)

- Eén bestand: [`index.html`](index.html), met HTML, CSS en JavaScript. Er is geen framework en geen server nodig.
- **Stem**: de ingebouwde spraakfunctie van de browser (Web Speech API). Welke stem je hoort, hangt dus af van je telefoon. Op een iPhone klinken de "Premium"- of "Verbeterd"-stemmen het natuurlijkst.
- **Voortgang** wordt opgeslagen in de browser (`localStorage`) op het toestel zelf. Er wordt niets verstuurd.
- Gehost met **GitHub Pages**.

## Para jugar 🇪🇸

1. Abre **https://sylvievvv.github.io/ingles-con-buddy/** en Safari o Chrome.
2. En el iPhone: pulsa *Compartir* → *Añadir a pantalla de inicio* para tenerlo como una app.
3. Sube el volumen: pulsa 🔊 para escuchar y 🐢 para escuchar despacio.
4. ¡Un poquito cada día! 🎣

---

Gemaakt met ❤️ voor mijn Spaanse vrienden.
