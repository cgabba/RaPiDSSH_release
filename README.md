# RaPiDSSH Distribution & Release Repository

Repository ufficiale per la distribuzione e l'aggiornamento automatico di **RaPiDSSH** (Remote Desktop & SSH Session Manager).

## 🚀 Ultima Versione: **v1.4.71**
- **Data rilascio**: 2026-11-09
- **Pacchetto Portable (Zero Installazione)**: [Scarica RaPiDSSH-v1.4.71-Portable.zip](https://github.com/cgabba/RaPiDSSH_release/releases/download/v1.4.71/RaPiDSSH-v1.4.71-Portable.zip)
- **Feed Manifest Aggiornamenti**: [version.json](https://raw.githubusercontent.com/cgabba/RaPiDSSH_release/main/version.json)

### Novità di questa versione:
Novità di RaPiDSSH v1.4.71:

• Normalizzazione Automatica NTLM per UltraVNC MS-Logon II: risolta l'incompatibilità nell'autenticazione con credenziali di dominio contenenti suffissi DNS/FQDN (es. 'dominio.it\utente' o formato UPN 'utente@dominio.it'). Il motore VNC converte automaticamente il dominio nel formato NetBIOS piatto richiesto dall'SSP NTLM di Windows, prevenendo il rifiuto delle credenziali.
• Gestione Avanzata Protezione Anti-Brute-Force: rilevamento dello stato di blocco temporaneo dell'IP lato server UltraVNC con avviso informativo chiaro sui tempi di attesa per il ripristino.

---
*Per il codice sorgente e la documentazione del progetto, visitare il repository principale.*
