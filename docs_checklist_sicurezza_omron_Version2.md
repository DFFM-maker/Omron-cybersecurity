# Checklist operativa interna – Sicurezza OMRON automazione

## 1. Autenticazione utenti Sysmac Studio
- [ ] Attivare autenticazione utenti su Sysmac Studio e controller NJ/NX
- [ ] Definire ruoli e permessi granulari (admin, designer, operator, observer)
- [ ] Gestire rotazione, complessità e scadenza delle password
- [ ] Abilitare e monitorare il logging degli accessi e delle operazioni

## 2. Criptazione delle comunicazioni Sysmac Studio → PLC
- [ ] Abilitare Secure Communication (TLS) tra Sysmac Studio e PLC
- [ ] Usare protocolli sicuri: OPC UA, DB Connection Service, VPN per accessi remoti
- [ ] Configurare correttamente le impostazioni di connessione sicura

## 3. Firewall perimetrale e segmentazione rete
- [ ] Implementare firewall perimetrale su singola macchina (esempio: Flowpack) o linea
- [ ] Segmentare la rete: VLAN, filtraggio pacchetti, chiusura porte TCP/UDP non necessarie
- [ ] Definire policy di accesso e di monitoraggio del traffico

## 4. Funzioni di sicurezza nei controller OMRON
- [ ] Proteggere file progetto e programmi utente (password, no restoration info, write protection)
- [ ] Abilitare access log e audit trail
- [ ] Pianificare e gestire aggiornamenti firmware/software
- [ ] Applicare funzioni di “complete erasure” sui dispositivi smaltiti

## 5. Formazione, policy, esempi pratici
- [ ] Erogare formazione periodica su security policy e rischi agli operatori
- [ ] Documentare e applicare best practice per la gestione quotidiana della sicurezza
- [ ] Eseguire simulazioni, demo e audit regolari basati su esempi reali

---

**Note:**  
- Aggiornare la checklist in base alle evoluzioni normative e ai feedback dal team.
- Richiedere a Omron esempi pratici, checklist minime e supporto per audit.