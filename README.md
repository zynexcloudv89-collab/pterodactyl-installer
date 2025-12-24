# Pterodactyl Panel One-Click Installer

![Pterodactyl](https://img.shields.io/badge/Pterodactyl-Panel-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Shell](https://img.shields.io/badge/Shell-Bash-yellow)

A complete one-click installation script for Pterodactyl Panel on Ubuntu/Debian systems.

## ✨ Features
- ✅ Complete Pterodactyl Panel installation
- ✅ Automatic dependency installation
- ✅ Secure database configuration
- ✅ Nginx web server setup
- ✅ Redis caching
- ✅ Queue worker configuration
- ✅ One-line installation

## 🚀 Quick Installation

### One-Line Install
```bash
bash <(curl -s https://raw.githubusercontent.com/your-username/pterodactyl-installer/main/install.sh)
```

### With Debug Output
```bash
bash <(curl -s https://raw.githubusercontent.com/your-username/pterodactyl-installer/main/install.sh) 2>&1 | tee install.log
```

## 📋 Requirements
- Ubuntu 20.04/22.04 or Debian 10/11
- Minimum 2GB RAM (1GB minimum)
- Root access
- Active internet connection

## 🔧 What Gets Installed
- PHP 8.1 with all extensions
- MariaDB Database
- Nginx Web Server
- Redis Cache
- Node.js 18.x
- Composer
- Pterodactyl Panel (Latest)

## 📁 Files
- `install.sh` - Main installation script
- `README.md` - This documentation

## 🛠️ Manual Installation Steps
If you prefer manual installation:

```bash
# Download script
curl -sSL -o pterodactyl-install.sh https://raw.githubusercontent.com/your-username/pterodactyl-installer/main/install.sh

# Make executable
chmod +x pterodactyl-install.sh

# Run installation
./pterodactyl-install.sh
```

## 🤝 Contributing
Feel free to submit issues and pull requests.

## 📄 License
This project is licensed under the MIT License.

## 👨‍💻 Author
**Danish** - Pterodactyl Installation Script

---
*Made with ❤️ for the Pterodactyl community*
