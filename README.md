# Stock Price Prediction with PyTorch (LSTM vs GRU)

AMZN hisse verisi üzerinde, PyTorch ile LSTM ve GRU modelleri kullanarak zaman serisi
fiyat tahmini yapan bir öğrenme projesi. 6 haftalık bir ML öğrenme planı kapsamında,
her adım ayrı bir commit olarak geliştirildi.

## Proje Amacı

- ML temellerini (regresyon, train/test split, MSE/RMSE) pratikte öğrenmek
- PyTorch'un temel iş akışını (tensor, nn.Module, training loop) kavramak
- Gerçek zaman serisi verisiyle (hisse fiyatları) çalışmak: normalizasyon, sliding window
- LSTM ve GRU mimarilerini uygulamak ve karşılaştırmak
- Sonuçları eleştirel biçimde değerlendirmek (naive baseline ile kıyaslama)

## Kurulum

```bash
git clone https://github.com/KULLANICI_ADIN/stock-price-prediction-pytorch.git
cd stock-price-prediction-pytorch
python -m venv .venv
.venv\Scripts\activate          # Windows
python -m pip install -r requirements.txt
jupyter notebook
```

## Proje Yapısı