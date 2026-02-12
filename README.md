

# Computer Shop Premium WordPress Theme

A high-performance, custom-built e-commerce WordPress theme designed specifically for computer hardware and electronics stores. This theme features a modern UI, heavy JavaScript animations, and full WooCommerce integration.

## 🚀 Key Features
* **Modern Tech Stack:** Bootstrap 5, Swiper.js, and Custom CSS Animations.
* **Dynamic Homepage:** 3 Video sections with scroll-triggered animations.
* **Interactive UI:** Custom follower cursor and smooth parallax effects.
* **WooCommerce Ready:** Custom templates for shop, products, and AJAX-based cart.
* **Optimized Performance:** Conditional asset loading and RTL support (Vazirmatn Font).

## 📂 Folder Structure
The project follows a modular structure for scalability:
- `/assets`: All CSS, JS, Fonts, and Images.
- `/includes`: Core PHP logic, WooCommerce hooks, and Setup.
- `/template-parts`: Reusable UI components and sections.
- `/templates`: Custom page templates.

## 🛠 Installation
1. Clone the repository into `wp-content/themes/computer-shop`.
2. Run `npm install` (if using compilers) or simply activate the theme via WordPress Dashboard.
3. Install WooCommerce and recommended plugins.
4. Import sample products via the CSV provided in Milestone 17.

## 📈 Roadmap (Milestones)
- [ ] M1-M3: Core WordPress Files & Asset Management
- [ ] M4-M6: Homepage Sections & Component Architecture
- [ ] M7-M10: Advanced Customizer & Heavy JS/CSS Interactions
- [ ] M11-M12: WooCommerce Deep Integration & AJAX Actions
- [ ] M13-M17: Optimization, RTL, and Final Delivery

## 📝 License
Private Project - All Rights Reserved.








2. در پیشخوان وردپرس → **ظاهر > تم‌ها**، تم **Computer Shop** را فعال کنید.
3. افزونه **WooCommerce** را نصب و فعال کنید.
4. برای شخصی‌سازی، از **ظاهر > سفارشی‌ساز** استفاده کنید.

> 💡 **نکته**: برای استفاده از انیمیشن‌های صفحه اصلی، در بخش **سفارشی‌ساز** یا از طریق مدیریت ووکامرس، سه ویدیوی MP4/WebM را در بخش Hero Section آپلود کنید.

---

## 🎥 ویژگی‌های صفحه اصلی (Home Page)

- **اسلایدر ویدیویی**: پشتیبانی از ۳ ویدیو با کنترل‌های پخش/توقف
- **Parallax & Scroll Animations**: انیمیشن‌های ظاهر شدن با اسکرول (ScrollReveal)
- **رنگ‌آمیزی موس**: موس با رنگ‌های پویا که با حرکت کاربر تغییر می‌کند (با Canvas/JS)
- **اجزا تعاملی**: محصولات، خدمات، نظرات و CTA با انیمیشن‌های Bootstrap 5 + Swiper.js

---

## 🛡️ امنیت و استانداردها

- تمام ورودی‌ها با `sanitize_*` و خروجی‌ها با `esc_*` پاک‌سازی شده‌اند
- از Nonce در فرم‌ها و Ajax استفاده شده است
- بدون استفاده از `eval()` یا کدهای خطرناک
- مطابق با [WordPress Theme Handbook](https://developer.wordpress.org/themes/)

---

## 📄 مجوز (License)

این تم تحت مجوز **GNU General Public License v3.0** منتشر شده است.  
شما مجازعالی! با توجه به اینکه **فقط یک `README.md` برای GitHub می‌خوای** (نه کد، نه فایل‌ها)، و همچنین با در نظر گرفتن:

- ساختار پروژه‌ات کاملاً مشخص است  
- تم وردپرس فروشگاهی با پشتیبانی WooCommerce  
- طراحی حرفه‌ای هوم‌پیج با انیمیشن‌های اسکرول، ویدیو، و رنگ‌آمیزی موس  
- استفاده سنگین از Bootstrap + CSS خالص + JavaScript ماژولار  
- پشتیبانی RTL و فونت فارسی (وزیر)  

در ادامه یک **README.md حرفه‌ای، جذاب و مستند‌شده** برای ریپازیتوری GitHub برات آماده کردم — مناسب برای نمایش عمومی، تحویل به مشتری، یا استفاده شخصی.

---

### ✅ `README.md`

```markdown
# 🖥️ Computer Shop – قالب وردپرس فروشگاهی مدرن

![WordPress](https://img.shields.io/badge/WordPress-5.0%2B-blue?logo=wordpress)
![WooCommerce](https://img.shields.io/badge/WooCommerce-7.0%2B-orange?logo=woocommerce)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3-purple?logo=bootstrap)
![RTL Support](https://img.shields.io/badge/RTL-%D8%AA%D9%88%D8%B3%D8%B9%D8%AF-%2300A651)
![License](https://img.shields.io/badge/License-GPLv3-green)

قالب **Computer Shop** یک تم اختصاصی، واکنش‌گرا و بهینه‌شده برای فروشگاه‌های لوازم کامپیوتری و الکترونیکی است که با استانداردهای مدرن توسعه وردپرس ساخته شده و کاملاً با **WooCommerce** یکپارچه است.

---

## 🌟 ویژگی‌های کلیدی

- ✅ **صفحه اصلی پویا**: شامل اسلایدر ویدیویی (۳ ویدیو قابل آپلود)، انیمیشن‌های اسکرول هوشمند و افکت‌های تعاملی
- 🎨 **افکت موس رنگی**: موس با رنگ‌های داینامیک و انیمیشن‌های روان در صفحه اصلی
- 📱 **ریسپانسیو کامل**: طراحی موبایل‌فرست با پشتیبانی از تمام دستگاه‌ها
- 🇮🇷 **پشتیبانی RTL + فونت وزیر**: فونت فارسی **Vazirmatn** به‌صورت داخلی و بدون وابستگی به CDN
- ⚡ **بهینه‌سازی عملکرد**: بارگذاری شرطی Assetها، Lazy Load، حذف استایل‌های غیرضروری ووکامرس
- 🧩 **ساختار ماژولار**: کدها به‌صورت تمیز، مستند‌شده و قابل نگهداری تقسیم‌بندی شده‌اند
- 🛠️ **سفارشی‌سازی پیشرفته**: پشتیبانی از Customizer، Shortcode، Ajax، و تم‌های گوتنبرگ
- 📦 **قالب‌های صفحه**: Full-width، Sidebar، Landing Page و ...

---

## 🗂️ ساختار پروژه

```
computer-shop/
├── assets/               # CSS, JS, تصاویر، فونت‌ها
├── includes/             # توابع، تنظیمات، کلاس‌ها
├── template-parts/       # کامپوننت‌های قابل استفاده مجدد
├── templates/            # قالب‌های صفحه و ووکامرس
├── languages/            # پشتیبانی چندزبانه (POT)
├── *.php                 # فایل‌های اصلی وردپرس (index, header, footer, ...)
├── style.css             # هدر تم و استایل اصلی
├── screenshot.png        # پیش‌نمایش (1200×900)
└── README.md
