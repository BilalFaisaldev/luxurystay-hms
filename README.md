
#  LuxuryStay Management Suite

> **LuxuryStay Management Suite** is a premium, professional, and fully-functional Hotel Management System (HMS) designed to streamline end-to-end hospitality operations. Crafted with an elegant and modern **"Natural Tones"** design theme, this software elevates hotel, resort, and boutique stay management into a seamless digital experience.

---

##  Visual Identity & The "Natural Tones" Aesthetic

The interface is engineered to evoke a high-end, luxury boutique vibe, prioritizing aesthetic warmth, readability, and modern minimalism:

*   **Warm & Eye-Safe Color Palette:** Features a sophisticated blend of soft off-whites (`#FAF9F6`), deep rich charcoal (`#2D2926`) for structural elements, and premium gold/brass accents (`#C5A059`) for brand highlights.
*   **Elegant Typography:** A curated combination of classic serif typography (Lora/Georgia) for editorial-style headings, paired with clean, readable sans-serif (Inter) and JetBrains Mono for interactive controls and data states.
*   **Bento Grid Layouts:** Dashboard cards and room modules are built using structured Bento-style grids, featuring soft borders, subtle shadows, and fluid interactive hover animations.

---

##  Core Functional Modules

### 1. Interactive Dashboard (Main Console)
*   **Real-time Metrics:** Elegant counters displaying live performance indicators including Occupancy Rate, Average Daily Rate (ADR), Daily Revenue, and Active Guest statistics.
*   **Visual Analytics:** Interactive charts (powered by Recharts/D3) displaying Verified Revenue Flow, Room Allocation Status (Pie Charts), and historical monthly occupancy trends.

### 2. Rooms & Suites Inventory Management
*   **Visual Grid Layout:** A comprehensive, single-screen live inventory system of all rooms.
*   **Real-time Room Status:** Distinct, color-coded visual indicators showing whether a room is **Available**, **Occupied**, **Cleaning**, **Maintenance**, or **Reserved**.
*   **Smart Filters:** Rapid filtering of rooms by Category (e.g., Suite, Deluxe, Standard) and real-time operational status.

### 3. Reservations & Booking Engine
*   **Complete Guest Lifecycle:** Seamless transactional flow covering booking creation, digital Check-In, and structured Check-Out with instant billing and invoicing.
*   **Instant Search:** High-performance search and filter functionality to locate guests, bookings, or room details in seconds.

### 4. Housekeeping & Concierge Services
*   **Housekeeping Tracker:** Direct tool to flag dirty rooms and dynamically assign cleanup tasks to staff.
*   **Room Service & Dining Hub:** Real-time log and order tracking system for guest requests, including spa sessions, in-room dining, laundry, and specialized concierge services.

### 5. Maintenance Desk & Guest Feedback
*   **Issue Logging:** Facility to report room maintenance issues (e.g., HVAC, plumbing, electrical faults) mapped with priority levels (Low, Medium, High) and staff assignments.
*   **Feedback & Sentiment Hub:** A specialized guest review monitor displaying real-time feedback scores and basic sentiment classification to help optimize hotel hospitality standards.

### 6. Role Simulator & Live Settings
*   **Role Switcher:** Instant administrative simulations allowing you to switch between **Super Admin**, **Hotel Manager**, **Receptionist**, **Housekeeping**, **Maintenance**, or **Guest** roles to test varied permission layers.
*   **Operational Control Panel:** Quick configurations for shift timings, general hotel metadata, and basic security overrides.

---

##  Tech Stack

*   **Frontend:** React.js, TypeScript, Vite, Tailwind CSS
*   **Styling & UI:** Custom "Natural Tones" palette, Lucide React (Icons)
*   **Charts & Visualization:** Recharts / D3.js
*   **State & Tooling:** Bun / Node.js, TSConfig

---

##  Getting Started

### Prerequisites
Make sure you have [Bun](https://bun.sh/) or [Node.js](https://nodejs.org/) installed.

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/BilalFaisaldev/luxurystay-hms.git](https://github.com/BilalFaisaldev/luxurystay-hms.git)
   cd luxurystay-hms
Install dependencies:

Bash

bun install# or
npm install
Set up Environment Variables:
Duplicate the .env.example file and rename it to .env:

Bash

cp .env.example .env
(Note: Make sure to fill in your environment variables inside the .env file. Do not push your real .env file to GitHub!)
Start the development server:

Bash

bun run dev# or
npm run dev
Build for production:

Bash

bun run build# or
npm run build
yay bhi paste karon

👤 Author

Developed by Bilal Faisal Arain

Role: Full Stack Web Developer & QA Tester

Location: Karachi, Pakistan 🇵🇰

Email: bilaifaisalarain@gmail.com

GitHub: @bilaifaisaldev

Instagram: @bilal.faisalarain

project-link: https://luxurystay-hms-103758282821.asia-southeast1.run.app/

   
