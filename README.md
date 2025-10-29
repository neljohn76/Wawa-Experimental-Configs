# Wawa-Experimental-Configs
This repository is for Wuthering waves experimental configs made by me

# ⚙️ Experimental Config Collection (v2.7+)

> Advanced Unreal Engine configuration presets designed for maximum Vulkan performance and feature stability across Exynos, MediaTek, and Universal Android platforms.

---

## 🔹 Exynos Vulkan-Forced Config

### 📖 Description
This configuration is **fully Vulkan-enforced** and finely tuned for **Exynos chipsets** using **Mali GPUs**.  
It maximizes reflection accuracy, shadow fidelity, and GPU thread balance, ensuring smooth performance under Vulkan rendering.

### 💡 Highlights
- **Vulkan API Forced:** `r.GraphicsRHI=Vulkan`
- **Optimized for Mali GPUs** — stable frame pacing, reduced driver overhead  
- **Enhanced reflections** with realistic specular detail  
- **Balanced particle density** for foliage and effects  
- **Thermal-aware tuning** for longer gaming sessions  

### ⚙️ Ideal For
> Samsung Galaxy S, Note, and FE devices (Exynos variants)

---

## 🔸 MediaTek Vulkan Config

### 📖 Description
Built for **MediaTek SoCs**, this version ensures **consistent Vulkan stability** and **GPU optimization** for Mali-G and PowerVR architectures.  
It prioritizes frame-time consistency and shader preloading efficiency.

### 💡 Highlights
- Vulkan API enabled with low-latency driver scheduling  
- **PowerVR-friendly texture streaming**  
- Adjusted **render-thread prioritization** for hybrid core CPUs  
- Slightly reduced post-processing for stability under thermal pressure  
- Optimized particle behavior (leaves, smoke, debris)  

### ⚙️ Ideal For
> Devices powered by **Dimensity** or **Helio** chipsets (e.g., Infinix, Tecno, Redmi, Realme)

---

## ⚫ Universal Vulkan Config

### 📖 Description
A **cross-platform config** designed for general Android Vulkan support.  
This version merges the best of Exynos and MediaTek optimizations to ensure wide compatibility while keeping high-quality reflections, particles, and shadows intact.

### 💡 Highlights
- **Universal Vulkan Enforcement**
- Stable on **Snapdragon**, **Exynos**, and **MediaTek** devices  
- **Balanced visuals + performance** (no chipset bias)  
- **Reflection-ready foliage and lighting** enabled  
- Unified scalability and particle tuning  

### ⚙️ Ideal For
> Users seeking a single configuration for any Android UE game without chipset-specific edits

---

## 🧱 Version Compatibility
| Config Type | Vulkan Support | Version | Tested Devices |
|--------------|----------------|----------|----------------|
| Exynos | ✅ Forced | v2.7+ | Galaxy S21 FE (Exynos 2100) |
| MediaTek | ✅ Native | v2.7+ | Dimensity 8100, Helio G99 |
| Universal | ✅ Auto | v2.7+ | Snapdragon 855+, Exynos, Dimensity |

---

> 🧩 “Each config is experimental, tuned for the edge of Vulkan performance — not just visuals, but synergy between GPU, CPU, and thermal design.”
