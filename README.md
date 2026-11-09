# RaPiDSSH Distribution & Release Repository

Repository ufficiale per la distribuzione e l'aggiornamento automatico di **RaPiDSSH** (Remote Desktop & SSH Session Manager).

## 🚀 Ultima Versione: **v1.4.72**
- **Data rilascio**: 2026-11-09
- **Pacchetto Portable (Zero Installazione)**: [Scarica RaPiDSSH-v1.4.72-Portable.zip](https://github.com/cgabba/RaPiDSSH_release/releases/download/v1.4.72/RaPiDSSH-v1.4.72-Portable.zip)
- **Feed Manifest Aggiornamenti**: [version.json](https://raw.githubusercontent.com/cgabba/RaPiDSSH_release/main/version.json)

### Novità di questa versione:
Novità di RaPiDSSH v1.4.72:

• Supporto Completo Tastiera Sessione VNC: implementata la mappatura dinamica dei tasti tramite API Win32 (ToUnicode) con gestione di tutti i layout di tastiera (caratteri accentati, punteggiatura, combinazioni Shift/AltGr, tastierino numerico, tasti funzione e navigazione) e tracciamento affidabile dello stato KeyDown/KeyUp.
• Risolto Blocco e Freeze alla Chiusura Scheda VNC: eliminato il deadlock del thread UI disaccoppiando l'aggiornamento del framebuffer tramite BeginInvoke e gestendo la chiusura e il rilascio del client socket in modo asincrono in background.

---
*Per il codice sorgente e la documentazione del progetto, visitare il repository principale.*
