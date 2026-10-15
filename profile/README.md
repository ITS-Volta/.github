# 📘 Corso UF 13.3 - Dispositivi Medici Software, App e mHealth

**Docente:** Ing. Alessandro Pellegrino  
**Anno formativo:** 2026/2027  
**Durata complessiva:** 60 ore  
**Stato aggiornamento:** 15 ottobre 2026

---

## 🧭 Obiettivi e programma del corso

Il corso introduce alla progettazione e allo sviluppo di **dispositivi medici software (SaMD)** attraverso un percorso orientato al lavoro, che integra aspetti normativi, ingegneria del software e laboratorio pratico.

Gli studenti impareranno a partire da uno scenario clinico, definire una **destinazione d'uso**, raccogliere requisiti verificabili, progettare un'architettura, sviluppare un prototipo e documentare le scelte effettuate.

### Argomenti principali

- **Normativa e qualità:** Regolamento (UE) 2017/745 (MDR), qualificazione e classificazione del software medicale, IEC 62304, ISO 14971, ISO 13485, IEC 82304-1 e linee guida MDCG.
- **Analisi dei requisiti:** stakeholder, elicitation, requisiti utente, funzionali, non funzionali, di sicurezza e regolatori, SRS e tracciabilità.
- **Architettura software:** architetture a livelli, monolite e microservizi, modello C4, componenti, flussi di dati, interfacce e decisioni progettuali.
- **Sviluppo applicativo:** database relazionali, SQL, API REST, backend **Python/Django** e frontend web.
- **Sicurezza e dati sanitari:** autenticazione, autorizzazione, minimizzazione dei dati, GDPR, controllo degli accessi e gestione degli errori.
- **Rischio e verifiche:** identificazione dei pericoli, situazioni pericolose, controlli del rischio, test, verifica e validazione.
- **Processo di sviluppo:** Agile, Git, issue tracking, code review e documentazione del progetto.
- **Documentazione regolatoria:** struttura e contenuti essenziali del fascicolo tecnico, evidenze e matrice di tracciabilità.

L'attività di laboratorio ruota attorno a **quattro progetti di gruppo**. L'obiettivo non è realizzare un prodotto commercializzabile o certificato, ma sperimentare in modo realistico il processo di sviluppo e documentazione di un software con una destinazione d'uso medica.

---

## 🎓 Progetti degli studenti

Ogni gruppo sviluppa un **prototipo didattico di SaMD** con uno scenario clinico definito, utenti identificati e funzionalità verificabili. Tutti i progetti prevedono:

- **Database relazionale** per utenti, osservazioni, dati clinici e storico delle operazioni.
- **Backend Django** con logica applicativa, validazione dei dati e API REST.
- **Frontend web** per l'interazione con paziente e/o personale sanitario.
- **Autenticazione e autorizzazione** con ruoli e permessi coerenti.
- **Documentazione tecnica**, analisi dei requisiti, gestione dei rischi e test.
- **Funzionalità opzionale con LLM eseguito in locale**, senza inviare dati sanitari a servizi esterni. Gli output generativi richiedono controlli e conferma umana; non sostituiscono decisioni cliniche.

### Progetto 1 - PressureCare
**Monitoraggio domiciliare dell'ipertensione**

Una soluzione per raccogliere e consultare misurazioni pressorie longitudinali, facilitando il monitoraggio da parte di paziente e personale sanitario.

**Funzionalità attese:**
- Inserimento delle misurazioni di pressione sistolica, diastolica e frequenza cardiaca.
- Consultazione dello storico e rappresentazione grafica dei trend.
- Gestione del paziente e visualizzazione della dashboard clinica.
- Segnalazioni basate su **regole deterministiche e soglie documentate**, evitando diagnosi automatiche.

**Opzionale - LLM locale:** generazione di una bozza di sintesi delle misurazioni da sottoporre a revisione del professionista sanitario.

### Progetto 2 - PostOp Care
**Monitoraggio del recupero postoperatorio**

Una soluzione per registrare i dati di follow-up dopo un intervento e facilitare l'individuazione di risposte che richiedono la valutazione del personale sanitario.

**Funzionalità attese:**
- Compilazione periodica di questionari su sintomi e condizioni generali.
- Storico delle risposte e dashboard di follow-up.
- Evidenziazione di situazioni da verificare tramite **regole esplicite**, con logica di triage simulata.
- Tracciamento degli eventi e degli interventi dell'operatore.

**Opzionale - LLM locale:** sintesi strutturata dei diari di follow-up, sempre verificata dall'operatore.

### Progetto 3 - GlucoTrack
**Monitoraggio longitudinale dei parametri metabolici**

Una soluzione per raccogliere e analizzare misurazioni metaboliche, con attenzione alla qualità, alla provenienza e alla rappresentazione dei dati.

**Funzionalità attese:**
- Registrazione di misurazioni (per esempio glicemia) con unità di misura, data, ora e origine.
- Visualizzazione di storico, grafici e andamento temporale.
- Dashboard per il professionista sanitario.
- Controlli di coerenza e tracciabilità della provenienza del dato.

**Opzionale - LLM locale:** estrazione di dati strutturati da note testuali, con conferma esplicita prima del salvataggio.

### Progetto 4 - RehabTrack
**Monitoraggio di un percorso riabilitativo**

Una soluzione per gestire il piano riabilitativo e seguirne l'esecuzione, includendo aderenza, dolore riferito e andamento del percorso.

**Funzionalità attese:**
- Definizione e consultazione di un piano di esercizi assegnato dal professionista.
- Registrazione delle sessioni svolte e dell'aderenza.
- Raccolta del dolore riferito e di osservazioni successive alle sessioni.
- Dashboard di avanzamento per il fisioterapista.

**Opzionale - LLM locale:** proposta di riepilogo o compilazione assistita di contenuti strutturati, da confermare prima dell'utilizzo.

> **Nota didattica:** la qualificazione come dispositivo medico, la classe di rischio e gli obblighi applicabili dipendono dalla **destinazione d'uso dichiarata** e dalle funzionalità effettive. Ogni gruppo dovrà motivare queste scelte nella documentazione; nessuno dei prototipi è destinato all'uso clinico reale.

---

## 👥 Team di lavoro

L'assegnazione nominativa dei componenti ai quattro progetti per l'edizione 2026/2027 sarà riportata qui quando definita. I ruoli possono essere distribuiti tra:

- **Project Manager:** organizzazione del backlog, milestone e coordinamento.
- **Analista software:** stakeholder, requisiti, SRS e tracciabilità.
- **Software Developer:** database, backend, frontend e test.
- **Referente qualità/rischio:** analisi dei rischi e raccolta delle evidenze documentali.

Le responsabilità sono condivise: tutti i componenti devono conoscere l'architettura e saper spiegare le principali scelte progettuali.

---

## 🗓️ Calendario del corso

**Legenda:** ✅ svolta · ⏳ programmata · 🎓 esame finale

| Giornata | Data | Orario | Ore | Stato |
|---|---|---|---:|---|
| Giovedì | 01/10/2026 | 14:00-18:00 | 4 | ✅ Svolta |
| Mercoledì | 07/10/2026 | 13:00-17:00 | 4 | ✅ Svolta |
| Giovedì | 08/10/2026 | 14:00-18:00 | 4 | ✅ Svolta |
| Lunedì | 12/10/2026 | 14:00-18:00 | 4 | ✅ Svolta |
| Martedì | 13/10/2026 | 14:00-17:00 | 3 | ✅ Svolta |
| Giovedì | 15/10/2026 | 14:00-18:00 | 4 | ✅ Svolta |
| Martedì | 20/10/2026 | 14:00-17:00 | 3 | ⏳ Programmata |
| Giovedì | 22/10/2026 | 14:00-17:00 | 3 | ⏳ Programmata |
| Martedì | 27/10/2026 | 14:00-17:00 | 3 | ⏳ Programmata |
| Giovedì | 29/10/2026 | 14:00-17:00 | 3 | ⏳ Programmata |
| Lunedì | 09/11/2026 | 14:00-17:00 | 3 | ⏳ Programmata |
| Giovedì | 12/11/2026 | 14:00-17:00 | 3 | ⏳ Programmata |
| Martedì | 17/11/2026 | 14:00-17:00 | 3 | ⏳ Programmata |
| Giovedì | 19/11/2026 | 14:00-17:00 | 3 | ⏳ Programmata |
| Martedì | 01/12/2026 | 14:00-17:00 | 3 | ⏳ Programmata |
| Venerdì | 04/12/2026 | 14:00-17:00 | 3 | ⏳ Programmata |
| Giovedì | 10/12/2026 | 14:00-17:00 | 3 | ⏳ Programmata |
| Giovedì | 17/12/2026 | 14:00-18:00 | 4 | 🎓 Esame finale |

**Riepilogo (al 15/10/2026)**

- **Ore complessive previste:** 60.
- **Ore svolte fino al 13/10/2026:** 19.
- **Ore programmate dal 15/10/2026:** 41 (incluse 4 ore di esame).
- **Ore di attività prima dell’esame:** 56.
- **Esame finale:** giovedì **17/12/2026**, dalle **14:00 alle 18:00** (4 ore).

---

## 🧩 Lezioni e contenuti

Le attività descrivono il percorso didattico, mentre il calendario sopra riporta le date effettive. I temi delle lezioni future sono indicativi e possono essere adattati all'avanzamento dei gruppi.

### Lezione 1 - Introduzione ai dispositivi medici software e quadro normativo ✅
**01/10/2026 - 4 ore**

- Software medicale, mHealth e differenza tra software sanitario e dispositivo medico.
- Destinazione d'uso, qualificazione e classificazione secondo MDR 2017/745.
- Ruolo delle norme IEC 62304, ISO 14971, ISO 13485 e delle linee guida MDCG.
- Ciclo di vita del software, sicurezza, tracciabilità e documentazione.

### Lezione 2 - Raccolta e analisi dei requisiti ✅
**07/10/2026 - 4 ore (13:00-17:00)**

- Identificazione degli stakeholder e tecniche di elicitation.
- Requisiti business, utente, funzionali, non funzionali, di interfaccia, di sicurezza e regolatori.
- Differenza tra bisogno, requisito, soluzione e criterio di accettazione.
- SRS, priorità, criteri di qualità, testabilità e ambiguità.
- Matrice di tracciabilità e applicazioni agli scenari sanitari.

### Lezione 3 - Architettura software ✅
**08/10/2026 - 4 ore**

- Dall'analisi dei requisiti alla progettazione architetturale.
- Architetture layered, monolitiche e a microservizi; separazione delle responsabilità.
- Modello C4: System Context, Container, Component e Code.
- Backend, frontend, database e API REST.
- Scelte architetturali in ambito medicale: auditabilità, sicurezza, manutenibilità e verifica.

### Lezioni successive - Sviluppo e project work ⏳
**Dal 12/10/2026**

- Presentazione e avvio dei quattro progetti, definizione della destinazione d'uso e degli stakeholder.
- Analisi dei requisiti di progetto, SRS e backlog iniziale.
- Modellazione del database: entità, relazioni, vincoli e SQL.
- Python e Django: modelli, ORM, views, routing e API REST.
- Frontend web, autenticazione, ruoli e gestione sicura dei dati.
- Git, branch, issue e organizzazione Agile del lavoro.
- Gestione del rischio secondo ISO 14971: pericoli, situazioni pericolose e misure di controllo.
- Verifica e validazione: unit test, test delle API, casi di prova e tracciabilità.
- Preparazione della documentazione tecnica e delle evidenze di progetto.
- Integrazione **facoltativa** di funzionalità con LLM locale, con analisi specifica di rischio, privacy e supervisione umana.
- Revisione finale, dimostrazione del prototipo e presentazione del lavoro.

---

### Esame finale - Presentazione e valutazione dei progetti 🎓
**17/12/2026 - 4 ore (14:00-18:00)**

- Presentazione dei progetti e dimostrazione dei prototipi realizzati.
- Discussione delle scelte progettuali, della documentazione, dei rischi e dei test.
- Valutazione finale secondo i criteri indicati di seguito.

---

## 📦 Deliverable richiesti ai gruppi

1. **Descrizione del prodotto:** scenario clinico, utenti, destinazione d'uso prevista, ambito e limiti.
2. **Analisi dei requisiti:** stakeholder, requisiti numerati, criteri di accettazione e SRS.
3. **Progettazione:** diagrammi di architettura (preferibilmente C4), modello ER, schema del database e descrizione delle API.
4. **Prototipo funzionante:** database, backend Django e frontend integrati, con dati di test fittizi.
5. **Gestione del rischio:** identificazione dei pericoli, valutazione, misure di controllo e rischi residui nel contesto didattico.
6. **Verifica del software:** piano dei test, casi di prova, risultati ed eventuali anomalie.
7. **Tracciabilità:** collegamento tra requisiti, componenti, rischi, misure di controllo e test.
8. **Fascicolo tecnico semplificato:** raccolta ordinata degli elaborati e delle motivazioni progettuali.
9. **Repository Git e presentazione finale:** codice, istruzioni di avvio, ruoli, contributi e demo.

### Criteri di valutazione

Saranno considerati la qualità dell'analisi dei requisiti, la coerenza dell'architettura, la qualità del prototipo, la gestione dei rischi, la completezza della documentazione, la tracciabilità, i test e la capacità di presentare e motivare le scelte effettuate.

---

## 🛠️ Stack tecnologico di riferimento

| Livello | Tecnologie |
|---|---|
| Backend | Python, Django, Django REST Framework |
| Database | PostgreSQL (oppure SQLite nelle prime esercitazioni) |
| Frontend | HTML, CSS, JavaScript e/o framework concordato |
| Interfacce | API REST, JSON |
| Versionamento | Git e repository condiviso |
| Test | unittest/pytest, test Django e test API |
| AI opzionale | LLM locale, senza trasferimento di dati clinici verso servizi esterni |

**Importante:** usare esclusivamente **dati sintetici o fittizi** per il laboratorio. I prototipi sono destinati alla formazione e **non devono essere utilizzati per decisioni cliniche reali**.

---

*README aggiornato al 15 ottobre 2026. Calendario e assegnazioni potranno essere aggiornati in funzione delle comunicazioni didattiche.*
