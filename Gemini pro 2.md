## فعال‌سازی فوری ویندوز ۱۰ و ۱۱: راهکاری ۴۰ ثانیه‌ای

[![Readme](https://img.shields.io/badge/README_IN-فارسی-blue?logo=readme)](README-FA.md)
[![Readme](https://img.shields.io/badge/README_IN-ENGLISH-blue?logo=readme)](README.md)

> این مخزن شامل روشی برای فعال‌سازی ویندوز ۱۰ و ۱۱ در کمتر از ۴۰ ثانیه است. هر دو روش با نسخه‌های Home، Home N، Home Single Language، Home Country Specific، Professional، Education و Enterprise ویندوز سازگار است.

## روش ۱ (توصیه شده)
**فعال‌سازی فوری ویندوز با استفاده از (PowerShell)**

> [!TIP]
> روش‌های متعددی برای اجرای پاورشل در ویندوز ۱۰ و ۱۱ وجود دارد. [^1]

یکی از سریع‌ترین راه‌ها برای باز کردن پاورشل در ویندوز، جستجو در منوی استارت است. می‌توانید مراحل زیر را دنبال کنید:

**گام ۱.** کافی است روی آیکون استارت یا جستجو کلیک کرده و "PowerShell" را در کادر جستجو تایپ کنید.
> یک روش آسان دیگر: [^2]

<p align="center">
  <br><img src="https://github.com/user-attachments/assets/5a10538a-c8c2-4934-868b-fd8e910f1f9e" width="540px">
</p>

---
<br><br>
**گام ۲.** در مرحله بعد، باید بر روی گزینه "Run as Administrator" کلیک کنید تا پاورشل با **امتیازات مدیریتی** اجرا شود.

<p align="center">
  <br><img src="https://github.com/user-attachments/assets/1f25dd2a-16db-4053-a45c-aac6f8a9e470" width="540px">
</p>

---
<br><br>
**گام ۳.** اکنون، پس از مکث کوتاهی برای اجرای برنامه، این خط را `کپی` کنید:

```CSS
irm https://get.activated.win | iex
```
---
<br><br>
**گام ۴.** حالا آن را (با راست کلیک) جایگذاری کرده و کلید اینتر را بزنید. در پنجره تازه باز شده، چندین گزینه وجود دارد که از بین آن‌ها باید گزینه `۱` را انتخاب کرده و چند ثانیه منتظر بمانید تا فرآیند تکمیل شود.

<p align="center">
  <br><img src="https://github.com/user-attachments/assets/0c3689a1-1595-40b3-97e2-041dac423237" width="540px">
</p>

<br><br>
**تبریک می‌گوییم**، ویندوز شما فعال شد. اکنون می‌توانید کلید اینتر را برای خروج از CMD زده و پاورشل را ببندید و منوی فعال‌سازی ویندوز را بررسی کنید. [^3]

<br><br>
<br><br>
<br><br>
<br><br>

## روش ۲
**فعال‌سازی فوری ویندوز با استفاده از CMD (خط فرمان)**

> [!NOTE]
> به یاد داشته باشید که به **اینترنت متصل** باشید.
>
> استفاده از **VPN ضروری نیست.**

**گام ۱.** ابتدا روی آیکون استارت یا جستجو کلیک کرده و "CMD" را در کادر جستجو تایپ کنید. پس از مشاهده گزینه Command Prompt، آن را به عنوان **مدیر** اجرا کنید.
> روش آسان دیگر: [^2]

<p align="center">
  <br><img src="https://github.com/NiREvil/workers-cloudflare/blob/main/Other/pics/win1.png" width="480px">
</p>

---
<br><br>
### در ادامه لیست کلیدهای لایسنس آمده است

|            **کلید**            |   **نسخه**   |
|:-----------------------------:|:--------------:|
| TX9XD-98N7V-6WMQ6-BX7FG-H8Q99 |      Home      |
| 3KHY7-WNT83-DGQKR-F7HPR-844BM |     Home N     |
| 7HNRX-D7KGG-3K4RQ-4WPJ4-YTDFH |  Home sl [^5]  |
| PVMJN-6DFY6–9CCP6–7BKTT-D3WVR |  Home cs [^6]  |
| W269N-WFGWX-YVC9B-4J6C9-T83GX |  Professional  |
| MH37W-N47XK-V7XM9-C7227-GCQG9 | Professional N |
| NW6C2-QMPVW-D7KKK-3GKT6-VCFB2 |   Education    |
| 2WH4N-8QGBV-H22JP-CT43Q-MDWWJ |   Education N  |
| NPPR9-FWDCX-D2C8J-H872K-2YT43 |   Enterprise   |
| DPH2V-TTNVB-4X9Q3-TJR4H-KHJW4 |  Enterprise N  |

![rainbow](https://github.com/NiREvil/vless/assets/126243832/1aca7f5d-6495-44b7-aced-072bae52f256)

<br><br>
**گام ۲.** نصب کلید کلاینت KMS.

از این دستور استفاده کنید:
```CSS
slmgr /ipk yourlicensekey
```
> [!NOTE]
> لطفاً یکی از **کلیدهای لایسنس** را از لیست که با **نسخه ویندوز شما مطابقت دارد** انتخاب کرده و آن را با عبارت `yourlicensekey` در دستور جایگزین کنید.

> [!TIP]
> چگونه نسخه ویندوز خود را بررسی کنیم [^3].

<p align="center">
  <br><img src="https://github.com/NiREvil/workers-cloudflare/blob/main/Other/pics/win2.png" width="480px">
</p>
<p align="center">
  <br><img src="https://github.com/NiREvil/workers-cloudflare/blob/main/Other/pics/win3.png" width="340px">
</p>

---
<br><br>
**گام ۳.** تنظیم آدرس سرور KMS.

از دستور زیر برای اتصال به سرور KMS من استفاده کنید:

```CSS
slmgr /skms kms8.msguides.com
```

<p align="center">
  <br><img src="https://github.com/NiREvil/workers-cloudflare/blob/main/Other/pics/win4.png" width="480px">
</p>

<p align="center">
  <br><img src="https://github.com/NiREvil/workers-cloudflare/blob/main/Other/pics/win5.png" width="340px">
</p>

---
<br><br>
**گام ۴.** فعال‌سازی ویندوز.
آخرین مرحله، فعال‌سازی ویندوز با استفاده از دستور زیر است:

```CSS
slmgr /ato
```

<p align="center">
  <br><img src="https://github.com/NiREvil/workers-cloudflare/blob/main/Other/pics/win6.png" width="480px">
</p>

<p align="center">
  <br><img src="https://github.com/NiREvil/workers-cloudflare/blob/main/Other/pics/win7.png" width="240px">
</p>

---
<br><br>
**گام ۵.** اکنون وضعیت فعال‌سازی را دوباره بررسی کنید [^4].

<p align="center">
  <br><img src="https://github.com/NiREvil/workers-cloudflare/blob/main/Other/pics/win8.png" width="480px">
</p>

**انجام شد ✅**
ویندوز شما با موفقیت فعال شد.

---
<br><br>
**کنجکاو باشید 🤍🪐**

[![Telegram](https://img.shields.io/badge/TELEGRAM-blue.svg?logo=telegram)](https://t.me/F_NiREvil)
[![Twitter](https://img.shields.io/badge/TWITTER-blue.svg?logo=x)](https://twitter.com/NiREvil_)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png"></picture>

![rainbow](https://github.com/NiREvil/vless/assets/126243832/1aca7f5d-6495-44b7-aced-072bae52f256)
---
<br><br>

[^1]: [۱۰ روش برای اجرای پاورشل در ویندوز](https://www.google.com/amp/s/www.minitool.com/news/open-windows-11-powershell.html%3famp)

[^2]: روش آسان دیگر برای اجرای پاورشل: روی منوی استارت خود **راست کلیک** کرده تا منوی دسترسی سریع باز شود و **Windows Terminal (admin)** را در ویندوز ۱۱ یا **Windows powershell (admin)** را در ویندوز ۱۰ از لیست منو انتخاب کنید.

[^3]: برای بررسی نسخه ویندوز خود: روی منوی استارت خود **راست کلیک** کرده و گزینه **system** را انتخاب کنید. نسخه ویندوز شما را می‌توانید در بخش دوم زیر عنوان **Edition** مشاهده کنید. همچنین می‌توانید مراحل روش ۲ را با **کپی و جایگذاری** دنبال کنید. دستورات را کپی کرده و سپس برای جایگذاری، **راست کلیک** در **cmd یا powershell** انجام دهید.

[^4]: برای دیدن وضعیت فعال‌سازی ویندوز، باید به این مسیر بروید:
Settings → Update & Security → activation menu

[^5]: نسخه Home Single Language.

[^6]: نسخه Home Country Specific.
