# animecix-webhook
Animecix.tv sitesinden yeni bölümleri takip eden ve Discord'a webhook ile bildirim gönderen Python botu. Veritabanı olarak SQLite kullanır.

## Özellikler
- Veritabanı ile bölüm takibi, önceden bildirimi yapılmış bölümleri tekrar bildirmesini engeller.
- Discord üzerinden oluşturulmuş bir rolü etiketleyerek hedef kanalda yeni bölüm bildirimi gönderimi.

## Kurulum
1. Repoyu klonlayın: `git clone ...`
2. Gereksinimleri yükleyin: `pip install -r requirements.txt`
3. `.env` dosyasını oluşturun ve şunları ekleyin:
   - `WEBHOOK_URL = <discord-webhook-url>`
   - `ROL_ID = <discord-rol-id>`