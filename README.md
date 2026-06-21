# TechFix AI - Akıllı Saha Teşhis Asistanı (Final Projesi)

TechFix AI; saha teknik personelinin operasyon esnasında karşılaştığı HP kurumsal yazıcı arızalarını, Wincor/Diebold ATM donanım kilitlenmelerini ve Cisco network/siber güvenlik problemlerini saniyeler içinde yerel dökümantasyon ve yapay zeka mantığıyla onarım talimatlarına dönüştüren bir saha asistanı prototipidir.

---

## 🛠️ Kullanılan Teknolojiler
* **HTML5 & CSS3** - Yapısal düzen ve iskelet mimarisi.
* **Tailwind CSS** - Modern, hızlı ve responsive (mobil uyumlu) arayüz tasarımı.
* **Vanilla JavaScript** - Sıfır bağımlılık (Zero-dependency) ile çalışan dinamik arama ve sekme yönetim motoru.

---

## 🌟 Özellikler (Features)
* **Çift Tıklamayla Çalışma (MVP):** Herhangi bir derleyici, yerel sunucu veya ek kuruluma ihtiyaç duymadan doğrudan tarayıcıda çalışır.
* **Responsive Tasarım:** Saha personelinin telefon, tablet veya laptop ekranlarında kusursuz görüntüleme sağlar.
* **Gelişmiş Profil Sayfası:** Teknisyen istatistikleri, SLA puanı ve kurumsal profil fotoğrafı entegrasyonu.
* **Hızlı Kılavuz Erişimi (Manuals):** HP, Wincor ve Cisco orijinal dökümanlarına doğrudan yönlendirme bağlantıları.

---

## 📊 Aktif Hata Kodu Veri Tabanı (60 Kritik Arıza)
Arama motoruna girildiğinde spesifik saha çözüm adımlarını ve yedek parça önerilerini listeleyen kodların tam listesi:

### 1. HP LaserJet / Enterprise Yazıcı Grubu (26 Adet)
* **50.4** - Fuser Isıtıcı Voltaj Hatası
* **59.F0** - Transfer Belt Sürücü Motor Hatası
* **79** - Kritik Firmware / Formatter Boot Hatası
* **13.00.00** - Genel Kağıt Sıkışma Hatası
* **57.00.03** - Anakart Alt-Termistör Soğutma Fanı Arızası
* **10.00.00** - Siyah Toner Sarf Malzemesi / Çip Okuma Hatası
* **10.23.60** - Atık Toner Kutusu (Waste Toner) Dolu Hatası
* **32.1C.05** - Dahili Depolama NVRAM Okuma Hatası
* **40.00.01** - Formatter Anakart USB Giriş / I/O İletişim Hatası
* **41.02.00** - Dahili Motor Geçiş / Ana Tahrik Motor Hatası
* **51.00.10** - Lazer Tarayıcı (Laser/Scanner) Aynası Tozlanma Arızası
* **52.00.00** - Lazer Poligon Motor Hız ve Voltaj Hatası
* **54.00.01** - Çevre Sıcaklık/Nem Sensörü (Environment Sensor) Hatası
* **55.00.01** - Engine-to-Formatter Ribbon Kablo İletişim Hatası
* **56.00.01** - Yanlış Çıkış Seçimi / Deflector Solenoid Donanım Hatası
* **58.00.04** - Alçak Gerilim Güç Kaynağı (LVPS) Voltaj Dalgalanma Hatası
* **60.00.02** - Tepsi 2 Kaldırma Motoru (Lifter Drive) Hatası
* **62.00.00** - Dahili Sistem Belleği (DDR SO-DIMM RAM) Slot Hatası
* **65.00.01** - Fuser Çıkış Sensörü (Photo-Interrupter) Blokajı
* **66.00.15** - Harici Sonlandırıcı (Finisher) Ara Bağlantı Kablo Hatası
* **68.00.01** - Kalıcı Bellek / Dahili SSD Depolama Alanı Dolu Hatası
* **80.00.01** - Gömülü Network Kartı (JetDirect) Donanım Arızası
* **99.00.01** - İşletim Sistemi Eksik / SATA Hard Disk Bağlantı Hatası
* **41.03.02** - Tepsi Medya Boyutu Algılama Switch Kartı Hatası
* **30.01.44** - Üst Doküman Besleyici (ADF) Tarayıcı Kalibrasyon Arızası

### 2. Wincor / Diebold ATM Grubu (21 Adet)
* **005** - ATM / Şube İçi Banka Network İletişim Kesintisi
* **182** - CMD Dispenser Modülü Nakit Çıkış / Shutter Sıkışma Hatası
* **114** - IDCU Motorlu Kart Okuyucu Giriş / Anti-Skimming Blokajı
* **001** - Ana Güç Kaynağı Akü Grubu ve Çevrimiçi UPS Kesinti Hatası
* **002** - EPP V6 Güvenli Şifre Klavyesi İletişim / Tamper Hatası
* **003** - Alt Para Kasası Güvenlik Kilidi (Safe Lock) Alarm Tetiklemesi
* **004** - Alarm Yönetim Paneli Sismik/Isı Sensör Sinyal Hatası
* **006** - Depozito Ünitesi (BNA) Giriş Ağzı Mekanik Palet Blokajı
* **007** - Kullanıcı/Müşteri Güvenlik Kamerası DVR Kayıt Hatası
* **008** - Fatura Ödeme Barkod Okuyucu Modül RS232 İletişim Hatası
* **009** - IDCU Kart Giriş Kapağı (Shutter) Mekanik Kapak Arızası
* **010** - Madeni Para Verici (Coin Dispenser) Hopper Mekanizma Sıkışması
* **101** - Para Kaseti 1 Switch Tırnağı / Nakit Tükendi Uyarısı
* **102** - Kaset 2 Banknot Kalınlık Ayar Vidası Kalibrasyon Hatası
* **103** - Hatalı/Şüpheli Para Toplama (Reject/Retract) Kutusu Dolu Uyarısı
* **104** - Vakum Dağıtıcı Vantuzları (Suction Cups) Hava Sızıntısı Arızası
* **110** - Akıllı Çip Okuma Pin Bloğu EMV İletişim Hatası
* **115** - Manyetik Bant Okuyucu (MSR) Kafa Kirlilik Arızası
* **120** - Dış Kabin Temassız Kart Okuyucu (NFC) Anten Sinyal Kaybı
* **150** - Müşteri Makbuz Yazıcısı (Receipt Printer) Rulo Kağıt Bitti Hatası
* **151** - Termal Yazıcı Kafa (Thermal Print Head) Aşırı Isınma Hatası
* **152** - Makbuz Yazıcı Otomatik Kesici (Cutter) Bıçak Blokajı

### 3. Cisco Network & Siber Güvenlik Grubu (14 Adet)
* **BGP-DOWN** - Merkez BGP Protokolü / VPN Tünel Kesintisi
* **HIGH-CPU** - %100 CPU Limit Aşımı / Debug Süreç Aşımı Arızası
* **LOOP-DETECT** - Katman 2 Döngü (STP Loop) / Broadcast Fırtınası
* **PING-FAIL** - Gateway Yanıt Vermiyor / Cat6 Patch Kablo Sinyal Kaybı
* **OSPF-DOWN** - OSPF Komşuluk İlişkisi MTU/Area ID Uyuşmazlık Arızası
* **PORT-SECURITY** - Yetkisiz MAC Adresi Tetiklemesi (Err-Disable) Hatası
* **VLAN-MISMATCH** - Trunk Link İki Ucu Native VLAN ID Uyuşmazlığı
* **DUPLEX-HALF** - Speed/Duplex Mismatch Kaynaklı Paket Kolizyon Hatası
* **DHCP-EXHAUST** - Havuz Tükenmesi Kaynaklı IP Dağıtım Blokajı
* **ACL-BLOCK** - Erişim Listesi (ACL) Hatalı Paket Engelleme Durumu
* **STP-ROOT-FLAP** - Spanning Tree Root Bridge Sürekli Değişim Arızası
* **SFP-ERR** - Optik SFP Modül RX-TX Sinyal Desibel (dBm) Düşüş Hatası
* **ARP-POISON** - MitM / Sahte Gateway ARP Zehirlenmesi Saldırı Tespiti
* **MAC-FLAP** - Kablo Döngüsü Kaynaklı MAC Adresi Yer Değiştirme Hatası
* **CRYPTO-FAIL** - IPSec VPN Kripto Aşama 1 (Phase 1) AES/SHA Eşleşme Hatası
* **NTP-UNSYNC** - Şube İçi Sistem Saati NTP Zaman Sunucusu Senkronizasyon Kaybı
* **TACACS-FAIL** - AAA Sunucu Bağlantı Kesintisi / Local Login Kimlik Doğrulama
* **SNMP-FLOOD** - İzleme Yazılımları (PRTG/SolarWinds) SNMP Aşırı Sorgu Yükü
* **FIBER-ATT** - Telekom Altyapı Hattı Yüksek Fiber Sinyal Zayıflaması (-20 dBm)

---

## 🚀 Kurulum ve Çalıştırma
1. Proje klasörünün içerisinde yer alan **`profil.png`** dosyasının silinmediğinden emin olun (Profil sayfasındaki görselin yüklenmesi için gereklidir).
2. **`TechFix-AI.html`** dosyasına herhangi bir güncel tarayıcıda (Chrome, Edge, Opera, Safari) **çift tıklayarak** uygulamayı anında çalıştırabilirsiniz.
https://stitch.withgoogle.com/projects/10408722445395952460
