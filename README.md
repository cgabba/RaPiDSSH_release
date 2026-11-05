# RaPiDSSH Distribution & Release Repository

Repository ufficiale per la distribuzione e l'aggiornamento automatico di **RaPiDSSH** (Remote Desktop & SSH Session Manager).

## 🚀 Ultima Versione: **v1.4.58**
- **Data rilascio**: 2026-11-05
- **Pacchetto Portable (Zero Installazione)**: [Scarica RaPiDSSH-v1.4.58-Portable.zip](https://github.com/cgabba/RaPiDSSH_release/releases/download/v1.4.58/RaPiDSSH-v1.4.58-Portable.zip)
- **Feed Manifest Aggiornamenti**: [version.json](https://raw.githubusercontent.com/cgabba/RaPiDSSH_release/main/version.json)

### Novità di questa versione:
Novità di RaPiDSSH v1.4.58:

• Risolto Bug Ripristino Sessioni Aperte: introdotta la protezione atomica (_isRestorationCheckDone e _isShuttingDown) del journal active_sessions.json all'avvio e allo spegnimento. Risolto il problema per cui il journal veniva inavvertitamente svuotato prima della richiesta di ripristino all'avvio. Aggiunto supporto a percorsi fallback su LocalAppData per installazioni protette da permessi.
• Tema Scuro per Tutti i Menu Contestuali (TextBox & Editor): esteso il template dark globale ai menu contestuali (Taglia, Copia, Incolla) dei campi di testo, eliminando il popup bianco di sistema e garantendo contrasto e visibilità ottimali anche per gli elementi disabilitati.
• Posizionamento Centrato Finestra Video: la finestra video flottante ora si apre sempre centrata sullo schermo/monitor in cui risiede l'applicazione principale.

---
*Per il codice sorgente e la documentazione del progetto, visitare il repository principale.*
