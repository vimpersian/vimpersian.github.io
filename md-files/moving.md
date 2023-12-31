<div dir="rtl"><h1 id="moving">حرکت در فایل</h1></div>
<div dir="rtl"><h2 id="moving2">حرکت با حروف، کلمه یا توکن</h2></div>

<div dir="rtl">کلید‌های اساسی حرکت در ویم این‌ها هستند:</div>

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

<div dir="rtl">

برای  پرش به  پرانتز بسته،  گیومه بسته  و غیره از  **`%`** استفاده کنید
</div>

**`:h matchpairs`**
<br>

<div dir="rtl"><h1 id="moving3">حرکت  با خطوط</h1></div>

-   **`0 \ zero`**  -- حرکت به اول خط فعلی
-   **`$ \ dollar sign`** -- حرکت به آخر خط فعلی
-   **`^ \ caret sign`** -- حرکت به اولین  کاراکتر موجود در خط
-   **`#G`** / **`#gg`** / **`:#`** حرکت به شماره خط مشخص، (شماره خط جایگزین هشتگ شود)

<br>
<div dir="rtl">برای استفاده از این قابلیت، شماره خطوط را فعال کنید.</div>

```
:set number
```
<br>

<div dir="rtl"><h1 id="moving4">  حرکت  به وسیله صفحه</h1></div>
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
