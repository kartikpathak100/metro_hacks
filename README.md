

# GMRC Master Dispatch & Headway Recommender (PS-04)

An enterprise-grade, offline-first SCADA and Operations Control Center (OCC) dashboard engineered for the **Gujarat Metro Rail Corporation (GMRC)**. Built for the Smart India Hackathon, this system replaces rigid static timetables with dynamic, data-driven headway optimization to prevent station overcrowding during peak commutes, major cultural events (Navratri, IPL matches), and adverse weather shifts.

---

## Key Features

* **Dynamic Headway Optimization Engine:** Automatically computes optimal train frequencies by blending baseline passengers-per-hour (PPH), calendar day-types, weather disruptions, and special event multipliers while strictly respecting fleet rake limits and minimum safe headways ($\text{minH}$).
* **Official Dispatch Order Generator:** Generates a formal, printable OCC Daily Dispatch Order complete with regulatory reference numbers, active condition parameters, and official sign-off blocks for Station Controllers and Chief Controllers.
* **Multi-Platform Dispatch Broadcast:** Instantly packages headway adjustments, operational reasons, and instructions into standardized text blocks optimized for WhatsApp, Telegram, and SMS gateway broadcasting to field staff.
* **Economic & Environmental Impact Tracking:** Quantifies operational value by calculating revenue protected from passenger overflow, cumulative commuter hours saved, and estimated $\text{CO}_2$ tonnage abated by shifting road commuters to mass rapid transit.
* **Multilingual OCC Interface & Offline Resilience:** Offers full interface and broadcast localization across **English**, **Gujarati (ગુજરાતી)**, and **Hindi (हिन्दी)**. Built with 100% client-side local storage, it operates entirely offline to guarantee zero downtime during control room network interruptions.

---

## Technical Architecture

* **Frontend:** Modern HTML5, CSS3 (Responsive Grid & Flexbox), and Vanilla ES6+ JavaScript.
* **State Management & Persistence:** LocalStorage-backed persistence for custom rules, master matrices, and fleet parameters.
* **Deployment:** Lightweight static architecture deployable instantly via GitHub Pages, Vercel, or local OCC server nodes.

---

## Getting Started & Installation

1. **Clone the repository:**
```bash
git clone https://github.com/YOUR_USERNAME/gmrc-metro-planner.git

```


2. **Open the application:**
Navigate into the project directory and open `index.html` in any modern web browser. No backend server installation or database configuration is required.

---

## Deployment (GitHub Pages)

1. Push your project files (`index.html` and `README.md`) to your GitHub repository.
2. Go to your repository **Settings > Pages**.
3. Under **Branch**, select `main` and click **Save**. Your enterprise SCADA dashboard will be live instantly!
