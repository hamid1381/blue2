



<span>git clone https://github.com/iranpowergit/blue2.git</span>
</pre>
<h4 dir="rtl">داخل فایل cli.lua بروید
در خط ۱و۲و۹ بجای username یوزر سرور خودرا قرار دهید
در خط ۱۰ و ۱۱ شناسه سودو و
در خط  ۱۳۱۴شناسه بات api را قرار داده
سپس فایل را سیو کنید و خارج شوید.
<br>➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖<br>
طبق همین منوال به فایل api.lua بروید
درخط  ۴ بجای , username یوزر سرور خودرا
در خط ۵ توکن خود و
در خط ۱۰ و ۱۲ شناسه سودو خود را بگذارید سپس
در خط ۱۶۲ بجای شناسه اولی شناسه ی بات cli و بجای شناسه دومی شناسه ی سودو خود را قرار دهید.
<br>➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖<br>
</h4>حال ترمینال باز کنید و دستورات زیر را اجرا کنید
<pre>
<span>cd inline</span>
<span>chmod +x api.sh</span>
<span>chmod +x tg</span>
<span>chmod +x cli.sh</span>
<span>./cli.sh</span>
</pre>

<h4 dir="rtl">از شما شماره ربات خواسته می‌شود پس از وارد کردن آن کد ورود به اکانت ربات cli خواسته می‌شود آن را هم وارد کنید.
<br>حال ترمینال جدید باز کنید و ربات api را با دستورات زیر ران کنید.</h4>
<pre>
<span>cd inline</span>
<span>./api.sh</span>
</pre>
<h4 dir="rtl">قبل از دستورات لانچ screen بگذارید تا در صورت بستن ترمینال بات ها روشن بمونند
<h4 dir="rtl">هر دو بات باید باهم روشن باشند!
<h4 dir="rtl"> نکته ی مهم
<br>
 ۱. حتما به بات api دسترسی اینلاین بدهید
<br>
 ۲.بعد از لانچ کردن حتما بات api رو با cli استارت کنید<span/>
<br><br>
<h4 dir="rtl"><br>روشن کردن جفت بات ها با اتولانچ👇</h4>
<pre>
<span>killall tmux</span>
<span>killall screen</span>
<span>killall -9 bash</span>
<span>cd inline</span>
<span>./on.sh</span>
</pre>
