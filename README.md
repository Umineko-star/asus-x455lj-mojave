

<img src="https://raw.githubusercontent.com/umarhadi/asus-x455lj-mojave/master/img/1.png">

# Asus X455LJ MacOS Mojave 10.14.06(18G87)

Spesifikasi :
  <ul><li>Prosesor: Intel Core i5-5200U</li>
  <li>VGA: Intel HD Graphics 5500 & Nvidia 920M(Disabled)</li>
  <li>RAM: 8GB (4x2 DDR3L)</li>
  <li>Storage: Sandisk SSD Plus 120GB & HDD Hitachi 5400RPM SATA2 500GB</li>
  <li>Wireless Card: Qualcomm Atheros AR9565 </li></ul>
<img src="https://raw.githubusercontent.com/umarhadi/asus-x455lj-mojave/master/img/2.png">
Perfect Work:
<ul><li>VGA: Intel HD Graphics 5500</li>
  <li>Audio: latest AppleALC.kext + layout-id : 21. Lancar jaya, auto switch output.</li>
  <li>Camera / USB 2.0 Asus Webcam: latest USBInjectAll.kext</li>
  <li>Wireless Card Qualcomm Atheros AR9565: patch IO80211Family.kext </li>
<li>RAM Dual Channel: native tanpa kext, 4GB DDR3L 1333 + 4GB DDR3L 1600, clockspeed yang dipakai yang 1333. Menyesuaikan clockspeed terendah dari kedua RAM.</li>
<li>Baterai, termasuk indikatornya, shutdown, restart, sleep/hibernate: patch manual + latest ACPIBatteryManager.kext.</li>
  <li>Tombol Fn: bekerja normal semua, termasuk brightness dgn tombol f5 f6, volume.</li></ul>
Didn't Work:
  <ul><li>Realtek card reader, sudah hukum alam.</li></ul>

Bagi yang ingin mencoba install, mungkin memiliki Laptop/PC dengan spesifikasi yang hampir sama, bisa baca di sini. Sudah disertai link koleksi Vanilla DMG + Clover, direct access.
