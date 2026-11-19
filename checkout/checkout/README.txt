ساختار پروژه
============

index.html                 صفحه اصلی (HTML)
assets/
  css/
    fonts.css              تعریف @font-face (فونت‌ها)
    variables.css          رنگ‌ها، فونت، گردی گوشه‌ها (متغیرهای :root)
    base.css               ریست و استایل‌های پایه
    layout.css             چیدمان کلی صفحه (موبایل‌فرست)
    form.css               عنوان‌ها و بلوک‌های فرم
    fields.css             input / select / textarea
    shipping.css           انتخاب نحوه ارسال
    summary.css            پنل جزئیات خرید، آیتم محصول، مجموع‌ها، درگاه، دکمه پرداخت
    responsive.css         media queryها (تبلت ۶۴۰px و دسکتاپ ۹۹۲px)
  fonts/                   فایل‌های فونت (woff2)
  images/
    products/              عکس محصولات
    gateway/               لوگوی درگاه پرداخت
    icons/                 آیکون‌ها (در صورت نیاز)
  js/                      اسکریپت‌ها (در صورت نیاز)

نکته: ترتیب لینک شدن فایل‌های CSS در index.html مهم است؛ responsive.css باید آخر باشد.
