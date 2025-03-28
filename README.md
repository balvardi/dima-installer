# dima-installer
A secure and efficient plugin to export and import WordPress data for custom installations. Dima Software Group All Right Reserved. https://www.dimagroup.ir

---

# **Dima Installer**

[![WordPress Version](https://img.shields.io/badge/WordPress-%3E%3D5.0-blue)](https://wordpress.org/) [![PHP Version](https://img.shields.io/badge/PHP-%3E%3D7.0-blue)](https://www.php.net/) [![License](https://img.shields.io/badge/License-GPLv2-green)](https://www.gnu.org/licenses/gpl-2.0.html)

افزونه **Dima Installer** یک ابزار قدرتمند و امن برای مدیریت داده‌های سایت‌های وردپرس است. این افزونه به شما کمک می‌کند تا به راحتی تنظیمات، محتوای سایت، ابزارها (Widgets)، منوها (Menus) و حتی محصولات فروشگاهی خود را Backup بگیرید و در هر زمان که نیاز داشتید، آن‌ها را بازیابی کنید.

## **ویژگی‌های کلیدی**

- **Export و Import داده‌ها:**
  - امکان Export داده‌ها به فرمت‌های مختلف: **JSON**, **SQL** و **PHP**.
  - امکان Import داده‌ها از فایل‌های JSON، SQL و PHP برای بازیابی سریع.

- **Backup کامل دیتابیس:**
  - قبل از هر Import، افزونه به صورت خودکار یک Backup از دیتابیس موجود می‌گیرد تا در صورت بروز مشکل، بتوانید به حالت قبل بازگردید.

- **مدیریت ابزارها و منوها:**
  - Backup و Restore ابزارها (Widgets) و منوها (Menus) به صورت خودکار.
  - اطمینان از حفظ ظاهر و عملکرد سایت بدون نیاز به تنظیمات دستی.

- **امنیت بالا:**
  - اعتبارسنجی دقیق فایل‌های آپلود شده برای جلوگیری از اجرای کدهای مخرب.
  - دسترسی فقط برای مدیران سایت (`administrator`) به منوی افزونه.

- **فشرده‌سازی خروجی‌ها:**
  - فایل‌های Export شده به صورت فشرده (ZIP) ذخیره می‌شوند تا حجم کمتری داشته باشند و قابلیت انتقال آن‌ها آسان‌تر باشد.

- **سازگاری با WooCommerce:**
  - امکان Backup و Restore محصولات فروشگاهی (Products) به همراه دسته‌بندی‌ها و جزئیات آن‌ها.

- **سادگی استفاده:**
  - رابط کاربری ساده و کاربرپسند که نیازی به دانش برنامه‌نویسی ندارد.
  - دستورالعمل‌های واضح برای Export و Import داده‌ها.

---

## **چرا از Dima Installer استفاده کنید؟**

- **صرفه‌جویی در زمان:**  
  دیگر نیازی نیست به صورت دستی تنظیمات و محتوای سایت‌های خود را انتقال دهید. افزونه Dima Installer تمام این کارها را به صورت خودکار انجام می‌دهد.

- **کاهش خطا:**  
  با استفاده از این افزونه، احتمال بروز خطا در هنگام انتقال داده‌ها به حداقل می‌رسد.

- **امنیت:**  
  افزونه با به‌کارگیری روش‌های امنیتی مدرن، از داده‌های شما محافظت می‌کند و از اجرای کدهای مخرب جلوگیری می‌کند.

- **انعطاف‌پذیری:**  
  افزونه برای انواع سایت‌های وردپرس، از وبلاگ‌های ساده تا فروشگاه‌های پیچیده، مناسب است.

---

## **نحوه نصب و استفاده**

### **1. نصب افزونه:**

1. فایل‌های افزونه را از مخزن گیت‌هاب دانلود کنید:  
   🔗 [https://github.com/balvardi/dima-installer](https://github.com/balvardi/dima-installer)
2. فایل‌ها را در مسیر `wp-content/plugins/dima-installer` قرار دهید.
3. به داشبورد وردپرس بروید و افزونه را از بخش **افزونه‌ها > افزونه‌های نصب شده** فعال کنید.

### **2. Export داده‌ها:**

- به منوی **Dima Installer** بروید.
- روی دکمه‌های **Export Data as JSON**, **Export Data as SQL** یا **Export Data as PHP** کلیک کنید.
- فایل‌ها به صورت فشرده (ZIP) در پوشه `wp-content/uploads` ذخیره می‌شوند.

### **3. Import داده‌ها:**

1. فایل مورد نظر (JSON, SQL یا PHP) را آپلود کنید.
2. روی دکمه **Import Data** کلیک کنید.
3. افزونه به صورت خودکار داده‌ها را وارد سایت مقصد می‌کند.

---

## **نیازمندی‌ها**

- **وردپرس:** نسخه ۵.۰ یا بالاتر.
- **PHP:** نسخه ۷.۰ یا بالاتر.
- **دسترسی به دیتابیس:** برای Import فایل‌های SQL.

---

## **پشتیبانی و توسعه**

اگر در هنگام استفاده از افزونه با مشکلی مواجه شدید یا پیشنهادی برای بهبود آن دارید، لطفاً در بخش Issues مخزن گیت‌هاب اطلاع دهید:  
🔗 [Issues on GitHub](https://github.com/balvardi/dima-installer/issues)

---

## **مشارکت در پروژه**

اگر علاقه‌مند به مشارکت در توسعه این پروژه هستید:
1. Fork کنید.
2. تغییرات خود را اعمال کنید.
3. یک Pull Request ایجاد کنید.

---

## **هدیه برای جامعه وردپرس**

این افزونه با اهداف آموزشی و کمک به جامعه وردپرس ایجاد شده است. اگر از این افزونه استفاده می‌کنید و از آن راضی هستید:
- ⭐ ستاره بدهید تا ما را حمایت کنید.
- 🍴 Fork کنید و به توسعه پروژه کمک کنید.
- 📢 آن را با دوستان و همکارانتان به اشتراک بگذارید.

---

**با Dima Installer، مدیریت داده‌های وردپرس هرگز اینقدر آسان نبوده است!** 🚀

---

### **اطلاعات تماس**

اگر سوالی دارید یا نیاز به کمک دارید، می‌توانید از طریق روش‌های زیر با ما در تماس باشید:
- **GitHub:** [https://github.com/balvardi/dima-installer](https://github.com/balvardi/dima-installer)
- **ایمیل:** [info@dimagroup.ir]

---

