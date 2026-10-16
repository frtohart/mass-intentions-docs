# Mass Intentions Manager — Support & User Manual

Welcome to the official support page and user guide for **Mass Intentions Manager**, an iOS application designed for parish administrators and priests to manage, schedule, and synchronize Holy Mass intentions while maintaining canonical compliance.

---

## 📩 App Support & Contact

If you have questions, feedback, or need assistance with Mass Intentions Manager, please reach out to us:

* **Email Support:** massintentions.support@gmail.com
* **Privacy Policy:** View our [Privacy Policy](privacy)
* **Platform:** iOS 17.0+ (iPhone)

---

## 📖 User Manual & Guide

### 1. Overview & Key Capabilities
Mass Intentions Manager provides a structured workflow to ensure every Mass stipend and obligation is recorded accurately according to Church guidelines.

* **Canonical Safeguards:** Built-in validation for *Missa Pro Populo* (Canons 534/951) and 30 consecutive unbroken days for Gregorian Mass series (Canon 904).
* **Liturgical Protection:** Automatically blocks scheduling on Good Friday and Holy Saturday.
* **Apple Calendar Integration:** Bi-directional event creation and removal via EventKit with custom duration settings.
* **Data Privacy:** Local on-device storage, optional Face ID / Touch ID app lock, local backups, and full CSV import/export.

---

### 2. Viewing & Filtering the Schedule
Navigate to the **Schedule** tab to view all booked and upcoming Mass obligations.

* **View Modes:** Toggle between **Modern Timeline** (visual cards with calendar badges) and **Classic List** (grouped by Today, Upcoming, and Past) in **Settings**.
* **Filter Controls:** Use the top segmented control to filter by **All**, **Today**, **Upcoming**, or **Past**.
* **Search:** Search instantly by intention name, requester, or substitute celebrant.

---

### 3. Booking a New Mass Intention
To record an intention, open the **New Intention** tab:

1. **Intention & Requester:** Enter the intention name (e.g., *Mary O'Connor*), requester name, and toggle **Deceased (R.I.P.)** if applicable.
2. **Missa Pro Populo Quick Switch:** Enable the toggle at the top of the form for non-stipend parish Masses under Canons 534/951.
3. **Mass Type:** Select **Single Mass**, **Triduum**, **Novena**, or **Gregorian (30 Days)**.
   > **Note:** Gregorian series require 30 unbroken daily Masses. If any date in the 30-day window falls on Good Friday or Holy Saturday, the app will flag a conflict and require selecting an alternate start date.
4. **Recurrence:** Toggle **Repeat Intention** to set up weekly, monthly, or yearly recurring offerings with an optional end date.
5. **Stipends & Notes:** Record payment status (**Paid**, **Pending**, **Free**), currency, amount, and internal notes.

---

### 4. Editing, Rescheduling & Substitute Priest Coverage
Tap any item on the **Schedule** tab to open the **Edit Intention** screen:

* **Rescheduling:** Adjust individual date pickers or time slots. Changing the start date of a Gregorian series automatically recalculates all 30 consecutive days.
* **Substitute Priest Coverage:** Enter a guest priest's name in **Substitute Priest** (e.g., *Fr. Joseph*) and tap **Send Coverage Request to Priest** to share details via Messages, WhatsApp, or Mail.

---

### 5. Calendar Synchronization & Backups
* **Syncing Calendar:** Go to **Settings** $\rightarrow$ **Calendar Actions**, enable **Sync to Apple Calendar**, choose a target calendar, and tap **Sync All Existing Masses Now**.
* **Automatic Backups:** In **Settings** $\rightarrow$ **Backups**, choose an auto-backup frequency (**Daily**, **Weekly**, **Monthly**) or select a shared iCloud folder for automated JSON/CSV background exports.
* **CSV Import/Export:** Import spreadsheet records via **Import Intentions from CSV** or export data using **Export Schedule to CSV**.

---

## ❓ Frequently Asked Questions (FAQ)

#### Why is the app blocking me from booking a Mass on Good Friday or Holy Saturday?
Mass intentions cannot be offered on Good Friday or Holy Saturday per universal liturgical law. The app enforces this rule to prevent scheduling conflicts.

#### Where is my data stored?
All data is stored locally on your device using SwiftData. The developer has no access to your parish records, stipend amounts, or personal information.

#### How do I restore data on a new device?
Export a JSON backup from your old device in **Settings** $\rightarrow$ **Backups**, transfer the file via iCloud Drive or AirDrop, and select **Restore Database from Backup** on your new device.

---

## 🛡️ Note for App Store Reviewers (Guideline 2.1)

* **Liturgical Rules:** Date selection restrictions on Good Friday/Holy Saturday and Gregorian series date validation are intentional canonical safeguards (Canons 534, 904, 951).
* **System Integrations:** Calendar access uses standard iOS `EventKit`, and App Lock uses native iOS `LocalAuthentication` (Face ID / Touch ID).

---

## Contact & Support
For assistance, bug reports, or privacy inquiries regarding Mass Intentions Manager, please contact:

* **Support Team:** Mass Intentions Manager Support
* **Email:** massintentions.support@gmail.com
