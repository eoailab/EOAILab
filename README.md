# EO-Churn

## Proje Hakkında
EOAI Lab'in "Enterprise Owned AI" felsefesiyle geliştirilen özel churn tahmin modeli.

## Başarı Kriteri
- Hedef metrik: Recall > 86.5
- Teslim tarihi: ______

## Ekip
| İsim | Rol | Sorumluluk |
|---|---|---|
| Riza | Lead Engineer / Founder | Review, mimari kararlar |

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
