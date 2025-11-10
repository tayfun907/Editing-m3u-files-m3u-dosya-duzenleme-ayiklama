# 📺 IPTV Liste Düzenleyici

Bu araç, `m3u` veya `m3u8` IPTV listelerinizi tarayıcı tabanlı arayüz ile kolayca düzenlemek, filtrelemek, sıralamak, kategorilendirmek ve dışa aktarmak için tasarlanmıştır.

#

## 🚀 Başlarken

Bu aracı kullanmanın iki temel yolu vardır:

* **Canlı Kullanım (Önerilen):** Geliştiricinin sunduğu [**https://tinyurl.com/m3uurlduzenle**](https://tinyurl.com/m3uurlduzenle) üzerinden aracı doğrudan tarayıcınızda kullanın.
* **Yerel Kullanım:** Kod dosyasını (`index.html`) bilgisayarınıza indirin ve herhangi bir tarayıcıda çift tıklayarak internet bağlantısına ihtiyaç duymadan çalıştırın.

Kullanıma başlamak için:

1.  Uygulamayı açın.
2.  `.m3u` veya `.m3u8` dosyanızı **Dosya** butonundan yükleyin veya **URL** alanına liste adresini girin.

## ✨ Temel Özellikler

* **Hızlı Ayrıştırma:** Büyük M3U listelerini hızlı ve asenkron olarak işler.
* **Kalıcı Depolama:** Veriler tarayıcınızın yerel belleğinde (IndexedDB) kalıcı olarak saklanır.
* **Kanal Yönetimi:** Başlık, kategori ve URL'leri çift tıklayarak anında düzenleme.
* **Toplu İşlemler:** Seçili kanalları silme, taşıma veya dışa aktarma.
* **Hata Kontrolü:** Çalışmayan/Kırık URL'leri tespit etme (Basit `HEAD` kontrolü).
* **Oynatıcı Desteği:** Entegre VideoJS/HLS/Shaka oynatıcı ile kanalları anında test etme.
