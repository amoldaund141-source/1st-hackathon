# 1st-hackathon
# 🧾 ScanWise AI

**ScanWise AI** is a smart, AI-powered expense tracker designed to eliminate manual data entry. By simply taking a photo of a receipt, the application uses Google's **Gemini AI** to automatically extract the store name, transaction date, total amount, and spending category.

> **Status:** MVP (Minimum Viable Product)
> **Version:** 1.0 Production

## 🚀 Key Features

* **📸 AI Receipt Scanning:** Uses Google Gemini 2.5 Flash to analyze images and extract structured data in seconds.
* **🧠 Smart Categorization:** Automatically detects expense types (e.g., Food 🍔, Travel 🚕, Shopping 🛍️) and assigns relevant icons.
* **👥 Multi-User Support:** "Netflix-style" account switching allows multiple users to track their own separate expenses on the same device.
* **💾 Persistent Data:** All data (users and expense history) is saved securely in the browser's LocalStorage, surviving page refreshes.
* **📱 Mobile-First Design:** A clean, professional UI optimized for touch interaction with smooth scrolling and neumorphic elements.

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Custom "Clean Fintech" Design), Vanilla JavaScript (ES6+).
* **AI Model:** Google Gemini API (`gemini-2.5-flash`).
* **Storage:** Browser `localStorage`.
* **Icons:** Google Fonts & Emoji-based UI.

## 🏃‍♂️ How to Run

Since this is a client-side Single Page Application (SPA), no backend server installation is required.

1.  **Download** the project files.
2.  **Open** the `index.html` file in any modern web browser (Chrome, Edge, Safari).
3.  **Start Scanning!**

## 📖 User Guide (Demo Script)

If you are presenting this project, follow this flow to show off all features:

1.  **Onboarding:**
    * The app detects no users are saved and launches the **Sign Up** screen.
    * Create a user (e.g., "Rahul").

2.  **Scanning a Receipt:**
    * On the Dashboard, tap the **Camera Icon** (Upload Zone).
    * Select a receipt image.
    * Click **"Analyze Receipt"**.
    * *Watch as the AI extracts the price and category automatically.*

3.  **Reviewing History:**
    * Go to the **History Tab**.
    * Show how the transaction is listed with a specific icon (e.g., 🍔 for food).

4.  **Multi-User Demo:**
    * Go to **Profile** -> **Log Out**.
    * Create a second user (e.g., "Priya").
    * Log out again.
    * Show the **Account Chooser** screen where you can easily switch between Rahul and Priya.

## ⚠️ API Note

This project uses the **Free Tier** of the Google Gemini API.
* **Limit:** ~15 requests per minute.
* **System Busy Message:** If you scan too fast, you may see a "System Busy" warning. This is normal. Please wait 60 seconds or use the app's built-in fail-safe mode (which will simulate a successful scan to keep the demo moving).

## 🔮 Future Roadmap

* [ ] Export expenses to PDF/CSV.
* [ ] Monthly spending charts and analytics.
* [ ] Cloud sync (Firebase/Supabase).

---
*Built for the 2025 AI Hackathon.*



***Note : Enter your API Key in place of 
