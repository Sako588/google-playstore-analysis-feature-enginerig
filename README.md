# Google Play Store Apps - Exploratory Data Analysis & Feature Engineering

Bu layihə çərçivəsində **Google Play Store** tətbiqlərinin məlumat bazası (`dataset`) üzərində hərtərəfli məlumatların təmizlənməsi, xüsusiyyətlərin mühəndisliyi (Feature Engineering), kateqoriyalı dəyişənlərin kodlaşdırılması (Encoding) və kəşfiyyat xarakterli məlumat təhlili (EDA) aparılmışdır.

## 🚀 Layihənin Mərhələləri (Workflow)
1. **Məlumatların Təmizlənməsi (Data Cleaning):** 
   - Çatışmayan (missing/null) dəyərlərin aşkarlanması və tənzimlənməsi.
   - Ölçü (`Size`), qiymət (`Price`) və endirmə (`Installs`) sütunlarındakı simvolların (`M`, `k`, `$`, `,`) təmizlənməsi və rəqəmsal tipə (`numeric`) çevrilməsi.
   - Dublikat sətirlərin silinməsi.
2. **Feature Engineering və Encoding:**
   - Mövcud sütunlardan yeni xüsusiyyətlərin yaradılması (tarix sütunundan il, ay, gün çıxarılması və s.).
   - Maşın öyrənməsi modelləri üçün kateqoriyalı sütunların uyğun üsullarla (One-Hot / Label Encoding) kodlaşdırılması.
3. **Vizuallaşdırma və Analiz (EDA):**
   - Tətbiq kateqoriyalarına görə reytinq (`Rating`) və rəy (`Reviews`) paylanmaları.
   - Ödənişli və pulsuz tətbiqlərin qrafik müqayisəsi (KDE plot, Barplot, Korrelyasiya Heatmap).

## 🛠️ İstifadə Olunan Kitabxanalar
* **Pandas** & **NumPy** (Data manipulyasiyası və təmizləmə)
* **Matplotlib** & **Seaborn** (Qrafiklər və vizuallaşdırma)

## 📂 Layihə Strukturu
```text
├── data/               <- Təmizlənmiş və ya orijinal Play Store dataset faylı (.csv)
├── notebooks/          <- EDA, Feature Engineering və qrafiklərin qurulduğu Jupyter Notebook
└── README.md           <- Layihə təsviri
