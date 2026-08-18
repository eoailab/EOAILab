# EO-Churn — [Proje/Müşteri Adı]

## Proje Hakkında
EOAI Lab'in "Enterprise Owned AI" felsefesiyle geliştirilen, [müşteri adı] için özel churn tahmin modeli.

## Başarı Kriteri
- Hedef metrik: [örn. AUC ≥ 0.85]
- Teslim tarihi: [tarih]

## Ekip
| İsim | Rol | Sorumluluk |
|---|---|---|
| Riza | Lead Engineer / Founder | Review, mimari kararlar |
| Sude | ML Engineer | Model geliştirme |

## Kurulum
```bash
git clone [repo-url]
cd eo-churn-[musteri]
pip install -r requirements.txt --break-system-packages
```

## Proje Yapısı
```
├── data/               # Ham ve işlenmiş veri (gerçek müşteri verisi ASLA burada commit edilmez!)
├── notebooks/          # Keşif ve deneme notebook'ları
├── src/                # Üretim kodu (pipeline, model, API)
│   ├── features/
│   ├── model/
│   └── api/
├── tests/              # Test dosyaları
├── docs/               # Mimari kararlar, notlar
└── requirements.txt
```

## Git Workflow
Bkz. [CONTRIBUTING.md](./CONTRIBUTING.md)

## Durum
🟡 Geliştirme aşamasında
