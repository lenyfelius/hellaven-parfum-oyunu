# Hellaven — 2D Parfüm Atölyesi

Bağımsız HTML/CSS/JavaScript Canvas oyunu. Paket yöneticisi, API anahtarı veya derleme gerekmez.

## Çalıştırma

```sh
python3 -m http.server 8000
```
Tarayıcıda http://localhost:8000 açın. index.html doğrudan tarayıcıda da açılabilir.

## Kontroller

- WASD / yön tuşları: hareket
- E: yakındaki istasyonu aç
- Esc: istasyonu kapat
- Dokunmatik yön tuşları ve istasyona dokunarak yürüme

## Mevcut oyun

Üç esans seçimi, müşteri siparişleri, üretim, satış, para, itibar ve hassas terazi geliştirmesi. Kare, yuvarlak, uzun ve oval şişeler; etiket renkleri ve parfüm isimleri. Şişe şekli üretimden sonra korunur. İlerleme oturum belleğindedir; sayfa yenilenince sıfırlanır.

## Dosyalar

- index.html: tüm oyun arayüzü, Canvas çizimleri ve oyun mantığı
- perfume.png: atölye görseli
- AGENTS.md: geliştirme bağlamı ve doğrulama rehberi

## Codex web'e aktarma

1. GitHub'da `hellaven-parfum-oyunu` adlı bir depo oluşturun (isterseniz private).
2. Bu klasörün dosyalarını çıkarın. GitHub'daki Add file → Upload files ile DOSYALARI yükleyin ve commit edin. ZIP dosyasını tek başına yüklemeyin.
3. Codex web'de GitHub hesabınızı bağlayın, bu depoya erişim verin ve ilgili cloud environment/depo seçimini yapın.
4. İlk görev: “Bu depodaki Hellaven 2D parfüm oyununu incele. AGENTS.md dosyasını oku, oyunu çalıştır ve mevcut işlevleri koruyarak geliştirmeye hazırlan.”

Bu paket son yayınlanan oyunun kaynak kopyasıdır. Codex'teki değişiklikler mevcut Sites bağlantısını kendiliğinden güncellemez.
