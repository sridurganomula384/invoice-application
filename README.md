# invoice-application
An application developed to help people with  sorting invoice issues.
InvoiceEase is a browser-based invoice management tool developed using HTML, CSS, and JavaScript. It provides a clean, interactive interface for businesses to create, manage, and print invoices without requiring a backend server. All data is stored locally in the browser, making it lightweight and easy to use.

🔹 Key Features

Invoice Generation – Dynamic invoice creation with editable fields for buyer details, GST, FSSAI, transport info, and delivery terms.

Smart Item Table – Add/remove rows for goods with auto-calculated totals, discounts, and GST.

Autocomplete & History – Frequently used buyer details, transport info, and invoice numbers are stored in LocalStorage and suggested automatically.

Auto Calculations – Real-time computation of totals, super discount, grand total, and conversion of amount to words.

HSN Summary – Automated syncing of HSN/SAC values with taxable amounts.

Persistence with LocalStorage – Each invoice is stored in the browser and can be reloaded by entering the invoice number.

Incremental Invoice Numbers – Next invoice number is generated automatically after printing.

Print-Friendly Mode – Optimized layout for direct printing as a professional invoice.

Bank & Declaration Section – Pre-filled bank details, declaration text, and receiver acknowledgment built into the template.

🔹 Tech Stack

Frontend: HTML5, CSS3 (responsive + print media styling)

Logic & Data Handling: Vanilla JavaScript

Storage: Browser LocalStorage (JSON-based persistence)

Libraries: jsPDF (optional for export), custom autocomplete implementation

Deployment: Runs fully in the browser – can be hosted on GitHub Pages or any static server

🔹 Purpose

The goal of InvoiceEase is to provide a lightweight, offline-friendly, and professional invoice tool for small businesses. By combining a print-optimized layout, smart auto-calculations, and local persistence, it eliminates the need for heavy databases or external dependencies while still delivering a complete invoicing solution.
