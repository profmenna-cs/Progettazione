---
marp: true
theme: default
---

# Progettazione concettuale
## Studiamo un'applicazione web

---

# Obiettivo

Impariamo ora quali sono i passaggi per la progettazione di un'applicazione web. Lo faremo studiando un applicazione web esistente... magari ci scappa anche uno spuntino!

---

# Applicazione web a tre livelli

Questa è la struttura tipica di un'applicazione web:

![h:400 center](img/Architettura%20tre%20livelli.svg)

---

# Livello presentazione

I dati sono presentati all'utente attraverso viste, costituite da una o più pagine web con cui l'utente può interagire.

Le viste sono realizzate con i tipici strumenti per lo sviluppo web lato client: 
- HTML: struttura della pagina
- CSS: aspetto della pagina
- JS: interattività, validazione dati lato client
- React, Vue, Angular: framework lato client

---

# Livello applicazione

Costituisce un ponte tra i dati e la loro presentazione. Riceve e valida dati utenti, interroga o aggiorna il database, gestisce aspetti quali autenticazione e autorizzazione.

Implementato in un linguaggio web server side (ad esempio PHP). Le sue applicazioni sono eseguite dal web server quando l'utente richiede la visualizzazione di una vista.

---

# Livello dati

