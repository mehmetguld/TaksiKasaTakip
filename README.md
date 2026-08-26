# 🚕 Taksi Kasa Takip

Taksi şoförleri ve durak işletmecileri için tasarlanmış, tamamen tarayıcı üzerinde ve çevrimdışı (offline) çalışabilen, detaylı gelir-gider takip web uygulamasıdır.

Bu uygulama, herhangi bir sunucuya veya veritabanına ihtiyaç duymadan verilerinizi doğrudan cihazınızın tarayıcısına (LocalStorage) kaydeder. Cihazınıza "Ana Ekrana Ekle" yöntemiyle kurarak tıpkı yerel bir mobil uygulama gibi kullanabilirsiniz.

## ✨ Öne Çıkan Özellikler

* **Çevrimdışı Çalışma:** İnternet bağlantısı olmadan gelir ve gider ekleme imkanı.
* **Gelişmiş Gelir Birleştirme:** Aynı gün içinde girilen birden fazla geliri (Nakit, Kredi Kartı, HGS vs.) otomatik olarak toplayıp tek satırda gösterir.
* **Çoklu Para Birimi:** TL'nin yanı sıra Dolar ($) ve Euro (€) cinsinden gelirleri ayrı ayrı takip edebilme.
* **Detaylı Raporlama:** İstenilen tarih aralıklarında (günlük, haftalık, aylık, yıllık) filtreleme.
* **Aylık Özet Tablosu:** Tüm verilerinizi aylara bölerek net kâr-zarar durumunu tek ekranda sunar.
* **Borç Takibi:** Ödenmemiş giderleri (veresiye/borç) kırmızı etiketlerle işaretleme ve sonradan "Ödendi" olarak güncelleyebilme.
* **Dışa/İçe Aktarım (Yedekleme):** Veri kaybını önlemek veya başka cihaza geçiş yapmak için verileri JSON formatında indirebilme ve geri yükleyebilme.
* **Excel & PDF Çıktısı:** Seçilen tarih aralığındaki tüm hareketleri tek tıkla Excel (.xlsx) veya PDF olarak cihaza kaydetme.

## 🚀 Kurulum ve Kullanım

Uygulamayı kullanmak için herhangi bir kurulum yapmanıza gerek yoktur, sadece HTML dosyasını çalıştırmanız yeterlidir.

### 1. Yerel (Bilgisayarda) Kullanım
Projeyi bilgisayarınıza indirin ve `index.html` (veya `Taksi_Kasa_Takip_v2.html`) dosyasını Google Chrome, Safari veya Firefox gibi modern bir tarayıcıda açın. 

### 2. Mobil Uygulama Gibi Kullanım (Önerilen)
Uygulamayı telefonunuzda tam ekran ve ikonlu bir şekilde kullanmak için:
1. Bu projeyi kendi GitHub hesabınıza Fork'layın veya yükleyin.
2. **GitHub Pages** ayarlarından projeyi canlıya alın.
3. GitHub'ın size verdiği linki telefonunuzun tarayıcısında (iOS için Safari, Android için Chrome) açın.
4. Tarayıcı menüsünden **"Ana Ekrana Ekle" (Add to Home Screen)** seçeneğine dokunun.
5. Artık telefonunuzun menüsündeki ikona tıklayarak uygulamayı internetsiz kullanabilirsiniz.

## 🛠️ Kullanılan Teknolojiler

* **HTML5, CSS3, JavaScript (ES6)**
* **Bootstrap 5:** Modern ve mobil uyumlu (responsive) arayüz tasarımı.
* **FontAwesome:** Kullanıcı arayüzü ikonları.
* **SheetJS:** Excel formatında dışa aktarım işlemleri.
* **html2pdf.js:** Tabloları PDF formatına dönüştürme işlemleri.
* **LocalStorage:** Tarayıcı tabanlı yerel veri saklama (Veritabanı niyetine).

## ⚠️ Önemli Uyarı
Bu uygulama verileri sadece kullanıldığı tarayıcının yerel hafızasında tutar. Tarayıcı geçmişini/çerezleri temizlemeniz durumunda verileriniz silinebilir. Bu nedenle **Ayarlar** menüsünden düzenli olarak **JSON** formatında yedek almanız (Dışa Aktar) şiddetle tavsiye edilir.
