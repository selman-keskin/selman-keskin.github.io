# Selman Keskin — kişisel web sitesi

## Yerel önizleme
index.html dosyasını tarayıcıda açın veya bu klasörde `python3 -m http.server 8000` çalıştırıp http://localhost:8000 adresine gidin.

## GitHub Pages ile yayınlama
1. GitHub hesabınızda `KULLANICIADINIZ.github.io` adlı public repository oluşturun.
2. ZIP arşivini açın. İçindeki dosyaları ve blog klasörünü repository köküne yükleyin (index.html kökte olmalı).
3. Settings → Pages → Build and deployment → Deploy from a branch → main → / (root) → Save.
4. Yayın tamamlandığında https://KULLANICIADINIZ.github.io adresini açın.

## Düzenleme
- index.html: kişisel bilgiler, kariyer, projeler, blog kartları.
- style.css: renkler, şekiller, mobil tasarım.
- app.js: tema ve blog filtreleri.
- blog/: Türkçe yazılar. Yeni bir HTML dosyası oluşturup ana sayfadaki blog bölümüne bağlantısını ekleyebilirsiniz.
- Fotoğraf sağlanmadığı için SK baş harfli geometrik tasarım kullanılmıştır. Fotoğraf eklemek için site köküne profil.jpg koyup index.html içindeki initials div yerine `<img src="profil.jpg" alt="Selman Keskin" style="position:absolute;left:34%;top:34%;width:32%;height:32%;object-fit:cover;border-radius:50%">` ekleyin.
- Kariyer bilgilerini resmi CV ile, LinkedIn adresini de kendi profilinizle karşılaştırın. Blog yazıları yayın öncesi gözden geçirilmesi gereken taslaklardır.

Site harici kütüphane, takip kodu veya sunucu gerektirmez. Ücretsiz yayın koşulları platforma bağlıdır.
