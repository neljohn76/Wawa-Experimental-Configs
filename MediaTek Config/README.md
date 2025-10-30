# 🔸 MediaTek Vulkan Config (Experimental)

> Tailored for **Dimensity** and **Helio** chipsets — balancing Vulkan stability with visual fidelity and efficient GPU usage.

---

## ⚙️ Overview
This config enables Vulkan rendering by default and fine-tunes parameters to prevent driver instability on MediaTek SoCs.  
It reduces shader overhead and ensures smoother gameplay across Vulkan-based Unreal titles.

---

## 💡 Key Features
- Vulkan API **active by default**  
- Optimized **PowerVR & Mali-G threading**  
- Balanced **render quality vs. thermal output**  
- Stable **foliage & particle system** (leaves, dust)  
- Reduced **frame timing jitter**

---

## ⚠️ Warning
- ⚠️ **Backup your config first!**  
  Save your current `Engine.ini` and `DeviceProfiles.ini` before applying.  
- Some Helio chipsets may not handle Vulkan well on certain UE builds.  

---

## 💡 Tips
- If you experience **thermal throttling**, lower `r.ViewDistanceScale` to 2.0.  
- For better stability, **lock your FPS** at 60.  
- Reboot your phone after applying the new config.

---

## 🧱 Ideal Devices
> Dimensity 9000 • Helio G99 • Infinix Zero Ultra • Redmi Note 12 Pro+

---

> ⚙️ “MediaTek done right — Vulkan strong, stable, and surprisingly smooth.”
