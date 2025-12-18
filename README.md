# f2fui – Frontend Client for f2f

> **Status:** 🟡 Draft  
> **Last Updated:** 2025-12-14  
> **Contributor-friendly:** ✅

---

## هدف پروژه
`f2fui` یک **Single Page Application (SPA)** است که با **Vue.js و Bootstrap** ساخته شده و وظیفه اتصال به **REST APIهای f2f backend** را دارد.  
وظایف اصلی:
- نمایش فروشگاه اینترنتی (Front Store)
- خرید محصول (Buy Product)
- مقایسه محصولات (Compare Product)
- اعلان‌ها (Notifications)
- ارسال ایمیل به مشتری (Email notifications)

---

## تصاویر پروژه
![alt text](f2f_ui_1.png?raw=true)
![alt text](f2f_ui_2.png?raw=true)
![alt text](f2f_ui_3.png?raw=true)
![alt text](f2f_ui_4.png?raw=true)

---

## نصب و راه‌اندازی

### پیش‌نیازها
- Node.js و npm
- اتصال به backend `f2f`

### نصب وابستگی‌ها
```bash
npm install


## اجرای پروژه در محیط توسعه
`npm run serve`

## کامپایل برای محیط Production
`npm run build`

## اجرای تست‌ها
`npm run test`

## بررسی و اصلاح کد
`npm run lint`


مشکلات رایج

خطای vue-cli-service: command not found
راه حل: حذف پوشه node_modules و اجرای مجدد npm install

`rm -rf node_modules
npm install`

