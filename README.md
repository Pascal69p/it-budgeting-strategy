#  IT Budget Strategist

> AI-powered IT budget planning and forecasting platform.

&#127942; **Winner — Southwest MN Hacks**

  **Authors:** [github.com/Pascal69p](https://github.com/Pascal69p) & [github.com/Saar0](https://github.com/Saar0)

---

##  Overview

IT Budget Strategist helps organizations plan, track, and forecast technology expenses. Upload Excel spreadsheets, manage budget categories, track actual spending, and use AI to get actionable insights.

---

##  Features

| Feature | Description |
|---|---|
| **Budget Planning** | Create multi-year budgets with quarterly breakdowns |
| **Expense Tracking** | Record actual spending with real-time variance analysis |
| **AI Analysis** | Intelligent insights, recommendations, and risk assessment |
| **Multi-Variable Forecasting** | Model scenarios with inflation, AI investment, cloud adoption, and optimization factors |
| **Excel Import/Export** | Upload existing budgets or export data for external analysis |
| **Historical Trends** | Track performance across multiple fiscal years with CAGR calculations |
| **Data Management** | Local storage, backup, and restore capabilities |

---

##  Tech Stack

| Layer | Technology |
|---|---|
| **Backend** | Node.js, Express.js |
| **Database** | SQLite |
| **Frontend** | HTML5, CSS3, JavaScript |
| **Charts** | Chart.js |
| **Excel Processing** | SheetJS (XLSX) |
| **AI** | Google Gemini API |

---

##  Prerequisites

Before running the project, install:

- [Node.js](https://nodejs.org/) (version 14 or higher)
- npm (included with Node.js)
- A modern web browser

---

##  Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/Pascal69p/it-budgeting-strategy.git
cd it-budgeting-strategy
```

### 2. Install dependencies

```bash
npm install
```

> **Note:** You may see warnings about deprecated packages or a message about one high severity vulnerability. These do not prevent the application from running.

**Optional — audit and fix:**

```bash
npm audit
npm audit fix
```

### 3. (Optional) Update npm

```bash
npm install -g npm@latest
```

### 4. Initialize the database

If you see the message:

```
Database not found. Run npm run init-db first.
```

Run:

```bash
npm run init-db
```

### 5. Start the server

```bash
npm start
```

### 6. Open in your browser

- **App:** [http://localhost:3001](http://localhost:3001)
- **API health check:** [http://localhost:3001/api/health](http://localhost:3001/api/health)

---

##  Usage

1. Upload an Excel budget file or create a new plan
2. Adjust budget categories and investment percentages
3. View forecasts and scenario simulations
4. Generate AI insights and recommendations

---

##  Common Issues and Fixes

| Issue | Solution |
|---|---|
| `node` or `npm` not recognized | Install Node.js, restart your terminal, ensure Node.js is added to PATH |
| Database not found | Run `npm run init-db` |
| Port already in use | Edit `server.js`: `const PORT = 3001;` |
| Gemini API not working | Ensure API key is configured. Some features may not function without it |

---

##  Future Improvements

- Improved UI and UX
- Advanced forecasting models
- Cloud deployment
- Enhanced AI recommendations
- Real-time collaboration features
