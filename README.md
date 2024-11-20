# **Unlimited Name Tags Plugin** 🎮✨
*A powerful tool to customize and manage player name tags like never before!*

[![Discord](https://img.shields.io/discord/1263414013040263249?label=Discord&logo=discord&color=5865F2)](https://discord.gg/W4Fu8fqCKs)  
[![CodeFactor](https://www.codefactor.io/repository/github/alexdev03/unlimitednametags/badge)](https://www.codefactor.io/repository/github/alexdev03/unlimitednametags)  
[![API Version](https://img.shields.io/github/v/release/alexdev03/UnlimitedNametags?&color=blue)](https://github.com/alexdev03/UnlimitedNametags/releases/latest)

![Unlimited Name Tags in Action](https://i.imgur.com/w7zlGaO.gif)

---

## 📌 **Overview**
Unlimited Name Tags is a robust plugin designed for Minecraft servers running **Paper 1.19.4+** or **Spigot 1.20.2+**. While the plugin supports Spigot, **Paper is highly recommended** for optimal performance and compatibility with advanced features.

Enhance your server's customization by tailoring player name tags, integrating dynamic placeholders, and supporting vanish plugins seamlessly. Built with ease-of-use and flexibility in mind, this plugin elevates the player experience while simplifying server management.

---

## 🌟 **Features**
- **🎨 Customizable Name Tags**: Change colors, formats, and add extra details to player name tags.
- **⚡ Placeholder Support**: Integrate with [PlaceholderAPI](https://github.com/PlaceholderAPI/PlaceholderAPI) for dynamic, real-time information.
- **👥 Relational Placeholders**: Fully supports relational placeholders to display dynamic information based on the relationship between players.
- **🕵️ Vanish Integration**: Automatically hide name tags for vanished players.
- **⚙️ Easy Configuration**: Simple yet powerful configuration via `settings.yml`.
- **🛠️ Bedrock Support**: Limited Bedrock compatibility through Geyser; text displays are converted into armor stands due to platform restrictions.

---

## 🚀 **Getting Started**

### **Installation**

1. **Download the Plugin**  
   Get the latest Unlimited Name Tags JAR from:
    - [BuiltByBit](https://builtbybit.com/resources/unlimitednametags.46172/)
    - [SpigotMC](https://www.spigotmc.org/resources/unlimitednametags.117526/)

2. **Add Dependencies**  
   Download [PacketEvents](https://modrinth.com/plugin/packetevents) and place it in the `plugins` directory.

3. **Upload to Server**  
   Place both JAR files (`UnlimitedNameTags` and `PacketEvents`) in the `plugins` directory.

4. **Restart the Server**  
   Restart your server to load the plugin.

5. **Configure**  
   Customize the `settings.yml` file located in the plugin's folder to suit your server’s needs.

---

## 🛠️ **Usage**

### **Commands**

#### Main Commands:
- **`/unt`**: Displays the plugin version and a list of available commands. *(Permission: none)*
- **`/unt reload`**: Reloads the plugin configuration without restarting the server. *(Permission: `unt.reload`)*
- **`/unt debug`**: Performs a debug operation for troubleshooting. *(Permission: `unt.debug`)*

#### Name Tag Management:
- **`/unt show <player>`**: Displays the name tag for a specific player. *(Permission: `unt.show`)*
- **`/unt hide <player>`**: Hides the name tag for a specific player. *(Permission: `unt.hide`)*
- **`/unt refresh <player>`**: Refreshes the name tag of a specific player for the command sender. *(Permission: `unt.refresh`)*

#### Customization and Configuration:
- **`/unt billboard <type>`**: Sets the default billboard type (e.g., `CENTER`, `FIXED`, etc.). *(Permission: `unt.billboard`)*
- **`/unt formatter <formatter>`**: Sets the default name tag formatter. *(Permission: `unt.formatter`)*

#### Managing Other Players' Name Tags:
- **`/unt hideOtherNametags [-h]`**: Hides the name tags of other players. Use the `-h` flag to suppress the confirmation message. *(Permission: `unt.hideOtherNametags`)*
- **`/unt showOtherNametags [-h]`**: Displays the name tags of other players. Use the `-h` flag to suppress the confirmation message. *(Permission: `unt.showOtherNametags`)*

---

## **Default Permissions**
- **`unt.shownametags`**: Enabled by default. Revoking this permission hides other name tags globally for the player.
- **`unt.showownnametag`**: Enabled by default. Revoking this permission hides the player's own name tag.

---

## 🔌 **Integrations**

Unlimited Name Tags works seamlessly with:

- **[PlaceholderAPI](https://github.com/PlaceholderAPI/PlaceholderAPI)**: Add dynamic data (e.g., health, rank) to name tags.
- **Vanish Plugins**: Automatically hide name tags for invisible players.
- **Type Writer**: Adjust name tags during cinematic mode.
- **[Oraxen](https://oraxen.com/)**: Ensures compatibility with 3D helmets.
- **MiniPlaceholders**: Works when using MiniMessage for advanced formatting.
- **Custom Plugins**: Easily hook into your custom plugins to extend functionality.

---

## 📜 **Supported Versions**
- **Paper**: Fully supported from **1.19.4+** *(highly recommended)*.
- **Spigot**: Supported from **1.20.2+**, but Paper is preferred for enhanced performance.

> **Note**: For versions below 1.19.4, text displays are not supported as the necessary packet functionality does not exist.

---

## 💬 **Support**

Need help? Join our [Discord Server](https://discord.gg/W4Fu8fqCKs)! For **pre-sale questions**, feel free to use the **#chat** channel. If you need support, please open a ticket and ensure your license is verified to gain access to assistance.

---

Take your server customization to the next level with **Unlimited Name Tags**! 🚀
