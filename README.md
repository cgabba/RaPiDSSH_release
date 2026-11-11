# RaPiDSSH Distribution & Release Repository

Repository ufficiale per la distribuzione e l'aggiornamento automatico di **RaPiDSSH** (Remote Desktop & SSH Session Manager).

## 🚀 Ultima Versione: **v1.4.77**
- **Data rilascio**: 2026-11-11
- **Pacchetto Portable (Zero Installazione)**: [Scarica RaPiDSSH-v1.4.77-Portable.zip](https://github.com/cgabba/RaPiDSSH_release/releases/download/v1.4.77/RaPiDSSH-v1.4.77-Portable.zip)
- **Feed Manifest Aggiornamenti**: [version.json](https://raw.githubusercontent.com/cgabba/RaPiDSSH_release/main/version.json)

### Novità di questa versione:
Novità di RaPiDSSH v1.4.77:

• Risoluzione Crash Multi-Ping (XamlParseException Thread Affinity): eliminata l'allocazione di SolidColorBrush da thread in background tramite la nuova classe NetworkPingBrushes con pennelli congelati (.Freeze()) condivisi tra thread.
• Rilevamento Intelligente Subnet Locale: implementato il probing del routing del kernel Windows e il controllo del Default Gateway attivo, escludendo gli indirizzi fittizi APIPA (169.254.x.x) e identificando subito la scheda reale.
• Icone di Stato Colorate nella Griglia: sostituite le emoji monocromatiche con indicatori vettoriali Ellipse ad alta visibilità (verde vivido e rosso vivo).
• Restyling Tasto 'Annulla Scansione': pulsante in colore neutro da inattivo, con evidenziazione in rosso cremisi vivace (#C0392B) quando la scansione è in corso.

---
*Per il codice sorgente e la documentazione del progetto, visitare il repository principale.*
