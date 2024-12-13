## فعال‌سازی فوری ویندوز ۱۰ و ۱۱: راه حلی ۴۰ ثانیه‌ای

[![Readme](https://img.shields.io/badge/README_IN-فارسی-blue?logo=readme)](README-FA.md)  
[![Readme](https://img.shields.io/badge/README_IN-ENGLISH-blue?logo=readme)](README.md)  

> این مخزن حاوی روشی است که می‌تواند ویندوز ۱۰ و ۱۱ را در کمتر از ۴۰ ثانیه فعال کند. هر دو روش با نسخه‌های خانگی، خانگی N، خانگی تک زبانه، خانگی مخصوص کشور، حرفه‌ای، آموزشی و سازمانی ویندوز سازگار هستند.


## روش اول (پیشنهادی)

> [!TIP]
> روش‌های زیادی برای اجرای PowerShell در ویندوز ۱۰ و ۱۱ وجود دارد. [^1].

یکی از سریع‌ترین راه‌ها برای باز کردن PowerShell در ویندوز، جستجو در منوی Start است. می‌توانید مراحل زیر را دنبال کنید:

**مرحله ۱.** کافیست روی آیکون شروع یا جستجو کلیک کنید و عبارت "PowerShell" را در کادر جستجو تایپ کنید.
> روش آسان دیگر: [^2].

![1000034946](https://github.com/user-attachments/assets/5a10538a-c8c2-4934-868b-fd8e910f1f9e)

**مرحله ۲.** سپس، باید روی `Run as Administrator` کلیک کنید تا PowerShell با **مجوزهای مدیریتی** اجرا شود.

![1000034947](https://github.com/user-attachments/assets/1f25dd2a-16db-4053-a45c-aac6f8a9e470)

**مرحله ۳.** حالا، پس از مکث کوتاهی برای اجرای دستور، لطفا خط زیر را `کپی` کنید:

```CSS
irm https://get.activated.win | iex
```

**مرحله ۴.** حالا آن را (با کلیک راست) جای‌گذاری کنید و کلید Enter را فشار دهید. در پنجره جدیدی که باز می‌شود، چندین گزینه وجود دارد که باید گزینه `1` را انتخاب کرده و چند ثانیه صبر کنید تا فرآیند تکمیل شود.

![1000034926](https://github.com/user-attachments/assets/0c3689a1-1595-40b3-97e2-041dac423237)

**تبریک!** ویندوز شما فعال شده است. حالا می‌توانید کلید Enter را فشار دهید تا از CMD خارج شده و PowerShell را ببندید و منوی فعال‌سازی ویندوز را بررسی کنید. [^3]


---

## روش دوم

**فعال‌سازی فوری ویندوز ۱۰/۱۱** با استفاده از CMD (Command Prompt).

> [!NOTE]
> به **اینترنت** **متصل** باشید.
>
> **نیازی به VPN نیست**.

**مرحله ۱.** ابتدا، روی آیکون شروع یا جستجو کلیک کنید و عبارت "CMD" را در کادر جستجو تایپ کنید. پس از مشاهده گزینه Command Prompt، آن را به عنوان **مدیر** اجرا کنید.
> روش آسان دیگر: [^2].

<p align="center">
  <br><img src="https://github.com/NiREvil/workers-cloudflare/blob/main/Other/pics/win1.png" width="480px">
</p>

### لیست کلیدهای لایسنس

|            **کلید**            |   **نسخه**  |
|:-----------------------------:|:--------------:|
| TX9XD-98N7V-6WMQ6-BX7FG-H8Q99 |      خانگی      |
| 3KHY7-WNT83-DGQKR-F7HPR-844BM |     خانگی N     |
| 7HNRX-D7KGG-3K4RQ-4WPJ4-YTDFH |  خانگی تک زبانه [^5]  |
| PVMJN-6DFY6–9CCP6–7BKTT-D3WVR |  خانگی مخصوص کشور [^6]  |
| W269N-WFGWX-YVC9B-4J6C9-T83GX |  حرفه‌ای  |
| MH37W-N47XK-V7XM9-C7227-GCQG9 | حرفه‌ای N |
| NW6C2-QMPVW-D7KKK-3GKT6-VCFB2 |   آموزشی    |
| 2WH4N-8QGBV-H22JP-CT43Q-MDWWJ |   آموزشی N  |
| NPPR9-FWDCX-D2C8J-H872K-2YT43 |   سازمانی   |
| DPH2V-TTNVB-4X9Q3-TJR4H-KHJW4 |  سازمانی N  |

![rainbow](https://github.com/NiREvil/vless/assets/126243832/1aca7f5d-6495-44b7-aced-072bae52f256)

**مرحله ۲.** نصب کلید کلاینت KMS.

از این دستور استفاده کنید:

```CSS
slmgr /ipk yourlicensekey
```

> [!NOTE]
> لطفاً یکی از **کلیدهای لایسنس** را از لیست بالا که با **نسخه ویندوز شما مطابقت دارد** انتخاب کرده و آن را جایگزین عبارت `yourlicensekey` در دستور کنید.

> [!TIP]
> نحوه بررسی نسخه ویندوز [^3].


<p align="center">
  <br><img src="https://github.com/NiREvil/workers-cloudflare/blob/main/Other/pics/win2.png" width="480px">
</p>

<p align="center">
  <br><img src="https://github.com/NiREvil/workers-cloudflare/blob/main/Other/pics/win3.png" width="340px">
</p>

**مرحله ۳.** تنظیم آدرس ماشین KMS.

از دستور زیر استفاده کنید:

```CSS
slmgr /skms kms8.msguides.com
```

برای اتصال به سرور KMS من.

<p align="center">
  <br><img src="https://github.com/NiREvil/workers-cloudflare/blob/main/Other/pics/win4.png" width="480px">
</p>  

<p align="center">
  <br><img src="https://github.com/NiREvil/workers-cloudflare/blob/main/Other/pics/win5.png" width="340px">
</p>  

---

**مرحله ۴.** فعال‌سازی ویندوز.
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

**مرحله ۵.** و حالا وضعیت فعال‌سازی را دوباره بررسی کنید. [^4]

<p align="center">
  <br><img src="https://github.com/NiREvil/workers-cloudflare/blob/main/Other/pics/win8.png" width="480px">
</p>


**تمام شد ✅**
ویندوز شما با موفقیت فعال شد.


---


**کنجکاو باشید 🤍🪐**

[![Telegram](https://img.shields.io/badge/TELEGRAM-blue.svg?logo=telegram)](https://t.me/F_NiREvil)    [![Twitter](https://img.shields.io/badge/TWITTER-blue.svg?logo=x)](https://twitter.com/NiREvil_)


<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png"></picture>


---

[^1]: [۱۰ روش برای اجرای PowerShell در ویندوز](https://www.google.com/amp/s/www.minitool.com/news/open-windows-11-powershell.html%3famp)

[^2]: ساده‌ترین راه دیگر برای اجرای PowerShell: **کلیک راست** روی منوی Start برای باز کردن منوی پیوند سریع و انتخاب **Windows Terminal (admin)** در ویندوز ۱۱ یا **Windows PowerShell (admin)** در ویندوز ۱۰ از لیست منو.

[^3]: برای بررسی نسخه ویندوز خود: **کلیک راست** روی منوی Start و انتخاب گزینه **System**. نسخه ویندوز شما در بخش دوم زیر **Edition** قابل مشاهده است. همچنین می‌توانید مراحل روش ۲ را با **کپی پیست کردن** آنها دنبال کنید. دستورات را کپی کنید و سپس **کلیک راست** در **cmd یا PowerShell** برای چسباندن آنها کلیک کنید.

[^4]: برای مشاهده وضعیت فعال‌سازی ویندوز باید به مسیر زیر بروید:
Settings → Update & Security → Activation menu.

[^5]: نسخه خانگی تک زبانه.

[^6]: نسخه خانگی مخصوص کشور.
