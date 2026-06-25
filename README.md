# BomeraKing

Reklamsız, web tabanlı **King** skor-tutma uygulaması (bomeraking.com). Tek bir `index.html` dosyası — tarayıcıda açınca çalışır, skorlar cihazda (localStorage) saklanır.

## Kullanım
`index.html` dosyasına çift tıkla (veya tarayıcıya sürükle). Telefonda da çalışır.

## Sistem (doğrulanmış)
- 4 oyuncu · tek 52'lik deste · kişi başı 13 kart
- **20 el** — her oyuncu 5 el sahibi: **3 ceza + 2 koz**
- 12 ceza eli (6 ceza × 2) + 8 koz eli (4 renk × 2)
- İlk el koz girilmez

### Puanlar
| Tür | Puan |
|-----|------|
| El almaz | −50 / el |
| Kupa | −30 / kupa |
| Kız (Q) | −100 |
| Erkek (J+K) | −60 |
| Son iki | −180 / el |
| Rıfkı (K♥) | −320 |
| Koz | +50 / el |

Cezalar toplamı **−5200**, kozlar toplamı **+5200** → oyun sonunda 4 oyuncunun toplamı her zaman **0**. Uygulama bunu otomatik kontrol eder.

## Sonraki adım
İstenirse PWA / native app haline getirilebilir.
