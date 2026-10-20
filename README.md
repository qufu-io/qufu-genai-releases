# GenAI · Q-ASR

Windows 11 için Türkçe ve İngilizce yerel ses yazımı. Ctrl + çift tırnak tuşlarını basılı tutun, konuşun ve bırakın.

[GenAI Setup.exe indir](https://github.com/qufu-io/qufu-genai-releases/releases/latest/download/GenAI%20Setup.exe) · [Sürümler](https://github.com/qufu-io/qufu-genai-releases/releases) · [Kullanım kılavuzu](docs/KULLANIM.md)

## Kurulum

Windows 11 x64 gerekir. En az 4 GB RAM, uygulama ve model için yaklaşık 2 GB boş alan ayırın; 16 GB RAM önerilir. Kurucu uygun Vulkan veya CPU sürümünü seçer. Vulkan 1.2 destekli güncel ekran kartı sürücüsü önerilir; CPU daha yavaş çalışabilir.

Küçük setup modeli içermez. Q-ASR / Whisper Turbo Q5 modeli ilk kullanımda uygulama içinden yaklaşık 575 MB indirilir. Konuşma tanıma daha sonra çevrimdışı çalışır. macOS sürümü henüz yoktur.

Setup henüz kod imzalı değildir. Windows bilinmeyen yayıncı uyarısı gösterebilir. Yalnızca bu depodaki sürümleri kullanın; SHA256SUMS.txt ile dosya bütünlüğünü kontrol edebilirsiniz.

## Özellikler ve veriler

- Basılı tutarak dikte, kopyalama, yapıştırma ve isteğe bağlı Enter ile gönderme.
- Sese tepki veren, taşınabilir ve boyutlandırılabilir maskot.
- Model eğitimi sekmesinde taslak kayıt, kelime düzeltme, onaylama ve silme.
- Kişisel düzeltme hafızası; bu işlem model ağırlıklarına anlık fine-tuning yapmaz.
- Destek Ol ile yalnızca açıkça onayladığınız kayıtları, cihaz izni ve paylaşım onayıyla gönderme.
- Güncellemeleri GitHub Releases üzerinden kontrol etme; mevcut kişisel kayıtlar korunur.

Kurulu uygulama kullanıcı verilerini `%LOCALAPPDATA%/GenAI` altında tutar. Ses ve metin yalnızca Destek Ol bölümünden Gönder'e bastığınızda paylaşılır. Online cihaz durumu için ses içermeyen cihaz kimliği/sürüm bildirimleri gönderilir; sunucu IP ve son görülme bilgisini işler. Ayrıntılar: [Gizlilik](docs/PRIVACY.md).

Bu depo kurulum paketlerini ve belgeleri içerir. Uygulama kaynak kodu özel depoda tutulur. Paket içindeki LICENSE ve üçüncü taraf lisansları geçerlidir.

Yazar / bakım: **Alper <alper@qufu.io>**. Katkı: **Codex** (AI-assisted development).

## English

GenAI is a Windows 11 x64 push-to-talk dictation app for Turkish and English. Hold Ctrl + double quote, speak, then release. The installer selects Vulkan or CPU support; download the local Q-ASR / Whisper Turbo Q5 model in the app. Recognition then works offline. Personal corrections do not train model weights in real time. Sending training recordings is optional and requires explicit consent and device approval. Updates use GitHub Releases. Source code is maintained privately.

[Download](https://github.com/qufu-io/qufu-genai-releases/releases/latest/download/GenAI%20Setup.exe) · [Report a bug](https://github.com/qufu-io/qufu-genai-releases/issues/new/choose) · Contact: alper@qufu.io
