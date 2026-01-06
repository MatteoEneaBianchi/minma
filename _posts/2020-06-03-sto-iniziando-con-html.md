---
layout: post
title:  "Sto iniziando a capire l'HTML (e un po' di CSS)"
date:   2020-06-03
categories: Informatica
---

Da qualche giorno mi è venuta la curiosità di capire come funzionano i siti web, tipo cosa c’è dietro quando apri una pagina su internet. All’inizio pensavo fosse una cosa super complicata, tipo roba da esperti, ma poi ho scoperto che si può iniziare con qualcosa di semplice: l’HTML. Ho guardato qualche video e letto due guide online, e ho provato a scrivere il mio primo file `.html`. È strano ma anche bellissimo vedere che se scrivi `<h1>` poi ti esce un titolo gigante sullo schermo! 😄 Ho anche scoperto che c’è il CSS, che ti fa cambiare i colori, i font, puoi mettere lo sfondo, fare tutto più carino... e sto provando a combinare le due cose insieme. Non è facile ma è una figata!

Adesso sto cercando di fare una mia mini-pagina personale, tipo con il mio nome, una descrizione, qualche immagine e magari qualche link. Mi piace l’idea che tutto questo sia fatto solo scrivendo del testo, senza programmi strani. Per ora è tutto molto semplice, tipo un foglio con un po’ di scritte e colori, ma già mi emoziona. Ecco un esempio di quello che ho scritto:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>La mia prima pagina</title>
    <style>
      body {
        background-color: #f0f0f0;
        font-family: sans-serif;
      }
      h1 {
        color: darkgreen;
      }
    </style>
  </head>
  <body>
    <h1>Ciao, sono Gabriel!</h1>
    <p>Questa è la mia prima pagina web fatta con HTML e un po' di CSS.</p>
    <a href="https://www.youtube.com">Vai su YouTube</a>
  </body>
</html>
