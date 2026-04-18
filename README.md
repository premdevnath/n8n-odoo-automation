# n8n Telegram to Odoo Purchase Automation
## 🖼 Workflow Preview

<p align="center">
  <img src="Screenshot 2026-04-18 104956.png" width="800"/>
</p>

## 🔥 Overview

This workflow automates the process of creating Purchase Orders in Odoo ERP using data received from Telegram and Excel.

## ⚙️ Workflow Steps

1. Telegram Trigger receives file/data
2. Vendor checked in Odoo
3. If not found → Vendor created
4. Purchase Order created
5. Excel data extracted and split
6. Products matched in Odoo
7. PO lines created
8. Errors logged if product not found

## 🛠 Tech Stack

* n8n
* Odoo ERP
* Telegram API
* Excel Processing

## 💡 Use Case

* Automates manual purchase entry
* Saves time and reduces human error
* Useful for FMCG / Inventory businesses

## 🚀 How to Use

1. Import JSON into n8n
2. Add credentials (Telegram + Odoo)
3. Run workflow

## 👨‍💻 Author

Prem Devnath
