# RaPiDSSH Distribution & Release Repository

Repository ufficiale per la distribuzione e l'aggiornamento automatico di **RaPiDSSH** (Remote Desktop & SSH Session Manager).

## 🚀 Ultima Versione: **v1.4.39**
- **Data rilascio**: 2026-10-30
- **Pacchetto Portable (Zero Installazione)**: [Scarica RaPiDSSH-v1.4.39-Portable.zip](https://github.com/cgabba/RaPiDSSH_release/releases/download/v1.4.39/RaPiDSSH-v1.4.39-Portable.zip)
- **Feed Manifest Aggiornamenti**: [version.json](https://raw.githubusercontent.com/cgabba/RaPiDSSH_release/main/version.json)

### Novità di questa versione:
Novità di RaPiDSSH v1.4.39:

• Ripristino e Funzionamento Completo Backup Automatico: collegati i trigger per l'esecuzione del backup completo cifrato (.rsbak) all'apertura dell'applicazione (in background non bloccante), alla chiusura (in modalità sincrona protetta) e al salvataggio manuale del database.
• Gestione Sicura Password di Backup: eliminato qualsiasi fallback insicuro sulla password dei file aperti. Il backup automatico richiede ora tassativamente una password dedicata memorizzata in modo protetto tramite Windows DPAPI legata all'utente corrente.
• Interfaccia e Wizard Impostazioni Aggiornati: indicatore di stato visivo chiaro se la password di backup è impostata o mancante, con guida contestuale per impostarla all'abilitazione del servizio o alla richiesta di backup immediato.

---
*Per il codice sorgente e la documentazione del progetto, visitare il repository principale.*
