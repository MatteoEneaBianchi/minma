---
layout: post
title:  "Ho usato PHP per fare login e logout"
date:   2023-12-15
categories: Informatica
---

Di recente ho deciso di imparare come funziona un sistema di **login e logout** in un sito web. Ovviamente, ho scelto di farlo usando **PHP**, visto che è uno dei linguaggi più usati per gestire la logica lato server.

Ho iniziato con la creazione di un semplice form di login, con un campo per l'email e uno per la password. Il primo passo è stato creare una tabella nel database per salvare gli utenti. Ho capito che, oltre ai dati come nome e email, bisogna pensare anche alla sicurezza, quindi ho fatto attenzione a **criptare** la password con `password_hash()`, in modo che, anche se qualcuno accedesse al database, non avrebbe potuto vedere le password in chiaro.

Poi ho scritto il codice PHP per verificare se l'utente che si sta connettendo esiste già nel database. Se sì, verifico se la password inserita corrisponde a quella salvata. Se tutto va bene, viene creata una sessione con `session_start()`, che mi permette di **mantenere l'utente loggato** durante la navigazione.

Per il logout, ho usato un semplice link che distrugge la sessione con `session_destroy()`, e così l'utente viene disconnesso dal sito.

Cosa mi ha sorpreso? È stato bello vedere come PHP gestisce tutto il processo, dalla verifica dei dati nel database alla gestione delle sessioni. Ma ho anche capito che, quando si parla di login, la sicurezza è **fondamentale**. Ho iniziato a leggere anche su altre pratiche come **l'uso di HTTPS** e la protezione contro le **SQL injection**, che sono temi su cui voglio approfondire in futuro.

Adesso, con questo sistema di login e logout funzionante, posso iniziare a fare altre cose più avanzate, come la gestione degli utenti nel pannello admin del mio sito.

