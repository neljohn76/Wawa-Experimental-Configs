# ⚙️ Experimental Config Collection (v2.7+)

> Advanced Unreal Engine 4/5 configuration presets tuned for **Vulkan API**, optimized per chipset architecture.  
> Designed to push visual fidelity, reflection quality, and GPU efficiency without sacrificing stability.

---

## 🔵 Qualcomm Vulkan+ Performance Config

### 📖 Description
Optimized for **Qualcomm Snapdragon SoCs**, this config focuses on achieving the **highest frame stability** while maintaining crisp reflections and balanced GPU load under Vulkan.  
Built to take full advantage of **Adreno GPU drivers**, async compute, and high clock retention.

### 💡 Highlights
- `r.GraphicsRHI=Vulkan` (enforced Vulkan rendering)  
- Optimized **Adreno shader threading** for lower frame latency  
- Increased **reflection and post-processing** accuracy  
- Adaptive **thermal throttling guard** for sustained performance  
- Calibrated **r.RenderTargetPoolMin** for better memory control  

### ⚙️ Ideal For
> Devices like LG V50S, Galaxy S21 FE Snapdragon, POCO F3, and most Snapdragon 8xx/7xx/6xx phones.

---

## 🔹 Exynos Vulkan-Forced Config

### 📖 Description
This config enforces Vulkan rendering on **Exynos devices** using **Mali GPUs**, unlocking advanced reflection layers and smoother rendering transitions.  
It minimizes driver overhead and improves synchronization between CPU and GPU threads.

### 💡 Highlights
- Vulkan API **forced** for all render paths  
- Optimized **Mali GPU pipeline** with adjusted frame buffers  
- Enhanced **reflections, shadows, and post effects**  
- Balanced **particle draw distance** for realism and performance  
- Reduced shader compilation stutter  

### ⚙️ Ideal For
> Samsung Galaxy devices running Exynos 9611 / 9820 / 2100 / 2200 chipsets.

---

## 🔸 MediaTek Vulkan Config

### 📖 Description
Specially crafted for **MediaTek chipsets** using **Mali-G and PowerVR GPUs**.  
This config emphasizes stability, shader efficiency, and sustained Vulkan rendering performance.

### 💡 Highlights
- Vulkan API active by default  
- Optimized **PowerVR and Mali-G threading**  
- Lower **post-processing bias** to prevent heat spikes  
- Consistent **frame-time handling** on hybrid CPUs  
- Tuned **foliage and leaf particle system**  

### ⚙️ Ideal For
> Dimensity 800–9000, Helio G95–G99, and similar MediaTek devices.

---

## ⚫ Universal Vulkan Config

### 📖 Description
A general-purpose configuration that merges key optimizations from **Qualcomm**, **Exynos**, and **MediaTek**.  
Designed for broad compatibility — a true “drop-in and go” Vulkan config.

### 💡 Highlights
- Auto Vulkan detection with `r.GraphicsRHI=Vulkan`  
- Balanced **reflections, shadows, and particle load**  
- Stable frame output across multiple GPU vendors  
- Unified scalability and post-process tuning  
- Perfect for testing across different hardware  

### ⚙️ Ideal For
> Any Android UE-based game, regardless of chipset.

---

## 🧱 Version Compatibility

| Config Type | Vulkan Support | Version | Tested On |
|--------------|----------------|----------|------------|
| Qualcomm | ✅ Forced | v2.7+ | LG V50S, POCO F3, Galaxy S21 FE (Snapdragon) |
| Exynos | ✅ Forced | v2.7+ | Galaxy S21 FE (Exynos 2100) |
| MediaTek | ✅ Native | v2.7+ | Infinix Zero Ultra, Redmi Note 12 Pro+ |
| Universal | ✅ Auto | v2.7+ | Any Vulkan-capable Android device |

---

> 🧩 “Every config is an experiment — where Vulkan meets precision, reflection meets performance, and your GPU gets to show off its true potential.”
