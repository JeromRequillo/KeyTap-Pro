![AHK Version](https://img.shields.io/badge/Language-AutoHotkey_v2-green) ![Platform](https://img.shields.io/badge/Platform-Windows-blue) ![License](https://img.shields.io/badge/License-MIT-yellow)
![Usage](https://img.shields.io/badge/Usage-Internal_Tool-orange)
![Status](https://img.shields.io/badge/Status-In_Production-success)
![Target](https://img.shields.io/badge/Target-Non--Technical_Users-blueviolet)
# 🎯 KeyTap Pro v4.4.0

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

### 3. ⌨️ Dynamic Custom Text Hotkeys
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
## 💼 Real-World Use Case & Internal Application

While **KeyTap Pro** is compiled as a modular utility for the broader open-source community, this solution was originally architected out of operational necessity as a **custom-tailored internal workspace tool**.

I designed, developed, and deployed this application specifically to tackle production-level challenges within my team's daily routines:
*   **Empowering Non-Technical Coworkers:** By encapsulating complex background scripting engines inside an accessible, user-friendly GUI, teammates without a programming background can completely leverage advanced workflow automations without modifying source configurations.
*   **Mitigating Human Error:** Automating complex transactional number progressions, multi-line corporate tax deductions, and extensive template indexing has drastically dropped manual keying fatigue and improved departmental data-entry accuracy.

This project showcases how lightweight scripting frameworks can be turned into robust, enterprise-ready workflow solutions that deliver immediate operational efficiency.

---

## 🛡️ Security & Integrity

As this tool is intended for deployment in professional workstation environments, the following safety measures are implemented:
*   **Zero External Connectivity:** KeyTap Pro operates entirely offline. It does not send, receive, or log data to any external servers or cloud services, ensuring total data privacy.
*   **Input Privacy:** The software does not function as a keylogger; text macros and sequence increments are only triggered by explicit user hotkey inputs.
*   **Open Source Transparency:** The full source code is provided in the `src/` directory for security auditing and verification.

---

## 📜 License & Usage

This project is licensed under the **MIT License**. 

You are free to:
*   **Use** the software for personal or commercial purposes[cite: 1].
*   **Modify** the source code to fit your specific internal workflow[cite: 1].
*   **Distribute** the compiled executable within your organization[cite: 1].

*Disclaimer: The developer is not responsible for any data loss or errors resulting from the misuse of the automation features. Always verify output during initial setup.*

---
**Developed & Maintained by:** [Jerom Requillo](https://github.com/JeromRequillo) 🚀
