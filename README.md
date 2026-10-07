# 🛡️ FareWall - Automated Contest Monitoring Tool

**FareWall** is a security and integrity monitoring client designed to ensure fairness during coding contests and academic assessments. It runs unobtrusively in the background to log system events and session activity for contest organizers.

> ⚠️ **Note:** This repository contains only the compiled executable file (`.exe`). The source code and security architecture are kept private to ensure platform integrity.

---

## 📌 Features

- **Automated Setup:** Automatically verifies and installs missing dependencies if required.
- **Real-Time Connectivity:** Syncs participant status, signals, and session updates with the contest panel.
- **Stealth Background Mode:** Runs silently in the background without interrupting standard workspace interactions.
- **Alert System:** Receives global contest notices and direct updates from contest administrators.

---

## 🚀 Quick Start Guide

### Prerequisites
- **Operating System:** Windows 10 / 11 (64-bit)
- **Permissions:** Administrator privileges are required to run network verification tools.

---

### 📥 Installation & Running

1. **Download the Executable:**
   Download the latest release executable (`FareWall.exe` or `main.exe`) from the [Releases](../../releases) tab or from the root directory of this repository.

2. **Run as Administrator:**
   Right-click on the `.exe` file and select **Run as administrator**.

3. **Join Your Contest Session:**
   - Enter the **Room ID** provided by your contest host.
   - Enter your **Participant Name / Machine Name** (defaults to your PC name).

4. **Automatic Driver Verification:**
   - If **___** is already installed on your system, FareWall will launch immediately.
   - If missing, a terminal window will open to safely download and install ___. Follow the on-screen prompts to complete the setup.

---

## 🛠️ Frequently Asked Questions (FAQ)

<details>
<summary><b>Why does the app require Administrator rights?</b></summary>
Administrator privileges are required to check system driver registries and install missing dependencies for active session monitoring.
</details>

<details>
<summary><b>What should I do if I enter the wrong Room ID?</b></summary>
Simply close the application, re-launch the executable, and type the correct Room ID given by your instructor or host.
</details>

<details>
<summary><b>Will this affect my PC performance during the contest?</b></summary>
No. FareWall is lightweight and optimized to consume minimal CPU and RAM while running in the background.
</details>

---

## 🔒 Privacy & Compliance

FareWall operates strictly within the contest session parameters provided by your room supervisor. No private files or credentials are uploaded outside the contest monitoring workflow.

---

*Maintained by Md Mahbub Tanmay*
