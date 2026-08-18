# Katkı Kuralları — EOAI Lab

## Branch İsimlendirme
- `feature/kisa-aciklama` → yeni özellik (örn. `feature/fintech-churn-model`)
- `fix/kisa-aciklama` → hata düzeltme
- `docs/kisa-aciklama` → dokümantasyon

`main` branch'ine **asla doğrudan commit atılmaz.**

## Akış
1. Kendi branch'ini `main`'den aç: `git checkout -b feature/isim`
2. Üzerinde çalış, küçük ve anlamlı commit'ler at
3. İşin bitince Pull Request (PR) aç
4. Lead Engineer (Riza) review yapmadan merge edilmez
5. Onay sonrası `main`'e merge edilir, branch silinir

## Commit Mesaj Formatı
```
[tip] kısa açıklama

örn: [feat] SHAP değerlerini pipeline'a ekle
     [fix] eksik veri işleme hatası düzeltildi
     [docs] README güncellendi
```

## PR Açarken
- Ne yaptığını 2-3 cümleyle açıkla
- Değişiklik büyükse ekran görüntüsü/örnek çıktı ekle
- Kendi kendine merge etme, review bekle

## Veri Güvenliği — ÇOK ÖNEMLİ
- Gerçek müşteri verisi **hiçbir zaman** repo'ya commit edilmez
- `.env`, API anahtarları, credential'lar asla commit edilmez
- Şüphen varsa commit atmadan önce sor

## Takıldığında
Slack'te #eo-churn-[musteri] kanalına yaz, 2 saat içinde cevap gelmezse Riza'ya doğrudan mesaj at.
