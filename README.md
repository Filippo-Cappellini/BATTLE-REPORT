# BATTLE-REPORT
azioni, informazioni e attività completate per il progetto 



<img width="907" height="289" alt="1" src="https://github.com/user-attachments/assets/87667583-76a1-446a-91d5-4420be10f756" />





<img width="907" height="300" alt="2" src="https://github.com/user-attachments/assets/6a11280e-95dd-4ac8-929d-1fd7ba1080ed" />




# Cybersecurity Lab – Report tecnico delle attività

**Periodo:** 05/11/2026 – 06/11/2026  
**Durata:** 2 giornate  
**Hardware principale:** Raspberry Pi  
**Sistema operativo:** Ubuntu Server 26.04.1 LTS

---

# 1. Contesto e obiettivi del progetto

Questo report documenta le attività svolte durante due giornate di laboratorio dedicate alla cybersecurity, alla configurazione di sistemi informatici, al monitoraggio della rete e all'analisi delle vulnerabilità.

L'ambiente di lavoro è stato realizzato utilizzando principalmente un Raspberry Pi, sul quale è stato installato Ubuntu Server 26.04.1 LTS.

Durante il laboratorio sono stati utilizzati diversi strumenti di sicurezza informatica, tra cui Wazuh, Nmap, Hydra, Kali Linux, John the Ripper e Wireshark.

È stato inoltre configurato un Honeypot con un sistema di Whitelist e blocco automatico degli indirizzi IP non autorizzati per una durata di 24 ore.

L'obiettivo generale è stato quello di acquisire esperienza pratica nella configurazione di un ambiente di cybersecurity, nell'analisi del traffico di rete, nell'individuazione delle vulnerabilità e nell'utilizzo di strumenti di sicurezza.

# 2. Attività preparatorie

## 2.1 Preparazione di gruppo

Durante la fase iniziale sono state svolte attività organizzative per predisporre l'ambiente di laboratorio.

Le attività preparatorie hanno riguardato:

- Organizzazione delle attività da svolgere durante le due giornate.
- Preparazione dell'ambiente di lavoro.
- Individuazione degli strumenti hardware e software necessari.
- Coordinamento delle attività tra i partecipanti.
- Verifica del materiale disponibile.

## 2.2 Preparazione individuale

Sono state svolte attività preliminari per familiarizzare con gli strumenti utilizzati durante il laboratorio.

In particolare:

- Preparazione degli strumenti software.
- Verifica degli ambienti di lavoro.
- Familiarizzazione con le principali funzionalità degli strumenti di cybersecurity.
- Approfondimento delle tecnologie utilizzate.

# 3. Cronologia delle attività

## Giornata 1 – 05/11/2026

### 3.1 Configurazione della rete

La prima fase ha riguardato la configurazione dell'infrastruttura di rete necessaria per consentire la comunicazione tra i dispositivi utilizzati durante il laboratorio.

Attività svolte:

- Supporto nella configurazione della rete.
- Collegamento dei dispositivi all'infrastruttura.
- Verifica della connettività.
- Analisi dei dispositivi collegati alla rete.
- Individuazione degli indirizzi IP.
- Verifica della comunicazione tra i dispositivi.

### 3.2 Setup del Raspberry Pi

È stata effettuata la configurazione iniziale del Raspberry Pi, utilizzato come dispositivo hardware principale dell'ambiente di laboratorio.

Attività svolte:

- Configurazione iniziale del Raspberry Pi.
- Preparazione del dispositivo.
- Installazione del sistema operativo.
- Configurazione delle impostazioni di base.
- Verifica del corretto funzionamento.

### 3.3 Installazione di Ubuntu Server 26.04.1 LTS

Ubuntu Server 26.04.1 LTS è stato installato direttamente sul Raspberry Pi, che è stato utilizzato come piattaforma hardware per l'ambiente server.

Attività svolte:

- Installazione di Ubuntu Server sul Raspberry Pi.
- Prima configurazione del sistema operativo.
- Preparazione dell'ambiente per le successive attività di laboratorio.

**Nota:** le ulteriori operazioni di aggiornamento, configurazione e hardening devono essere documentate specificando i comandi e le impostazioni effettivamente applicati.

## Giornata 2 – 06/11/2026

### 3.4 Installazione e configurazione di Wazuh

È stata effettuata l'installazione e la configurazione della piattaforma Wazuh, utilizzata per il monitoraggio della sicurezza dell'ambiente informatico.

Attività svolte:

- Installazione della piattaforma Wazuh.
- Configurazione iniziale del sistema.
- Verifica del funzionamento della dashboard.
- Esplorazione delle funzionalità di monitoraggio e sicurezza.
- Consultazione delle informazioni raccolte.

### 3.5 Attività con l'agente Wazuh

È stata approfondita la gestione dell'agente Wazuh, utilizzato per raccogliere informazioni dai dispositivi monitorati e comunicarle alla piattaforma centrale.

Aspetti da documentare:

- Installazione dell'agente.
- Configurazione della comunicazione con il server Wazuh.
- Registrazione del dispositivo.
- Verifica dello stato di connessione.
- Analisi delle informazioni raccolte.
- Consultazione degli eventi e degli alert.

**Nota:** specificare i dispositivi sui quali è stato installato l'agente e confermare se la connessione al server è stata completata correttamente.

### 3.6 Installazione di strumenti di cybersecurity

Durante il laboratorio sono stati installati e sperimentati diversi strumenti dedicati all'analisi della sicurezza informatica.

**Nmap**

Strumento utilizzato per l'analisi della rete e l'individuazione dei dispositivi e dei servizi attivi.

Attività:

- Installazione dello strumento.
- Analisi degli host presenti nella rete.
- Individuazione degli indirizzi IP.
- Analisi delle porte e dei servizi disponibili.

**Hydra**

Strumento utilizzato per effettuare test di autenticazione e verificare la robustezza delle credenziali in ambienti autorizzati.

Attività:

- Installazione dello strumento.
- Esplorazione delle funzionalità.
- Prime prove di utilizzo.

### 3.7 Analisi delle vulnerabilità tramite Wazuh

È stata effettuata un'attività di consultazione delle vulnerabilità individuate dalla piattaforma Wazuh.

Attività svolte:

- Consultazione della sezione dedicata alle vulnerabilità.
- Individuazione delle possibili CVE (Common Vulnerabilities and Exposures).
- Analisi delle vulnerabilità segnalate.
- Osservazione della gravità delle vulnerabilità.
- Verifica degli indirizzi IP associati ai dispositivi monitorati.
- Analisi delle informazioni relative agli host.

L'attività ha permesso di comprendere come Wazuh possa essere utilizzato per individuare e monitorare possibili criticità di sicurezza.

### 3.8 Configurazione Honeypot e sistema di protezione tramite Whitelist

È stato configurato un Honeypot per monitorare eventuali tentativi di connessione e individuare accessi non autorizzati.

È stato inoltre implementato un sistema di controllo basato su una Whitelist contenente gli indirizzi IP autorizzati.

Attività svolte:

- Installazione e configurazione dell'Honeypot.
- Implementazione di una lista di indirizzi IP autorizzati.
- Configurazione del controllo sugli indirizzi IP che tentano di accedere al sistema.
- Blocco automatico degli indirizzi IP non presenti nella Whitelist.
- Implementazione di un blocco temporaneo della durata di 24 ore.
- Monitoraggio dei tentativi di connessione e degli accessi sospetti.

**Funzionamento del sistema:**

1. Un dispositivo tenta di connettersi all'Honeypot.
2. Il sistema verifica se l'indirizzo IP è presente nella Whitelist.
3. Se l'indirizzo IP è autorizzato, viene gestito secondo le regole di accesso configurate.
4. Se l'indirizzo IP non è presente nella Whitelist, viene automaticamente bloccato per 24 ore.

**Obiettivo:** realizzare un sistema automatizzato di controllo degli accessi, monitoraggio delle connessioni e blocco temporaneo degli indirizzi IP non autorizzati.

# 4. Configurazione, aggiornamento e hardening di Ubuntu Server 26.04.1 LTS

Ubuntu Server 26.04.1 LTS è stato installato sul Raspberry Pi e utilizzato come ambiente server per le attività di laboratorio.

Le attività di configurazione e sicurezza del sistema vengono documentate attraverso le seguenti aree:

- Installazione del sistema operativo.
- Configurazione iniziale del server.
- Configurazione della rete.
- Aggiornamento del sistema operativo e dei pacchetti.
- Verifica degli utenti e dei relativi privilegi.
- Controllo dei servizi attivi.
- Verifica delle porte in ascolto.
- Configurazione del firewall.
- Verifica delle impostazioni di accesso remoto.
- Applicazione delle misure di hardening.

**Nota:** per ogni intervento di aggiornamento e hardening dovranno essere aggiunti i comandi utilizzati e le modifiche effettivamente effettuate.

# 5. Setup e attività con Flipper Zero

Questa sezione è dedicata alla documentazione delle attività effettuate con Flipper Zero.

Aspetti da documentare:

- Configurazione iniziale del dispositivo.
- Verifica del firmware.
- Funzionalità utilizzate.
- Eventuali prove pratiche effettuate.
- Risultati delle attività.

**Nota:** completare questa sezione con le attività effettivamente svolte durante il laboratorio.

# 6. Sfide pratiche di cybersecurity – Battle1 (Raspberry Pi)

Durante il pomeriggio sono state affrontate diverse sfide pratiche di cybersecurity, con l'obiettivo di mettere in pratica le conoscenze acquisite e approfondire il funzionamento delle tecniche di attacco e degli strumenti utilizzati.

L'obiettivo è stato quello di completare il maggior numero possibile di esercizi, affrontando anche attività che inizialmente richiedevano uno studio preliminare.

Per alcune sfide è stato necessario documentarsi sulle tecniche di attacco coinvolte, comprenderne il funzionamento e successivamente applicare le conoscenze acquisite per individuare la soluzione dell'esercizio.

### 6.1 Ambiente di lavoro

Per affrontare diverse sfide è stato utilizzato Kali Linux come ambiente principale di lavoro.

### 6.2 Strumenti utilizzati

**Kali Linux**

Distribuzione Linux dedicata alla sicurezza informatica, utilizzata per svolgere le attività pratiche e sperimentare diversi strumenti.

**John the Ripper**

Strumento utilizzato per attività di analisi delle password e verifica della robustezza delle credenziali.

**Wireshark**

Strumento utilizzato per l'analisi del traffico di rete, l'ispezione dei pacchetti e l'interpretazione delle comunicazioni tra dispositivi.

### 6.3 Svolgimento delle sfide

Durante gli esercizi è stato necessario:

- Analizzare le tracce e gli obiettivi delle singole sfide.
- Comprendere le tecniche di attacco richieste.
- Documentarsi sul funzionamento degli strumenti.
- Effettuare prove pratiche utilizzando Kali Linux.
- Utilizzare John the Ripper per le attività relative alle password.
- Utilizzare Wireshark per analizzare il traffico di rete.
- Interpretare i risultati ottenuti.
- Cercare soluzioni attraverso la sperimentazione.

Per approfondire alcuni concetti tecnici è stato utilizzato anche Claude come supporto didattico, soprattutto durante le attività con Wireshark, per comprendere meglio l'interpretazione dei pacchetti e le funzionalità dello strumento.

**Risultato:** acquisizione di maggiore familiarità con gli strumenti di penetration testing e analisi di rete, sviluppando capacità di ricerca autonoma, problem solving e comprensione delle tecniche utilizzate negli esercizi.

**Dettagli da integrare:** elenco delle singole sfide affrontate, livello di completamento, difficoltà incontrate e risultati ottenuti.

# 7. Altre attività degne di nota

Oltre alle attività principali sono stati effettuati approfondimenti relativi agli strumenti e alle tecnologie utilizzate.

In particolare:

- Familiarizzazione con diversi strumenti di cybersecurity.
- Collaborazione nella configurazione dell'infrastruttura di rete.
- Analisi delle informazioni raccolte dai dispositivi.
- Approfondimento delle tecniche di monitoraggio.
- Ricerca autonoma delle informazioni necessarie per risolvere gli esercizi.
- Utilizzo di strumenti di intelligenza artificiale come supporto all'apprendimento.

# 8. Strumenti utilizzati

| Strumento | Utilizzo |
|---|---|
| Raspberry Pi | Hardware principale del laboratorio |
| Ubuntu Server 26.04.1 LTS | Sistema operativo installato sul Raspberry Pi |
| Wazuh | Monitoraggio e analisi della sicurezza |
| Wazuh Agent | Raccolta delle informazioni dai dispositivi monitorati |
| Nmap | Scansione e analisi della rete |
| Hydra | Test di autenticazione |
| Honeypot | Monitoraggio delle connessioni |
| Whitelist | Gestione degli indirizzi IP autorizzati |
| Kali Linux | Ambiente per le attività pratiche |
| John the Ripper | Analisi delle password |
| Wireshark | Analisi del traffico di rete |
| Flipper Zero | Attività di sperimentazione hardware |
| Claude | Supporto didattico e approfondimento tecnico |
| GitHub | Documentazione delle attività |

# 9. Allegati e documentazione tecnica

Per rendere il report completo e riproducibile, è possibile aggiungere al repository i seguenti materiali di supporto.

| Allegato | Descrizione |
|---|---|
| Screenshot Raspberry Pi | Configurazione e funzionamento del dispositivo |
| Screenshot Ubuntu Server | Informazioni sul sistema operativo |
| Screenshot Wazuh | Dashboard e vulnerabilità individuate |
| Screenshot Wazuh Agent | Stato degli agenti monitorati |
| Screenshot Nmap | Risultati delle analisi di rete |
| Screenshot Wireshark | Esempi di analisi del traffico |
| Screenshot Battle1 | Sfide affrontate e risultati |
| Script Honeypot | Codice utilizzato per la gestione della Whitelist e del blocco IP |
| Configurazioni Ubuntu | File e impostazioni del server |
| Configurazioni Wazuh | Configurazioni della piattaforma e degli agenti |
| Report CVE | Vulnerabilità individuate e relative informazioni |

Eventuali indirizzi IP pubblici, credenziali, chiavi private, token e informazioni sensibili dovranno essere oscurati prima della pubblicazione su GitHub.

# 10. Obiettivi raggiunti

Le due giornate di laboratorio hanno permesso di affrontare diverse attività nell'ambito della sicurezza informatica.

Le principali competenze e attività sviluppate riguardano:

- Configurazione e gestione del Raspberry Pi.
- Installazione di Ubuntu Server 26.04.1 LTS.
- Configurazione dell'infrastruttura di rete.
- Utilizzo di Wazuh per il monitoraggio della sicurezza.
- Analisi delle vulnerabilità e delle CVE.
- Individuazione degli indirizzi IP.
- Utilizzo di Nmap e Hydra.
- Configurazione di un Honeypot con sistema di Whitelist.
- Implementazione del blocco automatico degli IP non autorizzati per 24 ore.
- Utilizzo di Kali Linux.
- Analisi delle password tramite John the Ripper.
- Analisi del traffico di rete tramite Wireshark.
- Sperimentazione pratica attraverso le sfide Battle1.
- Ricerca autonoma e risoluzione di problematiche tecniche.

P.s su alcune cose ho avuto difficolta soprattutto nel non conoscere proprio tutti i tipi di attacchi che servivano per gli esercizi del pomeriggio ma li mi sono fatto aiutare dalla AI 



P.s ho spippolettato con il flipper 0 
