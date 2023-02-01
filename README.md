> _Fork_ deze leertaak en ga aan de slag. Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. De instructie vind je in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)

# Mijn "Funda" Object detail page 
<!-- Geef je project een titel en schrijf in één zin wat het is -->

## 📚 Inhoudopgave

  * [Opdracht](#opdracht)
  * [Beschrijving](#beschrijving)
  * [Kenmerken](#kenmerken)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)
  
## Opdracht
Het object/product __"Funda"__ pagina herbouwen.

## Beschrijving
<!-- In de Beschrijving staat hoe je project er uit ziet, hoe het werkt en wat je er mee kan. -->
<!-- Voeg een mooie poster visual toe 📸 -->
<!-- Voeg een link toe naar Github Pages 🌐--> 
📸 - __Mobiele Versie__

<img src="https://user-images.githubusercontent.com/112857932/214675583-d1c51cb5-cd39-4554-bbc8-138abd9c5bdd.jpeg" width="20%">   <img src="https://user-images.githubusercontent.com/112857932/214676657-4421252b-ffa3-4485-b559-667464731395.jpeg" width="20%">  <img src="https://user-images.githubusercontent.com/112857932/214676710-2ce8ac05-db03-487c-9cf7-7113761a0466.jpg" width="20%">  <img src="https://user-images.githubusercontent.com/112857932/214676760-218acfc2-6c6b-4cd6-97d6-63fce3e16280.jpg" width="20%">

📸 - __Desktop Versie__

<img src="https://user-images.githubusercontent.com/112857932/214679027-7ea029ea-d00a-44b2-aeb7-e1e267aa88c5.png" width="100%">

🌐 - __Mijn Funda Versie "link"__ - https://ibadr49.github.io/MijnFunda-object-detail-page/


## Kenmerken
<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met JS gedaan en hoe? -->

Zie hieronder stukje code hoe ik een __Accordion__ met JavaScript heb gebruikt.

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
