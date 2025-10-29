# ⚫ Universal Vulkan Config (Experimental)

> A cross-platform config combining the best optimizations from **Qualcomm**, **Exynos**, and **MediaTek**.  
> Designed for anyone who wants a stable, reflection-ready, and Vulkan-powered experience.

---

## ⚙️ Overview
This universal setup applies Vulkan optimizations that work across multiple GPU architectures.  
It balances graphics fidelity, frame pacing, and thermal stability.

---

## 💡 Key Features
- **Universal Vulkan enforcement** (`r.GraphicsRHI=Vulkan`)  
- Balanced **reflections**, **shadows**, and **particle effects**  
- Stable performance on **Snapdragon**, **Exynos**, and **MediaTek**  
- Tuned **r.Streaming.PoolSize** for efficient memory use  
- Great baseline for testing or debugging Vulkan behavior  

---

## ⚠️ Warning
- ⚠️ **Backup your current configs before replacing!**  
  These files are **experimental** and may behave differently on each device.  
- If your game doesn’t load, delete the new `.ini` files and restore your originals.

---

## 💡 Tips
- Works best when the device is in **High Performance Mode**.  
- Check Vulkan support via `adb shell dumpsys SurfaceFlinger | grep Vulkan`.  
- Combine with your preferred `DeviceProfiles.ini` for chipset-specific tuning.

---

## 🧱 Ideal Devices
> Any Android device with Vulkan support (Snapdragon, Exynos, MediaTek)

---

> ⚙️ “One config to rule them all — balanced, stable, and Vulkan from the core.”