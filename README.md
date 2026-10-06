# PharmERP
💊 PharmERP Pro - Offline Medicine Shop ERP & POS
Version 1.0.0 — Advanced Desktop Medicine Shop Management System with Local SQLite & GitHub OTA Auto-Updates.
🌟 Key Features (প্রধান বৈশিষ্ট্যসমূহ)
🔒 100% Offline-First: Operates fully offline using a local encrypted SQLite database stored securely in %APPDATA%\MedicineERP.
⚡ Fast POS Billing: Pack + Loose conversions, FEFO (First Expired, First Out) batch tracking, and barcode scanning support.
🔄 Simplified Returns & Adjustments: Customer/Supplier returns, Credit Notes, Cash Refunds, and automated ledger adjustments.
📊 Comprehensive Reports: Sales, Purchase, Stock Expiry, Profit/Loss, and Dues position reports with instant printing.
🔄 GitHub OTA Auto-Updates: Built-in auto-updater configured to pull seamless updates directly from GitHub Releases.
📥 Download & Installation (ইনস্টলেশন গাইড)
Go to the Assets section below.
Download PharmERP Pro Setup 1.0.0.exe.
Run the installer and follow the on-screen instructions to create a desktop shortcut.
🛠️ Developer Build Guide (.exe তৈরি করার নির্দেশিকা)
If you want to build the Windows .exe installer locally from the source code, follow these steps in your terminal:
code
Bash
# 1. Clone the repository
git clone https://github.com/madeeasyall/Medicine-ERP-.git
cd Medicine-ERP-

# 2. Install dependencies
npm install

# 3. Build and package the Windows .exe installer
npm run electron:dist
Build Output: Once the build process is complete, you will find the generated .exe installer inside the dist_electron/ folder.
📋 Changelog (v1.0.0)
Initial release of PharmERP Pro with full offline SQLite architecture.
Added robust return management, print preview formatting, and automated GitHub release updater.
