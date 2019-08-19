

<img src="https://raw.githubusercontent.com/umarhadi/asus-x455lj-mojave/master/img/1.png">

# Asus X455LJ MacOS Mojave 10.14.06(18G87)

Spesifikasi:
- Prosesor: Intel Core i5-5200U
- VGA: Intel HD Graphics 5500 & Nvidia 920M(Disabled)
- RAM: 8GB (4x2 DDR3L)
- Storage: Sandisk SSD Plus 120GB & HDD Hitachi 5400RPM SATA2 500GB
- Wireless Card: Qualcomm Atheros AR9565 
<img src="https://raw.githubusercontent.com/umarhadi/asus-x455lj-mojave/master/img/2.png">
Perfect Work:
- VGA: Intel HD Graphics 5500
- Audio: latest AppleALC.kext + layout-id : 21. Lancar jaya, auto switch output.
- Camera / USB 2.0 Asus Webcam: latest USBInjectAll.kext 
- Wireless Card Qualcomm Atheros AR9565: patch IO80211Family.kext 
- RAM Dual Channel: native tanpa kext, 4GB DDR3L 1333 + 4GB DDR3L 1600, clockspeed yang dipakai yang 1333. Menyesuaikan clockspeed terendah dari kedua RAM.
- Baterai, termasuk indikatornya, shutdown, restart, sleep/hibernate: patch manual + latest ACPIBatteryManager.kext.
- Tombol Fn: bekerja normal semua, termasuk brightness dgn tombol f5 f6, volume.
Didn't Work:
- Realtek card reader, sudah hukum alam.

Bagi yang ingin mencoba install, mungkin memiliki Laptop/PC dengan spesifikasi yang hampir sama, bisa baca di sini. Sudah disertai link koleksi Vanilla DMG + Clover, direct access.
