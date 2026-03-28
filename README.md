# 🛠️ MakeCycle-Lab | Hardware Project Assets

Welcome to my hardware laboratory. This repository hosts the original development files and assets shared on my **YouTube channel: [Your Channel Name]**.

### 📢 Important Notice
* **Static Repository**: This is a non-interactive repository for resource hosting. Due to time constraints on hardware reverse engineering and PCB design, **Issues and Pull Requests (PRs) will not be processed.**
* **Feedback & Support**: If you have technical questions or suggestions, please leave a comment on the corresponding YouTube video. I check them regularly.
* **Disclaimer**: All files are provided "as-is" for educational and hobbyist purposes. Please ensure you have sufficient engineering knowledge before attempting any modifications.

---

### 📂 Project Directory

* **`00-display-mainboards-and-sub-boards`**
    * **Logic**: To minimize redundant design, I developed a modular system consisting of **Universal Display Mainboards** and **Device-Specific Adapters**.
    * **Contents**: This folder hosts universal driver boards for **eDP, MIPI, and RGB** interfaces, along with various functional sub-boards.
    * **Usage**: Check the specific device folder to identify supported protocols. A complete monitor conversion requires a **Device-Specific Display Adapter** paired with a **Supported Universal Mainboard**.

* **`01-generic-touch-controller-boards`**
    * **Logic**: Designed to standardize touch interaction. This directory contains or collects **Touch Controller Boards** for **I2C and SPI** touchscreens.
    * **Contents**: Controller boards responsible for **USB to I2C/SPI** conversion.
    * **Usage**: Refer to the specific device folder to find compatible controllers. A functional USB touchscreen is achieved by combining a **Device-Specific Touch Adapter** with a **Universal Touch Controller**.

* **`06-ipad-adapters`**
    * **Contents**: Retrofitting resources for various iPad models.
    * **Organization**: Organized into sub-folders by model number (e.g., iPad 3, Air 2, Pro). Please navigate to the corresponding folder based on your hardware.

---

### How to get files:
Detailed production files (Gerber, STEP, BOM) are hosted as ZIP assets in the [Releases] section. Please refer to the download links in each sub-directory's description.

---
*Reviving legacy hardware, one bit at a time.*