# axora-forum-addon
A free forum plugin for the Axora CMS platform. Includes board creation, thread discussions, replies, reporting system and modern Bootstrap 5 interface.
---
Axora is a modern, modular CMS platform developed in PHP and MySQL.
Get the full Axora system here: https://csibusz.wuaze.com

Demo: demo@example.com/123456

https://www.codester.com/items/56128/axora-login-registration-system
---
# Axora Forum Addon

A free and modern forum plugin designed for the Axora CMS platform.  
Includes board management, thread creation, replies, reporting system, pagination, flood protection, and CSRF validation.

![Preview Screenshot](https://csibusz.wuaze.com/scren.jpg)
---
![Preview Screenshot](https://csibusz.wuaze.com/screen5.jpg)
---
![Preview Screenshot](https://csibusz.wuaze.com/screen3.jpg)

---

## 🔧 Features

- Forum boards with descriptions and rules
- Thread creation with rich-text formatting
- Reply system with modern UI
- Sticky threads
- Report abuse functionality
- CSRF + Flood protection
- Responsive Bootstrap 5 layout (2025 design trends)

---

## 📦 Requirements

- Axora CMS v1.19+
- PHP 8.0+
- MySQL 5.7+
- Enabled `forum` plugin in `plugins.json`

---

## 🚀 Installation

1. Copy the `forum/` and admin/ folder into your Axora `/plugins/` directory.
2. Ensure the plugin is enabled:
```json
{
  "forum": {
    "name": "forum",
    "enabled": true
  }
}
