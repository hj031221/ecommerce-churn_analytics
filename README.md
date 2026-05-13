## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/hj031221/ecommerce-churn_analytics.git
cd ecommerce-churn-analytics
```

### 2. Create and activate virtual environment
```bash
python -m venv .venv

# Windows
.venv\Scripts\activate

# Mac/Linux
source .venv/bin/activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Add dataset
- Kaggle에서 데이터 다운로드
- 링크: https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction
- 다운로드 후 `data/` 폴더에 넣기

### 5. Create output directories
```bash
mkdir outputs\figures
mkdir outputs\models
mkdir outputs\reports
```

### 6. Run notebooks in order
```
01_EDA.ipynb
02_preprocessing.ipynb
03_modeling.ipynb
04_xai.ipynb
05_survival.ipynb
06_rfm.ipynb
```