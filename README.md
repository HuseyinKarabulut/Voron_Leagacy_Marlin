
<img width="752" height="752" alt="VORON_Legacy_Assembly v5" src="https://github.com/user-attachments/assets/3d401963-6f7f-41a6-9bf3-f36dd228581e" />



# 📁 Özelleştirilmiş Marlin 2.x Yapılandırması

## 🔧 Donanım Özellikleri
- 🖥 **Anakart:** MKS Robin Nano V3
- 🖥 **Ekran:** MKS TFT35 (MKS T35)
- ⚙ **Mekanik Yapı:** CoreXY
- 🧵 **Ekstrüder Sayısı:** 2 (Tek nozzle - Single Nozzle sistemi aktif)
- 🎛 **Sürücüler:** TMC2209 (X, Y, Z, E0, E1)
- 🌡 **Sıcaklık Sensörleri:** Hotend ve Tabla için 100K NTC (EPCOS)
- 🛑 **Endstop Konfigürasyonu:** X min, Z min, Y max endstop kullanımı
- 🛠 **Problama:** Sabit monte edilmiş z-probu, Offset: { -20, -1, -1.2 }
- 🖨 **Yazdırılabilir Alan:** 235 x 235 x 227.3 mm

## ⚠ Önemli Ayarlar
- COREXY etkin
- PID sıcaklık kontrolü ve termal koruma açık
- Tek nozzle (SINGLENOZZLE) aktif
- Yazılımsal endstoplar açık
- Inaktif ekstrüder devre dışı bırakma aktif

## 📦 Kullanım
1. Dosyaları Marlin 2.x kaynak dizinine kopyalayın.
2. `Configuration.h` ve gerekirse diğer yapılandırma dosyalarını değiştirin.
3. PlatformIO veya Arduino IDE ile derleyin ve yükleyin.

## 🛠 Kaynaklar
- [Marlin Resmi Sitesi](https://marlinfw.org/)
- [MKS Robin Nano V3 Bilgi Sayfası](https://makerbase3d.com/product/robin-nano-v3-eagle-32bit-168mhz-f407-control-board-3d-printer-parts-tft-screen-usb-print/)
- [MKS Robin Nano V3 Github](https://github.com/makerbase-mks/MKS-Robin-Nano-V3.X)

## ⚡ Uyarılar
⚠ Bu yapılandırma yalnızca ilgili donanım için optimize edilmiştir. Farklı donanımlarda kullanmadan önce mutlaka inceleme ve test yapınız.

---

# 📁 Customized Marlin 2.x Configuration

## 🔧 Hardware Features
- 🖥 **Mainboard:** MKS Robin Nano V3
- 🖥 **Screen:** MKS TFT35 (MKS T35)
- ⚙ **Mechanics:** CoreXY
- 🧵 **Extruders:** 2 (Single Nozzle system enabled)
- 🎛 **Drivers:** TMC2209 (X, Y, Z, E0, E1)
- 🌡 **Temperature Sensors:** 100K NTC for Hotend and Bed
- 🛑 **Endstops:** X min, Z min, Y max
- 🛠 **Probing:** Fixed-mounted probe, Offset: { -20, -1, -1.2 }
- 🖨 **Printable Area:** 235 x 235 x 227.3 mm

## ⚠ Key Settings
- COREXY enabled
- PID temperature control & thermal protection enabled
- Single Nozzle system active
- Software endstops enabled
- Disable inactive extruder option active

## 📦 Usage
1. Copy files to your Marlin 2.x source directory.
2. Replace `Configuration.h` and other necessary files.
3. Compile and upload via PlatformIO or Arduino IDE.

## 🛠 Resources
- [Official Marlin Website](https://marlinfw.org/)
- [MKS Robin Nano V3 Info Page](https://makerbase3d.com/product/robin-nano-v3-eagle-32bit-168mhz-f407-control-board-3d-printer-parts-tft-screen-usb-print/)
- [MKS Robin Nano V3 Github](https://github.com/makerbase-mks/MKS-Robin-Nano-V3.X)


## ⚡ Warnings
⚠ This configuration is optimized for specific hardware. Always review and test thoroughly before using on other setups.
