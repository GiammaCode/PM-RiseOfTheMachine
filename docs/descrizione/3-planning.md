---
layout: default
title: Planning
nav_order: 3
---

# Planning

La fase di planning rappresenta il cuore strategico del progetto, dove tutte le decisioni prese durante lo scoping 
vengono tradotte in un piano operativo dettagliato. 

Per questo progetto di sviluppo del videogioco "Rise of the Machine", la pianificazione richiede un approccio 
strutturato che tenga conto della timeline serrata e della complessità tecnica dell'intelligenza artificiale strategica.

## Joint Project Planning Session (JPPS)

La Joint Project Planning Session è stata organizzata in due sessioni distinte per massimizzare l'efficacia del 
processo di pianificazione e garantire il coinvolgimento appropriato di tutti gli stakeholder.

### Prima Sessione - Kick-off e Working Session

**Partecipanti:**
- Scrum Muster
- Product Owner
- Team tecnico interno (Rappresentante team tecnico, Sviluppatore Soft e UI Developer)
- Cliente
- Tecnografo

**Fase 1: Kick-off**

**Obiettivo:** Allineamento di tutti gli stakeholder sul progetto e definizione del framework operativo

**Attività svolte:**
- Presentazione del core team: Introduzione dei membri del team di sviluppo che si uniscono al progetto
- Revisione del POS: Conferma degli obiettivi e dei success criteria definiti in fase di scoping
- Presentazione della timeline critica: Illustrazione della roadmap di 4 mesi con particolare enfasi sui milestone 
sincronizzati con l'uscita del trailer del film
- Definizione delle regole operative: Stabilimento di protocolli di comunicazione, frequenza dei meeting e procedure 
di escalation

**Fase 2: Working Session**

**Obiettivo:** Trasformazione dei requisiti in una struttura di lavoro operativa e definizione delle prime stime

**Attività svolte:**
- Validazione e prioritizzazione dell'RBS: Conferma della Requirements Breakdown Structure con focus sui requisiti 
Must-Have per rispettare la timeline
- Generazione della WBS preliminare: Decomposizione dei requisiti in attività specifiche seguendo un approccio modulare
- Stima preliminare effort e durata: Prima valutazione delle risorse necessarie utilizzando la three-point technique 
per i componenti critici
- Identificazione delle dipendenze critiche: Mappatura delle relazioni tra i componenti IA, UI e integrazione 
multipiattaforma
- Stesura del Project Definition Statement (PDS): Espansione del POS con dettagli tecnici e operativi

### Seconda sessione - Pianificazione Dettagliata

**Partecipanti:**
- Core Team tecnico
- Scrum Muster
- Product Owner
- Resource Manager
- QA Tester

**Obiettivo:** Finalizzazione del piano operativo con schedule dettagliata e allocation delle risorse

**Attività svolte:**
- Raffinamento WBS: Completamento della Work Breakdown Structure con decomposizione fino al livello di task
- Costruzione Project Network Diagram: Creazione del diagramma delle dipendenze utilizzando il metodo Task-on-Node
- Identificazione Critical Path: Determinazione delle attività critiche che impattano sulla deadline del progetto
- Resource leveling: Ottimizzazione dell'allocazione delle risorse per evitare over-allocation
- Definizione milestone e deliverable: Stabilimento dei checkpoint principali allineati con le esigenze del
cliente (GANTT)
- Raffinamento dell'analisi dei rischi, aggiunta della parte di gestione

## Approccio PMLC e Metodologia

Basandosi sull'analisi condotta durante lo scoping, il progetto adotta un approccio PMLC adattivo per le seguenti ragioni:

- **Goal chiaramente definito:** L'obiettivo finale (videogioco strategico sincronizzato con il trailer del film) è ben definito
- **Solution parzialmente definita:** Le specifiche tecniche dell'IA e del bilanciamento gameplay richiedono iterazioni
- **Timeline fissa:** La data di rilascio non è negoziabile, richiedendo flessibilità nell'implementazione
- **Stakeholder engagement:** Necessità di feedback continuo dalla casa cinematografica
- **Imprevisti:** Evenienza non remota di dover modificare la fase di scoping

**Sprint pianificate:**
- **Sprint 1 (Settimane 1-2):** Setup architettura e Prototipo IA core
- **Sprint 2 (Settimane 3-4):** Sviluppo IA Core, Design UI, scelta asset Cinematogr.
- **Sprint 3 (Settimane 5-6):** Sviluppo interfaccia, Logica di gioco, Implementazione Motore AI
- **Sprint 4 (Settimane 7-8):** Integrazione componenti di base per il primo prototipo
- **Sprint 5 (Settimane 9-10):** Sviluppo interfaccia, Logica di gioco, Implementazione Motore AI
- **Sprint 6 (Settimane 11-12):** Bilanciamento gameplay, testing multipiattaforma
- **Sprint 7 (Settimane 13-14):** Integrazione Asset e Ottimizzazione
- **Sprint 8 (Settimane 15):** Testing finale e preparazione rilascio

**Rilasci pianificati:**
- **Settimana 4:** Mostriamo il prtotipo AI e una bozza di UI con le scene scelte del film
- **Settimana 8:** Primo prototipo funzionante del gioco
- **Settimana 12:** Secondo prototipo bilanciato e testato su più piattaforme
- **Settimana 15:** Rilascio versione finale

## Contratto e Gestione Finanziaria

### Tipologia Contrattuale

Dopo un'attenta analisi dei rischi e delle incertezze del progetto, si è optato per un contratto misto che combina:

**Componente Fixed-Price (60% del valore):**
- Sviluppo motore IA base
- Implementazione interfaccia utente
- Setup architettura multipiattaforma
- Deliverable documentali

**Componente Time & Materials (40% del valore):**
- Bilanciamento e tuning IA
- Personalizzazioni richieste dal clientef
- Integrazione elementi cinematografici
- Testing e debugging finale

**Vantaggi di questo approccio:**
- **Per il cliente:** Controllo sui costi principali con flessibilità per modifiche
- **Per il fornitore:** Protezione sui componenti incerti e coverage dei rischi tecnici
- **Per il progetto:** Equilibrio tra predictability e adaptability

### Cash Flow Management

[Analisi e gestione finanziaria](documentazione/Analisi_finanziaria.md)

## Deliverable della Fase di Planning

I seguenti documenti sono stati prodotti e sono disponibili in allegato:

- **Project Definition Statement (PDS):** Versione estesa del POS con dettagli tecnici
- **Work Breakdown Structure (WBS):** Decomposizione completa delle attività
- **Stima tempistiche:** Stima tedel tempo necessarie per ogni attività
- **Project Network Diagram:** Diagramma delle dipendenze e critical path
- **GANTT**: calendario attività e tempistiche 
- **Risk Management Plan:** Strategie di mitigazione dei rischi identificati
- **Gestione finanziaria:** costi, entrate, budget e cash flow

La fase di planning si conclude con l'approvazione formale del piano da parte di tutti gli stakeholder e 
l'autorizzazione a procedere con la fase di execution.