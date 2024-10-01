-- Relazione sulla virtualizzazione --

La virtualizzazione consente di condividere le risorse hardware con più sistemi operativi o applicazioni contemporaneamente, su un singolo hardware.

Questo processo ci permette di migliorare l'efficenza e l'utilizzo delle risorse hardware. 

Anziché avere 3 computer con 3 sistemi operativi differenti, possiamo avere 1 solo computer con tutti e 3 i sistemi operativi in esecuzione nello stesso momento, condividendo CPU, RAM, SSD...

Questo, oltre che essere vantaggioso a livello personale, lo è ancora di più a livello aziendale. Con gli stessi server, si possono offrire molteplici servizi differenti, senza dover istituire dei server appositi per un singolo servizio.

Questa pratica non riduce solamente i costi di gestione, ma aumenta anche le performance e rende ogni sistema più sicuro, dato che sono isolati e se un sistema viene infettato, questo non può infettare le altre macchine (ogni macchina è in una sandbox).

Per utilizzare le macchine virtuali ci affidiamo agli hypervisor, un software che ci permette non solo di crearle ma anche di gestirle.

Ci sono 3 livelli di hypervisor:

- Livello 1: funzionano direttamente su hardware fisico senza la necessità di un sistema operativo host. Accendo il pc e il sistema è già virtualizzato (ad esempio Windows Subsystem for Linux).

- Livello 2: funzionano sopra un sistema operativo host, che si occupa della gestione dell'hardware. L'hypervisor invece gestisce le macchine virtuali (ad esempio VirtualBox).

- Livello 3: viene virtualizzato il software anziché l'intero sistema operativo (ad esempio Microsoft 365 su MacOS).

-- Compito della lezione 1 --

- Installazione di virtualbox

- Installazione di Kali Linux, Metasploitable e Windows 10 su macchine virtuali

Nota per Windows 10: affinché il sistema si avvi con successo, abilitare l'accelerazione 3d nelle impostazioni del sistema - livello esperto. 128mb di memoria video sono sufficienti.
