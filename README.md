# PhishGuard-Analyzer
​A Python-based security tool that detects phishing threats using heuristic analysis. It scans URLs for "Red Flags" like IP-based hosting, character obfuscation (@ symbols), and sensitive keywords. Featuring a sleek CustomTkinter dark-mode UI, it provides real-time risk scoring to protect users.

## 🚀 Features
* **Heuristic Risk Scoring:** Dynamically calculates a risk percentage based on URL structure.
* **IP Host Detection:** Flags raw IP addresses, a common tactic for bypassing DNS filters.
* **Lexical Analysis:** Scans for redirection symbols (like '@') and suspicious subdomains.
* **Sensitive Keyword Matching:** Identifies high-risk terms like 'login', 'banking', and 'verify'.
* **Modern GUI:** Responsive dark-mode interface built with CustomTkinter.

## 🛠️ Tech Stack
* **Language:** Python 3.12+
* **UI Framework:** CustomTkinter
* **Core Libraries:** `re` (Regular Expressions), `urllib`

## 📂 Installation & Usage
1. Clone the repository:
   ```bash
   git clone [https://github.com/Priya-492002/PhishGuard-Analyzer.git](https://github.com/Priya-492002/PhishGuard-Analyzer.git)
