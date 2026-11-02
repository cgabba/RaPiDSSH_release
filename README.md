# RaPiDSSH Distribution & Release Repository

Repository ufficiale per la distribuzione e l'aggiornamento automatico di **RaPiDSSH** (Remote Desktop & SSH Session Manager).

## 🚀 Ultima Versione: **v1.4.44**
- **Data rilascio**: 2026-11-02
- **Pacchetto Portable (Zero Installazione)**: [Scarica RaPiDSSH-v1.4.44-Portable.zip](https://github.com/cgabba/RaPiDSSH_release/releases/download/v1.4.44/RaPiDSSH-v1.4.44-Portable.zip)
- **Feed Manifest Aggiornamenti**: [version.json](https://raw.githubusercontent.com/cgabba/RaPiDSSH_release/main/version.json)

### Novità di questa versione:
Novità di RaPiDSSH v1.4.44:

• Fix Crash Chiusura Finestre Flottanti: risolta l'eccezione InvalidOperationException che si verificava alla chiusura della finestra indipendente tramite 'X' (gestione sincrona e pulita del ciclo di vita della finestra in OnClosing senza chiamate Close() concorrenti).
• Dock / Undock Sessioni Flottanti: possibilità di sganciare qualsiasi sessione attiva in una finestra indipendente da scheda, tasto destro server o drag&drop, con opzione Always on Top e riaggancio rapido.
• Fix Contrasto Proprietà Cartella & Dialoghi: griglia icone e testi convertiti a temi dinamici per perfetta visibilità in modalità chiara e scura.

---
*Per il codice sorgente e la documentazione del progetto, visitare il repository principale.*
