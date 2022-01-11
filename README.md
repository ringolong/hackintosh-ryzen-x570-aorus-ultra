# hackintosh-ryzen-x570-aorus-ultra

Operating System: Monterey (12.1)

OpenCore: 7.5

## Hardware:

- Motherboard: Gigabyte X570 Aorus (I removed the Intel bluetooth/WiFi card)

- Processor: AMD Ryzen 5900x

- Ram: F4-3200C16D-64GTZN (Needs to be overclocked to 3200MHz)

- GPU: AMD Radeon RX 5700 8 GB

- Samsung 980 PRO PCIe 4.0 NVMe M.2 SSD

- Network Adapter:  Tp-Link TG-3468 (RealtekRTL8111.kext)

- WiFi/Bluetooth:  fenvi FV-T919


## BIOS:

- Disable fTPM (re-enable after installation)

- Disable above 4g decoding 


## Configuration:

- Update Platform Information

- Update processor core count if not 12 core

Use [GenSMBIOS] to update your platform information.

[GenSMBIOS]: <https://github.com/corpnewt/GenSMBIOS>
