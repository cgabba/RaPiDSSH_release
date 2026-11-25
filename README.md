# RaPiDSSH Distribution & Release Repository

Repository ufficiale per la distribuzione e l'aggiornamento automatico di **RaPiDSSH** (Remote Desktop & SSH Session Manager).

## 🚀 Ultima Versione: **v1.4.98**
- **Data rilascio**: 2026-11-25
- **Pacchetto Portable (Zero Installazione)**: [Scarica RaPiDSSH-v1.4.98-Portable.zip](https://github.com/cgabba/RaPiDSSH_release/releases/download/v1.4.98/RaPiDSSH-v1.4.98-Portable.zip)
- **Feed Manifest Aggiornamenti**: [version.json](https://raw.githubusercontent.com/cgabba/RaPiDSSH_release/main/version.json)

### Novità di questa versione:
Novità di RaPiDSSH v1.4.98:

• Ottimizzazione Ricerca & Virtualizzazione Albero:
  - Introdotto debouncing (160ms) sulla ricerca testuale e abilitata la virtualizzazione UI con riciclo dei nodi (VirtualizingStackPanel) per una digitazione istantanea e fluida.
• Filtro Avanzato Dinamico per Tag (AND/OR & Negazione NOT):
  - Nuovo pulsante filtro avanzato (🌪️) accanto alla barra di ricerca con indicatore di stato attivo.
  - Aggiunta dinamica di N condizioni sui tag, selettore modalità globale TUTTI (AND) / ALMENO UNO (OR), e inversione per singola condizione tra ✔ Include e 🚫 NON ha (negazione).
• Ordinamento Alfabetico Cartelle di Sistema:
  - Supporto ordinamento A-Z / Z-A anche su tutte le cartelle speciali (Connessioni Recenti, Preferiti, Attive, Tutti i Server, Tag e singole cartelle tag) con persistenza su settings.json.
• Fix Doppio Clic TreeView:
  - Risolto il disallineamento del doppio clic che poteva aprire un server diverso da quello cliccato risolvendo esattamente il TreeViewItem sotto il cursore.

---
*Per il codice sorgente e la documentazione del progetto, visitare il repository principale.*
