# 🏏 PKR Pro Trader V7 (Premium Edition)

**PKR Pro Trader** is a professional, mobile-first bankroll management application designed to help traders and bettors track their daily progress, maintain discipline, and visualize their journey toward a monthly financial target.

It runs entirely in your browser (no internet or server required) and saves data securely on your device.

---

## 🌟 Key Features

### 1. 💼 Session Management
*   **Morning Routine:** Enter your **Opening Balance** to start the day.
*   **Risk Calculator:** Automatically calculates a "Safe Bet Size" (2% - 5% of bankroll) to prevent reckless trading.
*   **Evening Routine:** Enter your **Closing Balance**. The app automatically calculates Profit/Loss.
*   **Stop Loss:** Set a daily loss limit. If you exceed it, the app flags the day with a "Stop Loss Hit" warning.

### 2. 📊 Advanced Analytics
*   **Interactive Graph:** Visualizes your bankroll growth over the month.
*   **Form Guide (Heatmap):** A calendar view showing your last 14 days (Green = Win, Red = Loss, Grey = No Play).
*   **Vital Stats:** Tracks Win Rate (%), Average Win, Average Loss, and Best Day.
*   **AI Prediction:** Calculates the estimated date you will hit your monthly target based on your current average performance.

### 3. 🛡️ Security & Privacy
*   **App Lock:** Secure the app with a **4-Digit PIN**. The app locks automatically when refreshed or closed.
*   **Privacy Mode (Stealth):** Click the 👁️ (Eye) icon to **blur all monetary values**. Perfect for using the app in public without revealing your balance.

### 4. 💾 Data Management
*   **Auto-Save:** Data is saved instantly to your device's LocalStorage.
*   **Backup & Restore:**
    *   **Export:** Download your history as a `.csv` file (Excel compatible).
    *   **Import:** Restore your data from a backup file (useful if you switch phones).
*   **Auto-Delete:** The app keeps data for the current month (45-day rolling window) to keep things fresh.

### 5. 🎮 Gamification & Sharing
*   **Streak Counter:** Tracks consecutive winning days.
*   **WhatsApp Status Card:** Generate a beautiful "Daily Summary" card that hides your total balance but shows your daily profit/loss—perfect for sharing screenshots.

---

## 🚀 How to Use

### 1. Initial Setup
1.  Open the app (`index.html`).
2.  Click the **Settings (⚙️)** icon in the top right.
3.  Set your **Monthly Target** (e.g., 100,000 PKR).
4.  (Optional) Set a **Default Stop Loss** and a **Security PIN**.

### 2. Daily Workflow
*   **Start Session:**
    *   Click "Start Session".
    *   Enter your current wallet balance.
    *   Check the "Safe Bet" suggestion to know your limits.
*   **Live Mode:**
    *   The app will show a "Live" indicator. You can minimize the app while you trade/play.
*   **End Session:**
    *   Return to the app and enter your final balance.
    *   Add a **Note** (e.g., "Good discipline today" or "Chased losses").
    *   Click "Save Result".

### 3. Analyzing Performance
*   Check the **Progress Bar** under your balance to see how close you are to your goal.
*   Look at the **Heatmap** to identify if you are on a losing streak.
*   Use **Privacy Mode** if you are showing the graph to a friend.

---

## ⚠️ Important Notes

*   **Where is data stored?**
    All data is stored in your browser's **Local Storage**. We do not send data to any server.
*   **Data Safety:**
    If you clear your browser's "Cache & Cookies," your data will be lost. **Regularly use the "Download Backup" feature** in Settings to keep your data safe.
*   **Mobile Experience:**
    The app is optimized for mobile. Add it to your Home Screen for a full app-like experience.

---

## 🛠️ Technology Stack

*   **HTML5 & JavaScript (ES6):** Core logic.
*   **Tailwind CSS:** Modern, glassmorphism UI styling.
*   **Chart.js:** Performance graphing.
*   **Lucide Icons:** Visual iconography.