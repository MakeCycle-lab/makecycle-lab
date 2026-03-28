# a1416-ipad3-touch-adapter: iPad 3/4 Touch Adapter (I2C)

![a1416-ipad3-touch-adapter overview](./a1416-ipad3-touch-adapter-01.jpg)

The **a1416-ipad3-touch-adapter** converts the iPad 3 touchscreen matrix into a standard 6-pin I2C output. This design is based on the **Goodix GT9110** touch controller chip.

### Compatibility
This adapter is compatible with the following models:
* **iPad 3** (A1416, and cellular versions)
* **iPad 4** (A1458, and cellular versions)

---

## Connection Guide: Touchscreen to Adapter
The image below demonstrates how to connect the iPad 3 touchscreen to the **a1416-ipad3-touch-adapter**.

![Touchscreen to adapter connection](./a1416-ipad3-touch-adapter-02.jpg)

---

## USB Touchscreen Integration
The **a1416-ipad3-touch-adapter** outputs an I2C interface. To enable USB control, an **I2C-to-USB Controller** is required. Compatible touch controllers include:

1. **i2c-00-touch-controller-ch554-3rd**

For technical details and firmware regarding these controllers, please refer to the **`01-generic-touch-controller-boards`** directory at the root of the repository.

### System Setup Example
The following image shows the connection between the **a1416-ipad3-touch-adapter** and the **i2c-00-touch-controller-ch554-3rd** USB controller:

![Touch adapter to USB controller setup](./a1416-ipad3-touch-adapter-03.jpg)