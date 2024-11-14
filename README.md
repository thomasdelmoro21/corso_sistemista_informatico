# Corso Sistemista Informatico
***Dare più importanza agli aspetti delle reti locali, dispositivi NAS, server e roba simile***

---

## LINUX
- Guardare video della [playlist](https://youtube.com/playlist?list=PLqCTMbdFWqyarZ79nAVpFf1uRGqcqpB2W&si=zJffFiNN7DhzzrDa)
- Ricordarsi bene i comandi base della bash (terminale).
- Tip: se hai la possibilità sul tuo pc segui il tutorial sull'installazione di Linux con VM (es. con VirtualBox) e prova a metterci un po' le mani (creare cartelle, spostare file, eseguire script, installare app...) così impari bene come funziona Linux e ti fai anche un'idea di cosa sono i sistemi di virtualizzazione.


## ATTIVITA SISTEMISTICHE NELLE RETI LOCALI
Parti sempre dalla playlist sopra.  
Inoltre all'incirca un sistemista deve conoscere le seguenti cose quindi cerca di farti un'infarinatura generale e concentrarti su cosa sono e a cosa servono le cose in grassetto. (Cerca su youtube o semplicemente fai domande specifiche a ChatGPT).
### Gestione Server
- **Installazione e Configurazione del Sistema Operativo**: Saper configurare sistemi operativi server (ad esempio, Windows Server o distribuzioni Linux).
- **Gestione dei Ruoli di Server**: Studiare indicativamente come configurare e amministrare servizi come **DHCP**, **DNS**, **file server**, **server web**, e **database server**.
- **Gestione della Sicurezza**: Studiare **firewall**, regole di accesso, e come applicare patch di sicurezza per proteggere il sistema.
- Backup e Ripristino: Sapere cosa sono Backup e Ripristini.
- Virtualizzazione: Conoscere soluzioni di virtualizzazione (ad esempio, VMware o Hyper-V) per ottimizzare l'uso dell'hardware (vedi dopo).
### Gestione Client
- **Installazione e Configurazione dei Sistemi Operativi**: Saper configurare e gestire i computer client con sistemi operativi come Windows, macOS o Linux.
- Gestione delle Identità Utente: Configurare e amministrare utenti, gruppi e permessi tramite servizi come Active Directory o altre soluzioni di gestione centralizzata.
- Configurazione delle Politiche di Gruppo (GPO): Implementare politiche di sicurezza e configurazioni specifiche per i computer client.
- Configurazione della Condivisione dei File: Configurare l'accesso ai file server e gestire le autorizzazioni per la condivisione di file.
### Gestione Rete
- **Configurazione del Router e Switch**: Conoscere dispositivi di rete per garantire connettività, **VLAN**, e routing tra sottoreti.
- Gestione del Wi-Fi: Configurare e mantenere punti di accesso (modem) wireless, garantendo che le reti siano sicure e ben funzionanti.
- **Firewall e Sicurezza della Rete**: Conoscere firewall per proteggere la rete da accessi non autorizzati.
- **Gestione degli IP**: Conoscere basi degli **indirizzi IP**, configurazioni **DHCP** per la distribuzione automatica degli indirizzi.
## SISTEMI DI VIRTUALIZZAZIONE
- **Virtualizzazione del Server**: consente di eseguire più macchine virtuali su un server (VM) in modo da accedere ai dati e alle risorse computazionali da più client anche contemporaneamente. Guardare quali sono i principali hypervisor (**VMware**, **Microsoft Hyper-V** e Xen)
- **Virtualizzazione del Desktop**: VDI, RDP
- **Virtualizzazione delle Apllicazioni**: Garantisce che gli applicativi siano accessibili dal client anche senza installarli direttamente. Guardare come funziona **Docker**.

## SISTEMI DI STORAGE
è la parte più difficile su cui trovare documentazione.  
Studiare:
- Memorie locali di base: HDD, SSD, SSD NVME
- **NAS**: dispositivo di archiviazione connesso alla rete. Guardare su youtube come costruire e configurare un NAS.
- DAS: sapere che è un dispositivo di archiviazione colegato direttamente al server tramite cavo.
- SAN, iSCSI: sapere piu o comeno cosa sono
- **Cloud**: sapere all'incirca cosa sono Amazon AWS, Google Cloud Storage e Microsoft Azure Blob Storage in termini di archiviazione

## BASI DI RETI DI TRASMISSIONE
- Libro: Reti di Telecomunicazione
- Tips: Non ti perdere troppo nei discorsi lunghi e incomprensibili, concentrati soprattutto su quello che scrivo tra i capitoli, guarda sempre le figurine e soprattutto i disegnini, se c'è roba di storia salta sempre.
- Capitoli: 1 (tutto), 4 (4.1, 4.2, 4.4, 4.5 concentrarsi sull'avere un'idea di come è fatto un IPv4, IPv6 si può anche saltare, 4.7.2, 6.1 capire bene cos'è e come è fatto un MAC Address, 6.3 da sapere nel dettaglio tutti i dispositivi cercare anche su internet, 6.4, 7.1.1, 15.1, 15.2, 15.3, 15.4, 15.4 concentrarsi su come funzionano crittografie con chiave pubblica e chiave privata, 15.5


## BASI DI DATI E SQL
- Libro: Databases Illuminated
- Tips: Impossibile sapere tutto dei database. Cerca di prendere il più possibile dalle slide perché il libro è un casino. Studiati bene come si fanno nella pratica le query ovvero gli esercizi dove c'è SELECT ... FROM ... ecc., purtroppo ho perso gli appunti quindi ci sono pochi esempi che ho trovato su un drive dell'uni. Studiati il file con le domande dell'orale... probabilmente ti chiederanno roba simile o query pratiche.
- Slide: Tutte
- Capitoli Libro: 1 (tutto), 3 (3.1, 3.2, 3.3, 3.4, 3.5, 3.5, 3.7, 3.8), 4 (tutto), 5 (5.1, 5.2, 5.3, 5.4, 5.5), 6 (fare dalle slide), 8 (8.1, 8.2, 8.3, 8.4, 8.5, 8.6 anche qui spiega chiave pubblica, 8.11)


## TECNOLOGIE PER IL WEB
Conoscere all'incirca quali sono i principali paradigmi per la progettazione web:
- Struttura della pagina web (**MarkUp**): **HTML**, Definizione dello stile: **CSS**, Dinamicità del sito (**Javascript**)  --> [video semplice youtube](https://www.youtube.com/watch?v=n8UExVPB2Pw)
- Indicativamente cos'è il **PHP**
- Sapere bene distinzione tra backend e frontend
- Avere idea di quali sono framework più nuovi per frontend (**React**, **Angular**) e backend (**Django**, **Node.js**)
- Conoscere basi di SQL (vedi sopra)
- Sapere BENE cosa sono **RESTful API** (GET, POST, PUT, DELETE) e cosa sono i **WebSocket**

## SICUREZZA INFORMATICA E PROTEZIONE DEI DATI
- Dovrebbero bastare le basi di sicurezza al capitolo 15 del libro di reti e quelle dei dati nel capitolo 8 sui database
