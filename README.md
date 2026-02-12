🚀 SkillPay AI – Salary Prediction System

📌 Proje Amacı

SkillPay AI, AI ve Data rollerinde maaş tahminini sezgisel değil, veri odaklı şekilde gerçekleştirmek amacıyla geliştirilmiş uçtan uca bir makine öğrenmesi projesidir.

Bu proje, “Beklediğim maaş nedir?” sorusunu bir regresyon problemi olarak ele alır ve gerçek iş ilanı verileri üzerinden analitik bir model kurar.

📊 Kullanılan Veri Seti

Kaggle AI & Data Jobs Dataset

İçerik:

Job Title

Experience Level

Employment Type

Company Location

Remote Ratio

Salary (USD)

🔍 Uygulanan Adımlar

Veri yükleme ve temel inceleme (shape, info, describe)

Eksik veri analizi

Exploratory Data Analysis (EDA)

Maaş dağılımı ve aykırı değer analizi

Feature Engineering

Kategorik değişkenlerin encode edilmesi

Maaş dağılımındaki çarpıklık için log-transform uygulanması

Train-test split

Regresyon modelleme

Cross-validation

Model performans değerlendirme (MAE, RMSE, R²)

Residual analizi

🤖 Model Yaklaşımı

Maaş verisinin sağa çarpık dağılım göstermesi nedeniyle hedef değişkene log dönüşümü uygulanmıştır.
Regresyon tabanlı model, çapraz doğrulama ile test edilerek genellenebilirliği analiz edilmiştir.

🛠 Kullanılan Teknolojiler

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

🎯 Sonuç

SkillPay AI, maaş tahmini problemini veri bilimi perspektifinden ele alarak iş başvurularında daha gerçekçi ve analitik maaş beklentisi belirlenmesini amaçlamaktadır.


📌 Project Objective

SkillPay AI is an end-to-end machine learning project designed to predict salary ranges in AI and Data roles using real-world job listing data.

The project reframes the question “What salary should I expect?” as a supervised regression problem.

📊 Dataset

Kaggle AI & Data Jobs Dataset

Includes:

Job Title

Experience Level

Employment Type

Company Location

Remote Ratio

Salary (USD)

🔍 Project Workflow

Data loading and structural inspection (shape, info, describe)

Missing value analysis

Exploratory Data Analysis (EDA)

Salary distribution and outlier analysis

Feature engineering

Encoding categorical variables

Log transformation applied to target variable

Train-test split

Regression modeling

Cross-validation

Model evaluation (MAE, RMSE, R²)

Residual analysis

🤖 Modeling Approach

Due to the right-skewed salary distribution, log transformation was applied to stabilize variance and improve model performance.

The regression model was validated using cross-validation to ensure generalization capability.

🛠 Technologies Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

🎯 Outcome

SkillPay AI provides a data-driven approach to salary expectation modeling and demonstrates an end-to-end applied machine learning workflow.
