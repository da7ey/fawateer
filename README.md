# New Soul Advertising — نظام إدارة الأعمال

![Logo](139051.png)

نظام إدارة أعمال متكامل لوكالات الدعاية والإعلان في مصر. يشتغل كملف HTML واحد على المتصفح — مفيش حاجة تتنصب ولا سيرفر يتشغل.

## 🌐 Live Demo

[https://YOUR_USERNAME.github.io/newsoul-advertising](https://YOUR_USERNAME.github.io/newsoul-advertising)

*(استبدل YOUR_USERNAME باسم حسابك على GitHub)*

---

## ✨ المميزات

| الميزة | الوصف |
|--------|-------|
| 🔐 **تسجيل الدخول** | باسورد محلي (افتراضي: `1234`) |
| 👥 **العملاء** | سجل عملاء كامل مع تفاصيل التواصل |
| 📁 **المشاريع والفواتير** | إدارة مشاريع + فواتير + دفعات تفصيلية |
| 💰 **عروض الأسعار** | تحويل تلقائي لمشروع لما العميل يوافق |
| 💸 **المصروفات** | تسجيل مصروفات + التزامات شهرية |
| 📊 **التقارير** | تحصيل عمري + كشف حساب + تدفق نقدي + أجندة |
| 🧾 **الفواتير** | تصميم احترافي مع QR Code + مشاركة واتساب |
| 📱 **موبايل** | Responsive — يشتغل على الجوال والتابلت |
| 💾 **التصدير/الاستيراد** | JSON backup كامل |
| ☁️ **النسخ الاحتياطي** | JSON + إيميل تلقائي |

---

## 🚀 الرفع على GitHub Pages

### الطريقة السريعة (بدون Git)

1. افتح [github.com](https://github.com) واعمل **New Repository**
2. سمّيه `newsoul-advertising` وخليه **Public**
3. في صفحة الـ Repo، اضغط **Uploading an existing file**
4. اسحب ملف `index.html` من المجلد ده → Commit
5. روح **Settings** → **Pages** → **Source**: `Deploy from a branch`
6. اختار **Branch**: `main` / **Folder**: `root` → **Save**
7. استنى دقيقتين → افتح الرابط اللي هيظهر

### الطريقة بـ Git

```bash
# 1. نزل الملف وفكّه
# 2. افتح Terminal/PowerShell في المجلد

git init
git add index.html
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/newsoul-advertising.git
git push -u origin main
```

بعدها:
- Repo → Settings → Pages → Source: `main` / `root` → Save
- الرابط هيبقى: `https://YOUR_USERNAME.github.io/newsoul-advertising`

---

## 🔐 تسجيل الدخول

- **الباسورد الافتراضي**: `1234`
- الباسورد بيتحفظ في `localStorage` — ممكن تغيّره من الكونسول

---

## 💾 النسخ الاحتياطي

### تصدير يدوي
- لوحة التحكم → زر **⬇️ تصدير** → يحفظ ملف JSON

### استيراد
- لوحة التحكم → زر **⬆️ استيراد** → اختار ملف JSON سابق

### نسخ احتياطي تلقائي
- كل يوم أحد: يحفظ ملف JSON + يفتح إيميل لـ `da7ey@yahoo.com`
- زر **☁️ نسخ احتياطي** يدوي في لوحة التحكم

---

## ⚠️ تنبيهات

| المشكلة | الحل |
|---------|------|
| البيانات ضاعت | استورد ملف JSON سابق |
| الباسورد نسيانه | امسح `ns_password` من LocalStorage (F12 → Application → Local Storage) |
| القائمة المنسدلة فاضية | امسح `ns_activities` من LocalStorage وأعد تحميل |
| الكتابة بطيئة | تأكد من تحميل آخر نسخة |

---

## 📱 الموبايل

التطبيق **Responsive**:
- الشريط الجانبي بيتحول لقائمة منبثقة
- الجداول قابلة للتمرير أفقياً
- الكروات بتترتب عمودياً

---

## 🖨️ الطباعة

كل الفواتير وعروض الأسعار وكشوف الحسابات بتطبع بشكل احترافي:
- 🎨 هيدر مع لوجو + QR Code
- 📋 شريط تواصل (عنوان + موبايل + أرضي + إيميل + فيسبوك)
- 📄 جدول منظم + إجماليات
- 📱 فوتر مع شكراً + سوشيال ميديا

> **تلميح:** استخدم **Save as PDF** في نافذة الطباعة.

---

## 📲 مشاركة واتساب

في نافذة الفاتورة:
1. اضغط زر **واتساب** (أخضر)
2. يفتح واتساب ويب برسالة جاهزة

---

## 🛠️ التقنيات المستخدمة

- HTML5 + CSS3 (Custom Properties, Grid, Flexbox)
- Vanilla JavaScript (مفيش Frameworks)
- Chart.js — للرسوم البيانية
- Font Awesome — للأيقونات
- Google Fonts (Tajawal) — للخط العربي
- localStorage — لتخزين البيانات محلياً

---

## 📄 الترخيص

MIT License — استخدمه حراً في مشاريعك التجارية.

---

## 📞 الدعم

- 📍 **العنوان:** 2 شارع الحصري، فيصل، الجيزة
- 📱 **موبايل:** 01090235208
- ☎️ **أرضي:** 0237835124
- 📧 **إيميل:** NewSoulAdv@proton.me
- 🌐 **فيسبوك:** /NewSoulAdv

---

<p align="center">
  <strong>Made with ❤️ in Egypt</strong>
</p>
