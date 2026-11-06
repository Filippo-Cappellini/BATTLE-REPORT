# BATTLE-REPORT
azioni, informazioni e attività completate per il progetto 



<img width="907" height="289" alt="1" src="https://github.com/user-attachments/assets/87667583-76a1-446a-91d5-4420be10f756" />





<img width="907" height="300" alt="2" src="https://github.com/user-attachments/assets/6a11280e-95dd-4ac8-929d-1fd7ba1080ed" />




# Cybersecurity Lab – Attività svolte

## Descrizione del progetto

Questo repository documenta le attività svolte durante la configurazione di un ambiente di laboratorio dedicato alla cybersecurity, al monitoraggio della rete e all'analisi delle vulnerabilità.

L'obiettivo è configurare un ambiente basato su Raspberry Pi, installare strumenti di sicurezza informatica e analizzare i dispositivi collegati alla rete.

## Attività completate

### 1. Setup del Raspberry Pi
- Configurazione iniziale del Raspberry Pi.
- Preparazione del sistema operativo.
- Configurazione delle impostazioni di base.
- Verifica del corretto funzionamento del dispositivo.

### 2. Configurazione della rete
- Supporto nella configurazione della rete.
- Verifica della connettività.
- Analisi dei dispositivi collegati alla rete.
- Individuazione degli indirizzi IP dei dispositivi.

### 3. Installazione e configurazione di Wazuh
- Installazione della piattaforma Wazuh.
- Configurazione iniziale del sistema.
- Verifica del funzionamento della dashboard.
- Esplorazione delle funzionalità di monitoraggio e sicurezza.

### 4. Installazione di strumenti di cybersecurity
Installazione e prime prove di alcuni strumenti utili per l'analisi della sicurezza informatica:

- **Hydra:** strumento per il test dell'autenticazione e la verifica della robustezza delle credenziali.
- **Nmap:** strumento per la scansione della rete e l'individuazione di host e servizi attivi.

### 5. Analisi delle vulnerabilità e degli indirizzi IP
- Consultazione delle vulnerabilità rilevate da Wazuh.
- Analisi delle possibili CVE (Common Vulnerabilities and Exposures).
- Identificazione degli indirizzi IP dei dispositivi presenti nella rete.
- Osservazione delle informazioni relative agli host monitorati.
- Verifica delle possibili criticità di sicurezza individuate.

## Strumenti utilizzati

| Strumento | Utilizzo |
|---|---|
| Raspberry Pi | Hardware del laboratorio |
| Wazuh | Monitoraggio e analisi della sicurezza |
| Hydra | Test di autenticazione |
| Nmap | Scansione e analisi della rete |
| GitHub | Documentazione delle attività |

## Obiettivi raggiunti

- Configurazione di un ambiente di laboratorio.
- Familiarizzazione con strumenti di cybersecurity.
- Configurazione di un sistema di monitoraggio tramite Wazuh.
- Analisi della rete e dei dispositivi collegati.

### 6. Configurazione Honeypot e sistema di protezione tramite Whitelist

Installazione e configurazione di un Honeypot per monitorare eventuali tentativi di accesso non autorizzati.

Implementazione di un sistema di Whitelist contenente gli indirizzi IP autorizzati.

Configurazione di un controllo sugli indirizzi IP che tentano di accedere al sistema.

Gli indirizzi IP non presenti nella Whitelist vengono automaticamente bloccati.

Implementazione di un blocco temporaneo della durata di 24 ore per gli indirizzi IP non autorizzati.

Monitoraggio dei tentativi di connessione e degli accessi sospetti.

Funzionamento del sistema

Un dispositivo tenta di connettersi all'Honeypot.

Il sistema verifica se l'indirizzo IP è presente nella Whitelist.

Se l'indirizzo IP è autorizzato, viene gestito secondo le regole di accesso configurate.

Se l'indirizzo IP non è presente nella Whitelist, viene automaticamente bloccato per 24 ore
- Consultazione e analisi delle vulnerabilità CVE.

### 7. Sfidaa nel pomeriggio 

abbiamo iniziato a fare delle sfide ho provato a farne il più possibile anche se alcune mi sono dovuto prima informare su come si basava l'attacco e di conseguenza risolvere poi l'esercizio   


