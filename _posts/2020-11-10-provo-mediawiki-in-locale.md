---
layout: post
title:  "Ho provato a usare MediaWiki in locale!"
date:   2020-11-10
categories: Informatica
---

In questi giorni mi è venuta una pazza idea: **e se provassi a fare un mio mini-Wikipedia?** 😂 Allora ho scoperto che il software che usa Wikipedia si chiama **MediaWiki**, e si può **scaricare e installare in locale**! Non è proprio semplicissimo come aprire un file `.html`, ma mi sono divertito un sacco a provare.

Per farlo andare ho dovuto installare un po’ di cose, tipo **PHP**, **MySQL** (o MariaDB), e un server tipo **Apache**. Io ho usato **XAMPP**, che ha già tutto dentro. Poi sono andato sul sito di MediaWiki, ho scaricato l’ultima versione, l’ho messa nella cartella `htdocs`, e ho seguito la configurazione nel browser. Dopo qualche tentativo (e un paio di errori 😅), sono riuscito ad aprire la mia *wiki* personale su `localhost`. È stato un momento bellissimo!

Il bello è che funziona proprio come Wikipedia, cioè puoi creare pagine, modificare il contenuto, usare il **wikitext** (tipo `== Titolo ==` per fare titoli, o `[[link]]` per creare collegamenti tra le pagine), e tutto resta salvato nel database. Non ho fatto un sito pubblico ovviamente, è solo sul mio PC, ma mi ha fatto capire come funzionano dietro le quinte quei siti giganti pieni di contenuti.

Adesso sto provando a creare una mia wiki con argomenti che mi piacciono, giusto per imparare. Magari più avanti provo a personalizzare lo stile o ad aggiungere estensioni. Per ora è già una figata poter scrivere tipo:

```wikitext
== Benvenuto sulla mia Wiki ==
Questa è una pagina di test. [[Clicca qui]] per andare a un'altra pagina!
