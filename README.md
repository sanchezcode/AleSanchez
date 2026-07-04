# AleSanchez
MyPortfolio
# FoodFlow 🍔📦 – IT Ticketing & SLA Monitor for Restaurants

FoodFlow is a Full Stack web application designed specifically for the fast-paced retail and hospitality sectors. It bridges the gap between store managers facing critical hardware failures (POS, kitchen printers, payment terminals) and L1/L2 IT Helpdesk teams who need to minimize business downtime during peak service hours.

## 🚀 Live Demo & Links
- **Live Demo:** [Link to your deployed app, e.g., Vercel/Render]
- **Frontend Repository:** [Link to frontend code]
- **Backend API Repository:** [Link to backend code]

---

## ✨ Features

- **Instant Ticket Creation:** Simplified, mobile-friendly interface for store crew and managers to report issues in under 30 seconds.
- **Real-Time L1/L2 Dashboard:** Live updating ticket queue powered by WebSockets, allowing technicians to claim and update incidents instantly.
- **SLA-Based Prioritization:** Automated urgency assignment (Critical, High, Medium, Low) based on the affected asset (e.g., a broken main kitchen printer triggers an immediate "Critical" SLA status).
- **Remote Access Logs:** Built-in section to log resolution steps taken via remote tools like AnyDesk or TeamViewer.
- **Analytics & Reporting:** Weekly automated summaries of recurring hardware issues per store location to help with preventive maintenance.

---

## 🛠️ Tech Stack

**Frontend:**
- React.js (Context API for state management)
- Tailwind CSS (For a fully responsive, mobile-first design)
- Axios (API consumption)

**Backend & Database:**
- Node.js & Express.js (RESTful API architecture)
- MongoDB & Mongoose (Flexible schema for multi-site restaurant structures)
- Socket.io (For real-time, bi-directional event communication)

**DevOps & Tools:**
- Git & GitHub (Version control)
- Postman (API testing)

---

## 📦 Database Schema Preview

The application handles relational-like data efficiently using MongoDB ObjectIds to connect `Tickets` to specific `Stores` and `Assets`:

```json
{
  "_id": "64a7b2e9f1a2b3c4d5e6f7a8",
  "storeId": "Store_021_Milan",
  "reporter": "Store Manager",
  "assetType": "POS Terminal / Thermal Printer",
  "issueDescription": "Main receipt printer not printing orders during dinner rush. Status light flashing red.",
  "urgency": "Critical",
  "status": "In Progress",
  "assignedAgent": "Alejandro Sanchez",
  "remoteToolUsed": "AnyDesk",
  "createdAt": "2026-07-04T19:30:00.000Z"
}
