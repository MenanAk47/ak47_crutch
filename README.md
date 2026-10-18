# Medical Crutch Fivem ESX/QB/QBX Framework

**The ultimate medical crutch and injury roleplay experience for FiveM servers.** Elevate your hospital and medical roleplay with authentic crutch props, realistic limping movement styles, dynamic physical detachment, and enforceable recovery timers. Featuring built-in relog protection and seamless multi-framework support via `ak47_lib`, this script ensures medical immersion is both engaging and impossible to bypass.

---

<img width="1920" height="1080" alt="thumbnail" src="https://github.com/user-attachments/assets/d65a8e8b-d4fd-434e-bca3-50356e58beb7" />

---


## 🔥 Key Features

Designed to improve roleplay immersion and economy balancing:

### 🩼 Realistic Crutch & Injury Mechanics

* **Authentic Prop & Limping Clipset:** Equips a high-detail medical crutch attached realistically to the player's ped while continuously applying GTA V's authentic injured walk style.
* **Enforced Action Restrictions:** Configurable system disables jumping, running/sprinting, weapon drawing/firing, and melee combat actions while the crutch is active.

### 🏃‍♂️ Dynamic Physics & Interactive World

* **Dynamic Detach & Drop on Impact:** If a player gets knocked down, ragdolls, falls, or enters melee combat, the crutch dynamically drops into the game world.
* **Interactive 3D Pickup System:** Players can approach their dropped crutch in the world and press [E] to play a realistic pickup animation and re-equip it.
* **Seamless Vehicle Detection:** The crutch automatically hides when entering any vehicle and cleanly re-appears when stepping out.

### 🚑 Medical & EMS Prescription System

* **Whitelisted Job Commands:** Authorizes EMS and hospital staff (`ambulance` job) to assign or dismiss crutches using `/setcrutch` and `/removecrutch`.
* **Interactive Time Dialog:** Prompts doctors with a clean input modal to specify injury recovery time (in minutes) within configured minimum and maximum limits.
* **Synchronized Medical Animations:** Plays a synchronized medical treatment animation facing the target patient during prescription or removal.
* **Voluntary Roleplay Toggle:** Includes a `/crutch` command for citizens to self-equip a crutch for voluntary roleplay scenarios if they are not serving a medical penalty.

### 💾 Persistent Injury Timer & Anti-Combat Log

* **Server-Side Relog Protection:** Remaining crutch time is persistently saved to the database every minute; reconnecting or relogging automatically re-applies the crutch and timer.
* **Automated Database Setup:** Executes table creation automatically on startup with zero manual SQL importing required.

### 🛠️ Technical Excellence

* **Multi-Framework & Target Support:** Seamlessly works with ESX, QB, QBX, and various target systems (ox_target, qb-target, qtarget).
* **Highly Secure:** Built-in server-side exploit checks, including distance validation and trigger authentication, to prevent cheating.
* **Lightweight & Optimized:** Zero idle client hitching with distance-based sleep threads for dropped world props and instant synchronization via `ak47_lib`.

---

## 💻 Framework:

* ESX, QB, QBX

---

## ⚙️ Dependencies:

* ak47_lib: https://github.com/MenanAk47/ak47_lib/releases/latest

---

## ⚙️ How To Install:

* Download ak47_crutch from your cfx portal.
* Add the script in your resources folder.
* Add items based on your framework instruction.
* Add item images into inventory.
* Start the script in your server.cfg below framework files.
* Make sure you have all dependencies.
* Restart the server.

---

## 🔗 Links & Support:

* **📖 Documentation:** [https://docs.menanak47.com/multi-framework/ak47_crutch](https://docs.menanak47.com/multi-framework/ak47_crutch)
* **🛒 Buy Now (Tebex):** [https://menanak47.tebex.io/package/6419367](https://menanak47.tebex.io/package/6419367)
* **💬 Discord Support:** [https://discord.gg/menanak47](https://discord.gg/menanak47)

---

## 📝 Note:
* We don't support custom framework. Make sure you are using official framework update.
* Renaming the script is not allowed. It may break the functionalities.
* Don't upload the script with FileZilla, Use Winscp if you are using FTP for file uploading
