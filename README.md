# از قفسه تا مشاور انتخاب 🧭

![Single File](https://img.shields.io/badge/build-single--file-ef4056)
![Zero Dependencies](https://img.shields.io/badge/dependencies-0-0d9488)
![Dark / Light](https://img.shields.io/badge/theme-dark%20%2F%20light-141417)
![RTL](https://img.shields.io/badge/lang-فارسی%20(RTL)-2563eb)
![No Framework](https://img.shields.io/badge/framework-none-77777f)

**A product-design case study (in Persian):** diagnosing why users of a major e-commerce platform abandon the digital-goods category listing at **2× the normal exit rate — before ever opening a single product page** — and redesigning that exact page from a "shelf" into a "choice advisor". Includes root-cause analysis, competitive benchmarking, seven designed components across two solution tracks, an implementation roadmap, and a four-layer success-metrics framework. The page itself is part of the portfolio: analysis, copy, UI design and code are all by the author, in one dependency-free HTML file.

🔗 **Live demo:** `https://USERNAME.github.io/REPO-NAME/` *(بعد از فعال‌سازی Pages، این لینک را جایگزین کن)*

---

<div dir="rtl">

## این ریپازیتوری چیست؟

یک **کیس‌استادی کامل طراحی محصول** درباره‌ی مسئله‌ای واقعی در تجارت الکترونیک:

> نرخ خروج از فهرست کتگوری کالای دیجیتال، ۲ برابر بقیه‌ی صفحات است — و کاربر **پیش از باز کردن حتی یک صفحه‌ی محصول**، اپلیکیشن را می‌بندد.

با سه قید سخت: **بدون آزمون A/B، بدون پرسشنامه، بدون دسترسی به داده‌ی داخلی.**

## چه چیزی داخلش پیدا می‌کنید؟

| بخش | محتوا |
|---|---|
| 🔍 **کشف مسئله** | هشت سوال تشخیصی و جواب‌هایشان، سه پرسونا، شواهد میدانی با هزینه‌ی صفر، نقشه‌ی سفر و لحظه‌های خروج |
| ⚡ **تشخیص ریشه‌ای** | حذف شش فرضیه با شواهد؛ علت اصلی: فلجِ انتخاب — کارتِ کم‌اطلاعات × ۳٬۸۴۶ گزینه × نبودِ راهنما |
| 📊 **بنچمارک رقابتی** | ماتریس شکاف هفت قابلیت در سطح فهرست: آمازون، فلیپ‌کارت، تکنولایف، ترب |
| 🧩 **راه‌حل طراحی** | دو راهکار (کاهش ریزش در همان جلسه / بازگشت و تبدیل به خرید) با **هفت کامپوننت طراحی‌شده به‌صورت زنده در خود صفحه** |
| 🗺 **برنامه‌ی اجرا** | چهار فاز در شانزده هفته با گانت‌چارت، تیم، و جدول ریسک‌ها با پاسخ مشخص |
| 📈 **متریک‌های موفقیت** | سیزده شاخص در چهار لایه: نتیجه، پیشرو، رفتاری و نگهبان — با روش سنجش بدون A/B (گروه شاهد طبیعی) |
| 📚 **منابع** | یازده ارجاع معتبر: Think with Google، NN/g، Baymard، Kahneman & Tversky، Fogg و... |

## نکات فنی این صفحه

- **تک‌فایل و بدون وابستگی** — همه‌چیز (استایل، اسکریپت، آیکون‌ها و حتی تصویر پروفایل به‌صورت base64) داخل یک `index.html`
- **حالت تیره/روشن** با CSS Custom Properties، ذخیره‌ی امن ترجیح کاربر و احترام به `prefers-reduced-motion`
- **گلس‌مورفیسم واقعی** — `backdrop-filter` با پس‌زمینه‌ی محیطی که به شیشه چیزی برای مات کردن می‌دهد
- **داک ناوبری شناور** با تشخیص خودکار بخش فعال (IntersectionObserver)
- **۲۵ آیکون SVG دست‌ساز** به‌صورت اسپرایت داخلی
- **مقاوم در برابر محیط‌های سندباکس** — دسترسی به حافظه‌ی مرورگر پشت لایه‌ی امن؛ خطای یک ماژول، بقیه را از کار نمی‌اندازد
- **واکنش‌گرای کامل** — موبایل‌اول، با جدول‌های اسکرول‌شونده و گرید تطبیقی

## اجرا و استقرار

هیچ مرحله‌ی Build وجود ندارد:

- **لوکال:** فایل `index.html` را در مرورگر باز کنید. همین.
- **GitHub Pages:** ریپو را Public کنید ← Settings ← Pages ← Deploy from a branch ← `main` و `/ (root)` ← Save
- **Vercel / Netlify:** ریپو را Import کنید؛ بدون هیچ تنظیمی دیپلوی می‌شود.

## نویسنده

**سینا حسینی** — طراحی محصول

تحلیل، متن، طراحی رابط و کدنویسیِ این پرونده، همگی توسط نویسنده انجام شده است.

</div>

---

<sub>© Sina Hosseini — case-study content and design. Code is free to learn from; please don't republish the case study as your own.</sub>
