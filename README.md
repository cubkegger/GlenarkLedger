# GlenarkLedger
Portable accounting software for farming 
# 🌾 GlenarkLedger for Farms

**GlenarkLedger for Farms** is a specialized, open-source double-entry financial accounting system built specifically for agricultural operations, farm management, and educational instruction. Designed with a clean Tkinter graphical user interface, it provides robust tracking for multi-line voucher groups, inventory, departmental breakdowns, and government tax reporting (GST/QST/TVQ).

---

## 🚀 Key Features

* **Voucher Grouping System:** Groups related transactions (e.g., Expense + Input Tax + Cash Payment) into a single linked financial event with live balance checks.
* **Precision Account Filtering:** Smart search logic that handles short prefix codes (1–2 digits) strictly while allowing full account code lookups (3+ digits).
* **Departmental Cost Accounting:** Track income and expenses across specific farm departments (e.g., Cereal Crops, Livestock, Orchards, Greenhouses).
* **Tax Filter Isolator & Reconciler:** Instantly aggregate and review GST/QST/TVQ input and output tax credits across your active ledger and all historical monthly archives.
* **Monthly & Annual Archiving:** One-click month closures that snapshot active databases into a clean `Archive/` folder and spin up a fresh ledger for the new month.
* **Comprehensive Reporting:** Generate custom account reports, end-of-year category summaries, and export data seamlessly to **CSV**, **XML**, or **print-ready HTML reports**.

---

## 📋 Standard Chart of Accounts Series

GlenarkLedger organizes accounts into standardized number series:
* **10000 Series (Assets):** Cash, bank accounts, accounts receivable, tax input credits, inventory, equipment, and land.
* **20000 & 30000 Series (Liabilities & Equity):** Operating lines, mortgages, loans, and owner's equity.
* **40000 & 60000 Series (Income / Revenue):** Crop sales, livestock sales, dairy pools, and government subsidies (AgriStability/ASRA).
* **50000 & 70000 Series (Expenses & Charges):** Seed, fertilizer, fuel, veterinary care, repairs, and salaries.

---

## 🛠 Installation & Requirements

GlenarkLedger is written in pure Python using standard libraries, making it lightweight and easy to run across platforms.

1. **Prerequisites:** Python 3.8 or higher installed on your system.
2. **Clone the Repository:**
   ```bash
   git clone https://github.com/cubkegger/GlenarkLedger.git
cd GlenarkLedger
📥 [Download GlenarkLedger AppImage for Linux](https://github.com/cubkegger/GlenarkLedger/raw/main/glenark_ledger.appimage)
