<!-- Banner -->
<p align="center">
  <img src="assets/banner.png" alt="Unreal Vulkan Config Banner" width="800"/>
</p>

<h1 align="center">⚙️ Unreal Engine Vulkan Config Collection (v2.7+)</h1>
<p align="center">
  <em>Experimental configurations tuned for Vulkan API performance, reflection quality, and smooth gameplay across major Android chipsets.</em>
</p>

---

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/API-Vulkan-blue?style=for-the-badge&logo=vulkan" alt="Vulkan API"></a>
  <a href="#"><img src="https://img.shields.io/badge/Status-Experimental-orange?style=for-the-badge" alt="Status"></a>
  <a href="#"><img src="https://img.shields.io/badge/Version-v2.7%2B-success?style=for-the-badge" alt="Version"></a>
</p>

---

## 🌍 Overview
These configs fine-tune Unreal Engine rendering for Vulkan-capable Android devices — pushing higher reflections, better shadow accuracy, and GPU-optimized thread handling.  
Each config is customized per chipset to get the most stable performance possible without losing that high-fidelity look.

---

## 🧩 Configurations

| Chipset | Folder | Vulkan Support | Description |
|----------|---------|----------------|--------------|
| 🔵 Qualcomm | [`Qualcomm/`](./Qualcomm%20Config) | ✅ Forced | Optimized for **Adreno GPUs** — high FPS & stable reflections |
| 🔹 Exynos | [`Exynos/`](./Exynos%20Config) | ✅ Forced | Refined Vulkan config for **Mali GPUs** — clean lighting, minimal stutter |
| 🔸 MediaTek | [`MediaTek/`](./MediaTek%20Config) | ✅ Native | Stable Vulkan config for **Dimensity / Helio** chips |
| ⚫ Universal | [`Universal/`](./Universal%20Config) | ✅ Auto | Balanced setup for all Vulkan-supported devices |

---

## ⚠️ Warnings

> ⚠️ **Always back up** your existing config files before replacing them.  
> These are *experimental configs* that can cause issues if your device or UE version handles Vulkan differently.

**Backup Path Example:**

Android/data/<game_package>/files/UE4Game/<GameName>/Saved/Config/Android/

---

## 💡 Tips
- Use **Performance Mode** before launching the game.  
- If the game fails to boot, delete the `.ini` and restore your backup.  
- Pair Vulkan configs with proper **thermal management apps** for best stability.  
- Ideal for testing in **Wuthering Waves**, **Tower of Fantasy**, **PUBG UE**, and other Vulkan-based titles.

---

## 🧠 Version Info
- **Engine:** Unreal Engine 4 / 5  
- **API:** Vulkan  
- **Config Version:** v2.7  
- **Status:** Experimental  
- **Last Updated:** 2025-10-29  

---

## 👤 Credits
Created by **Nel**  
Inspired by **Kuro’s Config Type (v2.7+)** and the **LG V50S Experimental Config Project**

> 🧩 “Vulkan runs deep — reflections, frames, and the fire beneath your GPU.”
