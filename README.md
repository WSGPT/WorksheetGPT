
# 🚀 WorksheetGPT

**WorksheetGPT** is a powerful, completely free, and unlimited mobile automation tool designed exclusively for **Gibson School Systems** students. It takes the manual work out of your daily eLearning routine by automatically syncing your portal, fetching pending assignments, and actually solving them for you. 

Watch the automation happen right on your screen with live clicks and scrolls, or let it run in the background while you stay updated via persistent notifications.

---

## ✨ Key Features

*   🎯 **Exclusive to Gibson School Systems:** Custom-built to accurately navigate and interact with the Gibson eLearning platform.
*   💸 **100% Free & Unlimited:** No paywalls, no hidden fees, and absolutely no limits on how many profiles or worksheets you can automate.
*   👀 **Live Automation Visibility:** Watch the app work in real-time. See the live clicks, scrolls, and page navigation as the engine autonomously interacts with the web portal.
*   🔔 **Persistent Live Notifications:** Keep track of the bot's progress without keeping the app open. A persistent notification provides live, second-by-second updates of current actions and seamlessly reports any errors.
*   🤖 **Dual Solving Modes:** 
    *   **Solve All Flow:** Automatically runs through the last 10 tests of *each* course with a single tap.
    *   **Manual Selection:** Pick and choose exactly which tests you want solved from the Activity tab, with the ability to queue tasks across multiple different courses.
*   🛡️ **Robust Error Handling:** Network drop? Unexpected portal logout? The app catches all errors, reports them via notifications and the in-app console, and safely retries or skips to keep the queue moving.
*   🌙 **Customizable UI:** Full support for **Light Mode**, **Dark Mode**, and **System Theme** settings to match your device preferences.

---

## 🛠️ User Flow & How It Works

### 1. Multi-Profile Management
*   **Add & Edit Profiles:** Add multiple student profiles to handle work for siblings or friends. You can easily edit profile credentials at any time.
*   **Isolated Storage:** All data (courses, tests, and login credentials) for each profile is stored completely separately to prevent mixing up assignments.

### 2. Synchronization (SYNC)
*   Once your profile is active, tap the **SYNC** button on the Dashboard.
*   WorksheetGPT will securely log in to the Gibson School Systems portal and automatically fetch your data.
*   The **Activity** tab is then populated and lists all your courses, worksheets, tests, and optionally grades of previously completed activities (activated through the settings page.)

### 3. Execution (SOLVE)
Choose how you want to automate:
*   **The "Solve All" Flow:** Hit **SOLVE** from the Dashboard to trigger the automated batch process. 
*   **Selective Solving:** Navigate to the **Activities** tab and manually check the exact tests you want the app to complete. You can freely select specific tests across multiple courses at once, then start the process.

### 4. Sit Back and Watch (or Don't!)
*   **Foreground:** Keep the app open to watch the WebView automatically navigate, scroll through pages, and click on your behalf.
*   **Background:** Minimize the app and let it run. The persistent notification will keep you updated on exactly which course and test is currently being processed. *(Note: Background running is fully supported on newer Android devices. Support for older devices is currently in development and coming soon.)*

---

## ⚙️ Under the Hood: The Automation Engine

WorksheetGPT uses a highly resilient background engine that intelligently reacts to the state of the web portal.

*   **Failsafe Submission & Verification:** Rest assured that no questions or worksheets will ever be skipped. Before making any final submission, WorksheetGPT meticulously scans the page for unanswered questions and reattempts them. If a question consistently fails to resolve, the app halts the submission process and prompts you for manual intervention. 
*   **Smart Session Management:** If the Gibson platform detects an overlapping session (e.g., "You are already logged in"), WorksheetGPT identifies the conflict, safely logs out, and re-authenticates to guarantee a clean workspace.
*   **Sequential Processing:** Selected tasks are queued and processed one-by-one to avoid overloading the eLearning server and to ensure every single submission registers correctly.

---

## 🔒 Privacy, Security & Transparency

Your privacy is our top priority.

*   **100% Local Storage:** Usernames, passwords, course lists, and test data are saved entirely **locally** on your mobile device. 
*   **No Cloud Tracking:** We do not transmit, collect, or store your login details or academic data on any external servers. Everything happens right on your phone, **as can be verified by any network traffic monitoring tools**.
*   **Open for Verification:** We believe in complete transparency. Developers, security researchers, or any tech-savvy users interested in reviewing the underlying code can request access to our repository by reaching out to us on Instagram at **[@WorksheetGPT](https://instagram.com/WorksheetGPT)**.

---

## 📢 Updates & Support

All future updates, patch notes, and feature announcements will be posted exclusively on our Instagram. Drop us a follow or send a DM if you run into any issues!

👉 **Follow us: [@WorksheetGPT](https://instagram.com/WorksheetGPT)**

---

## 📥 Installation

*Download the latest release from the Releases tab and install the APK on your Android device.*

*Note on Compatibility: Full background automation requires newer device API levels to ensure smooth execution without battery-optimization interruptions. Optimization for older legacy devices is arriving in an upcoming patch.*
