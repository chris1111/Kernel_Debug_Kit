# Kernel_Debug_Kit for Kext-Drop

Kernel Debug Kit for macOS -
Read Me
Use the Kernel Debug Kit (KDK) to debug kernel-level code, such as kernel extensions you
create.
Performing Two-Machine Debugging
The KDK supports the debugging of kernel-level code, such as kernel extensions, from a second
Mac.
- The target device is the Mac that runs the code you want to debug.
- The host device is the Mac that runs the debugger.
- Identify Device Compatibility
- On Apple silicon, perform two-machine debugging using your Mac’s built-in Ethernet ports.
- On Intel-based Macs, perform two-machine debugging using your Mac’s built-in Ethernet ports,
- the Ethernet port on the Apple Thunderbolt display, or the Apple Thunderbolt to Gigabit Ethernet
adapter. You may also use third-party Thunderbolt Ethernet adapters that support one of the
### following chipsets:
• Broadcom C-IV
• Aquantia AQC107/113
• Intel 82574L
#### Note: You cannot perform two-machine debugging using USB Ethernet adapters or wireless
networking on any Mac.
You must connect the host and target device to the same network.
