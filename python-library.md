## Pandas
Pandas (Python for Data Analysis): untuk proses analisis data seperti manipulasi data, persiapan data, dan pembersihan data.

- **read_csv()**        : membaca file csv
- **str.match()**       : mencocokan dengan karakter tertentu
- **drop()**            : menghapus
- **count()**           : mengitung masing-masing variable
- **drop_duplicates()** : menghapus data duplicate rows
- **fillna()**          : mengisi dengan nilai tertentu
- **quantile()**        : melihat quantile ke tertentu
- **mask()**            : menganti nilai tertentu jika kondisi memenuhi
- **astype()**          : merubah tipe data
- **value_counts()**    : mengitung nilai unik dari kolom
- **sort_values(**)     : mengurutkan isi data
- **isnull()**          : mendeteksi missing values
- **dropna()**          : menghapus missing values
- **replace()**         : mengganti nilai

---
## Matplotlib
Matplotlib adalah library Python yang fokus pada visualisasi data.
- **figure()**          : membuat figure gambar baru
- **subplots()**        : membuat gambar dan satu set subplot
- **title()**           : memberi judul pada gambar
- **ylabel()**          : memberi label sumbu Y pada gambar
- **xlabel()**          : memberi label sumbu Y pada gambar
- **pie()**             : membuat pie chart
---
## Seaborn
Seaborn membuat visualisasi lebih indah dibanding matplotlib biasa
- **sns.boxplot**       : membuat boxplot
- **countplot()**       : membuat plot dengan jumlah pengamatan di setiap bin kategorik variable
- **heatmap()**         : Plot rectangular data as a color-encoded matrix
---
## Scikit-learn
untuk mempersiapkan data sebelum pemodelan
- **LabelEncoder()**          : merubah nilai dari suatu variable menjadi 0 atau 1
- **train_test_split()**      : membagi data menjadi 2 row bagian (Training & Testing)
- **LogisticRegression()**    : memanggil algoritma Logistic Regression
- **RandomForestClassifier()**: memanggil algoritma Random Forest Classifier
- **confusion_matrix()**      : membuat confusion matrix
- **classification_report()** : membuat classification report, yang diantaranya berisi akurasi model
---
## Xgboost
Algoritma extreme gradient boosting (xgboost)
- **XGBClassifier()**        : memanggil algoritma XG Boost Classifier
---
## kmodes
digunakan untuk melakukan permodelan menggunakan **algoritma K-Modes** dan **K-Prototypes**
- from kmodes.kmodes import KModes
- from kmodes.kprototypes import KPrototypes
---
## Pickle 
mengimplementasikan protokol biner untuk serializing dan de-serializing dari struktur objek Python
- dump()                     : untuk menyimpan model
