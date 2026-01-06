---
layout: post
title:  "A cosa serve un database? L'ho capito solo dopo averlo rotto"
date:   2023-08-05
categories: Informatica
---

All’inizio, quando sentivo parlare di **database**, pensavo fosse una roba da sviluppatori avanzati, sistemisti o da chi gestiva grandi portali. Poi ho iniziato a lavorare con WordPress, a esplorare i file, i contenuti e… inevitabilmente sono arrivato a **phpMyAdmin**.

E da lì, tutto è cambiato.

Un giorno, mentre provavo a capire meglio come erano strutturati i dati nel mio sito WordPress, sono finito dentro la tabella `wp_posts`. Ho visto titoli, contenuti, slug, ID... ed ero affascinato dal fatto che tutto quello che vedevo online passava **da lì sotto**.

Preso dall'entusiasmo, ho provato a fare qualche modifica manuale. Cambiare un titolo direttamente nel database. Funzionava! Mi sembrava di avere il "potere assoluto" sul sito, senza nemmeno entrare nel pannello di WordPress.

Finché… non ho fatto danni.

Non ricordo esattamente cosa ho toccato (credo una `JOIN` sbagliata o una cancellazione impulsiva), ma il risultato è stato che il sito ha smesso di caricare correttamente i post. Alcune pagine erano bianche, altre davano errore. In quel momento ho capito davvero **quanto tutto gira attorno al database**, anche se spesso te ne dimentichi.

Dopo qualche panico, backup e ricerca, sono riuscito a sistemare. Ma da quel momento ho preso più sul serio l’importanza del database: **è il cuore pulsante del sito**, non si vede, ma se si ferma lui si ferma tutto.

Adesso prima di toccare qualcosa faccio sempre un backup, e ho iniziato anche a tenere una copia esportata del database, giusto per sicurezza. È stata una lezione importante: smanettare va bene, ma **capire cosa si sta facendo prima di cliccare "esegui" è fondamentale**.

E se mi chiedessero oggi “a cosa serve un database?”, risponderei senza esitazioni:  
> “A far vivere il tuo sito. Anche se te ne accorgi solo quando non funziona più.”

