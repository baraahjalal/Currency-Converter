# 💱 Currency Converter

A **C# .NET Framework WinForms** application designed to provide simple and modern **currency exchange functionality**, built using **JSON files** for data storage and management.
This is an **early development version** focusing on the core conversion logic, user interface, and structure.

---

## 🚀 Overview

**Currency Converter** lets users:

* Convert between currencies using up-to-date exchange rates.
* Manage and update currencies locally through JSON files.
* Save and access favorite conversions.
* View a detailed conversion history.
* Log in (UI implemented; authentication logic in progress).

---

## 🧩 Current Features

| Feature                    | Description                                                                         |
| -------------------------- | ----------------------------------------------------------------------------------- |
| 💰 **Currency Conversion** | Convert amounts between different currencies using current or saved exchange rates. |
| 📂 **Currency Management** | Add, remove, or modify available currencies via the management form.                |
| ⭐ **Favourites**           | Mark specific currency pairs as favorites for quick access.                         |
| 🕓 **History**             | Keeps track of previous conversions.                                                |
| 🔐 **Login**               | Basic user login form (under development).                                          |
| 🏠 **Main Dashboard**      | Central navigation form connecting all features.                                    |

---

## 🛠️ Tech Stack

* **Language:** C#
* **Framework:** .NET Framework (WinForms)
* **Data Format:** JSON
* **IDE:** Visual Studio

---

## 📁 Project Structure

```
CurrencyConverter/
│
├── Classes/
│   ├── Currency.cs             → Represents a currency entity (code, name, rate, etc.)
│   └── CurrencyManager.cs      → Handles currency data loading/saving from JSON
│
├── Forms/
│   ├── CurrencyManagement.cs   → Manage currency records and data
│   ├── FrmConverter.cs         → Main converter UI
│   ├── FrmFavourites.cs        → Favorite conversions list
│   ├── FrmHistory.cs           → Conversion history
│   ├── FrmLogin.cs             → User login screen
│   └── FrmMain.cs              → Main application window
│
├── CurrencyCard.cs             → UserControl used to display a currency item visually
├── App.config                  → Application configuration file
├── packages.config             → NuGet package references
└── Program.cs                  → Application entry point
```

---

## ⚙️ Setup Instructions

1. Clone or download this repository.
2. Open the solution in **Visual Studio**.
3. Ensure **.NET Framework** (version 4.x or later) is installed.
4. Run the project — the main form (`FrmMain`) will launch automatically.
5. JSON data files should be placed in the project’s directory (for example: `currencies.json`).

---

## 🧭 Planned Improvements

* 🌐 Integrate real-time exchange rate API.
* 💾 Save user preferences and settings.
* 🎨 Enhance the UI with modern WinForms styling.
* 👤 Complete the login system and user profiles.
* 🧮 Improve error handling and validation.

---

## 👤 Author

**Baraah Arebi**


---

## 🏗️ Status

🚧 *This project is currently under active development. The structure and forms are in place, with logic implementation ongoing.*

---

**Last updated:** February 2026
