# CLAUDE.md — Özgür Özen Web Sitesi Projesi

## Proje Özeti

Özgür Özen'in kişisel marka web sitesi: **ozgurozen.com** — funnel mantığında, otomasyon + sesli AI agent odaklı, dönüşüm hedefli tek sayfalık site + SEO blog. Hostinger'da barınıyor.

---

## Marka Kimliği

- **İsim**: Özgür Özen (kişisel marka — QLTYdigital değil)
- **Domain**: ozgurozen.com
- **Hosting**: Hostinger (LiteSpeed + NVMe SSD)
- **Pozisyon**: Yapay zeka destekli iş süreçleri uzmanı
- **Hedef kitle**: Orta ve üst düzey işletme sahipleri/yöneticiler — yatırım yapabilecek, gerçek anlamda büyümek isteyen işletmeler
- **Hedef DEĞİL**: "Önce kazanalım sonra öderim" mantığındaki işletmeler

---

## Hizmet Hiyerarşisi

| Öncelik | Hizmet | Detay |
|---------|--------|-------|
| ANA | n8n Otomasyon + Sesli AI Agent | Temel funnel odağı, müşterinin ilk gördüğü |
| İKİNCİL | Google Ads + Meta Ads yönetimi | 6 yıl deneyim, sağlık sektörü yurt içi/dışı |
| İKİNCİL | SEO uyumlu web sitesi geliştirme | Ekip arkadaşıyla birlikte |
| DESTEK | Sosyal medya yönetimi | Ekip arkadaşıyla birlikte |
| DESTEK | UGC video üretimi | Ayrı sayfa/hizmet, funnel'ı kirletmemeli |

---

## Tasarım Kararları

- **Tema**: Koyu (dark) + amber aksanlar
- **Karakter**: "Güvenilir uzman" hissi
- **Renkler**:
  - Background: #070B14
  - Background secondary: #0C1220, #111827
  - Card: #0F172A
  - Primary (amber): #F59E0B
  - Amber scale: #FBBF24 → #D97706 → #B45309
  - Text: #E2E8F0
  - Text muted: #94A3B8
  - Border: rgba(255,255,255,0.06)
- **Fontlar**: 
  - Heading: Outfit (700, 600, 500)
  - Body: DM Sans (400, 500)
- **Animasyonlar**: Sade, az ama etkili — gradient mesh arka plan, scroll reveal, hover yükselme, sayaç animasyonu
- **Genel ilke**: Kısa, net, öz. İşletme sahibi 5 saniyede ne yaptığımı anlamalı.

---

## Funnel Yapısı (7+1 Bölüm)

1. **Hero/Hook**: "İşletmeniz siz uyurken de müşteri kaybediyor mu?" + tek CTA + istatistikler
2. **Acı noktalar**: 3 kart (geç dönüş, tekrar eden işler, reklam israfı)
3. **Çözüm**: 3 adım (analiz → kurulum → sonuç)
4. **Video bölümü**: YouTube embed + hemen altında randevu CTA'sı
5. **Sosyal kanıt**: Rakamlar + otel/sağlık referansları + müşteri yorumları
6. **Nasıl çalışır**: 4 adım (görüşme → analiz → kurulum → büyüme)
7. **SSS**: 6 soru (itiraz kırıcı)
8. **Randevu formu**: İsim, telefon, email, sektör, mesaj → n8n webhook

**Sabit elementler**: WhatsApp floating buton, sticky CTA bar, AI agent widget (platform seçilince)

---

## SEO Blog Stratejisi

- **/blog** sayfası eklenecek (ayrı sayfa, funnel'ı kirletmez)
- Blog otomasyonu: n8n → AI içerik üret → Nano Banana görsel → onay → yayınla
- Hedef: Haftada 2-3 yazı, SEO trafik çekme
- Konular: n8n otomasyon, AI agent, Google Ads ipuçları, sektörel case study'ler
- Blog'dan funnel'a yönlendirme: her yazının sonunda CTA

---

## Teknik Altyapı

| Araç | Kullanım |
|------|----------|
| Hostinger | Hosting + domain + SSL |
| n8n | Form webhook, blog otomasyonu, lead takip |
| Kimi K2.5 | Visual coding (referans siteden frontend üretme) |
| Nano Banana | AI görsel üretimi (hero, arka plan, avatar) |
| kie.ai | Renk şablonları, API gateway |
| Vapi veya ElevenLabs | Sesli AI agent (henüz seçilmedi) |
| Supabase | Lead veritabanı, blog draft depolama |
| Apify | Lead scraping (gelecek faz) |
| Calendly / özel form | Randevu sistemi |
| Google Search Console | SEO takip |

---

## Mevcut Sosyal Kanıtlar

- 150+ otomasyon sistemi kuruldu
- 6 yıl Google/Meta Ads deneyimi
- $7.000+ ürün segmentinde çalışılan marka var
- Otel sektörü: AI agent ile 7/24 müşteri karşılama sistemi kuruldu
- Sağlık sektörü: yurt içi + yurt dışı reklam yönetimi deneyimi
- Otellere sesli agent hizmeti sunuluyor

---

## Önemli Kurallar

1. Site SADE olmalı — kısa, net, öz. Kafa karıştırmamalı.
2. Tek CTA: "Ücretsiz strateji görüşmesi al" — her bölümde tekrar.
3. Otomasyon + AI agent ön planda, diğer hizmetler arka planda.
4. İşletme sahipleri otomasyonu bilmiyor — onların dilinde konuş.
5. Funnel tek sayfa, blog ayrı sayfa.
6. Video bölümü: YouTube embed + altında randevu CTA.
7. Marka: özgürözen, QLTYdigital kullanılmayacak.
8. Görseller: Nano Banana ile üretilecek, koyu tema + amber uyumlu.
9. WhatsApp otomasyonu: CTA'dan WhatsApp'a yönlendirme + n8n ile otomatik karşılama.
10. Randevu: form submit → Gmail'e düşmeli + WhatsApp onay.

---

## Gelecek Fazlar (şimdi yapılmayacak)

- [ ] Blog sayfası + otomasyon altyapısı
- [ ] Lead scraping sistemi (Apify + Supabase)
- [ ] Dashboard (içerik yönetimi, lead takip)
- [ ] Sesli AI agent entegrasyonu
- [ ] Müşteri sitesi üretim pipeline'ı (skill'lerle)
