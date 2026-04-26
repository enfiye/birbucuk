# birbuçuk

Politik ekoloji, çevre adaleti ve disiplinlerarası buluşmalar üzerine bir kolektif platform. ~2016'dan bu yana İstanbul'da sanatçıları, akademisyenleri ve aktivistleri bir araya getiriyor.

**https://enfiye.github.io/birbucuk/**

---

## Programlar

### Solunum (2017–2019)
Studio-X İstanbul'da gerçekleştirilen kapalı yuvarlak masa toplantıları. Dokuz buluşma: Su, Biyoçeşitlilik, Metabolizma, Sınırlar, İklim, Maden, Toplumsal Cinsiyet, Enerji, Toprak. Ayrıca Açık Radyo röportajı (Mart 2018).

### Sindirim (2019)
16. İstanbul Bienali "Yedinci Kıta" teması altında WORLBMON'da (MSGSÜ İstanbul Resim ve Heykel Müzesi) gerçekleştirilen kamusal buluşmalar. Beş nesne: Su, Benzin, Patates, Beton, İşlemci.

---

## Arşiv Yapısı

```
site/
  index.html          — Dil seçim sayfası (TR/EN/DE/FR/ES/IT/PT)
  style.css           — Ortak stil dosyası
  tr/                 — Türkçe (kaynak / otorite)
  en/                 — İngilizce çeviriler
  de/                 — Almanca çeviriler
  fr/                 — Fransızca çeviriler
  es/                 — İspanyolca çeviriler
  it/                 — İtalyanca çeviriler
  pt/                 — Portekizce çeviriler
  [lang]/pdf/         — PDF'ler (105 toplam: 15 × 7 dil)
```

Her dilde 15 belge: 9 Solunum toplantısı + 5 Sindirim Kamusal toplantısı + 1 Radyo röportajı.

**Türkçe PDF'ler kaynak metinlerdir.** Tüm çeviriler Türkçe'den yapılmıştır.

---

## PDF Üretimi

PDF'ler `make_pdf.py` ile ReportLab Platypus kullanılarak üretilmiştir. İsviçre tipografisi, Lato ailesi fontlar, #CC0000 kırmızı aksanı.

```python
make_pdf(output_path, lang_code, program_label, topic, date_str, body_text, is_radio=False)
```

Üretim scriptleri: `/tmp/gen_[konu]_[dil].py`

---

## Kurucu Ekip

- **Ayşe Ceren Sarı** — iklim ekonomisti, performans sanatçısı
- **Serkan Kaptan** — sistem mühendisi, çevre bilimci, dijital sanatçı
- **Yasemin Ülgen** — küratör, yazar
