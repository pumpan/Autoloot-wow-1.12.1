# Autoloot Client
[![Version](https://img.shields.io/github/v/release/pumpan/Autoloot-wow-1.12.1?color=blue&label=version)](https://github.com/pumpan/Autoloot-wow-1.12.1/releases)
![WoW Version](https://img.shields.io/badge/WoW-1.12.1-ff69b4)
![License](https://img.shields.io/badge/license-MIT-green)
[![Latest ZIP](https://img.shields.io/badge/dynamic/json?color=success&label=Latest&query=$.assets[0].download_count&url=https://api.github.com/repos/pumpan/Autoloot-wow-1.12.1/releases/latest)](https://github.com/pumpan/Autoloot-wow-1.12.1/releases/latest)
<a href="https://www.paypal.com/donate/?hosted_button_id=JCVW2JFJMBPKE" target="_blank">
    <img src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif" 
         alt="Donate with PayPal" style="border: 0;">
</a>
<a href="https://www.paypal.com/donate/?hosted_button_id=JCVW2JFJMBPKE" class="paypal-button" target="_blank">
    💙 Support Me with PayPal
</a>

---

## 📝 Overview

**Autoloot Client** brings a small but powerful quality-of-life feature that *vanilla WoW (1.12.1)* never had by default — **autoloot without holding `<Shift>`**.

Once installed, your client will automatically loot everything with a single right-click.  
If you want to temporarily disable autoloot, simply **hold `<Shift>`** while looting.  

Yes, **Rogues**, this means you can *pickpocket* seamlessly without issues. 🕵️‍♂️💰

*Original concept credited to a Reddit post on [r/Lightshope](https://www.reddit.com/r/lightshope/comments/7dpj1w/autoloot_client/) — thanks to the original author.*  

---

## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Changelog](#changelog)
- [License](#license)
- [Contact](#contact)

---


## ✨ Features
- ✅ Always autoloots without needing to hold `<Shift>`  
- 🧠 Hold `<Shift>` to temporarily disable autoloot  
- 🏴‍☠️ Compatible with pickpocketing  
- ⚙️ No addons or console commands required  
- 💾 Works directly from your client executable

---

## 🛠️ Installation
A.
    1. **Download the latest version:**  
       [![⬇ DOWNLOAD](https://img.shields.io/github/downloads/pumpan/Autoloot-wow-1.12.1/total?style=for-the-badge&color=00b4d8&label=⬇+DOWNLOAD)](https://github.com/pumpan/Autoloot-wow-1.12.1/releases/tag/Autoloot-launcher)
    
    2. **Backup your original WoW.exe:**  
       Rename it to something like: WoWBackup.exe
    
    3. **Place the new `WoW.exe`** in your WoW 1.12.1 root folder.
    
    4. **Launch the game** as usual using the new executable.
    
B. **OR** If you wanna edit your own client to Autoloot instead of downloading: open Wow.exe in your favorite hex editor(I use HxD) search for "74 10 33 C9 E8 C8 00 00 00 5F"(generated from 0x004C1ECF in cheat engine) Edit to "75 10 33 C9 E8 C8 00 00 00 5F" save profit. 


---

## ▶️ Usage

- Loot any mob → items are looted automatically.  
- Hold `<Shift>` while right-clicking to disable autoloot for that loot window.  
- Works identically to how retail WoW handles autoloot toggling.



