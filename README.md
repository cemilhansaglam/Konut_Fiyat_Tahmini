# 🏡 Konut Fiyatlarının Tahmini 📊  

Bu proje, **California Housing Prices** veri seti kullanılarak **konut fiyatlarını tahmin etmek** amacıyla geliştirilmiştir.  
Farklı **makine öğrenmesi modelleri** eğitilmiş ve karşılaştırılmıştır.  

## 📌 Proje İçeriği  
✔ **Veri Ön İşleme:** Eksik verilerin doldurulması, kategorik verilerin sayısallaştırılması  
✔ **Öznitelik Mühendisliği:** Yeni değişkenlerin eklenmesi (hane başına gelir, kişi başına oda sayısı vb.)  
✔ **Ölçekleme:** `StandardScaler` ile verilerin normalleştirilmesi  
✔ **Model Eğitimi:**  
   - **Lineer Regresyon**  
   - **Random Forest**  
   - **XGBoost** (En iyi sonuç veren model)  
✔ **Model Performansı:** RMSE ve R² metrikleri ile modellerin karşılaştırılması  

## 🚀 Kullanılan Teknolojiler  
🔹 **Python**  
🔹 **PySpark**  
🔹 **XGBoost**  
🔹 **Scikit-learn**  
🔹 **Pandas & NumPy**  

## 📊 En İyi Modelin Performansı  
✅ **Model:** XGBoost  
✅ **RMSE:** ~46,296  
✅ **R²:** ~0.845  
 
