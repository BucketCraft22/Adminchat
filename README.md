# 🛡️ AdminChat for Velocity

![Version](https://img.shields.io/badge/version-1.2-red.svg)
![Platform](https://img.shields.io/badge/platform-Velocity-blue.svg)
![License](https://img.shields.io/badge/license-GPL--3.0-green.svg)

**AdminChat** is a lightweight, high-performance Velocity plugin designed for network administrators. It provides a secure, cross-server channel for staff communication, featuring a multi-language system with automatic cloud updates.

---

## ✨ Features

* **Cross-Server Communication:** Chat with admins regardless of which sub-server they are on.
* **Server Tags:** Automatically displays the source server name (e.g., `(Lobby) Player » Message`).
* **Toggle Mode:** Use `/ac` to switch between global chat and admin-only mode.
* **Multi-Language Support:** Easy switching between languages with automatic file downloading from GitHub.
* **Logging:** Every admin message is logged into a dedicated `adminchat.log` file for audit purposes.
* **MiniMessage Support:** Full support for modern, gradient-based chat formatting.

---

## 🚀 Installation

1.  Download the latest `.jar` file.
2.  Place it into your Velocity `plugins` folder.
3.  Restart your proxy.
4.  Edit `plugins/adminchat/config.yml` to set your preferred language.

---

## 🛠️ Commands & Permissions

| Command | Alias | Description | Permission |
| :--- | :--- | :--- | :--- |
| `/ac <message>` | `/adminchat` | Sends a message to all online admins. | `adminchat.use` |
| `/ac` | - | Toggles automatic admin chat mode. | `adminchat.use` |
| `/ac help` | - | Shows the help menu. | `adminchat.use` |
| `/ac reload` | - | Reloads config and language files. | `adminchat.use` |

---

## 🌍 Language Support

AdminChat supports a dynamic language system. By default, it uses Hungarian, but you can switch to English instantly:

1.  Open `config.yml`.
2.  Change `language: hu` to `language: en`.
3.  Run `/ac reload` in-game.
4.  **The plugin will automatically download the `messages-en.yml` file from the official repository!**

---

## 📞 Support

Created by **BucketCraft**.
Need help? Reach out on Discord: `bucketcraft`

---

## 📜 Legal

This project is licensed under the **GNU General Public License v3.0**. 
See the `LICENSE` file for more details.
