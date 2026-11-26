# civil-eng-mentor-iran

یک Skill برای Claude: مهندس مشاور و منتور سازه، ژئوتکنیک و زلزله، مبتنی بر آئین‌نامه‌های ایران.
A Claude Skill acting as a consulting-engineer mentor (structural, geotechnical, earthquake) grounded in Iranian codes.

## ویژگی‌ها / Features
- پاسخ فارسی و راست‌چین (RTL، فونت Vazirmatn)
- ارجاع به شماره بند دقیق مبحث ۶، ۷، ۹، ۱۰ و استاندارد ۲۸۰۰ (بدون جعل شماره بند)
- مقایسه و چالش با ACI، Eurocode، ASCE 7/41، AISC، FEMA
- تحلیل‌های استاتیکی/دینامیکی خطی و غیرخطی
- ETABS، SAFE، SAP2000، CSiBridge، SeismoSignal (تشخیص خطا، تفسیر خروجی، تنظیمات)
- قانون: همیشه بر اساس جدیدترین ویرایش آئین‌نامه‌ها؛ در صورت نبود تأیید، صریحاً اعلام می‌شود

## محدودیت‌ها / Limitations
- نرم‌افزارها را اجرا نمی‌کند و فایل مدل را باز نمی‌کند؛ کد خطا، تنظیمات و اسکرین‌شات لازم است.
- مرجع قطعی، متن رسمی آئین‌نامه است. خروجی جایگزین بازبینی مهندس مسئول نیست.
- استاندارد ۲۸۰۰ ویرایش پنجم مبنا است ولی مقادیر آن باید با متن رسمی تطبیق داده شود؛ ویرایش فعلی مبحث ۱۰ هنوز تأیید نشده (docs/CODE-EDITIONS.md).
- پاسخ کوتاه در چت ساده داده می‌شود؛ پاسخ‌های مفصل به‌صورت صفحه RTL کارتی.

## ساختار / Structure
```
skill/civil-eng-mentor-iran/SKILL.md
skill/civil-eng-mentor-iran/references/   یادداشت‌های خلاصه از منابع
docs/CODE-EDITIONS.md                     وضعیت ویرایش آئین‌نامه‌ها
docs/SOURCES.md                           فهرست منابع
CHANGELOG.md  CONTRIBUTING.md  LICENSE
```

## نصب / Install
پوشه `skill/civil-eng-mentor-iran` را در بخش Skills کلود اضافه کنید.

## مشارکت / Contributing
CONTRIBUTING.md را ببینید.
