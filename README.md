# flash-card-german
EN:  Interactive German–Turkish vocabulary quiz built with Jupyter &amp; ipywidgets. Learn by clicking your way through flashcards.  TR:  Jupyter ve ipywidgets ile yapılmış interaktif Almanca–Türkçe kelime quizi. Butonlara tıklayarak kelime öğren.

# 🇩🇪 Flash Card German

Jupyter ve `ipywidgets` ile yapılmış interaktif **Almanca–Türkçe kelime quizi**. Butonlara tıklayarak kelime öğren, sonunda doğru/yanlış raporunu al.

## ✨ Özellikler

- 4 şıklı çoktan seçmeli kelime kartları
- Anlık doğru/yanlış geri bildirimi (renkli butonlar)
- Oyun sonu raporu: başarı yüzdesi + yanlış bildiğin kelimeler
- Sonuçlar CSV olarak kaydedilir (`dogrular.csv`, `yanlislar.csv`)
- Kendi kelime listeni `flash.csv`'ye ekleyerek genişletebilirsin

## 📦 Kurulum

```bash
pip install pandas ipywidgets notebook
```

## 🚀 Kullanım

1. Repoyu klonla:
```bash
   git clone https://github.com/KULLANICI_ADIN/flash-card-german.git
   cd flash-card-german
```
2. Jupyter Notebook'u aç:
```bash
   jupyter notebook main.ipynb
```
3. Hücreleri sırayla çalıştır (`Shift + Enter`).
4. Oyun başlar — şıklardan birine tıkla, "Sonraki →" ile devam et.
5. Oyun bitince "📊 Raporu Göster" butonuna bas.

## 📝 Kelime Listesi (`flash.csv`)

Kendi kelimelerini eklemek için CSV dosyasını düzenle:

```csv
Almanca,Türkçe
Hallo,Merhaba
Tschüss,Hoşça kal
...
```

## 🛠️ Kullanılan Teknolojiler

- Python 3
- Jupyter Notebook
- `pandas` — CSV okuma/yazma
- `ipywidgets` — interaktif butonlar ve arayüz

## 📄 Lisans

MIT

---

**Viel Erfolg beim Deutschlernen!** 🎯
