# Kullanım kılavuzu

1. GenAI Setup.exe ile kurun. Başlangıçta çalıştırma isteğe bağlıdır; ayrıca firewall izni gerekmez.
2. Sistem tepsisinden Ayarlar'ı açın, Modeli indir'e basın ve yüzde göstergesinin tamamlanmasını bekleyin.
3. Mikrofonu ve metin çıktısını seçip Kaydet'e basın. Varsayılan arayüz Türkçe'dir; English seçilebilir.
4. Metnin yazılacağı pencereyi seçin. Ctrl + çift tırnağı basılı tutup konuşun, bırakınca dönüşümü bekleyin. İşlem sırasında pencere değişirse metin panoda kalır.
5. Model eğitimi → Eğitimi Başlat ile test kaydı yapın, aynı düğmeyle bitirin. Kelimeye tıklayıp Düzelt veya Sil'i seçin. Metnin tamamını kontrol edip Taslağı Onayla'ya basın. Hatalı taslakları Taslağı Sil ile kaldırın. Alttaki Kaydet yalnızca genel/gelişmiş ayarları içindir.
6. Destek Ol penceresinde cihaz için gönderim izni isteyin. Yönetici onayından sonra İzni kontrol et'e basın; onaylı kayıtları göndermek için kullanım iznini işaretleyip Gönder'e basın.
7. Güncellemeyi kontrol et yeni sürümü bulunca Güncelle açılır. İndirilen paket doğrulanır, mevcut kayıtlar ve düzeltmeler korunur.

## Sorun giderme

- Model hazır değil: indirmenin tamamlandığını ve model dosyalarının bulunduğunu kontrol edin.
- Mikrofon bulunamadı: Windows mikrofon gizlilik iznini ve Ayarlar'daki mikrofon seçimini kontrol edin.
- Vulkan başlatılamadı: ekran kartı sürücüsünü güncelleyin. Otomatik mod CPU'ya geçebilir; CPU daha yavaştır.
- Windows uyarısı: sürüm imzasızdır. Resmi GitHub kaynağı ve SHA256SUMS.txt dosyasını kontrol edin.
- Güncelleme yapılamadı: boş disk alanını ve bağlantıyı kontrol edin. Yeniden denemeden önce kaydı bitirin.

Hata bildirirken uygulama sürümü, Windows sürümü, CPU/GPU modeli ve görülen hata metni yeterlidir. Ses kayıtlarınızı, erişim anahtarlarınızı veya kişisel verilerinizi issue'lara eklemeyin.
