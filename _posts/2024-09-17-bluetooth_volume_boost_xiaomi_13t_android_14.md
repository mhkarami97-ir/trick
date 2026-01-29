---
title: "افزایش مقدار Volume صدا در اسپیکر بلوتوثی متصل به اندروید 14 گوشی شیائومی 13t"
tags:
    - اندروید
---

یکی از مشکلاتی که در اندروید زمان اتصال به دستگاه بلوتوثی دیگر مانند اسپیکر با آن مواجه شوید، کم بودن صدا حتی در مقدار Max است. این مشکل را در گوشی Xiaomi 13t نیز دارد.  
برای حل آن کافی است به صورت زیر عمل کنید:  

ابتدا به بخش Setting و سپس About Phone بروید. در این بخش بر روی `OS Version` یا `MIUI Version` چند بار پشت سر هم کلیک کنید تا پیام فعال شدن `Developer Option` برای شما نمایش داده شود.  

اکنون به بخش تماس بروید و دستور زیر را وارد کنید.  

```
* # * # 3 6 4 6 6 3 3 # * # *
```

اکنون به سربرگ `Hardware Testing` بروید و سپس بر روی `Audio` کلیک کنید.  

![mhkarami97](/assets/img/post/bluetooth_volume_boost_xiaomi_13t_android_14.jpg)  

سپس مسیر زیر را ادامه دهید.  

 >  Volume > Audio Playback

اکنون در صفحه باز شده از بخش دوم Music را انتخاب کنید.  

![mhkarami97](/assets/img/post/bluetooth_volume_boost_xiaomi_13t_android_14-1.jpg)  

 کافی است Index 15 را از مقداری که دارد به 255 تغییر دهید.  
 دقت کنید که این مورد را باید برای هر 3 آیتم زیر انجام دهید. همچنین دقت کنید که به ازای هر کدام نیاز است بر روی Set کلیک کنید و سپس به آیتم بعدی بروید.  

 - BT A2DP
 - BT A2DP HP
 - BT A2DP SPK

اکنون یک بار گوشی خود را ریست کنید تا تنظیمات اعمال شود.  

اگر راه فوق عمل نکرد می‌توانید از بخش `Setting` به `Additional Settings` و سپس `Developer Options` بروید.  

مقدار Bluetooth audio codec را به `LDAC` و Bluetooth audio sample rate را به `96.0 KHZ` تغییر دهید.  

![mhkarami97](/assets/img/post/bluetooth_volume_boost_xiaomi_13t_android_14-2.jpg)  