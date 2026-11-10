# Kaynak ve Yardım Beyanı

**Ders:** YZM411 Bilgisayarlı Görü — Ödev 1: Renk, Aydınlatma ve Örnekleme
**Öğrenci:** Umut Barbaros BABAHAN — 230212065
**Tarih:** 10.11.2026

## 1. Veri

- `normal.jpg`, `golge.jpg` ve `lamba.jpg` fotoğraflarının üçü de kendi çekimimdir (Samsung S20 FE, Pro mod, ISO 200, 1/30 s, F1.8, beyaz dengesi 5000 K kilitli).
- Fotoğraflarda başka bir kaynaktan alınmış görüntü veya veri kümesi kullanılmamıştır.

## 2. Kullanılan yazılım ve kütüphaneler

| Kütüphane | Sürüm | Kullanım amacı |
|---|---|---|
| Python | 3.13.18 | Çalışma ortamı |
| OpenCV (`cv2`) | 5.0.0 | Görüntü okuma, renk uzayı dönüşümü (BGR→RGB, BGR→HSV), `inRange` ile maske, `resize` ile küçültme/büyütme |
| NumPy | 2.4.6 | Dizi işlemleri, yüzdelik, parlaklık ve gama dönüşümleri |
| Matplotlib | 3.10.0 | Şekiller, ızgaralı koordinat görüntüleri, histogramlar |
| pandas | 2.2.3 | Ölçüm tabloları ve CSV çıktıları |
| Google Colab | — | Defterin çalıştırıldığı ortam |

## 3. Başvurulan belgeler

- OpenCV belgeleri: renk dönüşümleri (`cvtColor`, OpenCV 8 bit HSV ölçeği: H 0–179, S ve V 0–255), `inRange`, `resize` ve enterpolasyon bayrakları (`INTER_NEAREST`, `INTER_AREA`, `INTER_CUBIC`).
- NumPy belgeleri: dizi indeksleme (`img[y, x, kanal]`), `percentile`, `clip`.
- YZM411 ders notları ve ödev yönergesi.

## 4. Yapay zekâ araçlarının kullanımı

- **Rapor:** Ödev raporunun taslağı, defterin kodu ve çıktıları üzerinden Claude (Anthropic) ile hazırlanmıştır. Taslaktaki tüm sayılar defterin kendi çıktılarından alınmıştır. Taslak tarafımdan okunmuş, gözden geçirilmiş ve düzenlenmiştir.
- **README.md ve bu beyan dosyası:** Claude (Anthropic) ile hazırlanmış, tarafımdan kontrol edilmiştir.
- **Defter (kod):** Defterin kodu; kendi çalışmam, Stack Overflow'daki yanıtlar ve Claude (Anthropic) yapay zekâ asistanının katkısıyla birlikte geliştirilmiştir. Deney düzeni, fotoğraflar, koordinat ve parametre seçimleri, tahminler ve sonuçların yorumu bana aittir. Stack Overflow'dan ve Claude'dan alınan kod parçaları tarafımdan bu ödevin deney düzenine uyarlanmış, çalıştırılarak sınanmış ve doğrulanmıştır.
  - Yararlanılan Stack Overflow yanıtları: https://stackoverflow.com/questions/51229126/how-to-find-the-red-color-regions-using-opencv/51230291#51230291
- **Tahminler (Bölüm 0.2):** Deneyler çalıştırılmadan önce tarafımdan yazılmıştır ve sonuçlar görüldükten sonra değiştirilmemiştir.

## 5. Beyan

Bu ödevdeki fotoğrafların, deney tasarımının, tahminlerin ve sonuçların yorumunun bana ait olduğunu; yukarıda belirttiğim dışında herhangi bir kaynaktan veya kişiden yardım almadığımı beyan ederim.

**Ad Soyad:** Umut Barbaros BABAHAN
**Öğrenci No:** 230212065
