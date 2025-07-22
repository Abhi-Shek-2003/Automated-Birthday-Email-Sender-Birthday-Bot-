# Automated-Birthday-Email-Sender-Birthday-Bot-

An automated system to send designed birthday wishes via Microsoft Outlook using dynamic employee data, personalized cards, and custom placements.

---

## 📌 Overview

**Automated-Birthday-Email-Sender-Birthday-Bot** automatically:
- Reads employee birthday details from an Excel sheet
- Generates a birthday card with employee photos and names placed on a custom background template
- Sends an email through Microsoft Outlook to all employees whose birthdays fall on the current day
- BCCs a fixed recipient (e.g., HR/Operations team)

---

## 🚀 Features

- 💼 Outlook email automation with embedded images
- 🧠 Reads birthdays dynamically from `employees.xlsx`
- 🖼️ Custom background template (`bg1.png`)
- 🧍 Dynamic image and name placement using `NewplacementsTry.json`
- 📏 Auto-resizes the final card (reduced to 65% of original size)
- 🗓️ Can be scheduled to run daily at 11:00 AM IST using Task Scheduler + `.bat` file

---

## 🗂️ Directory Structure

