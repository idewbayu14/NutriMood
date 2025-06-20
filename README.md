# NutriMood - Model Rekomendasi Makanan Berdasarkan Mood
NutriMood adalah sistem rekomendasi makanan cerdas yang menggunakan machine learning untuk memberikan saran makanan berdasarkan mood atau suasana hati pengguna. Proyek ini merupakan bagian dari capstone project yang bertujuan untuk membantu pengguna menemukan makanan yang tepat sesuai dengan kondisi emosional mereka.

📋 Deskripsi Proyek
NutriMood menganalisis hubungan antara nutrisi makanan dan dampaknya terhadap mood manusia. Dengan menggunakan deep learning, sistem ini dapat memprediksi dan merekomendasikan makanan yang dapat meningkatkan atau menjaga suasana hati pengguna.

🎬 Demo Video
![Demo Sistem Rekomendasi Makanan](assets/demo-aplikasi.gif)

✨ Fitur Utama
* 🎯 Prediksi mood berdasarkan kandungan nutrisi makanan
* 🍕 Rekomendasi makanan personal berdasarkan mood target
* 📊 Analisis nutrisi komprehensif
* 🇮🇩 Database makanan Indonesia yang lengkap
* 🤖 Model machine learning dengan akurasi tinggi (97,29%)

🚀 Performa Model
📈 Training Results
* Test Accuracy: 97.29%
* Test Loss: 0.1741
* Training Time: 19ms/step

📊 Classification Report
![Demo Sistem Rekomendasi Makanan](assets/demo-aplikasi.gif)

📉 Model Performance
![Demo Sistem Rekomendasi Makanan](assets/demo-aplikasi.gif)

Model menunjukkan konvergensi yang baik dengan:
* Training accuracy mencapai ~91%
* Validation accuracy mencapai ~95%
* Loss function menurun secara konsisten
* Tidak terjadi overfitting yang signifikan

🗂️ Dataset
📊 Sumber Data

1. nutritionDataset.csv - Dataset nutrisi komprehensif dengan informasi kalori, protein, karbohidrat, lemak, dan vitamin
2. indonesiaFoodAndDrink.csv - Database makanan dan minuman khas Indonesia
3. Food Ingredients and Recipe Dataset - Dataset resep dan bahan makanan dengan mapping gambar

🔄 Data Processing

* Raw Data: Data mentah dari berbagai sumber
* Processed Data: Data yang telah dibersihkan, dinormalisasi, dan siap untuk training
* Combined Dataset: nutrimood_combined_dataset.csv - Dataset gabungan yang digunakan untuk training model

🛠️ Instalasi dan Setup
1️⃣ Clone Repository
```python
git clone https://github.com/username/nutrimood.git
cd nutrimood
```

2️⃣ Install Dependencies
```python
pip install -r requirements.txt
```

3️⃣ Struktur Dependencies
* Data Processing: pandas, numpy
* Machine Learning: scikit-learn, tensorflow, keras
* Visualization: matplotlib, seaborn
* Utilities: joblib, scipy, tqdm

🧠 Metodologi Machine Learning
🏗️ Arsitektur Model

* Model Type: Deep Neural Network
* Framework: TensorFlow/Keras
* Preprocessing: StandardScaler, OneHotEncoder
* Features: Nutritional content (calories, protein, carbs, fat, vitamins, minerals)
* Target: Mood categories (Energizing, Focusing, Neutral, Relaxing)

📝 Training Process

1. Data Preprocessing: Normalisasi dan encoding fitur
2. Feature Engineering: Ekstraksi fitur nutrisi yang relevan
3. Model Training: Training dengan neural network
4. Validation: Cross-validation dan hyperparameter tuning
5. Evaluation: Testing pada data yang tidak terlihat

📊 Analisis dan Insights
🔍 Key Findings

* Makanan tinggi protein cenderung meningkatkan fokus
* Karbohidrat kompleks membantu stabilisasi mood
* Makanan dengan magnesium tinggi memberikan efek relaksasi
* Vitamin B kompleks berkorelasi dengan peningkatan energi

🎨 Visualisasi

* Distribusi nutrisi per kategori mood
* Korelasi antara komponen nutrisi dan mood
* Performance metrics model
* Feature importance analysis
