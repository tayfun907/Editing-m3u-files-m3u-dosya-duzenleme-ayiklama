# 📺 IPTV Liste Düzenleyici

Bu araç, `m3u` veya `m3u8` IPTV listelerinizi tarayıcı tabanlı arayüz ile kolayca düzenlemek, filtrelemek, sıralamak, kategorilendirmek ve dışa aktarmak için tasarlanmıştır.

## 🔒 Güvenlik ve Gizlilik Beyanı 

Bu araç, **gizlilik odaklı tasarlanmıştır** ve projenin yapısı gereği kullanıcı verilerini yerel tutarak gizliliğe öncelik verir.

* **İstemci Tarafı Çalışma:** Bu araç **tamamen tarayıcınızda (istemci tarafında)** çalışır. Kodunuzu görüntülemek için bir sunucuya ihtiyacınız yoktur.
* **XSS Koruması:** Kullanıcı tarafından girilen tüm metinler (kanal adı, kategori adı vb.) DOM'a eklenirken özel olarak temizlenir ve **salt metin olarak işlenir**. Bu, Cross-Site Scripting (XSS) saldırılarına karşı tam koruma sağlar.
* **Veri Gizliliği:** IPTV liste verileriniz veya kanal bilgileriniz **asla herhangi bir uzak sunucuya (geliştirici dahil) gönderilmez.**
* **Yerel Depolama:** Kanal listeniz, tarayıcınızın **IndexedDB** adlı güvenli yerel depolama alanında kalıcı olarak saklanır.
* **URL Yükleme:** Bir URL'den liste yüklediğinizde, liste verisi doğrudan o kaynaktan tarayıcınıza çekilir.

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
