# Parvathy A M · Flutter Developer Portfolio

A responsive, high-performance web portfolio for **Parvathy A M**, Flutter Developer based in Kochi, Kerala.

Featuring interactive mobile app prototype simulators and deep architectural breakdowns for four production Flutter applications:
1. **Telecaller CRM App** — Outbound/inbound call management, verified call tracking, and multi-channel social inbox.
2. **Retail Walk-in, Operations & Staff LMS App** — In-store showroom walk-in tracking, barcode inventory lookup, task dispatch, and staff LMS video courses.
3. **Rent Tracker** — Cross-platform property and cashflow management app built with Flutter (Material 3), Riverpod 2.x, and Supabase PostgreSQL with Row-Level Security (RLS).
4. **Expense Tracker** — Personal finance management, cashflow tracking, category analytics, savings milestones, and bill reminders built with Flutter, Firebase Auth, and local notifications.

---

## 🌟 Featured Projects Overview

### 1. Telecaller CRM App
- **Domain**: Outbound / Inbound Call Management & Sales CRM.
- **Key Features**: Automatic call duration timers and verification, JustDial lead segmentation, follow-up queues (*Today*, *Upcoming*, *Overdue*) with FCM push notifications, and unified social inbox (WhatsApp, Instagram, Facebook).
- **Tech Stack**: Flutter, Dart, Provider, REST APIs, Firebase Auth & FCM.

### 2. Retail Walk-in, Operations & Staff LMS App
- **Domain**: In-Store Showroom Operations, Barcode Inventory & Staff Upskilling.
- **Key Features**: Digital walk-in registration, live camera barcode scanning for instant item pricing and stock levels, sequential staff video training courses with assessment quizzes, daily task delegation with priority matrices, and Role-Based Access Control (Admin vs. Staff).
- **Tech Stack**: Flutter 3.x, Dart, Provider, Camera/Barcode Scanner, Video Player, Firebase.
- **Privacy & Masking**: All screenshots feature sanitized identities (*Alex Rivera · Operations Manager*) and generic retail cluster locations (*Metro Flagship Store*, *Store 101 - Central Hub*, etc.).

### 3. Rent Tracker
- **Domain**: Cross-Platform Property & Cashflow Management (Mobile, Tablet & Web).
- **Key Features**: Clean Layered Architecture, dynamic **Temporal Status Calculation Engine** (`calculateStatus(DateTime now)`) computing Paid/Pending/Overdue statuses on-the-fly without server cron dependencies, dual commercial vs. residential classification, reactive multi-filter stream combining full-text search with status predicates, and zero-trust Supabase PostgreSQL Row-Level Security (`auth.uid() = user_id`).
- **Tech Stack**: Flutter 3.x (Material 3), Riverpod 2.x (AsyncNotifier), Supabase (PostgreSQL + Auth + RLS), Google Fonts Plus Jakarta Sans.

### 4. Expense Tracker
- **Domain**: Personal Finance, Real-Time Expense/Income Ledger & Smart Savings.
- **Key Features**: Frictionless slide-up transaction capture, on-the-fly cashflow calculation engine with instant net balance recalculation, conic-gradient category donut chart & monthly analytics bar chart, horizontal category filtering, target savings goal milestone meters, and local notification reminders for bills and recurring subscriptions.
- **Tech Stack**: Flutter 3.x, Dart, Firebase Auth, Local Notifications, Vector Canvas Charts, Clean Architecture.

---

## 📱 Interactive Prototype Simulator

The web portfolio includes a responsive mobile device frame (`.dev`, `.scr`) with live interactive click-throughs:
- **App 1**: Telecaller App (Login, Dashboard, Leads, Reports, Chat Inbox, Conversation, Lead Form, Add Lead Popup, Call List, Call Details Sheet).
- **App 2**: Retail Walk-in & LMS App (Admin Home, Task List, New Task Creation, Staff Training, Cluster Walk-ins, Side Navigation).
- **App 3**: Rent Tracker App (Electric Indigo & Pure White FinTech theme with Plus Jakarta Sans typography, real-time KPI cashflow card, multi-filter rent ledger, tenant profile details, and add rental entry form).
- **App 4**: Expense Tracker App (Mint & Dark FinTech theme, Overview balance card, dynamic bar chart, transaction log, interactive conic statistics donut chart, monthly category breakdown tabs, bill reminders, target savings milestones, and live add transaction bottom sheet).

---

## 🚀 Running Locally

### Option 1: Direct File Opening
Double-click [`index.html`](file:///c:/flutter_apps/flutter-portfolio/index.html) or open it in any modern browser. All assets, mockups, and interactive prototypes run completely offline.

### Option 2: Local HTTP Server (Node.js)
```bash
# Start the development server
npm start
```
Then visit [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📁 Project Structure

```
flutter-portfolio/
├── index.html       # Complete portfolio website with 4 interactive prototypes & styles
├── server.js        # Lightweight local development server
├── package.json     # Project metadata and start scripts
└── README.md        # Documentation and walkthrough
```

