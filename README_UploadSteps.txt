# 🧩 خطوات رفع مشروع TrendStormer كاملة (خطوتان أساسيتان)

---

## ✅ الخطوة 1: رفع المشروع إلى GitHub

1. اذهب إلى [https://github.com](https://github.com)
2. أنشئ Repo جديد باسم: `trendstormer-ai`
3. فك الضغط عن `TrendStormer_Deploy_Complete.zip` على جهازك
4. اضغط `Upload files` ثم اسحب الملفات التالية:
   - `app_home.py`
   - `youtube_upload.py`
   - `logo.png`
   - `requirements.txt`
   - `.env.template`
   - `README.txt`
   - مجلد `pages/` (يجب أن يكون بداخله الصفحات الأربعة)
5. اضغط `Commit changes ✅`

---

## ✅ الخطوة 2: تشغيل المشروع على Streamlit Cloud

1. ادخل إلى: [https://share.streamlit.io](https://share.streamlit.io)
2. اضغط: `New App`
3. اختر المستودع `trendstormer-ai`
4. اضبط الخيارات التالية:
   - Branch = `main`
   - Main file = `app_home.py`
5. اضغط `Deploy`

---

## ⚠️ ملاحظات مهمة:

- لا تنس رفع ملف المصادقة الخاص بـ Google YouTube API:
```
client_secret_119912160971-9iv0g44tc99o8uuk4nhcdjhujjvm6bmk.apps.googleusercontent.com.json
```
- يجب أن يكون بجانب `app_home.py` داخل نفس الريبو
