![AHK Version](https://img.shields.io/badge/Language-AutoHotkey_v2-green) ![Platform](https://img.shields.io/badge/Platform-Windows-blue) ![License](https://img.shields.io/badge/License-MIT-yellow)
![Usage](https://img.shields.io/badge/Usage-Internal_Tool-orange)
![Status](https://img.shields.io/badge/Status-In_Production-success)
![Target](https://img.shields.io/badge/Target-Non--Technical_Users-blueviolet)
# 🎯 KeyTap Pro

KeyTap Pro is an open-source, fully portable workflow automation suite built using **AutoHotkey v2**. It provides an intuitive graphical interface designed to help users streamline repetitive typing, automate sequential indexing, and perform instant financial calculations on the fly without ever touching a single line of code.

---

## ✨ Key Features

### 1. 🧾 Smart Sequence & Invoice Generator
*   **Auto-Incrementing Engine:** Instantly prints a structured sequence (Prefix + Configurable Zero-Padded Digits + Suffix) that automatically increments and updates locally upon execution.
*   **Multi-Profile Architecture:** Create and manage independent profile environments. Each profile dynamically tracks its own distinct sequence numbers and formatting styles, perfect for switching between different clients, branches, or document types.
*   **Live Preview:** Adjust formatting parameters with real-time text feedback before committing changes.


### 2. 💰 Advanced VAT & Discount Tool
*   **In-Place Clipboard Processing:** Highlight any numerical value in any window, trigger the shortcut, and the tool will automatically compute and overwrite the text with the processed Net or Gross amount.
*   **Multi-Line Parsing Support:** Handles bulk processing cleanly by evaluating multi-line text strings line-by-line, omitting non-numeric anomalies safely.
*   **Built-in Workspace Calculator:** Features a fully visual data-entry panel providing comprehensive financial breakdowns (Gross, Applied Discount, Calculated Tax, and Net Total) with one-click clipboard copying.


### 3. 📂 Workflow Batch Folder Launcher
*   **One-Key Workspace Deployment:** Assign global hardware shortcuts to custom folder paths to instantly deploy targeted resources with a single key press.
*   **Ghost-Proof Input Security:** Engineered with a specialized `SendTextSafe` execution layer that temporarily blocks folder shortcuts while text automation is typing. This entirely eliminates accidental folder pop-ups caused by uppercase letter modifiers or shifting states.

### 4. 🧰 Micro-Utility Tooling (Mini Apps)
*   **Interface Integration:** Features a brand-new, dedicated dashboard panel to host upcoming localized tools and quick-action office extensions[cite: 2, 4].
*   **Text Manipulation Engine:** Integrated text-processing framework built for on-the-fly case management (`UPPERCASE`, `lowercase`, `Title Case`, and `Sentence case`).

### 5. ⌨️ Dynamic Custom Text Hotkeys
*   **No-Code Macro Management:** An interactive built-in control panel allowing users to easily map standard system modifiers (`Ctrl`, `Alt`, `Shift`) to multi-line text templates, common system commands, or boilerplate communications.
*   **Toggle & Reorder Functionality:** Quickly switch individual macros on or off, filter through saved text sequences, and reorder shortcut configurations effortlessly.

---

## 🚀 Global System Shortcuts

| Shortcut | Default Action | Technical Description |
| :--- | :--- | :--- |
| `Alt + F9` | **Generate Sequence** | Evaluates current profile criteria, types the string, and advances the sequence. |
| `Alt + V` | **Calculate Net VAT** | Extracts text selection, deducts or adds the profile's tax rate, and pastes the result. |
| `Alt + D` | **Apply Discount** | Processes targeted multi-line pricing arrays to subtract operational discount values. |
| `Alt + F10` | **Open Control Panel** | Launches the main tabbed Graphical User Interface (Fixed global shortcut). |

---

## 📦 Deployment & Portability

There are two ways to run **KeyTap Pro v4.6**:

### A. For Standard Users (Compiled .exe version)
1. **Download** the `KeyTapPro_v4_6.exe` from the Releases section.
2. **Place** the .exe file in any folder on your computer (e.g., C:\Tools\KeyTapPro).
3. **Run** the file (double-click).
4. The `settings.ini` file will be automatically generated in that same folder the first time you launch the app.

### B. For Developers (Raw .ahk script)
1. Ensure you have **[AutoHotkey v2.0](https://www.autohotkey.com/)** installed on your system.
2. Download the `KeyTapPro_v4_6.ahk` source file.
3. Run the script using the AutoHotkey engine.

*   **Zero Installation Required:** Completely registry-clean and independent. The application runs natively from localized environments, shared network directories, or external flash storage drives.
*   **Centralized Configuration:** Structural hotkeys, operational variables, and operational states are locally logged inside a single auto-generated `settings.ini` file for effortless deployment across multiple workstation devices.
*   **System Boot Integration:** To configure the software to launch automatically, press `Win + R`, type `shell:startup`, and establish a shortcut pointing to the application executable file.

---

## 📂 Repository File Structure

```text
📂 KeyTap-Pro/
├── 📄 KeyTap_Pro_v4.4.exe   # Standalone Compiled Desktop Executable
├── 📄 KeyTapPro_v4.4.ahk    # Open-Source Production Source Code (AHK v2)
├── 📄 settings.ini          # Local Configurations File (Auto-generated)
└── 📄 README.md             # Project Documentation Workspace
```
## 🛠️ The Origin Story: Why I Built This

This project was born out of operational necessity to solve a classic workplace problem: **script fatigue and maintenance bottlenecks.**

Originally, I developed multiple separate automation scripts to handle specific tasks and shared them with my team. While these tools drastically improved our department's speed, they created a massive headache:
* **The Mess:** Managing a dozen disconnected script files became confusing to organize and maintain.
* **The Dependency:** Because everything was hardcoded, team members had to call me over every single time they wanted to customize a template, change a sequence prefix, or adjust a setting.

### Tailored for the Workflow, Engineered for the Team
To fix this, I merged all those scattered tools into a centralized, multi-tab dashboard, evolving the scripts into a standalone application. **KeyTap Pro** was custom-built and heavily tailored around my personal daily workflow and the specific operational needs of our department. 

By putting an intuitive "no-code" GUI over the automation engine, the project achieves two things at once:
1. **Empowering Non-Technical Coworkers:** Teammates without a programming background can fully leverage, customize, and toggle advanced workflow automations on their own—anytime they need to—without ever touching a line of code or causing a bottleneck.
2. **Mitigating Human Error:** Automating complex transactional number progressions, multi-line corporate tax deductions, and extensive template indexing has drastically dropped manual keying fatigue and improved overall data-entry accuracy.

This project showcases how lightweight scripting frameworks can be turned into a robust workflow solution that delivers immediate operational efficiency.
---

## 🛡️ Security & Integrity

As this tool is intended for deployment in professional workstation environments, the following safety measures are implemented:
*   **Zero External Connectivity:** KeyTap Pro operates entirely offline. It does not send, receive, or log data to any external servers or cloud services, ensuring total data privacy.
*   **Input Privacy:** The software does not function as a keylogger; text macros and sequence increments are only triggered by explicit user hotkey inputs.
*   **Open Source Transparency:** The full source code is provided in the directory for security auditing and verification.

---

## 📜 License & Usage

This project is open-source and licensed under the **MIT License**. It’s designed to be as flexible and permissive as possible.

### ✅ What You Can Do
* **Workplace & Commercial Use:** Feel free to use this tool across your department, branch, or company.
* **Customization:** Modify the source code however you like to better fit your team's specific daily workflows.
* **Sharing:** Distribute the script or compiled versions to your coworkers or anyone who needs to speed up their tasks.

### 📋 The Only Rule (MIT Compliance)
* **Keep the Attribution:** If you copy, modify, or redistribute the source code, just keep the original copyright notice and credit to the author intact within the script files. 

---

### 💡 Just a Friendly Reminder
* **Test Before You Deploy:** Since this tool automates typing and clipboard functions, always try out your new sequences or shortcuts in a blank Notepad or safe environment first before running them on active production databases or live client files.
* **As-Is:** This utility is shared "as is" to help lighten the daily workload. While it’s built to be safe and completely offline, please use it responsibly!

---
**Developed & Maintained by:** [Jerom Requillo](https://github.com/JeromRequillo) 🚀
