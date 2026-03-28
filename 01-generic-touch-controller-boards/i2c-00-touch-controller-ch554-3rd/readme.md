# i2c-00-touch-controller-ch554-3rd: USB Touch Controller

![i2c-00-touch-controller-ch554-3rd overview](./i2c-00-touch-controller-ch554-3rd-01.jpg)

The **touch-controller-ch554** is a USB touch controller capable of interfacing with common touch driver ICs (such as Goodix, FocalTech, etc.) to create a functional USB touchscreen. It must be paired with a device-specific touch adapter to operate.

### Background & Credits
This project originates from the official WCH forum: [https://www.wch.cn/bbs/thread-70716-1.html](https://www.wch.cn/bbs/thread-70716-1.html). 

I have archived the original files in this repository to ensure availability. Please note:
* **Firmware**: Since the original source code is based on the Keil C51 environment (which lacks a free version), I have used the provided **.hex** firmware directly from the archive.
* **Hardware**: I have reconstructed the PCB for this project.

---

### 🛠️ Usage Example: iPad 3 USB Touchscreen Setup

To implement a USB touchscreen for an iPad 3, the following combination is required:

1.  **USB Touch Controller**: Use the **i2c-00-touch-controller-ch554-3rd** mainboard.
2.  **Touchscreen Adapter**: Locate the **iPad Series Adapters** directory, then find the **iPad 3 Adapter** collection. Use the touch adapter found within that project.

---

## 📥 Project Downloads

Click the link below to download the firmware and production files for the CH554 controller:

[Download touch-controller-ch554-3rd.zip (ZIP)](YOUR_RELEASE_DOWNLOAD_LINK_HERE)

---

## 📺 Video Guide

Click the link below to watch the application of the CH554 controller in the iPad 3 monitor conversion project:

[Watch the Tutorial on YouTube](https://www.youtube.com/watch?v=EXAMPLE_VIDEO_ID)

