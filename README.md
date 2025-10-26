# sing-box-cmd

# 💻 آموزش اجرای Sing-box در ویندوز

در این بخش، نحوه‌ی اجرای **Sing-box** در سیستم‌عاملرای Sing-boxرا مرحله‌به‌مرحله توضیح می‌دهیم.

---

## 📦 آماده‌سازی اولیه

1. فایل فشرده‌ی (`.zip`) مربوط بهز** را مرحله‌برا دانلود کنید.  
2. آن را در مسیرز

در این بخشاستخراج (Extract) کنید.  
3. پس از استخراج، فایل نحوه‌ی را حذف کنید تا پوشه‌ی-box در وینروی دسکتاپ باقی بماند.

---

## 🧭 ورود به پوشه‌ی Sing-box

1. در نوار جستجوی ویندوز، عبارتویندوز** را مریا💻 آموزش اجرای Sرا جستجو کنید.  
2. روی آن راست‌کلیک کرده و گزینه‌یوه‌ی اجرای **Sing-box** دررا انتخاب کنید.  
3. سپس دستور زیر را وارد کرده ونحوه‌ی اجرابزنید تا وارد پوشه شوید:

```powershell
cd .\Desktop\singbox
# 🟢 کانفیگ اول — IranRamona (کانال تلگرام / همراه / ایرانسل)
.\sing-box.exe run -c "IranRamonaکانال تلگرام-همراه-ایرانسل.json"

# 🟡 کانفیگ دوم — ssh-iranramona
.\sing-box.exe run -c "ssh-iranramona.json"

# 🔵 کانفیگ سوم — ssh-wearestand
.\sing-box.exe run -c "ssh-wearestand.json"

# 🟣 کانفیگ چهارم — wearestand-cdn
.\sing-box.exe run -c "wearestand-cdn.json"

# 🔴 کانفیگ پنجم — iranramona (جاویدنامان)
.\sing-box.exe run -c "iranramona.json"
