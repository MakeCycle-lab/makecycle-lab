# 🛠️ MakeCycle-Lab | Hardware Project Assets

🚀 **Project Overview**
Welcome to my hardware laboratory. This repository hosts the original development files and assets shared on my YouTube / Douyin Channel. 

---

### 📢 Notice
* **Archive Only**: This is a non-interactive repository. Issues and PRs will not be processed.
* **Support**: Please leave comments on YouTube/Douyin for technical questions.
* **License**: MIT (Excluding 3rd-party assets).

⭐ **Support this project by giving it a Star!**

---

### 📂 Project Directory

* **`00-Main-and-Peripheral-Boards`**
    * **Logic**: To minimize redundant design, I developed a modular system consisting of **Universal Host Boards** and **Peripheral Function Boards**.
    * **Naming Convention**: 
        * `Main-`: Universal driver boards (eDP, MIPI, RGB).
        * `Touch-`: Universal touch controller boards (USB to I2C/SPI).
        * `Peripheral-`: Common accessories (Keypads, Power modules, etc.).
    * **Contents**: Includes projects like `Main-DPtoiPad-Lite`, `Touch-Controller-CH554-3rd`, etc.

* **`01-iPad-Adapters`**
    * **Logic**: Specific interface bridges designed for the Apple iPad series.
    * **Contents**: Retrofitting resources (Display/Touch adapters) for various iPad models.
    * **Organization**: Sorted by model (e.g., iPad 3, Air 2, Pro). 

---

### 📥 How to Get Production Files (Gerber, BOM, STEP)

To keep the repository lightweight, detailed production files are hosted as **RAR/ZIP assets** in the [Releases] section. 

**Find your files by Category Tags:**
1.  **`Release-Main-Boards`**: All universal display driver assets.
2.  **`Release-Touch-Units`**: All touch controller firmware and hardware files.
3.  **`Release-Peripherals`**: Common accessory assets.
4.  **`Adapter-iPad-Series`**: All iPad-specific adapter boards.

> **Tip**: Each sub-directory's README contains a direct link to the corresponding Release Tag for quick access.

---
*Reviving legacy hardware, one bit at a time.*