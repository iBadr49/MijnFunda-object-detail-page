> _Fork_ deze leertaak en ga aan de slag. Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. De instructie vind je in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)

# Mijn "Funda" Object detail page 

> <img src="https://github.com/iBadr49/MijnFunda-object-detail-page/assets/112857932/30ca9e1e-9fb1-4f85-bf2b-c13961224da9" width="30%">

## Beschrijving

Ik heb voor mijn opdrachtgever bij Funda een objectdetailpagina ontwikkeld, met de primaire focus op de mobiele gebruikerservaring.

## Kenmerken
<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met JS gedaan en hoe? -->

Zie hieronder stukje code hoe ik een __Accordion__ met JavaScript heb gemaakt.

```Js
var acc = document.getElementsByClassName("accordion");
var i;

for (i = 0; i < acc.length; i++) {
  acc[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var panel = this.nextElementSibling;
    if (panel.style.display === "block") {
      panel.style.display = "none";
    } else {
      panel.style.display = "block";
    }
  });
}
```
## Bronnen

Funda (Voorbeeld) - https://www.funda.nl/koop/oss/huis-42059908-zwingelstraat-25/ <br>
Swiper - https://swiperjs.com/ <br>
W3S - https://www.w3schools.com/  <br>
MDN Web docs - https://developer.mozilla.org/en-US/

## Licentie

![GNU GPL V3](https://www.gnu.org/graphics/gplv3-127x51.png)

This work is licensed under [GNU GPLv3](./LICENSE).
