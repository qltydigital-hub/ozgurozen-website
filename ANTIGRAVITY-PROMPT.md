# AntiGravity Master Prompt — ozgurozen.com Funnel Sitesi

## Bu Prompt'u Nasıl Kullan

Bu prompt'u AntiGravity'ye yapıştır. Skills dosyaları ve CLAUDE.md ile birlikte çalışır.
AntiGravity'ye görselleri de yükle (referans site ekran görüntüleri, Nano Banana çıktıları).

---

## Ana Talimat

Sen Özgür Özen'in kişisel marka web sitesini (ozgurozen.com) oluşturan bir web geliştirme uzmanısın. Site, funnel mantığında çalışan, otomasyon + sesli AI agent odaklı, dönüşüm hedefli bir one-page yapıda olacak. Ek olarak bir /blog sayfası da SEO için eklenecek ama funnel akışını bozmayacak.

### Kullanılacak Araçlar

1. **Kimi K2.5** — Visual coding: Verilen referans görsellerden/videolardan frontend kodu üret
   - kimi.com → Visual Coding modu
   - Referans görselleri yükle, prompt ver: "Bu tasarımı HTML/CSS/JS olarak oluştur. Dark tema (#070B14 arka plan), amber (#F59E0B) aksanlar. Responsive, animasyonlu, single-page."
   - Kimi'nin ürettiği kodu al, aşağıdaki design tokens'a uyarla

2. **Nano Banana (Google Gemini)** — Görsel üretimi
   - Gemini uygulaması → 🍌Create images
   - Her bölüm için aşağıdaki prompt'ları kullan
   - Üretilen görselleri WebP formatına çevir, responsive srcset hazırla

3. **kie.ai** — Renk şablonları ve API referansı
   - Renk harmonisi kontrolü için
   - Gerekirse ek API entegrasyonları için

### Kesin Tasarım Kuralları

```
TEMA: Koyu (dark) + amber aksanlar
ARKA PLAN: #070B14 (ana), #0C1220 (ikincil), #0F172A (kart)
PRIMARY: #F59E0B (amber 500), hover: #FBBF24 (amber 400)
TEXT: #E2E8F0 (ana), #94A3B8 (muted), #475569 (dim)
BORDER: rgba(255,255,255,0.06)
HEADING FONT: Outfit — ağırlıklar: 700, 600, 500
BODY FONT: DM Sans — ağırlıklar: 400, 500
RADIUS: 10px (genel), 16px (kartlar)
ANİMASYON: Sade. Gradient mesh arka plan, scroll reveal, hover lift, sayaç.
```

### İçerik Kuralları

- KISA, NET, ÖZ. Her cümle maksimum 15-20 kelime.
- Jargon yok. "n8n" kelimesini müşteriye gösterme, "otomasyon sistemi" de.
- İşletme sahibi dilinde konuş: "müşteri kaybetmek", "zaman israfı", "kâr artışı"
- Her bölümde tek CTA: "Ücretsiz Strateji Görüşmesi Al"
- Türkçe. TDK kurallarına uygun.

---

## Bölüm Bölüm Talimatlar

### BÖLÜM 1: Hero / Hook

```
Başlık: "İşletmeniz siz uyurken de müşteri kaybediyor mu?"
Alt metin: "Cevapsız mesajlar, geciken teklifler, unutulan takipler — bunların hepsini yapay zeka sizin yerinize halletsin. 7/24 çalışan bir sistem kuralım."
CTA: "Ücretsiz Strateji Görüşmesi" (tek buton, amber)
İkincil: "Nasıl Çalışır?" (outline buton)
İstatistikler: 150+ Otomasyon | 6 Yıl Deneyim | 7/24 AI Destek
Badge: "Yapay Zeka Destekli Çözümler" (animasyonlu dot)
Arka plan: Gradient mesh (amber + mavi blob'lar, blur:100px, opacity:0.25)
```

**Nano Banana hero görseli prompt'u:**
```
Dark abstract background with subtle amber and blue gradient glow. 
Floating geometric mesh lines in deep navy space. 
No text, no people. Cinematic lighting. 16:9 ratio. Ultra minimal.
Dominant colors: #070B14 background with #F59E0B and #1E40AF subtle glows.
```

### BÖLÜM 2: Acı Noktalar

```
Tag: "Tanıdık mı?"
Başlık: "Birçok işletme bu sorunlarla boğuşuyor"

Kart 1 (telefon ikonu):
  Başlık: "Müşteri mesajlarına geç dönüyor musunuz?"
  Metin: "Gece gelen bir mesaj, sabah unutuluyor. Rakibiniz 5 dakikada dönüş yaptığında siz fırsatı çoktan kaybettiniz."

Kart 2 (saat ikonu):
  Başlık: "Ekibiniz aynı işi tekrar tekrar mı yapıyor?"
  Metin: "Veri girişi, dosya kovalamacası, manuel bildirimler — her gün saatlerce vakit alan ama değer üretmeyen işler."

Kart 3 (para ikonu):
  Başlık: "Reklam harcamalarınız sonuç getirmiyor mu?"
  Metin: "Bütçe harcanıyor ama gelen müşteri adayları takip edilemiyor, dönüşüm oranları düşük kalıyor."
```

### BÖLÜM 3: Çözüm (3 Adım)

```
Tag: "Çözüm"
Başlık: "İşletmeniz için yapay zeka destekli bir sistem kuruyorum"
Alt: "Müşteri talepleriniz, randevularınız, teklifleriniz ve takip süreçleriniz artık insan eline bağlı değil."

Adım 01 — Analiz:
  "İşletmenizin süreçlerini inceliyorum. Nerede zaman kaybediyorsunuz, hangi işler otomatikleştirilebilir — hepsini belirliyorum."

Adım 02 — Sistem kurulumu:
  "Otomasyon, sesli AI agent ve gerekiyorsa reklam altyapısını kuruyorum. Her şey sizin iş akışınıza özel tasarlanıyor."

Adım 03 — Sonuç:
  "Sistem 7/24 çalışıyor. Müşterilerinize anında dönüş yapılıyor, teklifler otomatik hazırlanıyor — siz büyümeye odaklanıyorsunuz."
```

### BÖLÜM 4: Video (YENİ)

```
Tag: "Beni Tanıyın"
Başlık: "2 dakikada ne yaptığımı anlatıyorum"
YouTube embed: [YOUTUBE_VIDEO_ID] — responsive, 16:9, lazy loaded
Alt CTA kutusu (video'nun hemen altında):
  "Bu çözüm işletmenize uygun mu?" 
  Buton: "Hemen Randevu Al" → #randevu bölümüne anchor
Tasarım: Video containerın etrafında subtle amber glow border
```

### BÖLÜM 5: Sosyal Kanıt

```
Tag: "Sonuçlar"
Başlık: "Rakamlar kendini gösteriyor"

Rakam kutuları (4 adet):
  150+ | Otomasyon sistemi kuruldu
  6 Yıl | Google & Meta Ads deneyimi
  $7.000+ | Üst segment müşteri referansı
  7/24 | AI Agent ile kesintisiz hizmet

Müşteri yorumu 1 (otel):
  "Gece 2'de gelen misafir sorularına artık yapay zeka cevaplıyor. Tüm otel bilgilerimize hâkim, Türkçe ve İngilizce destek veriyor."
  — Otel Yöneticisi, Antalya

Müşteri yorumu 2 (sağlık):
  "Reklam kampanyalarımız artık sadece tıklama getirmiyor — gelen müşteri adayları otomatik olarak takip ediliyor."
  — İşletme Sahibi, Sağlık Sektörü
```

### BÖLÜM 6: Nasıl Çalışır (4 Adım)

```
Tag: "Süreç"
Başlık: "4 adımda işletmeniz dönüşmeye başlıyor"

1. Ücretsiz strateji görüşmesi — 30 dk online
2. İşletme analizi — detaylı rapor
3. Sistem kurulumu — 1-2 haftada devreye alma
4. Büyüme — izleme, optimizasyon, yeni fırsatlar
```

### BÖLÜM 7: SSS

```
6 soru-cevap (details/summary yapısı):
1. Ne kadar sürede sonuç alırım?
2. Hangi sektörlere hizmet veriyorsunuz?
3. Fiyatlarınız nedir?
4. Otomasyon tam olarak ne yapıyor?
5. Sesli AI agent nedir?
6. Reklam yönetimi de yapıyor musunuz?
```

### BÖLÜM 8: Randevu Formu

```
Tag: "Başlayalım"
Başlık: "İşletmenizi otomatikleştirmeye hazır mısınız?"
Alt: "30 dakikalık ücretsiz strateji görüşmesinde işletmenizi dinleyeyim."

Form alanları: Ad Soyad, Telefon, Email, Sektör (dropdown), Mesaj
Submit: "Ücretsiz Görüşme Talep Et"
Alt not: "Bilgileriniz gizli tutulur. Spam göndermiyorum."

Form submit → n8n webhook → Gmail bildirimi + WhatsApp onay
```

### SABİT ELEMENTLER

```
WhatsApp floating buton: Sağ alt, yeşil, hover'da tooltip
Sticky CTA bar: Scroll'da aşağıdan belirir
AI Agent widget: Sağ alt (WhatsApp'ın üstünde) — platform seçilince eklenecek
Nav: Logo (özgürözen) + tek buton (Ücretsiz Görüşme Al)
```

### BLOG SAYFASI (/blog)

```
Ayrı sayfa — funnel'dan bağımsız
Minimal tasarım, aynı dark+amber tema
Blog kartları: başlık, özet, tarih, kapak görseli
Her yazının sonunda CTA: "Bu konuda yardım mı istiyorsunuz?" → randevu
SEO meta etiketleri her yazıda ayrı ayrı
```

---

## Animasyon Kuralları

```
1. Hero: Gradient mesh arka plan (2-3 blob, blur, yavaş hareket)
2. Scroll: Aşağıdan yukarı reveal (0.6s, ease-out, threshold:0.12)
3. Stagger: Kartlar sırayla belirme (100ms delay aralıklarla)
4. Sayaç: Rakamlar scroll'da tetiklenen animasyonla artış
5. Hover: Kartlarda translateY(-4px) + border renk değişimi
6. prefers-reduced-motion: TÜM animasyonlarda zorunlu
7. Genel: AZ AMA ETKİLİ. Gereksiz animasyon ekleme.
```

---

## Kimi K2.5 Kullanım Talimatları

1. kimi.com'a git → Visual Coding modu seç
2. Referans görselleri/videoları yükle
3. Prompt: "Bu tasarımı pixel-perfect HTML/CSS/JS'e çevir. Dark tema (#070B14 bg, #F59E0B amber aksan). Outfit + DM Sans fontları. Responsive. Scroll animasyonlu. Tek sayfa funnel yapısı."
4. Üretilen kodu indir
5. Design tokens'a uyarla (renkleri CSS değişkenlerine çevir)
6. BEM class isimlendirmesine geçir
7. Semantik HTML uygula

---

## Nano Banana Görsel Üretim Prompt'ları

### Hero arka plan:
"Dark abstract background with subtle amber (#F59E0B) and deep blue (#1E40AF) gradient glow. Floating geometric mesh lines in deep navy (#070B14) space. No text, no people. Cinematic, minimal. 16:9."

### Hizmet ikonları:
"Minimalist flat icon of [CONCEPT] on dark background. Single amber (#F59E0B) color accent. Clean lines, no gradients. Square format 400x400."

### Blog kapak:
"Professional blog header image about [TOPIC]. Dark tech aesthetic. Subtle amber accents. No text. 16:9 ratio 800x450."

### Testimonial avatar:
"Professional headshot placeholder. Dark background, warm amber side light. Silhouette style. Square 200x200."
