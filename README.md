# Executive Chef Control Center — Türkçe

İbrahim Başeğmez için hazırlanmış mutfak operasyonları yönetimi prototipi.

## İlk sürüm
Python + Streamlit + SQLite ile yerel çalıştırılabilir uygulama hazırlandı. Modüller:
- Reçete / porsiyon / onay / alerjen ve menü planlama
- Personel / vardiya / saatlik maliyet / eğitim
- Satın alma / envanter / minimum stok / gider
- HACCP kontrol kayıtları, uygunsuzluk, düzeltici faaliyet
- Olay / sorumlu / görev / misafir memnuniyeti
- 1, 7, 15 ve 30 günlük analitik ve JSON/CSV raporları
- Teorik food cost hedefine göre ±%30'dan büyük göreli sapmada panel uyarısı

## Durum ve erişim
Uygulamanın çalıştırılabilir kaynak ZIP paketi, ChatGPT konuşması içinde teslim edilmiştir. **Bu GitHub deposunda henüz uygulamanın tüm kaynak dosyaları yayınlanmamıştır.** Dağıtım öncesinde ZIP içindeki `app.py`, `core.py`, `tests/`, `requirements.txt` ve `.github/workflows/tests.yml` dosyaları eklenmelidir.

## Önemli uyarılar
- Bu repo herkese açıktır; müşteri, çalışan, finansal kayıt veya parola eklemeyin.
- Örnek veri sentetiktir.
- Güncel MVP uyarıları yalnızca panelde gösterir. Sürekli zamanlanmış tarama, WhatsApp/e-posta teslimi ve POS entegrasyonları tamamlanmamıştır.
- HACCP/CCP kontrol limitleri yetkili gıda güvenliği sorumlusunun onayıyla işletmeye özgü tanımlanmalıdır.
- Oturum açma, rol yönetimi, güvenli barındırma ve fiilî COGS entegrasyonu kurumsal kullanımdan önce şarttır.

## İzleyen geliştirmeler
1. Üretim veritabanı + RBAC + denetim logları
2. POS / stok / muhasebe mutabakatı
3. Günlük, 15 günlük, 30 günlük otomatik zamanlayıcı
4. SMTP/WhatsApp Business uyarıları, teslim kaydı, eskalasyon
5. HACCP limit, kalite ve personel yeterlilik onay akışları
