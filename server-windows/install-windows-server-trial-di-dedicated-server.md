# Install Windows Server (Trial) di Dedicated Server

## Summary

Ada 2 cara untuk installasi os windows di dedicated server, yaitu :

1. Dengan `.img` files
2. Dengan `.iso` files dengan `Qemu vKVM` **\[Recomended] \[Host: Hetzner]**

## Catatan

* Beberapa host dedicated tidak bisa install via `.img` ini karena terkadang tidak kompatiblenya driver seperti :
  * Bios Legacy vs UEFI
  * Driver Network Terlalu Lawas/Tidak Include Terinstall
* Server seperti Dedicated dari `Hetzner` rekomendasi menggunakan opsi nomor 2, dicoba dengan Dedicated NVMe, lancar

## Cara Installasi dengan .img

