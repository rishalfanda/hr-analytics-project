# HR Analytics Project

## Deskripsi
Proyek ini menganalisis data HR untuk memprediksi apakah karyawan akan mencari pekerjaan baru (target = 1) atau tidak (target = 0). Menggunakan Python, pandas, scikit-learn untuk preprocessing, model Logistic Regression, dan evaluasi metrik seperti accuracy, precision, recall, F1-score, dan ROC AUC.

Dataset: aug_train.csv (training) dan aug_test.csv (testing).

## Instalasi
1. Clone repo: `git clone https://github.com/username/nama-repo.git`
2. Instal dependensi: `pip install -r requirements.txt`
3. Jalankan notebook: `jupyter notebook HR_Analytics_Project.ipynb`

## Struktur File
- `HR_Analytics_Project.ipynb`: Kode utama (import data, preprocessing, model training, evaluasi).
- `aug_train.csv`: Dataset training.
- `aug_test.csv`: Dataset testing.
- `requirements.txt`: Daftar library yang digunakan.

## Hasil Utama
- Accuracy pada test set: ~76%.
- ROC AUC: ~0.786.
- Confusion Matrix: [[3320 986] [393 1049]].

## Cara Menjalankan
Buka notebook dan jalankan sel-sel secara berurutan.

## Kontribusi
Fork repo ini dan submit pull request jika ada perbaikan.

## Lisensi
MIT License.
