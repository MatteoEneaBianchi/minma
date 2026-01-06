---
layout: post
title:  "Ho trasformato il mio vecchio PC in un piccolo server!"
date:   2020-12-02
categories: Informatica
---

Qualche giorno fa ho guardato il mio vecchio computer del 2014 (che era lentissimo e non lo usavo più da un sacco) e mi sono chiesto: **"ma posso farci qualcosa di utile?"**. E boom! Mi è venuta l’idea di trasformarlo in un **mini server casalingo**, almeno per fare esperimenti. 😄 Non tipo server da internet, eh, ma una cosa semplice: **una cartella condivisa in rete** che posso aprire anche dal mio portatile.

Il PC ha ancora **Windows 7**, quindi non ho dovuto installare niente di strano. Ho semplicemente creato una cartella (l’ho chiamata `ServerCondiviso`), ci ho messo dentro dei file di test (tipo HTML, immagini, appunti), poi ho fatto clic destro > **Proprietà** > **Condivisione** > **Condividi...** e ho scelto “Tutti” con permesso di lettura e scrittura. Poi, nel mio portatile, ho aperto **Esplora file**, ho scritto `\\NOMEDELPC\ServerCondiviso` nella barra in alto… e ha funzionato! 😮

Ora posso spostare file da un computer all’altro senza chiavette USB, oppure testare i miei progetti HTML/CSS direttamente da lì, come se fosse una specie di server *finto* solo mio. Ovviamente non è veloce come un vero server, ma per provare e imparare va benissimo. Sto anche pensando di metterci dentro qualche progetto fatto con MediaWiki o HTML per vedere come si comportano se li "servo" da lì, oppure magari usarlo per backup. La cosa bella è che **sto imparando a usare quello che ho**, anche se vecchio, per fare cose nuove.

Prossimo passo? Magari provo a metterci **un server web tipo XAMPP** o **un piccolo NAS**. Chissà! Per ora, questo mio "serverino" mi basta per sentirmi un po’ hacker in casa. 💻📡😎
