## حرکت در فایل

در ویم یا وی‌آی، ما می‌توانیم با تنها یک کلید ، در متن حرکت کنیم. این حرکت‌ها به کلمات، گروهی از حروف ، اعداد، تک حرف ، توکن‌ها یا خط ‌ها باشند.
در منطق ویم، یک کلمه می‌تواند گروهی از حروف ، اعداد و  سمبل‌ها باشد. از طرفی دیگر یم توکن، هر آنچه که با فضای سفید، (اسپیس)  جدا شده باشد تلقی می‌شود.

### حرکت با حروف، کلمه یا توکن

کلید‌های اساسی حرکت در ویم این‌ها هستند:

-   **`h`** -- حرکت نشانگر به چپ
-   **`j`** -- حرکت نشانگر به پایین
-   **`k`** -- حرکت نشانگر به بالا
-   **`l`** -- حرکت نشانگر به راست
<br>
<div dir="rtl">
این کلید‌ها را می‌توان با یک شمارش همراه کرد تا به توان همان عدد انجام شوند
</div>
-  **`5j`**  پنج خط به پایین می‌رود
<br>

-   **`b`** -- حرکت به اول یک کلمه
-   **`B`** -- حرکت به اول یک توکن
-   **`w`** -- حرکت به اول کلمه‌ی بعد
-   **`W`** -- حرکت به اول توکن بعد
-   **`e`** -- حرکت به آخر کلمه
-   **`E`** -- حرکت به آخر توکن

<br>


برای  پرش به  پرانتز بسته،  گیومه بسته  و غیره از  **`%`** استفاده کنید
**`:h matchpairs`**
<br>

## حرکت  با خطوط
-   **`0 \ zero`**  -- حرکت به اول خط فعلی
-   **`$ \ dollar sign`** -- حرکت به آخر خط فعلی
-   **`^ \ caret sign`** -- حرکت به اولین  کاراکتر موجود در خط
-   **`#G`** / **`#gg`** / **`:#`** حرکت به شماره خط مشخص، (شماره خط جایگزین هشتگ شود)


برای استفاده از این قابلیت، شماره خطوط را فعال کنید.
**`:set number`**
برای  پرش به  پرانتز بسته،  گیومه بسته  و غیره از  **`%`** استفاده کنید
**`:h matchpairs`**
<br>

## حرکت  به وسیله صفحه
دستورهای زیر برای اسکرول کردن سریع در فایل کاربرد دارند.

-   **`Ctrl + b`** -- یک صفحه کامل به عقب رفتن
-   **`Ctrl + f`** -- یک صفحه کامل به جلو رفتن
-   **`Ctrl + d`** -- نصف صفحه جلو‌ رفتن
-   **`Ctrl + u`** -- نصف صفحه عقب رفتن
-   **`Ctrl + e`** -- صفحه را بدون حرکت دادن نشانگر یک خط پایین‌تر بردن
-   **`Ctrl + y`** --  صفحه را بدون حرکت دادن نشانگر یک خط بالاتر بردن
-   **`Ctrl + o`** -- به عقب رفتن در تاریخچه‌ی پرش ها. برای حرکت بین فایل‌ها و بافرها هم کاربرد دار
-   **`Ctrl + i`** -- برعکس دستور بالا

<br>

-   **`H`** -- حرکت به بالای صفحه
-   **`M`** -- حرکت به وسط صفحه
-   **`L`** -- حرکت به پایین صفحه

## وارد کردن متن

-   **`i`** -- وارد شدن به حالت ورود متن
-   **`I`** -- وارد کردن متن در اول خط
-   **`a`** -- سوییچ کردن به حالت ورود متن بعد از نشانگر
-   **`A`** -- وارد کردن متن در آخر خط
-   **`o`** -- باز کردن یک خط جدید زیر خط فعلی
-   **`O`** -- باز کردن خط جدید بالای خط فعلی
-   **`ea`** -- وارد کردن متن در آخر کلمه
-   **`Esc`** -- خارج شدن از حالت ورود متن و برگشنن به حالت نرمال
<br>

## ویرایش متن
-   **`r`** -- جایگزین کردن یک کاراکتر و بازگشت به حالت نرمال
-   **`cc`** -- جایگزین کردن کل خط (خط را پاک می‌کند و به خالت ورود متن می‌رود)
-   **`C`** / **`c$`** -- جایگزین کردن متن از مکان نشانگر تا آخر خط
-   **`cw`** -- جایگزین کردن تا آخر کلمه
-   **`s`** -- جایگزین کردن یک کاراکتر و رفتن به حالت ورود متن
-   **`J`** -- ادغام خط فعلی و خط زیر آن با یک اسپیس فاصله
-   **`gJ`** -- ادغام خط فعلی با خط زیر آن بدون اسپیس
-   **`u`** -- undo 
-   **`Ctrl`** + **`r`** -- redo
-   **`.`** -- تکرار آخرین دستور
<br>


### کات کپی و جایگذاری

-   **`yy`** -- کپی کردن کامل خط فعلی
-   **`#yy`** -- کپی کردن تعداد مشخصی از خطوط
-   **`dd`** -- کات کردن کل خط
-   **`#dd`** -- کات کردن تعداد مشخصی از خطوط
-   **`p`** -- جایگذاری بعد از نشانگر
-   **`P`** -- جایگذاری قبل از نشانگر


<br>

## حالت ویژوال

به غیر از حالت ورود متن (insert mode) و حالت نرمال (normal mode) و حالت دستوری (command mode)، حالت دیگری نیز به نام حالت ویژوال (visual mode) وجود دارد. از این مود برای انتخاب و ویرایش و انجام عملیات‌های مختلف بر روی بخش‌های بزرگ‌تری از متن استفاده می‌شود

ویژوال مود سه حالت کلی دارد.
- حالت کاراکتری
- حالت خطی
- حالت بلاک
```
character mode, line mode, and
block mode.
```
<br>

-   **`v`** -- انتخاب متن در حالت کاراکتری
-   **`V`** -- انتخاب متن در حالت خطی
-   **`Ctrl`**+**`v`** -- انتخاب متن در حالت بلاک

پس از فعال‌سازی یکی از حالت‌ها، با استفاده از کلید‌های جهت متن را انتخاب کنید.
<br>

-   **`o`** -- حرکت از ابتدای متن انتخاب شده به آخر آن
-   **`aw`** -- انتخاب یک کلمه
-   **`ab`** -- انتخاب یک بلاک کد که در بین پرانتز است
-   **`aB`** -- انتخاب یک بلاک کد که در بین آکولاد است {}
-   **`at`** -- انتخاب یک بلاک کد که در بین تگ است \<\>
-   **`ib`** -- انتخاب قسمت داخلی یک بلاک کد که بین پرانتز است
-   **`iB`** - انتخاب قسمت داخلی یک بلاک کد که بین آکولاد است {}
-   **`it`** -- انتخاب قسمت داخلی یک بلاک کد که بین یک تگ است \<\>

پس از انتخاب متن مورد نظر می‌توانید عملیات‌های مختلف را به وسیله‌ی کلید‌های زیر انجام دهید.

-   **`y`** -- کپی
-   **`d`** -- کات
-   **`p`** -- جایگذازی
<br>
## جستجو در متن


-   **`* \ asterisk`** -- رفتن به وقوع بعدی از کلمه‌ی زیر نشانگر
-   **`# \ pound sign`** -- رفتن به وقوع قبلی از کلمه‌ی زیر نشانگر
-   **`/pattern`** --جستجوی یک الگوی مشخص در فایل 
-   **`?pattern`** -- جستجوی یک الگوی مشخص از مکان فعلی تا اول متن
-   **`n`** -- پرش به وقوع بعدی الگوی یافت شده
-   **`N`** -- پرش به وقوع قبلی الگوی یافت شده

<br>

# ذخیره کردن و خروج از فایل

-   **`:w`** -- ذخیره کردن
-   **`:wq`** / **`:x`** / **`ZZ`** -- ذخیر کردن و خروج از ویم
-   **`:q`** -- خروج
-   **`:q!`**/ **`ZQ`** -- خروج بدون ذخیره کردن تغییرات
-   **`:w new_file_name `**-- ذخیره کردن تحت نامی جدید و ادامه دادن به ویرایش فایل اصلی
-   **`:sav`** -- ذخیره کردن تحت نامی جدید و ادامه‌ دادن به ویرایش فایل کپی شده
-   **`:w !sudo tee %`** -- ذخیره کردن فایل به‌وسیله‌ی سودو و تی، مناسب وقتی که فایلی را بدون دسترسی سودو باز کرده‌ایم [tee](https://wiki.archlinux.org/title/Tee)
<br>

## کار کردن با بیش از یک فایل

-   **`:e file_name `** -- باز کردن فایل در یک بافر جدید
-   **`:bn `** -- رقتن به بافر بعدی
-   **`:bp`** -- بازگشت به بافر قبلی
-   **`:bd `** -- بستن بافر
-   **`:b# `** -- رفتن به بافر با عدد شناسایی مشخص
-   **`:b file_name`** -- رفتن به بافر با نام مشخص
-   **`:ls`** -- لیست کردن تمام بافر باز ( شناسه‌ی عددی هر بافر کنار نام آن ظاهر خواهد شد)

<br>

-   **`:sp file_name `** -- باز کردن یک فایل در یک اسپلیت افقی
-   **`:vs file_name `** --باز کردن یک فایل در یک اسپلیت عمودی
-   **`:vert ba `** -- باز کردن همه‌ی بافر های فعلی در اسپلیت‌های عمودی
-   **`:tab ba `** -- ویرایش تمام بافر‌ها به‌وسیله تب‌
-   **`gt`** -- رفتن به تب بعدی
-   **`gT`** -- رفتن به تب قبلی



-   **`Ctrl+ws`** -- اسپلیت کردن صفحه به صورت افقی
-   **`Ctrl+wv`** -- اسپلیت کردن صفحه به صورت عمودی
-   **`Ctrl+ww`** -- سوییچ کردن بین اسپلیت ها (مشابه alt + tab)
-   **`Ctrl+wq`** -- بستن اسپلیت ها
-   **`Ctrl+wx`** -- جابجا کردن اسپلیت ‌ها با یگدیگر
-   **`Ctrl+=`** -- برابر کردن طول و عرض تمام اسپلیت‌ها

<br>

## مارک‌ها و پرش‌ها

-   **`m[a-z]`** -- مارک کردن موقعیت فعلی به‌وسیله‌ی حروف الفبا 
-   **`M[a-z]`** -- مارک کردن خط فعلی به‌وسیله‌ی خطوط الفبا 
-   **`` `a ``** - پرش به موقعیتی که با حرف آ مارک شده **`a`**
-   **`` `. ``** -- پرش به آخرین تغییر در فایل 
-   **`` `0 ``** -- پرش به آخرین موقعیت فایل قبل از بسته شدن ویم
-   **``` `` ```** -- پرش به آخرین پرش
-   **`:marks`** -- لیست کردن همه‌ی مارک ها
-   **`:jumps`** -- لیست کردن همه‌ی پرش ‌ها
-   **`:changes`** لیست کردن همه‌ی‌ تغییرات
-   **`Ctrl+o`** -- رفتن به پرش قبلی
-   **`Ctrl+i`** -- رفتن به پرش بعدی
-   **`g;`** -- رفتن به تغییر قبلی در لیست تغییرات
-   **`g,`** -- رفتن به نغییر بعدی در لیست تغییرات

## ماکرو
برای دستور ها یا ویرایش های تکرار شونده در ویم میتوان از ماکروها استفاده کرد.

-   **`qa `** -- ضبط کردن یک ماکرو **`a`**
-   **`q `** -- توقف ضبط یک ماکرو 
-   **`@a `** -- اجرا کردن ماکرو **`a`**
-   **`@@ `** -- اجرای دوباره‌ی ماکرو 

## فعال کردن تم‌ها در ویم

-   **`:colorscheme [colorscheme_name] `** -- تغییر تم رنگی
-   **`:colorscheme [space]+Ctrl+d`** -- لیست کردن تمام تم های رنگی موجود

