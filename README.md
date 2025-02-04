# **BloodBankSystem-Django**

## 📌 مقدمة

BloodBankSystem-Django هو نظام لإدارة بنوك الدم يهدف إلى تسهيل عمليات التبرع والطلبات بين المرضى والمتبرعين بطريقة آمنة وسهلة الاستخدام.

---

## 🛠️ متطلبات التشغيل

قبل تشغيل المشروع، تأكد من تثبيت المتطلبات التالية:

- Python 3.8 أو أحدث
- Django 3.2 أو أحدث
- قاعدة بيانات SQLite (مضمنة) أو أي قاعدة بيانات أخرى مثل PostgreSQL

---

## 🚀 طريقة تثبيت وتشغيل المشروع

### 1️⃣ **استنساخ المشروع**

```bash

cd BloodBankSystem-Django
```

### 2️⃣ **إنشاء بيئة افتراضية وتفعيلها**

```bash
python -m venv venv
# على نظام Windows
venv\Scripts\activate
# على نظام macOS/Linux
source venv/bin/activate
```

### 3️⃣ **تثبيت المتطلبات**

```bash
pip install -r requirements.txt
```

### 4️⃣ **تطبيق الترحيلات (Migrations) على قاعدة البيانات**

```bash
python manage.py migrate
```

### 5️⃣ **إنشاء مستخدم إداري**

```bash
python manage.py createsuperuser
```

ثم أدخل بيانات الحساب الإداري عند الطلب.

### 6️⃣ **تشغيل السيرفر المحلي**

```bash
python manage.py runserver
```

### 7️⃣ **الوصول إلى النظام**

افتح المتصفح وانتقل إلى:

```
http://127.0.0.1:8000/
```

للوصول إلى لوحة الإدارة:

```
http://127.0.0.1:8000/admin/
```

---

##

-
