# esp32-dev-board
it's a very small and minimalistic wireless esp32 dev board that runs off of USB-C, I wanted to make this project because I wanted to add wireless functionality to my projects and the esp32 has wifi and bluetooth which is perfect!
<img width="688" height="698" alt="image" src="https://github.com/user-attachments/assets/cbde067c-7b76-46e4-81b3-f725af5a22bb" /> <img width="894" height="1256" alt="image" src="https://github.com/user-attachments/assets/c698d4c1-0371-4cb8-8798-e44f6a0971c6" />

### Bill of Materials (BOM)

| Designator | Part Name / Value | Qty | Package/Footprint | Description | Supplier Part | Direct LCSC Link |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **U2** | ESP32-S3-WROOM-1-N8 | 1 | WIFIM-SMD | Wi-Fi + BT MCU Module, 8MB Flash | `C2913198` | [LCSC Part Link](https://www.lcsc.com/product-detail/C2913198.html) |
| **U6** | AP2112K-3.3TRG1 | 1 | SOT-25-5 | Linear Voltage Regulator LDO 3.3V 600mA | `C51118` | [LCSC Part Link](https://www.lcsc.com/product-detail/C51118.html) |
| **USB1** | UCR06-8161K-00BR | 1 | TYPE-C-SMD | USB-C Receptacle Connector, 16-Pin | `C9900214533` | [LCSC Part Link](https://www.lcsc.com/product-detail/C9900214533.html) |
| **LED1** | E6C0603URAC1UDA | 1 | LED0603 | Power Indicator LED, Ultra Bright Red | `C375444` | [LCSC Part Link](https://www.lcsc.com/product-detail/C375444.html) |
| **R4** | 1kΩ | 1 | R0402 | Current limiting resistor for LED1 | `C5151916` | [LCSC Part Link](https://www.lcsc.com/product-detail/C5151916.html) |
| **R3** | 10kΩ | 1 | R0603 | ESP32-S3 EN pin pull-up resistor | `C4109781` | [LCSC Part Link](https://www.lcsc.com/product-detail/C4109781.html) |
| **R1, R2** | 5.1kΩ | 2 | R0402 | USB-C CC1/CC2 configuration pull-downs | `C2791532` | [LCSC Part Link](https://www.lcsc.com/product-detail/C2791532.html) |
| **C2** | 22µF | 1 | C0603 | 3V3 main power rail stability filter | `C6119880` | [LCSC Part Link](https://www.lcsc.com/product-detail/C6119880.html) |
| **U7** | 100nF | 1 | C0603 | 3V3 decoupling bypass capacitor | `C20624283` | [LCSC Part Link](https://www.lcsc.com/product-detail/C20624283.html) |
| **C1** | 100nF | 1 | C0201 | Reset button hardware debounce filter | `C3871673` | [LCSC Part Link](https://www.lcsc.com/product-detail/C3871673.html) |
| **U3, U4** | REBOOTSW / BOOTSW | 2 | SW-SMD | Tactile Push Button Switches (Reset & Flash) | `C9900011101` | [LCSC Part Link](https://www.lcsc.com/product-detail/C9900011101.html) |
