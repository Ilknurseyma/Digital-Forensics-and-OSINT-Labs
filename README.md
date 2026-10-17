# Adli Bilişim (DFIR) ve OSINT Laboratuvar Analiz Raporları

Bu depo (repository); **Adli Bilişim (Digital Forensics)** ve **Açık Kaynak İstihbaratı (OSINT)** alanlarında gerçekleştirilen pratik laboratuvar çalışmaları, metodoloji dokümanları ve analiz raporlarını içermektedir.

## 🛠️ Kullanılan Araçlar ve Teknolojiler
- **Adli Bilişim / Bellek Analizi:** FTK Imager, Volatility Framework, Autopsy, MD5/SHA256 Hash Doğrulama
- **OSINT ve Üstveri (Metadata) Analizi:** ExifTool, TryHackMe CTF Laboratuvarları, Linux Terminali

---

## 📁 Depo İçeriği

### 1. Adli Bilişim ve Kanıt İnceleme
- **RAM İmajı Alma ve İnceleme (`RAM imaj alma inceleme.pdf`):** Çalışır durumdaki sistemlerden bellek dökümü (`.mem`) alma adımları ve bellek üzerindeki izlerin incelenmesi süreçleri.
- **Veri Bütünlüğü ve Hash Doğrulama (`hash_degeri_alma_compressed.pdf`):** Adli bilişim standartlarına uygun olarak dijital kanıtların kriptografik hash değerlerinin (MD5/SHA1/SHA256) çıkarılması ve bütünlük kontrolü.

### 2. OSINT ve Görsel Adli Bilişim
- **Üstveri Analizi ve Görsel İnceleme (`TryHackMe Ohsınt Odevi.pdf`):** CTF senaryoları üzerinde `ExifTool` ve OSINT yöntemleri kullanılarak konum tespiti, kamera detayları extraction işlemleri ve gizli veri/bayrak (flag) tespiti.
