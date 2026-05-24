RP2040 Wireless Mechanical Macro Pad for Windows and macOS This project turns a 4-key mechanical switch matrix and a standard rotary encoder into a high-performance USB macro pad and media controller. It functions as a native wired USB HID device to control shortcuts and volume across Windows, macOS, and Linux.
//Features
  - Works natively as a USB HID keyboard device, no custom software required.
  -  Anti-ghosting key matrix uses individual switching diodes to prevent current bleed and ensure full n-key rollover.
  -  Dedicated quadrature encoder integration provides smooth, real-time volume adjustment.Compact PCB design optimized for standard Cherry MX footprints and clean signal routing.
//Hardware Required
  - Raspberry Pi Pico (RP2040)
  - 4x Cherry MX (or compatible) mechanical switches
  - 4x 1N4148 switching diodes
  - EC11 Rotary Encoder with push switch
  - Custom PCB Board
  - Micro-USB cable for power and data
//Software Setup
  - [Active Development] Firmware and project sketch files are currently being written. The software stack will utilize the standard Arduino IDE framework with USB HID keyboard and encoder libraries to map the matrix layout.
//Usage
  - Once firmware development is complete, plugging the PicoMediaPad into your computer via USB will automatically enumerate it as a keyboard, allowing you to use your macro keys and control volume instantly.
