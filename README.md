# Tüketici Hakem Heyeti – Yasal Faiz Hesaplayıcı

Tüketici Hakem Heyeti kararları için hazırlanmış, mobil uyumlu ve çevrimdışı çalışabilen bir yasal faiz hesaplama uygulaması.

## Özellikler
- Ana para ve faiz başlangıç/bitiş tarihiyle hesaplama
- Tarihsel oranları dönemlere ayırarak basit faiz hesabı
- Faiz oranı dönemlerini ekleme, silme ve düzenleme
- Dönem bazında gün, oran ve faiz dökümü
- Sonuç özetini kopyalama ve yazdırma / PDF
- iPhone Safari üzerinden Ana Ekrana Ekle (PWA)
- Service Worker ile çevrimdışı kullanım

## iPhone'a yükleme
1. Uygulamayı iPhone'da Safari ile aç.
2. Paylaş düğmesine dokun.
3. **Ana Ekrana Ekle** seçeneğini seç.
4. Eklenen simgeye dokunarak uygulamayı tam ekran aç.

## GitHub Pages
Repository Settings → Pages → Build and deployment bölümünde **Deploy from a branch** seç.
Branch olarak `main`, klasör olarak `/(root)` seçip Save'e bas.
Yayın adresi: https://trustindestiny.github.io/tuketici-hakem-heyeti-yasal-faiz/

## Hesaplama notu
Uygulama başlangıç günü dahil, bitiş günü hariç olacak şekilde gerçek gün/365 ve basit faiz yöntemi kullanır. Varsayılan oran tarihçesi düzenlenebilir; hukuki dosyada kararın hüküm fıkrası ve uygulanacak güncel mevzuat kontrol edilmelidir. Bu araç hukuki danışmanlık veya icra dairesinin kesin hesabı yerine geçmez.

Tüm hesaplamalar cihaz üzerinde yapılır. Girilen tutar ve tarihler herhangi bir sunucuya gönderilmez.
