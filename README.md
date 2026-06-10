# Automated-Sorting-and-Assembly-System
Progetto di automazione industriale sviluppato in TIA Portal e Factory I/O, finalizzato alla realizzazione di una linea automatizzata per l’assemblaggio, il trasporto e lo smistamento di prodotti in base al colore.
Descrizione

Il sistema simula una linea industriale composta da nastri trasportatori, un robot cartesiano Pick & Place, un transfer di smistamento, elevatori e stazioni di uscita. L’intero impianto è controllato da un PLC Siemens S7-1200 attraverso una logica modulare basata su Sequential Function Chart (SFC), che coordina le diverse sequenze operative e garantisce il corretto flusso dei materiali. Lo SFC è particolarmente adatto alla gestione di processi sequenziali e a eventi discreti tipici dell’automazione industriale.

Funzionalità principali
Alimentazione automatica dei pallet.
Assemblaggio mediante robot cartesiano Pick & Place.
Trasferimento dei prodotti tra le diverse stazioni.
Riconoscimento del colore tramite sensori dedicati.
Smistamento automatico verso differenti linee di uscita.
Gestione di due elevatori per la movimentazione verticale dei prodotti.
Conteggio automatico dei pezzi lavorati.
Sistema di supervisione HMI/SCADA.
Gestione degli allarmi e delle anomalie operative.
Comandi di sospensione, reset e ripartenza controllata dell’impianto.
Architettura software

Il progetto è stato sviluppato seguendo una struttura modulare basata su Function Block (FB) indipendenti:

Conveyor Belt
Pick & Place Robot
Transfer System
Sorting Conveyors
Elevators
Supervisor
Main Coordinator

Ogni modulo implementa la propria logica sequenziale tramite SFC, mentre il blocco Main si occupa del coordinamento generale e dello scambio delle informazioni tra i sottosistemi.

Supervisione HMI

L’interfaccia HMI consente:

Monitoraggio in tempo reale dello stato dell’impianto.
Visualizzazione dei conteggi di produzione.
Segnalazione degli allarmi.
Gestione dei comandi operatore.
Diagnostica e supervisione del processo.

Le funzionalità di supervisione e monitoraggio sono tipiche delle piattaforme SCADA utilizzate nei sistemi industriali.

Tecnologie utilizzate
Siemens TIA Portal
PLC Siemens S7-1200
Sequential Function Chart (SFC)
Ladder Diagram (LAD)
Factory I/O
HMI / SCADA
Obiettivo del progetto

L'obiettivo è simulare una moderna linea di produzione automatizzata, applicando i principi dell'automazione industriale, della programmazione PLC, della progettazione modulare e della supervisione di processo, con particolare attenzione a robustezza, sicurezza operativa e manutenibilità del software.
