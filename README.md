# Yapay Zekâ Egzersizleri

Yapay zekâ dersi için iki şıklı alıştırma testleri.

**Tüm egzersizler:** https://damlasslan.github.io/AI_exercise/

| Konu | Soru | Doğrudan link | Soru dosyası |
|---|---|---|---|
| Yapay Zekâ Temel Kavramlar | 60 | https://damlasslan.github.io/AI_exercise/?konu=temel | `sorular.csv` |
| YZ ve İnsan-Makine Etkileşimi | 55 | https://damlasslan.github.io/AI_exercise/?konu=hci | `sorular-hci.csv` |

## Nasıl kullanılır
- Her soruda iki şık var: biri doğru, biri yanlış. Doğru olanı seç.
- Doğru seçersen **"Doğru!"** uyarısı çıkar.
- Yanlış seçersen yanlış şıkkın **neden yanlış olduğu** açıklanır ve doğru cevap yeşille gösterilir. İstersen **"Bu soruyu tekrar dene"** ile hemen yeniden deneyebilirsin; denemezsen soru birkaç soru sonra kendiliğinden tekrar gelir.
- Sonunda ilk denemede kaç soruyu doğru bildiğin gösterilir.
- Her konunun ilerlemesi tarayıcıda ayrı saklanır; sayfayı kapatıp açınca kaldığın yerden devam edersin.
- Klavye: `A` / `B` şık seç · `Enter` sonraki soru · `R` tekrar dene

## Soru eklemek / düzenlemek
İlgili konunun CSV dosyasını düzenleyin. Her satırda 4 sütun var:

`soru, dogru_cevap, yanlis_cevap, neden_yanlis`

Her alanı çift tırnak içinde yazın.

## Yeni konu eklemek
1. Aynı sütunlarla yeni bir CSV dosyası ekleyin.
2. `index.html` içindeki `TOPICS` listesine bir satır ekleyin.
