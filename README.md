# Kyrgyz News Topic Classifier 📰🇰🇬

Этот проект представляет собой классификатор новостных заголовков на кыргызском языке по категориям с использованием модели BERT.

## 📚 Описание проекта

Мы спарсили данные с сайта [kabar.kg](https://www.kabar.kg/) и распределили заголовки по шести тематикам:

- `sport` — Спорт  
- `kyrsyk` — Происшествия  
- `duino` — Международные новости  
- `ukuktartibi` — Закон и порядок  
- `politika` — Политика  
- `madaniat` — Культура  

Каждому заголовку была присвоена метка, после чего данные были объединены и подготовлены для обучения модели.

---

## 🧠 Используемые технологии

- Python 🐍  
- Pandas  
- scikit-learn  
- PyTorch  
- HuggingFace Transformers  
- BERT (bert-base-uncased)

---

## 🚀 Как запустить проект

### 1. Установите зависимости

Создайте и активируйте виртуальное окружение (рекомендуется):

```bash
python -m venv venv
source venv/bin/activate       # для macOS/Linux
venv\Scripts\activate          # для Windows
pip install -r requirements.txt
