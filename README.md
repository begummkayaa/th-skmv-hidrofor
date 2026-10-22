# Safety 4.0 Bootcamp – Laboratuvar Föyleri (TH SKMV Hidrofor Sürümü)

**Ad Soyad:** Begüm Kaya  
**Grup:** Gece B  
**Tarih:** 22.10.2026

## Seçilen Makine
**Standart Pompa TH 3 x SKMV 50/3 – Kullanım Suyu Hidrofor Seti**

Dikey çok kademeli 3 pompalı hidrofor seti. 10-16-25 bar gövde basıncı, basınçlı kolektör ve genleşme tankı, depo flatörü (kuru çalışma koruması), basınç şalterleri ve frekans kontrollü pano içerir. Senaryoda bir hastane binasının kullanım suyunu basmaktadır.

Laboratuvarlarda şişeleme hattı ve PaketPro 3000 örneklerinde yapılan çalışmalar bu makineye uyarlanmıştır.

> Not: Makine verileri Standart Pompa TH Serisi İşletme ve Bakım Kılavuzu ile TH SKMV kataloğundan alınmıştır. 4G uzaktan izleme modemi, BMS bağlantısı ve varsayılan pano şifresi gibi ağ bağlantıları ders senaryosu için varsayılmıştır.

## Laboratuvarlar

| Lab | Konu | Çıktı | Dosya |
|-----|------|-------|-------|
| 1 | Safety Architecture | Safety Function Map | `Lab1_Safety_Architecture.pdf` |
| 2 | IEC 62443 Mini Workshop | Zone / Conduit Diagram | `Lab2_IEC62443_Mini_Workshop.pdf` |
| 3 | Threat & Risk + Risk Matrix | Risk Register | `Lab3_Threat_Risk_Matrix.pdf` |
| 4 | Secure Remote Access | Secure Architecture | `Lab4_Secure_Remote_Access.pdf` |

## Özet
- **Tehlikeler:** basınç enerjisi (patlama), dönen mil/kaplin, 380 V pano, kuru çalışma
- **Emniyet fonksiyonları:** aşırı basınçta durdurma, kuru çalışmayı engelleme, bakımda beklenmedik çalışmayı önleme
- **Kritik bulgu:** internete açık 4G modem ile kontrol sistemi arasındaki dijital kesişim noktası
- **Hedef mimari:** jump server, VPN + MFA, kişisel hesap, oturum kaydı, varsayılan kapalı erişim
