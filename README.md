# ⚔️ AoE2 Damage Calculator

An interactive web app that lets you **compare units, civilizations, technologies, and bonuses** to calculate the real combat damage in **Age of Empires II: Definitive Edition**.

Built entirely with **Angular**, all calculations happen client-side — no backend required.

---

## 🧩 Features

- 📊 Compare damage between any two units  
- 🧱 Includes age progression (Dark → Imperial)  
- ⚙️ Takes into account:
  - Unit stats (attack, armor, hit points, attack rate)
  - Class bonuses (e.g., Pikemen vs Mounted)
  - Civilization bonuses (e.g., Bohemians’ +25% bonus damage)
  - Technologies (Forging, Blast Furnace, etc.)
- 🔄 Fully offline: all data stored in JSON files
- 💻 Real-time updates when changing units or civs

---

## 🧠 How it works

The app uses preloaded JSON data for units, technologies, and civilizations.  
Each selection triggers a calculation that considers:

