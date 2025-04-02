# Interactive Functionality

Ontwerp en maak voor een opdrachtgever een interactieve toepassing die voor iedereen toegankelijk is

De instructie vind je in: [INSTRUCTIONS.md](https://github.com/fdnd-task/the-web-is-for-everyone-interactive-functionality/blob/main/docs/INSTRUCTIONS.md)


## Inhoudsopgave

  * [Beschrijving](#beschrijving)
  * [Gebruik](#gebruik)
  * [Kenmerken](#kenmerken)
  * [Installatie](#installatie)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Beschrijving
Ik heb een voor mijn opdrachtgever Tumi Mundo een all-stories page, en een detail pagina die naar een unieke story leid.
<img src="/public/IMG/readme.png">
Hier de pagina: https://the-web-is-for-everyone-interactive-xyib.onrender.com/

## Gebruik
<!-- Bij Gebruik staat de user story, hoe het werkt en wat je er mee kan. -->
Ik heb een post-route aangemaakt waarmee ik via een profile een playlist kan liken. Deze playlist gaat na het klikken op de likeknop van de suggested playlists naar de liked playlists. 

Ik heb hiervoor een userstory geschreven: 
<img src="/public/IMG/userstory.png" height="100">

en een wireflow gemaakt:
<img src="/public/IMG/wireflow.png" height="200" width="100">

## Kenmerken
In mijn project heb ik een interactieve webapplicatie gebouwd met Node.js, Express, Liquid, Directus en client-side JavaScript. Daarnaast heb ik natuurlijk ook HTML en CSS gebruikt 

Node.js & Express: Express wordt gebruikt om routes te definiëren en de serverfunctionaliteit te beheren.

Liquid: Hiermee render ik dynamische content in mijn HTML-pagina’s.

Directus: Dit headless CMS levert de playlists en likes via een REST API.

Client-side JavaScript: Zorgt voor interactieve elementen, zoals het liken van playlists zonder herladen.

## Installatie
Als je de repository zelf wil installeren zou je eerst via github de repository kunnen forken en clonen. Daarna zou je via de terminal npm install moeten typen dan worden alle bestanden geinstalleerd. Daarna doe je npm start en dan kan je via localhost:8000 aan je website werken.

## Bronnen
Ik heb meerdere bronnen gebruikt vooral uit de directus database zoals:
https://fdnd-agency.directus.app/items/tm_likes 
https://fdnd-agency.directus.app/items/tm_playlist
https://fdnd-agency.directus.app/items/tm_story

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
