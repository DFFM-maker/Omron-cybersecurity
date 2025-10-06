# Sintesi Sicurezza OMRON – Punti Chiave & Best Practice

---

## 1. Autenticazione utenti su Sysmac Studio Omron
- User authentication, ruoli e logging accessi su PLC NJ/NX.
- Audit trail per tutte le operazioni critiche.

---

## 2. Criptazione delle comunicazioni Sysmac Studio → PLC
- Abilitare Secure Communication (TLS), OPC UA, VPN per accessi remoti.
- Applicazione multilayer: policy interne, difesa fisica, misure tecniche.

---

## 3. Firewall perimetrale – Esempio pratico su macchina/linea
- Implementazione firewall su macchina Flowpack o linea produttiva.
- Segmentazione rete, VLAN, filtraggio pacchetti, chiusura porte TCP/UDP.

---

## 4. Funzioni di sicurezza nei controller OMRON
- Protezione file progetto e user program (password, write protection).
- Aggiornamenti firmware/software pianificati.
- Funzioni di wipe sicuro per dispositivi dismessi.

---

## 5. Esempi pratici & Demo
- Configurazione autenticazione utenti su Sysmac Studio.
- Setup comunicazione criptata tra PC e PLC.
- Implementazione firewall per macchina Flowpack.
- Smaltimento sicuro PLC (complete erasure).

---

## Immagini di riferimento

### Minacce e danni nei sistemi FA:
![Minacce e danni](../img/page_1.png)  
*Esempi di minacce e impatti cyber su sistemi di automazione fabbrica* (Rif. Immagine 3)

---

### Difesa multilayer & funzioni di sicurezza OMRON:
![Difesa multilayer & funzioni](../img/page_2.png)  
*Schema Defense in Depth e funzioni di sicurezza integrate nei controller OMRON* (Rif. Immagine 4)

---

## Takeaways
- Adottare defense in depth multilayer (policy, fisico, tecnico)
- Usare tutte le funzioni di sicurezza disponibili
- Formazione, audit e checklist operativa
- Collaborazione con Omron per esempi pratici e supporto
