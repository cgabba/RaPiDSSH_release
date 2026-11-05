# RaPiDSSH Distribution & Release Repository

Repository ufficiale per la distribuzione e l'aggiornamento automatico di **RaPiDSSH** (Remote Desktop & SSH Session Manager).

## 🚀 Ultima Versione: **v1.4.61**
- **Data rilascio**: 2026-11-05
- **Pacchetto Portable (Zero Installazione)**: [Scarica RaPiDSSH-v1.4.61-Portable.zip](https://github.com/cgabba/RaPiDSSH_release/releases/download/v1.4.61/RaPiDSSH-v1.4.61-Portable.zip)
- **Feed Manifest Aggiornamenti**: [version.json](https://raw.githubusercontent.com/cgabba/RaPiDSSH_release/main/version.json)

### Novità di questa versione:
Novità di RaPiDSSH v1.4.61:

• Autenticazione SSH tramite Chiavi Private: introdotto il supporto all'autenticazione con chiavi SSH (Ed25519, RSA, ECDSA) sia per terminali interattivi che per sessioni SFTP, con gestione opzionale di passphrase cifrata.
• Gestione Portabile 'ssh_keys': le chiavi sono organizzate nella sottocartella locale 'ssh_keys'; la procedura di selezione copia automaticamente la chiave nella root portabile per garantire che i collegamenti funzionino sempre anche spostando l'app su un'altra unità o chiavetta USB.
• Backup Completo (.rsbak) con Chiavi Cifrate: il backup e ripristino di sistema include l'intero archivio 'ssh_keys' all'interno del pacchetto protetto da cifratura AES-256-GCM.
• Password Utente Preservata: il campo password rimane indipendente e consultabile per l'esecuzione di comandi 'su' o 'sudo' all'interno delle sessioni SSH.
• Fix Tema Menu Contestuale Editor di Testo: risolto il problema di contrasto dei menu contestuali nativi (Taglia, Copia, Incolla) nelle aree di testo e note, ora perfettamente integrati con il tema Dark attivo.

---
*Per il codice sorgente e la documentazione del progetto, visitare il repository principale.*
