# 💀 BIZHOST — PHP Hosting Terminal

> A lightweight, professional localhost hosting tool for Termux  
> Designed for mobile developers, testers, and cyber enthusiasts.

BIZHOST turns your Android device into a powerful PHP hosting environment with public internet access — all from a sleek cyber terminal interface.

---

## ⚡ Features

- 🔥 PHP Localhost Server (Port 8080)
- 🌐 Public Internet Access via Cloudflare Tunnel
- 📁 Direct Internal Storage Hosting
- 💻 Professional Cyber Terminal UI
- 🚀 One-Command Installation
- 🛡️ Lightweight & Fast
- 📱 Optimized for Termux
- 🧩 No Apache / Nginx Required
- 🎯 Beginner Friendly

---

## 📦 Requirements

- Android device
- Termux (latest version recommended)
- Internet connection (for installation & public link)
- Storage permission enabled

---

## 🚀 Installation

Open Termux and run:

```bash
apt update
apt install git
git clone https://github.com/bizft/BIZHOST.git
cd BIZHOST
chmod +x install bizhost
./install
```

---

## ▶️ Usage

Start the tool:

```bash
bizhost
```

---

## 🧭 Menu Options

### 🔹 Start Local Server

Runs PHP server on:

```
http://localhost:8080
```

Root directory:

```
/storage/emulated/0/BIZHOST
```

---

### 🔹 Create Public Link

Creates a secure public URL using Cloudflare Tunnel.

> ⚠️ The local server must be running first.

Example output:

```
STATUS : ACTIVE
Local  : http://localhost:8080
Public : https://example.trycloudflare.com
```

---

### 🔹 Open Site Directory

Opens hosting folder inside Termux shell for editing files.

---

### 🔹 Stop Server

Stops the running PHP server.

---

## 📁 Website Location

All website files are served from:

```
/storage/emulated/0/BIZHOST
```

You can edit files using any file manager or code editor.

Default page:

```
index.php
```

---

## 🌐 Access Your Website

### Local Access

Open browser on the same device:

```
http://localhost:8080
```

---

### Public Access

Use the generated Cloudflare URL to share your site worldwide.

---

## 🛡️ Security Notes

- Public links are temporary
- Do not host sensitive data
- Use responsibly
- Internet connection required for tunneling

---

## ⚙️ How It Works

BIZHOST uses:

- PHP built-in development server
- Cloudflare Quick Tunnel for public access
- Termux storage for hosting files
- Bash scripting for UI

---

## 🧹 Uninstallation

Remove tool manually:

```bash
rm $PREFIX/bin/bizhost
rm -rf ~/BIZHOST
```

Website files will remain in storage.

---

## 💻 Supported Platforms

- ✅ Android (Termux)
- ❌ Not designed for Windows / iOS

---

## ⚠️ Disclaimer

This tool is intended for educational and development purposes only.  
The author is not responsible for misuse.

---

## 👨‍💻 Author

**@bizft — BIZ FACTORY**

Cyber Tools • Mobile Hosting • Terminal Utilities

---

## ⭐ Support

If you like this project:

- ⭐ Star the repository
- 🍴 Fork it
- 📢 Share with others

---

## 💀 BIZHOST — Power in Your Pocket
