<div align="center">
  <img src="https://i.pinimg.com/736x/73/a6/6c/73a66c7305d2bfb15b9a51c8d07d796b.jpg" alt="Oxy Banner" width="20%">
  
  # Oxy - Gelişmiş Discord Botu
  
  [![Discord.js](https://img.shields.io/badge/Discord.js-v14-blue?style=flat-square&logo=discord)](https://discord.js.org/)
  [![Node.js](https://img.shields.io/badge/Node.js-v18%2B-green?style=flat-square&logo=node.js)](https://nodejs.org/)
  [![MongoDB](https://img.shields.io/badge/MongoDB-Data-red?style=flat-square&logo=mongodb)](https://www.mongodb.com/)
  [![License](https://img.shields.io/badge/Lisans-MIT-yellow?style=flat-square)](LICENSE)
  
  **OXY IN THE PARTY**
  
  [Özellikler](#-özellikler) • [Kurulum](#-kurulum) • [Komutlar](#-komutlar) • [Destek](#-destek)
</div>

---

## 🌟 Özellikler

Oxy, sunucu deneyiminizi geliştirmek için tasarlanmış kapsamlı bir Discord botudur:

### 🔧 Yönetim
- Kanal kilitleme/açma
- Mesaj temizleme
- Rol yönetimi
- Sunucu duyuruları

### 🛡️ Moderasyon
- Otomatik spam koruması
- Küfür filtreleme
- Reklam engelleme
- Kara liste sistemi
- AFK yönetimi

### 🎉 Eğlence & Sosyal
- Eğlenceli etkileşim komutları (sarılma, öpme, yumruk)
- Profil özelleştirme
- Spotify entegrasyonu
- Ship uyumluluk kontrolü
- Twitter simülasyonu

### 🎫 Destek Sistemleri
- Birden fazla kategoride bilet oluşturma
- Başvuru panelleri (yetkili, öneri, şikayet)
- Tam özelleştirilebilir özel ses kanalları
- Sık sorulan sorular için otomatik yanıtlar

### 📊 İstatistikler & Takip
- Mesaj istatistikleri
- Ses etkinliği takibi
- Davet takibi
- Kayıt istatistikleri

### ⚙️ Özelleştirme
- Kategori seçimli dinamik yardım menüsü
- Rol seçim panelleri (bildirimler, oyunlar, renkler)
- Özel emoji yönetimi
- Sunucu afişi özelleştirme

---

## 🚀 Kurulum

### Gereksinimler
- Node.js v18 veya üzeri
- MongoDB veritabanı
- Discord Bot Token ([Rehber](https://discordjs.guide/preparations/setting-up-a-bot-application.html))

### Kurulum Adımları

1. Depoyu klonlayın:
```bash
git clone https://github.com/hasbutcu/priw-bot.git
cd priw-bot
```

2. Bağımlılıkları yükleyin:
```bash
npm install
npm install pm2 -g
```

3. Botunuzu yapılandırın:
- `conf.json` ve `Database/src/Settings/settings.json` dosyasını doldurun
- Bot tokeninizi, MongoDB bağlantı dizenizi ve diğer ayarları girin

4. Botu başlatın:
```bash
pm2 start ecosystem.config.js
```

5. Hataları Kontrol Edin:
```bash
pm2 log
```

---

## 📜 Komutlar

Oxy, sezgisel kategoriler halinde organize edilmiş 50+ komuta sahiptir:

| Kategori | Açıklama |
|----------|----------|
| **Yönetici** | Kilitleme, temizleme ve duyuru araçları gibi sunucu yönetim komutları |
| **Moderasyon** | Yasaklama, atma ve koruma sistemleri |
| **Eğlence** | Eğlence için interaktif komutlar |
| **Kullanıcı** | Profil, avatar ve yardımcı komutlar |
| **Sahip** | Geliştiriciye özel bot yönetim araçları |
| **Rol Seçimi** | Üyeler için kendi kendine atanabilir roller |
| **Sistem** | Çekirdek bot işlevselliği ve kurulum araçları |

Sunucunuzda mevcut tüm komutları açıklamalarıyla görmek için `.yardım` komutunu kullanın.

---

## 🛠️ Yapılandırma

Bot, modüler bir yapılandırma sistemini kullanır:

- `conf.json` - Ana yapılandırma dosyası
- `Database/src/Settings/` - Emojiler, roller ve sistem ayarları için JSON dosyalarını içerir
- Kalıcı veri depolama için MongoDB modelleri

---

## 🤝 Destek

Botla ilgili yardıma mı ihtiyacınız var?

- Geliştiriciyle iletişime geçin: **oxyinc**
- Hata raporları için [GitHub Issues](https://github.com/hasbutcu/priw-bot/issues) sayfasını kontrol edin
- [discord.gg/vsc](https://discord.gg/vsc)

---

## 📄 Lisans

Bu proje MIT Lisansı altında lisanslanmıştır - ayrıntılar için [LICENSE](LICENSE) dosyasına bakın.

---

## ❤️ Teşekkürler

- Harika kütüphaneleri için Discord.js topluluğuna teşekkürler
- Botun ilk halini benimle paylaştığı ve geliştirmeme izin verdiği için [schwest.](http://discord.com/api/users/1281228187560448014)'e teşekkürler

<div align="center">
  <a href="https://github.com/hasbutcu">oxy</a> tarafından ❤️ ile yapıldı
</div>