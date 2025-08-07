# 🩺 Breast Cancer Classification with Logistic Regression

Bu proje, göğüs kanseri verilerini kullanarak **Logistic Regression** algoritması ile sınıflandırma yapmayı amaçlamaktadır.  
Model, veri ön işleme adımlarından sonra eğitim ve test aşamalarını tamamlamış, yüksek doğruluk oranı elde etmiştir.

---

## 📊 Kullanılan Teknolojiler
- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- Matplotlib & Seaborn
- Jupyter Notebook

---

## 🔍 Model ve Yöntem
1. Veri seti yüklendi ve ön işleme adımları uygulandı
2. Eksik veriler ve aykırı değerler kontrol edildi
3. Özellikler ölçeklendirildi (**StandardScaler**)
4. **Logistic Regression** ile model kuruldu
5. Model doğruluğu ve diğer metrikler hesaplandı

---

## 📈 Sonuçlar
- **Doğruluk (Accuracy):** %97
- **Confusion Matrix** görselleştirildi
- Model, test verisi üzerinde yüksek başarı sağladı

---

## 💻 Nasıl Çalıştırılır
Aşağıdaki adımları terminalde çalıştırın:

```bash
git clone https://github.com/berkekarakanli/breast-cancer-ml.git
pip install -r requirements.txt
jupyter notebook breast-cancer-classification-with-logistic-regress.ipynb
