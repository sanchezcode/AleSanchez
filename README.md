# 💻 Alejandro Sanchez Toledo
### Full Stack Developer & IT Support Specialist
📍 Nova Milanese (MB) | 📱 3516141114

---

## 👤 About Me
Sono un Perito Informatico specializzato in **Full Stack Development** con esperienza sul campo nel supporto IT L1/L2. La mia esperienza nel settore retail e della ristorazione (da Crew McDonald's a tecnico Helpdesk) mi ha insegnato a lavorare sotto pressione, a comprendere al volo i bisogni degli utenti non tecnici e a risolvere problemi critici in tempi record. Creo applicazioni web moderne e gestisco l'infrastruttura tecnica sottostante.

---

## 🛠️ Tech Stack & Skills
- **Frontend:** HTML5, CSS3, JavaScript (ES6+), React.js
- **Backend:** Node.js, Express, Python, SQL (MySQL/PostgreSQL), REST APIs
- **IT Support & Operations:** Helpdesk L1/L2, Remote Support (AnyDesk, TeamViewer), Networking base (TCP/IP), Windows/Linux
- **Strumenti:** Git, GitHub, Docker, Postman, Sistemi di Ticketing

---

## 🚀 Featured Project: FoodFlow 🍔📦
*Questo è un esempio di sistema Full Stack che ho progettato unendo la mia esperienza nello sviluppo software a quella nell'assistenza tecnica per la ristorazione.*

FoodFlow è una web application progettata per gestire le segnalazioni IT nei fast food e ristoranti, riducendo al minimo il blocco delle vendite durante gli orari di picco.

### ✨ Funzionalità Chiave:
- **Apertura Ticket Rapida:** Interfaccia mobile-friendly per i direttori di punto vendita per segnalare guasti a casse o POS in meno di 30 secondi.
- **Dashboard in Tempo Reale:** Coda dei ticket aggiornata istantaneamente tramite WebSockets per i tecnici L1/L2.
- **Priorità Automatica (SLA):** Assegnazione automatica della gravità in base all'asset bloccato (es. stampante comande cucina = Critical SLA).

### ⚙️ Esempio di Struttura Dati (JSON):
```json
{
  "_id": "64a7b2e9f1a2b3c4d5e6f7a8",
  "storeId": "Store_Milano_02",
  "assetType": "POS Terminal / Printer",
  "issue": "Stampante comande non stampa durante il picco del pranzo.",
  "urgency": "Critical",
  "status": "In Progress",
  "assignedAgent": "Alejandro Sanchez",
  "remoteTool": "AnyDesk"
}
