# مستندات بازوی بله - Bale Docs

به مستندات ماژولار و LLM-friendly بازوی بله خوش آمدید. این مستندات به صورت modular طراحی شده‌اند تا خوانایی و دسترسی به اطلاعات را برای انسان‌ها و مدل‌های زبانی بزرگ (LLM) آسان‌تر کنند.

## ساختار پروژه

```
bale-docs/
├── index.html              # صفحه اصلی
├── css/
│   └── style.css          # استایل‌های مشترک
├── js/
│   └── navigation.js      # اسکریپت‌های ناوبری
├── modules/
│   ├── main/              # مستندات اصلی بازو
│   │   ├── module-01-bot-creation.html
│   │   ├── module-02-making-requests.html
│   │   └── ...
│   └── miniapp/           # مستندات مینی‌اپ
│       ├── module-m1-introduction.html
│       └── ...
└── README.md              # این فایل
```

## فهرست مستندات

### مستندات اصلی بازو (Main Bot Docs)

#### مفاهیم پایه
- [ماژول ۱: ساخت بازو](modules/main/module-01-bot-creation.html)
- [ماژول ۲: ایجاد درخواست](modules/main/module-02-making-requests.html)
- [ماژول ۳: دریافت آپدیت‌ها](modules/main/module-03-getting-updates.html)
- [ماژول ۴: متد Update](modules/main/module-04-update.html)
- [ماژول ۵: متد getUpdates](modules/main/module-05-getupdates.html)

#### متدهای Webhook
- [ماژول ۶: setWebhook](modules/main/module-06-setwebhook.html)
- [ماژول ۷: deleteWebhook](modules/main/module-07-deletewebhook.html)
- [ماژول ۸: getWebhookInfo](modules/main/module-08-getwebhookinfo.html)

#### انواع داده‌ها (Types)
- User, Chat, Message و سایر انواع در ماژول‌های جداگانه

### مستندات مینی‌اپ (MiniApp Docs)

#### مقدمات
- [ماژول M1: مقدمه مینی‌اپ](modules/miniapp/module-m1-introduction.html)
- [ماژول M2: مثال‌ها](modules/miniapp/module-m2-examples.html)
- [ماژول M3: راهنمای طراحی](modules/miniapp/module-m3-design-guide.html)

#### پیاده‌سازی
- [ماژول M6: پیاده‌سازی](modules/miniapp/module-m6-implementation.html)
- [ماژول M7: شیء WebApp](modules/miniapp/module-m7-webapp.html)
- [ماژول M8: متدها](modules/miniapp/module-m8-methods.html)

## ویژگی‌های این مستندات

### LLM-Friendly
- ساختار معنایی و تمیز HTML
- محتوای modular و جدا شده
- بدون JavaScript سنگین
- متادیتای کامل برای هر ماژول

### Modular Design
- هر بخش یک فایل مستقل
- بارگذاری سریع‌تر
- نگهداری آسان‌تر
- قابلیت جستجوی بهتر

### فارسی
- تمام محتوا به زبان فارسی (همانند مستندات اصلی)
- پشتیبانی کامل از RTL

## نحوه استفاده

### مشاهده مستندات
فایل `index.html` را در مرورگر خود باز کنید یا پروژه را روی GitHub Pages deploy کنید.

### Deploy روی GitHub Pages
1. این repository را به GitHub push کنید
2. به Settings > Pages بروید
3. Branch را روی `main` و folder را روی `/ (root)` تنظیم کنید
4. منتظر بمانید تا سایت deploy شود

## وضعیت پروژه

برای مشاهده وضعیت تکمیل ماژول‌ها، فایل [ROADMAP.md](ROADMAP.md) را مطالعه کنید.

## منابع اصلی

- [مستندات اصلی بازوی بله](https://docs.bale.ai)
- [مستندات مینی‌اپ بله](https://docs.bale.ai/miniapp)

## مجوز

این مستندات بر اساس مستندات رسمی بازوی بله ایجاد شده‌اند.
