به نام خدا

# کاربرد عملی اصول شئ‌گرایی SOLID با استفاده از روش Test Driven Development

## اهداف 
- آشنایی دانشجویان با اصول مهم شئ‌گرایی به ویژه OCP و LSP و استفاده عملی از آن‌ها 
- آشنایی دانشجویان با روش پیاده سازی Development Test Driven (TDD)

## نیازمندی‌ها
آشنایی اولیه با مفاهیم برنامه نویسی و طراحی شی‌گرا که دانشجویان قبلاً در درس برنامه‌سازی پیشرفته با آن آشنا شده‌اند.

## ابزارهای مورد استفاده
- یک Java IDE مانند IntelliJ IDEA و یا Eclipse به همراه jdk حداقل نسخه ۸ 
- کتابخانه Junit (برای زبان Java)

## منابع آموزشی
- [فیلم آموزشی](https://aparat.com/v/NUPoJ)
- [آشنایی با TDD](https://github.com/ssc-public/Software-Engineering-Lab/tree/main/resources/TDD)
- [داستان ارث‌بری مربع و مستطیل](https://softwareengineering.stackexchange.com/questions/238176/why-would-square-inheriting-from-rectangle-be-problematic-if-we-override-the-set)

## شرح آزمایش
برای انجام آزمایش، علاوه بر رعایت نکات مطرح‌شده در فیلم، باید به [روش Test Driven Development یا TDD](https://github.com/ssc-public/Software-Engineering-Lab/tree/main/resources/TDD) هم عمل کنید. گام‌های انجام آزمایش به شرح زیر هستند:

- پروژه‌ای به زبان Java بنویسید که با داشتن طول (height) و عرض (width) یک مستطیل (Rectangle)، مساحت آن را محاسبه کند (متد computeArea)
- برنامه‌ی قبل را به گونه‌ای گسترش دهید که امکان تغییر طول و عرض مستطیل وجود داشته باشد (متدهای set و get).
- برنامه قبلی را به گونه‌ای گسترش دهید که علاوه بر مستطیل، مربع را هم پوشش دهد.

پس از انجام مراحل فوق، جزئیات به‌کارگیری اصول و الگوهای مرتبط در هر مرحله و دلایل استفاده از آن‌ها و مشکلاتی را که مرتفع می‌کنند، در فایل README.md پروژه توضیح دهید.

## پرسش‌ها
پاسخ پرسش‌های زیر را داخل فایل README پروژه بنویسید:
1. هر یک از پنج اصل SOLID را در دو الی سه خط توضیح دهید.
2. اصول SOLID در کدام یک از گام‌های اصلی ایجاد نرم‌افزار (تحلیل نیازمندی‌ها، طراحی، پیاده‌سازی، تست و استقرار) استفاده می‌شوند؟ توضیح دهید.
3. در چرخه‌ی عمومی ایجاد نرم‌افزار، آزمون نرم‌افزار دیرتر از پیاده‌سازی نرم‌افزار انجام می‌شود، اما در روش TDD تست‌نویسی پیش از پیاده‌سازی شروع می‌شود. آیا این دو مورد با هم تناقضی دارند؟ توضیح دهید.
4. فرض کنید در آزمایش بالا نیازی به تغییر ابعاد مستطیل نداشتیم. آیا در این حالت می‌توانستیم مربع را از مستطیل به ارث ببریم؟ توضیح دهید.

## نحوه ارسال پروژه:
آدرس مخزن پروژه خود را ارسال کنید. توجه کنید که مخزن شما عمومی (public) باشد.