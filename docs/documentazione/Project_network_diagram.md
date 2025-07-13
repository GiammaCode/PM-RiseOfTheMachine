# Project Network Diagram

```mermaid
graph TB
    %% Sprint 1 (Settimane 1-2)
    S1["Sprint 1: Setup & Prototipo IA<br/>Durata: 2 settimane<br/>ES:0 EF:2 LS:0 LF:2<br/>Slack: 0"]
    
    %% Sprint 2 (Settimane 3-4)
    S2A["Sprint 2A: Sviluppo IA Core<br/>Durata: 2 settimane<br/>ES:2 EF:4 LS:2 LF:4<br/>Slack: 0"]
    S2B["Sprint 2B: Design UI<br/>Durata: 2 settimane<br/>ES:2 EF:4 LS:3 LF:5<br/>Slack: 1"]
    S2C["Sprint 2C: Asset Cinematografici<br/>Durata: 1 settimana<br/>ES:2 EF:3 LS:7 LF:8<br/>Slack: 5"]
    
    %% Sprint 3 (Settimane 5-6)
    S3A["Sprint 3A: Sviluppo Interfaccia<br/>Durata: 2 settimane<br/>ES:4 EF:6 LS:5 LF:7<br/>Slack: 1"]
    S3B["Sprint 3B: Logica di Gioco<br/>Durata: 2 settimane<br/>ES:4 EF:6 LS:6 LF:8<br/>Slack: 2"]
    S3C["Sprint 3C: Implementazione Motore IA<br/>Durata: 2 settimane<br/>ES:4 EF:6 LS:4 LF:6<br/>Slack: 0"]
    
    %% Sprint 4 (Settimane 7-8)
    S4["Sprint 4: Integrazione Base<br/>Durata: 2 settimane<br/>ES:6 EF:8 LS:6 LF:8<br/>Slack: 0"]
    
    %% Sprint 5 (Settimane 9-10)
    S5A["Sprint 5A: Sviluppo Interfaccia Avanzata<br/>Durata: 2 settimane<br/>ES:8 EF:10 LS:8 LF:10<br/>Slack: 0"]
    S5B["Sprint 5B: Espansione Logica Gioco<br/>Durata: 2 settimane<br/>ES:8 EF:10 LS:9 LF:11<br/>Slack: 1"]
    S5C["Sprint 5C: Ottimizzazione Motore IA<br/>Durata: 2 settimane<br/>ES:8 EF:10 LS:8 LF:10<br/>Slack: 0"]
    
    %% Sprint 6 (Settimane 11-12)
    S6A["Sprint 6A: Bilanciamento Gameplay<br/>Durata: 2 settimane<br/>ES:10 EF:12 LS:10 LF:12<br/>Slack: 0"]
    S6B["Sprint 6B: Testing Multipiattaforma<br/>Durata: 2 settimane<br/>ES:10 EF:12 LS:11 LF:13<br/>Slack: 1"]
    
    %% Sprint 7 (Settimane 13-14)
    S7A["Sprint 7A: Integrazione Asset<br/>Durata: 2 settimane<br/>ES:12 EF:14 LS:12 LF:14<br/>Slack: 0"]
    S7B["Sprint 7B: Ottimizzazione Performance<br/>Durata: 2 settimane<br/>ES:12 EF:14 LS:12 LF:14<br/>Slack: 0"]
    
    %% Sprint 8 (Settimana 15)
    S8["Sprint 8: Testing Finale & Release<br/>Durata: 1 settimana<br/>ES:14 EF:15 LS:14 LF:15<br/>Slack: 0"]
    
    %% Milestone e Release
    R1["Release 1: Prototipo IA + UI<br/>Settimana 4"]
    R2["Release 2: Primo Prototipo<br/>Settimana 8"]
    R3["Release 3: Prototipo Bilanciato<br/>Settimana 12"]
    R4["Release Finale<br/>Settimana 15"]
    BUFFER["Buffer Week<br/>Settimana 16"]

    %% Dipendenze tra sprint
    S1 --> S2A
    S1 --> S2B
    S1 --> S2C
    
    S2A --> S3C
    S2B --> S3A
    
    S3A --> S4
    S3B --> S4
    S3C --> S4
    
    S4 --> S5A
    S4 --> S5B
    S4 --> S5C
    
    S5A --> S6A
    S5B --> S6A
    S5C --> S6A
    S5A --> S6B
    
    S6A --> S7A
    S6A --> S7B
    S6B --> S7B
    
    S7A --> S8
    S7B --> S8
    
    %% Collegamento ai release
    S2A --> R1
    S2B --> R1
    S4 --> R2
    S6A --> R3
    S6B --> R3
    S8 --> R4
    R4 --> BUFFER

    %% Stili
    classDef critical fill:#ffebee,stroke:#d32f2f,stroke-width:3px,color:#000
    classDef normal fill:#ffffff,stroke:#1976d2,stroke-width:2px,color:#000
    classDef slack fill:#e8f5e8,stroke:#4caf50,stroke-width:2px,color:#000
    classDef milestone fill:#fff3e0,stroke:#ff9800,stroke-width:3px,color:#000
    classDef buffer fill:#f3e5f5,stroke:#9c27b0,stroke-width:2px,color:#000

    %% Applicazione stili - Critical Path principale
    class S1,S2A,S3C,S4,S5A,S5C,S6A,S7A,S7B,S8 critical
    class S2B,S3A,S5B slack
    class S2C,S3B,S6B normal
    class R1,R2,R3,R4 milestone
    class BUFFER buffer

```
## **Legenda**

**Critical Path (rosso):**

Questi task hanno slack \= 0 e determinano la durata minima del progetto

**Task con Slack (verde):** 

Hanno margine di manovra per ritardi senza impattare il progetto

**Task normale (bianco):** 

Hanno molto slack e possono essere posticipati
