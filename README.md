# RaPiDSSH Distribution & Release Repository

Repository ufficiale per la distribuzione e l'aggiornamento automatico di **RaPiDSSH** (Remote Desktop & SSH Session Manager).

## 🚀 Ultima Versione: **v1.4.55**
- **Data rilascio**: 2026-11-05
- **Pacchetto Portable (Zero Installazione)**: [Scarica RaPiDSSH-v1.4.55-Portable.zip](https://github.com/cgabba/RaPiDSSH_release/releases/download/v1.4.55/RaPiDSSH-v1.4.55-Portable.zip)
- **Feed Manifest Aggiornamenti**: [version.json](https://raw.githubusercontent.com/cgabba/RaPiDSSH_release/main/version.json)

### Novità di questa versione:
Novità di RaPiDSSH v1.4.55:

• Gerarchia Visiva Dinamica dell'Albero Server: quando non ci sono connessioni attive tutti i server mostrano il loro colore pieno standard (nero solido in tema chiaro). All'apertura di una o più sessioni, i server inattivi passano a un sobrio grigio discreto per abbattere il rumore visivo, le connessioni attive in background rimangono in colore pieno con indicatore verde vivo ▶, e la sessione correntemente in primo piano viene evidenziata in grassetto con accento visivo dedicato.
• Crash Recovery Journal in Tempo Reale: introdotto il salvataggio incrementale atomico dello stato delle sessioni su active_sessions.json ad ogni apertura/chiusura scheda o finestra flottante, garantendo il ripristino istantaneo di tutte le sessioni anche in caso di arresto forzato o crash dell'applicazione.

---
*Per il codice sorgente e la documentazione del progetto, visitare il repository principale.*
