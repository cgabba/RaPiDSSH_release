# RaPiDSSH Distribution & Release Repository

Repository ufficiale per la distribuzione e l'aggiornamento automatico di **RaPiDSSH** (Remote Desktop & SSH Session Manager).

## 🚀 Ultima Versione: **v1.4.84**
- **Data rilascio**: 2026-11-13
- **Pacchetto Portable (Zero Installazione)**: [Scarica RaPiDSSH-v1.4.84-Portable.zip](https://github.com/cgabba/RaPiDSSH_release/releases/download/v1.4.84/RaPiDSSH-v1.4.84-Portable.zip)
- **Feed Manifest Aggiornamenti**: [version.json](https://raw.githubusercontent.com/cgabba/RaPiDSSH_release/main/version.json)

### Novità di questa versione:
Novità di RaPiDSSH v1.4.84:

• Cartella Predefinita Log Ping su 'Logs/': apertura e salvataggio dei file di log e report CSV direttamente puntati sulla cartella dedicata 'Logs/' dell'applicazione anziché ereditare cartelle di backup o temporanee.
• Ordinamento Numerico IP nello Scanner di Sottorete: inserimento in tempo reale e ordinamento nativo per valore intero a 32-bit degli ottetti IPv4 (es. 192.168.1.1, 192.168.1.4, 192.168.1.10, 192.168.1.102) anziché l'ordinamento alfabetico/lessicografico.
• Prevenzione Blocco/Hang Sessioni RDP su Disconnessione Rete: configurazione di timeout di arresto RDP rapidi (2s anziché 30s di blocco del thread UI), keep-alive ogni 5 secondi, gestione eventi di auto-riconnessione con badge visivo informativo e rilascio immediato del controllo host per prevenire qualsiasi freeze dell'interfaccia quando l'IP remoto non risponde.

---
*Per il codice sorgente e la documentazione del progetto, visitare il repository principale.*
