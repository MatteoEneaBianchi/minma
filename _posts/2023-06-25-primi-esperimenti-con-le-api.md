---
layout: post
title:  "I miei primi esperimenti con le API"
date:   2023-06-25
categories: Informatica
---

Da quando ho iniziato a curiosare più a fondo nel mio sito WordPress, mi sono accorto che dietro a tutto quel pannello di gestione c’è molto di più. Una cosa che mi ha colpito è il fatto che WordPress espone una **REST API** che ti permette di interrogare direttamente il sito... senza nemmeno aprire l’admin.

Così ho deciso di fare qualche esperimento.

Ho iniziato accedendo agli endpoint predefiniti di WordPress, tipo `/wp-json/wp/v2/posts`, per vedere se riuscivo a ottenere i dati del blog in formato JSON. È stato strano ma affascinante vedere i contenuti del mio sito **fuori dal sito**, direttamente in formato "grezzo". Da lì ho capito che l’API è come un ponte tra il database e il mondo esterno, e che si possono creare interazioni anche fuori dal tema WordPress stesso.

Ho anche provato a capire cosa succede dietro le quinte, guardando dentro il database tramite **phpMyAdmin**, e notando come ogni post, pagina o impostazione venga salvata in tabelle ben precise, come `wp_posts`, `wp_postmeta`, `wp_users`, ecc. Le API fondamentalmente leggono (e se vuoi, scrivono) proprio da lì.

Non ho ancora usato le API per modificare contenuti (voglio prima capirle bene), ma penso che sia uno strumento potentissimo da usare in futuro. Magari per creare una dashboard personalizzata, o un'app che si collega direttamente al sito.

Questi primi test mi hanno fatto vedere WordPress in modo diverso: non solo come CMS, ma come base su cui costruire cose nuove.

