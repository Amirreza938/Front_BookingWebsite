# سفرینو (Safarino) - وب‌سایت رزرو هتل، پرواز و تجربه‌های سفر

![Safarino logo](assests/logo.png)

## 📌 معرفی پروژه

سفرینو یک پلتفرم جامع آنلاین برای رزرو هتل، پرواز و تجربه‌های سفر است که به کاربران امکان می‌دهد به سادگی و با بهترین قیمت، سفرهای خود را برنامه‌ریزی کنند. این پروژه با استفاده از HTML، CSS و JavaScript پیاده‌سازی شده و یک رابط کاربری کاربرپسند به زبان فارسی ارائه می‌دهد.

## 📋 فهرست مطالب

- [ویژگی‌های اصلی](#ویژگی‌های-اصلی)
- [تکنولوژی‌های استفاده شده](#تکنولوژی‌های-استفاده-شده)
- [ساختار پروژه](#ساختار-پروژه)
- [نحوه راه‌اندازی](#نحوه-راه‌اندازی)
- [راهنمای استفاده](#راهنمای-استفاده)
- [صفحات اصلی](#صفحات-اصلی)
- [جزئیات فنی](#جزئیات-فنی)
- [برنامه‌های آتی](#برنامه‌های-آتی)
- [همکاری در پروژه](#همکاری-در-پروژه)
- [لایسنس](#لایسنس)
- [تماس با ما](#تماس-با-ما)

## 🌟 ویژگی‌های اصلی

- **رزرو هتل**: جستجو، مقایسه و رزرو هتل‌های مختلف در مقاصد گوناگون
- **رزرو پرواز**: جستجو و رزرو پروازهای داخلی و خارجی
- **تجربه‌های سفر**: انتخاب و رزرو تجربه‌های متنوع گردشگری و تفریحی
- **سیستم نقد و بررسی**: امکان مشاهده و ثبت نظرات و امتیازدهی به هتل‌ها و پروازها
- **پروفایل کاربری**: مدیریت اطلاعات شخصی، سوابق رزرو و تراکنش‌ها
- **سیستم احراز هویت**: ثبت‌نام، ورود و مدیریت حساب کاربری
- **فیلترهای پیشرفته جستجو**: امکان فیلتر کردن نتایج بر اساس معیارهای مختلف
- **پشتیبانی از تقویم شمسی**: نمایش تاریخ‌ها به صورت هجری شمسی
- **طراحی واکنشگرا**: قابلیت استفاده در انواع دستگاه‌های مختلف
- **پشتیبانی از RTL**: پشتیبانی کامل از زبان فارسی و چینش راست به چپ

## 💻 تکنولوژی‌های استفاده شده

- **HTML5**: ساختار پایه صفحات وب
- **CSS3**: طراحی و استایل‌دهی صفحات
- **JavaScript**: افزودن قابلیت‌های تعاملی به صفحات
- **Font Awesome**: استفاده از آیکون‌ها در طراحی رابط کاربری
- **Responsive Design**: طراحی واکنشگرا برای دستگاه‌های مختلف
- **CSS Grid & Flexbox**: استفاده از تکنیک‌های مدرن چیدمان

## 📁 ساختار پروژه

```
Front_BookingWebSite/
│
├── auth.html            # صفحه احراز هویت و ثبت‌نام
├── flight.html          # صفحه نمایش اطلاعات و رزرو پرواز
├── home.html            # صفحه اصلی سایت
├── hotel.html           # صفحه نمایش اطلاعات و رزرو هتل
├── profile.html         # صفحه پروفایل کاربر
├── review.html          # صفحه نقد و بررسی‌ها
├── search.html          # صفحه جستجوی هتل و پرواز
│
├── styles/              # پوشه فایل‌های CSS
│   ├── auth.css         # استایل صفحه احراز هویت
│   ├── flight.css       # استایل صفحه پرواز
│   ├── home.css         # استایل صفحه اصلی
│   ├── hotel.css        # استایل صفحه هتل
│   ├── profile.css      # استایل صفحه پروفایل
│   ├── review.css       # استایل صفحه نقد و بررسی
│   └── search.css       # استایل صفحه جستجو
│
├── assests/             # پوشه تصاویر و فایل‌های رسانه‌ای
│   ├── destination1.jpg # تصویر مقصد گردشگری
│   ├── destination2.jpg # تصویر مقصد گردشگری
│   ├── flight1.jpg      # تصویر پرواز
│   ├── hotel1.jpg       # تصویر هتل
│   └── ...
│
└── README.md            # مستندات پروژه
```

## 🚀 نحوه راه‌اندازی

### پیش‌نیازها

- یک مرورگر وب مدرن (Chrome، Firefox، Edge، Safari)
- یک سرور وب محلی (اختیاری)

### مراحل راه‌اندازی

1. **دریافت کدهای پروژه**:
   ```bash
   git clone https://github.com/yourusername/safarino-booking.git
   cd safarino-booking
   ```

2. **راه‌اندازی سرور محلی** (یکی از این روش‌ها را انتخاب کنید):
   
   - با استفاده از پایتون:
     ```bash
     # برای پایتون 3
     python -m http.server
     # برای پایتون 2
     python -m SimpleHTTPServer
     ```
   
   - با استفاده از Node.js و http-server:
     ```bash
     npm install -g http-server
     http-server
     ```

3. **باز کردن وب‌سایت**:
   - مرورگر خود را باز کنید.
   - آدرس `http://localhost:8000/home.html` را وارد کنید.

4. **اگر نمی‌خواهید از سرور محلی استفاده کنید**:
   - به سادگی فایل `home.html` را مستقیماً در مرورگر خود باز کنید.

## 📖 راهنمای استفاده

### برای کاربران نهایی

1. **جستجوی هتل**:
   - به صفحه اصلی مراجعه کنید.
   - روی تب "هتل" کلیک کنید.
   - مقصد، تاریخ ورود و خروج، و تعداد مسافران را وارد کنید.
   - دکمه "جستجو" را کلیک کنید.
   - از فیلترها برای محدود کردن نتایج استفاده کنید.
   - روی "مشاهده و رزرو" برای رزرو هتل کلیک کنید.

2. **جستجوی پرواز**:
   - به صفحه اصلی مراجعه کنید.
   - روی تب "پرواز" کلیک کنید.
   - مبدا، مقصد، تاریخ رفت و برگشت، و تعداد مسافران را وارد کنید.
   - دکمه "جستجوی پرواز" را کلیک کنید.
   - از فیلترها برای محدود کردن نتایج استفاده کنید.
   - روی دکمه مشاهده پرواز و سپس "رزرو بلیط" برای تکمیل فرآیند رزرو کلیک کنید.

3. **ثبت نظر و بررسی**:
   - به صفحه "نقد و بررسی" مراجعه کنید.
   - به پایین صفحه بروید و بخش "ثبت نظر جدید" را پیدا کنید.
   - هتل یا پرواز مورد نظر را انتخاب کنید.
   - امتیاز، عنوان و متن نظر خود را وارد کنید.
   - دکمه "ارسال نظر" را کلیک کنید.

4. **مدیریت پروفایل**:
   - روی "پروفایل" در منوی اصلی کلیک کنید.
   - اطلاعات شخصی، رزروها و تراکنش‌های خود را مشاهده و مدیریت کنید.

### برای توسعه‌دهندگان

1. **ساختار HTML**:
   - از `<!DOCTYPE html>` استفاده شده است.
   - تمام صفحات دارای متا تگ‌های ضروری برای نمایش مناسب در دستگاه‌های مختلف هستند.
   - تمام صفحات از ویژگی `dir="rtl"` برای پشتیبانی از زبان فارسی استفاده می‌کنند.

2. **استایل‌های CSS**:
   - استایل‌های هر صفحه در فایل CSS مجزا ذخیره شده است.
   - از تکنیک‌های flexbox و grid برای طراحی انعطاف‌پذیر استفاده شده است.

3. **بهینه‌سازی**:
   - تصاویر با سایز مناسب ذخیره شده‌اند.
   - استایل‌ها به صورت جداگانه از HTML ذخیره شده‌اند.

## 📄 صفحات اصلی

### صفحه اصلی (home.html)

صفحه اصلی سایت که شامل بخش‌های زیر است:
- فرم جستجوی هتل، پرواز و تجربه‌های سفر
- بخش پیشنهادات ویژه
- مقاصد محبوب
- نمایش نقد و بررسی‌های برتر کاربران
- نمایش پروازهای پرطرفدار

**ویژگی‌های اصلی**:
- سیستم تب برای انتخاب نوع جستجو (هتل، پرواز، تجربه‌های سفر)
- نمایش پیشنهادات ویژه با تصاویر جذاب
- معرفی مقاصد محبوب با قیمت‌های پایه
- نمایش نظرات برتر کاربران

### صفحه احراز هویت (auth.html)

صفحه‌ای برای ثبت‌نام و ورود کاربران که شامل دو بخش اصلی است:
- فرم ورود به حساب کاربری
- فرم ایجاد حساب کاربری جدید

**ویژگی‌های اصلی**:
- سیستم تب برای تغییر بین فرم ورود و ثبت‌نام
- اعتبارسنجی فرم‌ها (با استفاده از HTML5 validation)
- لینک بازیابی رمز عبور

### صفحه هتل (hotel.html)

صفحه نمایش اطلاعات و رزرو هتل که شامل بخش‌های زیر است:
- گالری تصاویر هتل
- اطلاعات و توضیحات هتل
- امکانات هتل
- لیست اتاق‌ها و قیمت‌ها
- فرم رزرو هتل
- نظرات مهمانان قبلی

**ویژگی‌های اصلی**:
- گالری تصاویر با نمایش تصویر اصلی و تصاویر کوچک
- نمایش موقعیت هتل روی نقشه
- فیلتر برای انتخاب تاریخ ورود و خروج
- نمایش دقیق امتیازات هتل در دسته‌های مختلف
- فرم کامل رزرو با خلاصه هزینه

### صفحه پرواز (flight.html)

صفحه نمایش اطلاعات و رزرو پرواز که شامل موارد زیر است:
- مسیر و مشخصات پرواز
- اطلاعات شرکت هواپیمایی و هواپیما
- امکانات پرواز (چمدان، پذیرایی و...)
- فرم رزرو بلیط پرواز

**ویژگی‌های اصلی**:
- نمایش مسیر پرواز با تایم لاین گرافیکی
- اطلاعات کامل پرواز شامل شماره پرواز، نوع هواپیما و...
- سیستم انتخاب صندلی با نقشه هواپیما
- فرم کامل رزرو بلیط با اطلاعات مسافر و پرداخت

### صفحه پروفایل (profile.html)

صفحه مدیریت حساب کاربری شامل:
- اطلاعات شخصی کاربر
- لیست رزروهای انجام شده (هتل و پرواز)
- تاریخچه تراکنش‌های مالی

**ویژگی‌های اصلی**:
- تب‌های مختلف برای دسته‌بندی اطلاعات
- فرم ویرایش اطلاعات شخصی
- فرم تغییر رمز عبور
- فیلتر رزروها بر اساس نوع (هتل، پرواز، تجربه‌های سفر)
- نمایش خلاصه آماری تراکنش‌ها

### صفحه نقد و بررسی (review.html)

صفحه نمایش و ثبت نظرات و بررسی‌های کاربران که شامل:
- لیست نظرات کاربران درباره هتل‌ها و پروازها
- فیلترهای مختلف برای نمایش نظرات
- فرم ثبت نظر جدید

**ویژگی‌های اصلی**:
- فیلتر نظرات بر اساس نوع (هتل، پرواز)، امتیاز و تاریخ
- سیستم لایک کردن نظرات
- فرم ثبت نظر با امکان امتیازدهی و آپلود تصویر
- صفحه‌بندی نظرات

### صفحه جستجو (search.html)

صفحه جستجوی پیشرفته برای هتل‌ها، پروازها و تجربه‌ها:
- فرم‌های جستجو برای هر یک از خدمات
- فیلترهای پیشرفته (قیمت، امکانات، ستاره هتل و...)
- نمایش نتایج جستجو

**ویژگی‌های اصلی**:
- تب‌های مختلف برای انتخاب نوع جستجو
- فیلترهای پیشرفته و مرتب‌سازی نتایج
- نمایش نتایج به صورت کارت با اطلاعات مهم و تصویر

## 🔧 جزئیات فنی

### ساختار HTML

- از HTML5 Semantic Tags استفاده شده است (`header`, `nav`, `main`, `section`, `footer`).
- هر صفحه شامل بخش‌های زیر است:
  - هدر با منوی ناوبری
  - بخش اصلی محتوا
  - فوتر با اطلاعات تماس و لینک‌های مفید

### استایل‌های CSS

- از CSS3 برای استایل‌دهی استفاده شده است.
- ویژگی‌های CSS کلیدی:
  - استفاده از CSS Grid برای صفحه‌آرایی کلی
  - استفاده از Flexbox برای چیدمان اجزای داخلی
  - متغیرهای CSS برای تعریف رنگ‌ها و سایز‌های متداول
  - Media Queries برای طراحی واکنشگرا

### ساختار JavaScript

- از JavaScript برای افزودن قابلیت‌های تعاملی استفاده شده است:
  - تغییر تب‌ها
  - اعتبارسنجی فرم‌ها
  - انتخاب صندلی در صفحه پرواز
  - فیلتر کردن نتایج جستجو و نظرات
  - محاسبه قیمت نهایی در فرم‌های رزرو

## 🚧 برنامه‌های آتی

### قابلیت‌های در حال توسعه

1. **سیستم پرداخت آنلاین**: اتصال به درگاه‌های پرداخت آنلاین برای تکمیل فرآیند رزرو
2. **اپلیکیشن موبایل**: توسعه نسخه موبایل برای سیستم‌عامل‌های iOS و Android
3. **سیستم اطلاع‌رسانی**: ارسال ایمیل و پیامک برای اطلاع‌رسانی وضعیت رزروها
4. **سیستم تخفیف و کوپن**: امکان استفاده از کدهای تخفیف در زمان رزرو
5. **پشتیبانی از چند زبان**: قابلیت تغییر زبان سایت به انگلیسی و سایر زبان‌ها
6. **سیستم هوشمند پیشنهاد**: استفاده از الگوریتم‌های هوشمند برای پیشنهاد مناسب به کاربران

### بهینه‌سازی‌ها

1. **بهبود عملکرد**: بهینه‌سازی بارگذاری صفحات و تصاویر
2. **افزایش امنیت**: پیاده‌سازی سیستم امن احراز هویت و رمزنگاری داده‌ها
3. **بهبود SEO**: بهینه‌سازی برای موتورهای جستجو
4. **مقیاس‌پذیری**: بهبود ساختار کد برای پشتیبانی از تعداد زیاد کاربران

## 👥 همکاری در پروژه

اگر می‌خواهید در توسعه این پروژه همکاری کنید، از مشارکت شما استقبال می‌کنیم!

### نحوه مشارکت

1. **گزارش مشکلات**: اگر باگی پیدا کردید، لطفاً آن را در بخش Issues گزارش دهید.
2. **پیشنهاد قابلیت‌های جدید**: اگر ایده‌ای برای بهبود پروژه دارید، می‌توانید آن را مطرح کنید.
3. **ارسال Pull Request**: کد خود را فورک کرده، تغییرات را اعمال کنید و سپس Pull Request ارسال کنید.

### راهنمای کدنویسی

لطفاً برای مشارکت در کدنویسی، موارد زیر را رعایت کنید:
- از کدنویسی تمیز و قابل خواندن استفاده کنید.
- نام‌گذاری متغیرها و کلاس‌ها باید توصیفی و واضح باشد.
- کد را به خوبی مستندسازی کنید.
- از استانداردهای HTML5، CSS3 و ES6+ پیروی کنید.

## 📄 لایسنس

این پروژه تحت لایسنس MIT منتشر شده است. برای اطلاعات بیشتر، فایل LICENSE را مشاهده کنید.

## 📞 تماس با ما

- **وب‌سایت**: [www.safarino.com](http://www.safarino.com)
- **ایمیل**: info@safarino.com
- **تلفن**: ۰۲۱-۰۰۰۰۰۰۰۰
- **آدرس**: تهران، خیابان ولیعصر، نرسیده به پارک ساعی، پلاک 123

---

<div align="center">
  <p>با ❤️ توسعه داده شده توسط تیم سفرینو</p>
  <p>© ۱۴۰۲ - تمامی حقوق محفوظ است.</p>
</div>
