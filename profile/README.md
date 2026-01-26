# 📘 **Corso UF 13.3 – Dispositivi Medici Software, App e mHealth**
### Docente: **Ing. Alessandro Pellegrino**
### A.S. 2025/2026

---

## 🧭 Programma del Corso

Il corso introduce gli studenti ai fondamenti dello sviluppo software in ambito sanitario, con particolare attenzione a:

- Dispositivi Medici Software (MDR 2017/745)
- Ciclo di vita del software secondo IEC 62304
- Gestione del rischio (ISO 14971)
- Sistemi qualità (ISO 13485)
- App mHealth e applicazioni mobile
- Raccolta e analisi dei requisiti
- Progettazione API, backend e frontend
- Pattern di sviluppo moderni (Django + Android)

Il corso prevede lezioni teoriche e attività di laboratorio su tre progetti realizzati dagli studenti, più un progetto demo presentato dal docente come esempio guida.

---

# 🎓 **Progetti degli Studenti**

## **Progetto 1 – Dashboard del Medico (VitalBoard)**

Il medico necessita di una vista strutturata dei parametri vitali dei pazienti.  
La dashboard permetterà di:
- visualizzare storico misurazioni
- analizzare grafici di andamento
- vedere segnalazioni critiche
- integrare informazioni provenienti dagli altri progetti

---

## **Progetto 2 – App raccolta dati (DataCollector)**

Durante le visite domiciliari, l’infermiere (o paziente o wereable) registra:
- pressione
- saturazione
- temperatura
- sintomi
- eventuali foto

I dati vengono inviati al sistema e resi disponibili al medico nel Progetto 1.

---

## **Progetto 3 – Diario Clinico e Terapie (CareDiary)**

Il paziente può:
- annotare sintomi e note quotidiane
- monitorare dolore, umore, condizioni generali
- impostare promemoria della terapia

Dati e promemoria si integrano con la dashboard del medico.

---

# 🌟 **Progetto Demo – WoundMonitor**

Il paziente o l’infermiere fotografa una ferita, lesione o neo.  
La foto e la nota vengono salvate in uno storico.  
Il medico visualizza l’evoluzione e lascia un giudizio semplice:
- Monitorare
- Consigliare visita
- Valutazione urgente

Nessuna diagnosi automatica → solo supporto informativo.

---

# 👥 **Team di Lavoro**

### TEAM 1 - Progetto 1 (VitalBoard)
| Studente | User Git | Ruolo |
|---------|----------|-------|
| Mohamed Daloul | MomoDal | Project Manager |
| Francesco Santoianni | santofrancesco | Software Developer |
| Aichetou Agouda | aaisha-destiny | Analista software, Software Developer |
| Veronica Rampazzo | Vero335 |  Analista software, Software Developer |

### TEAM 2 - Progetto 3 (Diario clinico)
| Studente | User Git | Ruolo |
|---------|----------|-------|
| Lorenzo Del Cont Bernard | Lollooo04 | Analista Software, Sviluppo Software |
| Matteo Mastromarino | matteo | Analista Software |
| Alessia Jurman | alejpeg | Project Manager, Sviluppo  Software |
| Alex Vucec | Hellux-H | Sviluppo Software |

### TEAM 3 -Progetto 2 (Data Collector)
| Studente | User Git | Ruolo |
|---------|----------|-------|
| Silvestrini Davide | ItsDaWae | Analista Software, Sviluppo Software |
| Angelo Miranda | MirandaAngelo | Analista Software |
| Saverio Sironi | GitSaveS2 | Project Manager |
| Tommaso Perco | DeeDyne | Sviluppo Software |

---

# 🗓️ **Calendario del Corso**

| Giornata | Data | Orario | Ore | Stato |
|----------|------|--------|------|--------|
| venerdì | **31/10/2025** | 09:00–13:00 | 4 | ✔ |
| venerdì | **14/11/2025** | 09:00–13:00 | 4 | ✔ |
| venerdì | **21/11/2025** | 09:00–13:00 | 4 | ✔ |
| lunedì  | **24/11/2025** | 09:00–13:00 | 4 | ✔ |
| venerdì | **05/12/2025** | 09:00–13:00 | 4 | ✔ |
| giovedì | **08/01/2026** | 14:00–18:00 | 4 | ✔ |
| venerdì | **09/01/2026** | 14:00–18:00 | 4 | ✔ |
| lunedì |  **12/01/2026** | 14:00–18:00 | 4 | ✔ |
| martedì | **13/01/2026** | 14:00–18:00 | 4 | ✔ |
| giovedì | **15/01/2026** | 14:00–18:00 | 4 | ✔ |
| giovedì | **22/01/2026** | 14:00–18:00 | 4 | ✔ |
| martedì | 27/01/2026 | 14:00–18:00 | 4 | |
| giovedì | 29/01/2026 | 09:00–13:00 | 4 | |
| mercoledì | 04/02/2026 | 09:00–13:00 | 4 | |
| venerdì | 06/02/2026 | 09:00–13:00 | 4 | |


## 🧩 **Lezione 1 – Introduzione e Normative ✔**

Contenuti:
- Dispositivi Medici Software
- App mHealth e software ad uso clinico
- MDR 2017/745
- IEC 62304
- ISO 14971
- ISO 13485
- EN 82304-1
- MDCG Guidelines
- Tracciabilità
- Introduzione all’analisi dei requisiti

---

## 🧩 **Lezione 2 – Raccolta e Analisi dei Requisiti ✔**

Contenuti:
- Raccolta dei requisiti
- Identificazione stakeholder
- Tipologie di requisiti
- SRS (Software Requirements Specification)
- Matrice di Tracciabilità
- Presentazione dei progetti
- Presentazione progetto demo

---

## 🧩 **Lezione 3 – Architettura, Database, SQL e API ✔**

Contenuti:
- Architettura software moderna  
- Monoliti vs Microservizi  
- Pattern architetturali (MVC, Layered, Service-Oriented)  
- Comunicazione tra componenti  
- API REST: principi, metodi HTTP, status code  
- Introduzione ai Database relazionali  
- Modellazione ER e struttura delle tabelle  
- Chiavi primarie, chiavi esterne, vincoli, relazioni  
- Introduzione al linguaggio SQL  
- SELECT, INSERT, UPDATE, DELETE – panoramica completa  
- Esercitazione pratica: creazione tabelle e query reali  
- Introduzione agli indici e alle prestazioni di base  

---

## 🧩 **Lezione 4 – Programmazione in Python + Introduzione a Django ✔**

Contenuti:
- Esercitazione pratica di Python e Django
- Sintassi base di Python (variabili, tipi, funzioni)
- Strutture dati principali (liste, dict, tuple, set)
- Esecuzione condizionale e cicli  
- Moduli, package e import  
- Gestione degli errori (try/except)  
- Introduzione alle indentazioni (regola fondamentale in Python)  
- Esercitazioni pratiche (20 piccoli programmi)  
- Introduzione al framework Django  
- Views, URL routing, templates  
- Differenze tra Flask e Django  
- Panoramica su ORM e modelli Django

## 🧩 **Lezione 5 – Django e Laboratorio Progetti ✔**

Contenuti:
- Esercitazione pratica di Python e Django
- Laboratorio su progetti di gruppo

## 🧩 **Lezione 6 – Django e Laboratorio Progetti ✔**

Contenuti:
- Esercitazione pratica di Python e Django
- Laboratorio su progetti di gruppo
- Models in Django

## 🧩 **Lezione 7 – Django e Laboratorio Progetti ✔**

Contenuti:
- Esercitazione pratica di Python e Django
- Laboratorio su progetti di gruppo
- Views e urls in Django

## 🧩 **Lezione 8 – Django e Laboratorio Progetti ✔**

Contenuti:
- Esercitazione pratica di Python e Django
- Laboratorio su progetti di gruppo
- Query, Views e Template in Django

## 🧩 **Lezione 9 – Django e Laboratorio Progetti ✔**

Contenuti:
- Esercitazione pratica di Python e Django
- Laboratorio su progetti di gruppo
- Template: HTML, JS e CSS in Django

## 🧩 **Lezione 10 – Django e Laboratorio Progetti ✔**

Contenuti:
- Esercitazione pratica di Python e Django
- Laboratorio su progetti di gruppo
- Analisi dei rischi

