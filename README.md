# 🔐 WiFi Password Finder

## 👋 About Us
Welcome to the WiFi Password Security Checker – a robust and user-friendly tool designed to help users assess the strength of their WiFi passwords and enhance their digital security.

## ✨ Features
- 🔍 Scan available WiFi networks
- 🔒 Check password strength
- 🌙 Dark mode support
- 📤 Export results in multiple formats
- 📝 Connection history tracking
- 💾 Network profile management

## 🔍 Why This Project?
With the increasing risks of cyber threats, weak passwords can make networks vulnerable to unauthorized access. This tool empowers users by:
✅ Analyzing Password Strength – Evaluating the complexity of WiFi passwords.
✅ Providing Instant Feedback – Offering actionable suggestions for stronger security.
✅ Enhancing Cyber Hygiene – Encouraging best practices for password management.

## 🛠️ Requirements
- Python 3.x
- pywifi
- tkinter (usually comes with Python)
- pyperclip
- Additional dependencies

## ⚙️ Installation
1. Clone the repository or download the executable
2. If running from source, install the required modules:
```bash
# Create and activate virtual environment (recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install required packages
pip install pywifi
pip install pyperclip
```

## 🚀 Usage
1. Run the executable or Python script
2. Click 'Scan Networks' to find available WiFi networks
3. Select a network from the list
4. Choose a password list file
5. Click 'Start Cracking' to begin

## ⌨️ Shortcuts
- Ctrl+S: Save results
- Ctrl+O: Open password file
- Ctrl+Q: Quit
- F5: Scan networks
- F1: Help

## 🐛 Troubleshooting
If you encounter any issues with pywifi installation, try:
```bash
pip install --upgrade pip
pip install pywifi
```

For Windows users experiencing compatibility issues:
```bash
pip install comtypes
```
