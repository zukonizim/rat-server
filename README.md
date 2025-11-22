# RAT Projesi - Uzaktan Yönetim Aracı

**Uyarı: Bu proje yalnızca eğitim amaçlıdır. Bilgisayar sistemlerine yetkisiz erişim yasaktır.**

## Genel Bakış
Uzaktan Yönetim Aracı (RAT) ile:
- Node.js komut ve kontrol sunucusu
- Android istemci aracısı
- Telegram tabanlı kontrol arayüzü

  ## Sunucu Kurulumu
1. [BotFather](https://t.me/botfather) ile Telegram botu oluşturun
2. Bot belirtecinizi ve sohbet kimliğinizi kopyalayın
3. Sunucu dizininde şifreleme anahtarını oluşturun: `npm run keygen`
4. `.env.example` dosyasına dayalı `.env` dosyası oluşturun
5. Bağımlılıkları yükleyin: `npm install`
6. Sunucuyu başlatın: `npm start`

## Android İstemci Kurulumu
1. Projeyi Android Studio'da açın
2. `MainService.kt` dosyasındaki WebSocket URL'sini güncelleyin
3. Derleyin ve cihaza yükleyin: `./scripts/build-apk.sh`


## Dağıtım
- Sunucu: DigitalOcean için `scripts/deploy.sh` kullanın
- İstemci: APK derlemek için `scripts/build-apk.sh` kullanın


## Yasal Uyarı
Bu yazılım yalnızca eğitim amaçlıdır. Geliştirici, bu aracın herhangi bir şekilde kötüye kullanılmasından sorumlu değildir.
