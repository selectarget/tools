# Cyber Security Tools (Cyberpunk Edition)

![License](https://img.shields.io/badge/license-MIT-green)
![Style](https://img.shields.io/badge/style-Cyberpunk-ff003c)
![Lang](https://img.shields.io/badge/language-CN%2FEN-0cebeb)

**Online Cyber Security Tools** - A collection of essential tools for penetration testers and security researchers, wrapped in a stunning Cyberpunk/Hacker aesthetic.

> **Powered by sadsec**

## ✨ Features

### 🛡️ AV Recognition (杀软识别)
- **Fast Identification**: Quickly identify antivirus software from process lists.
- **Command Helper**: One-click copy for `tasklist /SVC` (CMD) and `Get-WmiObject` (PowerShell) commands.
- **Database**: Extensive database of AV process signatures.

### 🐚 Reverse Shell Generator (反弹Shell生成器)
- **Payload Generation**: Generate robust reverse shell payloads.
- **Bypass Techniques**: Uses Base64 encoding and special formatting to bypass WAFs and avoid bad characters.
- **One-Click Copy**: Easily copy generated payloads to clipboard.

### 🎨 Cyberpunk UI
- **Glitch Effects**: Authentic visual glitches on headers and interactions.
- **Neon Glow**: Glowing borders and text for that "hacker terminal" feel.
- **Scanlines**: CRT monitor scanline overlay.
- **Dark Mode**: Optimized for low-light environments.

### 🌐 Internationalization
- **Bilingual Support**: Seamlessly switch between **Chinese (Simplified)** and **English**.

## 🚀 Deployment

This project is designed to be hosted on **GitHub Pages**.

1.  Fork or Clone this repository.
2.  Go to **Settings** > **Pages**.
3.  Select the `main` branch and `/ (root)` folder.
4.  Save. Your site will be live at `https://<username>.github.io/<repo-name>/`.

## 🛠️ Development

### Prerequisites
- A modern web browser.
- A local web server (e.g., `python -m http.server`, `Live Server` in VS Code) is required to load `auto.json` due to CORS policies if running locally.

### Structure
- `index.html`: Main entry point.
- `hacker_style.css`: All styling (Cyberpunk theme).
- `auto.json`: Database for AV recognition.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---
*Created with ❤️ by sadsec*
