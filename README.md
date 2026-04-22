# تحلیل احساس کاربران با استفاده از یادگیری عمیق


این پروژه یک سیستم طبقه‌بندی نظرات کاربران است که با استفاده از یادگیری عمیق و کتابخانه PyTorch پیاده‌سازی شده است. هدف این پروژه تحلیل مثبت یا منفی بودن نظرات کاربران در مورد غذا است.

### مراحل انجام پروژه:
- فایل‌های اصلی دیتاست شامل `train.csv` و `test.csv` هستند.
- در فایل `dataset.ipynb`، ابتدا داده‌ها از زبان فارسی به انگلیسی ترجمه شده‌اند.
- سپس با استفاده از Google Gemini، داده‌ها به صورت خودکار برچسب‌گذاری (لیبل‌گذاری) مثبت یا منفی شده‌اند.
- در فایل `snappfood.ipynb`، مدل یادگیری عمیق برای طبقه‌بندی احساسات کاربران نسبت به غذا آموزش داده شده است.
- در فایل `model.ipynb`، مدل نهایی بارگذاری شده و ارزیابی نهایی انجام گرفته است.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]
(https://colab.research.google.com/github/mahbodabazari/comment_sentiment/blob/main/snappfood.ipynb)

---

# Sentiment Analysis of User Reviews Using Deep Learning


This project is a user review classification system implemented using deep learning with PyTorch. The goal is to analyze whether users' opinions about food are positive or negative.

### Project Workflow:
- The core dataset files are `train.csv` and `test.csv`.
- In `dataset.ipynb`, reviews are first translated from Persian to English.
- Then, the reviews are automatically labeled as positive or negative using Google Gemini.
- In `snappfood.ipynb`, a deep learning model is trained to classify the sentiment of food-related reviews.
- Finally, in `model.ipynb`, the trained model is loaded and evaluated.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]
(https://colab.research.google.com/github/mahbodabazari/comment_sentiment/blob/main/snappfood.ipynb)

