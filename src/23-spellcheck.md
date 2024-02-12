  <div dir="rtl"><h1> چک کردن املای کلمات</h1></div>
<div dir="rtl"><strong>آپشن های لازم:</strong></div>

```
set spell spelllang=en_us
set wildmode=longest,list,full
hi SpellBad ctermfg=red guifg=red
```

<div dir="rtl">پس از قراردادن این آپشن در ویم‌آرسی، ویم بصورت خودکار واژگانی که غلط نوشته‌شده باشند را قرمز می‌کند.
سپس برای پریدن به واژگان مشخص‌ شده از کلیدهای زیر استفاده می‌کنیم.
</div>


- `]s` 
- `[s`

<div dir="rtl"> پس از آن‌که نشانگر ما روی واژه‌ی مشخص شده قرار‌گرفت، با استفاده از عملیات زیر آن را اصلاح می‌کنیم:</div>

`z=` 

<div dir="rtl">
<code>=z</code>ما را وارد منوی انتخاب واژه با املای درست می‌کند. معمولا اولین پیشنهاد درست‌ترین پیشنهاد است. سپس با زدن کلید <code>1</code> اولین پیشنهاد را انتخاب می‌کنیم و واژه جایگزین می‌شود.
چنانچه انتخاب دوم، سوم الی آخر درست بودند، عدد مربوط به آن را وارد می‌کنیم.
</div>

<div dir="rtl">
پس به‌طور‌ خلاصه <code>z=1</code> سریع‌ترین راه اصلاح املای واژگان است.
</div>

<div dir="rtl">اگر از قرمز شدن واژگان هنگام کد زدن خسته شدید، می‌توانید با استفاده از یک keybinding ساده در ویم، فقط هنگام نیاز آن را فعال کنید</div>

```
noremap <F6> :setlocal spell! spelllang=en_us<CR>
```

<div dir="rtl">با قراردادن خط بالا در ویم‌آرسی، فشردن کلید <code>F6</code> حالت بررسی غلط‌های املایی را فعال می‌کند. اگر بخواهید که <code>F6</code> در حالت اینسرت هم این کار را انجام دهد باید یک مپینگ جدا برای آن تعریف کنید. keybinding ها در ویم،‌ اختصاصا برای مدهای مختلف تعریف می‌شوند.</div>

```
nnoremap <F6> :setlocal spell! spelllang=en_us<CR>
inoremap <F6> <C-o>:setlocal spell! spelllang=en_us<CR>
```

<div dir="rtl">همچنین با استفاده از یک تابع بسیار ساده در ویم‌اسکریپت و اختصاص یک keybinding به آن می‌توانیم فرایند ‍‍<code>z=1</code> را تسریع دهیم.</div>

```
function! FixSpell()
  normal! 1z=<CR>
endfunction

map gs :call FixSpell()<CR>
```
<div dir="rtl">از این پس با زدن کلید‌های <code>gs</code>روی واژگان قرمز شده، می‌توانیم اولین پیشنهاد اصلاح را اعمال کنیم.</div>
<br> 
<br> 

<div style="text-align:center;">
    <video width="640" height="360" controls>
    <source src="./media/spellchek.mp4" type="video/mp4">
    </video>
</div>


