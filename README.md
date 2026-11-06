# RaPiDSSH Distribution & Release Repository

Repository ufficiale per la distribuzione e l'aggiornamento automatico di **RaPiDSSH** (Remote Desktop & SSH Session Manager).

## 🚀 Ultima Versione: **v1.4.65**
- **Data rilascio**: 2026-11-06
- **Pacchetto Portable (Zero Installazione)**: [Scarica RaPiDSSH-v1.4.65-Portable.zip](https://github.com/cgabba/RaPiDSSH_release/releases/download/v1.4.65/RaPiDSSH-v1.4.65-Portable.zip)
- **Feed Manifest Aggiornamenti**: [version.json](https://raw.githubusercontent.com/cgabba/RaPiDSSH_release/main/version.json)

### Novità di questa versione:
Novità di RaPiDSSH v1.4.65:

• Supporto Nativo UltraVNC MS-Logon II (Tipo 113 / 0x71): implementata direttamente in C# la negoziazione crittografica Diffie-Hellman a 64 bit e la cifratura a blocchi DES (rfbEncryptBytes2) per consentire l'accesso a server UltraVNC protetti con autenticazione utente/dominio Windows (MS-Logon II), senza richiedere DLL o binari terzi.
• Bridge Stream VNC Ibrido: introdotto MsLogonBridgeStream che completa l'autenticazione Windows ad alto livello sul socket e instrada in modo trasparente il flusso RFB al motore grafico per il rendering del desktop e la gestione completa di mouse e tastiera.

---
*Per il codice sorgente e la documentazione del progetto, visitare il repository principale.*
